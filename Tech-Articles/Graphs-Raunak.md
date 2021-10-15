
Article Title: Some Graph Algorithms
Author Name: Raunak Agarwal
Author Profile: https://github.com/Raunak173
Date: 15-10-2021

//BFS OF GRAPH =>

vector<int>bfsOfGraph(int V, vector<int> adj[]){
	    vector<int> bfs; 
	    vector<int> vis(V, 0); 
	    queue<int> q; 
	    q.push(0); 
	    vis[0] = 1; 
	    while(!q.empty()) {
	        int node = q.front();
	        q.pop(); 
	        bfs.push_back(node); 
	        
	        for(auto it : adj[node]) {
	            if(!vis[it]) {
	                q.push(it); 
	                vis[it] = 1; 
	            }
	        }
	    }
	    
	    return bfs; 
	}
  
  //DFS OF GRAPH =>
  
   void dfs_helper(int node,vector <int> adj[],vector <int> &vis,vector <int> &ans){
        ans.push_back(node);
        vis[node]=1;
        for(auto it : adj[node]) {
            if(!vis[it]) {
                dfs_helper(it,adj,vis,ans); 
            }
        }
    }
    
    vector<int> dfsOfGraph(int v, vector<int> adj[]) {
        vector <int> ans;
        vector <int> vis(v+1,0);
        for(int i=0;i<v;i++) {
            if(!vis[i]) dfs_helper(i,adj,vis,ans); 
        }
        return ans;
    }
                             
    //DJIKSTRAS ALGO =>
  
   vector <int> dijkstra(int v, vector<vector<int>> adj[], int s)
    {
        priority_queue<pair<int,int>,vector<pair<int,int>>,greater<pair<int,int>>>pq;
        vector <int> dist(v+1,INT_MAX);
        
        dist[s]=0;
        pq.push(make_pair(0,s));
        
        while(!pq.empty()){
            auto node = pq.top().second;
            auto nodedist = pq.top().first;
            pq.pop();
            
            for(auto nbr:adj[node]){
                if(nodedist+nbr[1]<dist[nbr[0]]){ 
                    dist[nbr[0]]=nodedist+nbr[1];
                    pq.push({dist[nbr[0]],nbr[0]});
                }
            }
        }       
        return dist;       
    }
                                                  
    //TOPOLOGICAL SORT (USING BFS) =>
  
  vector<int> topoSort(int v, vector<int> adj[]) 
	//Kahns Algo
	{
	    vector <int> indegree(v,0);
	    queue <int> q; //For bfs
	    
	    for(int i=0;i<v;i++){
	        for(auto it:adj[i]){
	            indegree[it]++; //To count the indegree of each node.
	        }
	    }
	    
	    for(int i=0;i<v;i++){
	        if(indegree[i]==0) q.push(i); //Push node having indegree 0
	    }
	    
	    vector <int> ans; //To store sorted order
	    while(!q.empty()){
	        int node = q.front();
	        q.pop();
	        ans.push_back(node); //Pushing nodes in the queue in topo sort form.
	        
	        for(auto it:adj[node]){
	            indegree[it]--; //Removing the adjacent edges.
	            if(indegree[it]==0) q.push(it);
	        }
	    }
	    return ans;
	}

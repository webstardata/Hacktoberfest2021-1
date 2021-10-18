
=======================================================

Article Title:CSRF
Author Name: ASWIN
Author Profile:https://github.com/tez-580/
Date: 18-10-21

=======================================================

**Cross-Site Request Forgery (CSRF)**
Cross-Site Request Forgery (CSRF) is an attack that forces an end user to execute unwanted actions on a web application in which they’re currently authenticated. 
With a little help of social engineering , an attacker may trick the users of a web application into executing actions 
of the attacker’s choosing. If the victim is a normal user, a successful CSRF attack can force the user to perform state changing requests like transferring funds,
changing their email address, and so forth. If the victim is an administrative account, CSRF can compromise the entire web application.


**Preventing CSRF attacks******

The most robust way to defend against CSRF attacks is to include a CSRF token within relevant requests. The token should be:

    Unpredictable with high entropy, as for session tokens in general.
    Tied to the user's session.
    Strictly validated in every case before the relevant action is executed

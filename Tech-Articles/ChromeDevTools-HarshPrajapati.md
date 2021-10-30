
=======================================================   
  
Article Title: Chrome Dev Tools Hidden Features  
Author Name: Harsh Prajapati  
Author Profile: https://github.com/glitchharsh  
Date: 30-10-2021  
  
=======================================================  

## Chrome Dev Tools Hidden Features

Chrome Dev Tools is one of the most used tools among web developers. But it has some amazing features that most developers are not aware of.
In this article, I will discuss the top 5 Chrome DevTools experimental features every developer should try.
1. CSS Overview — Every bit and piece of styles
CSS Overview provides a summary of all the styles used in a web page.
It includes detailed information about colors, fonts, media queries, and unused declarations. This feature comes in handy when you make CSS modifications to the UI, and you don’t need to use 3rd party tools like color picker anymore.

### CSS Overview Tab on Chrome Developer Tools
  
How to enable this feature?
* On Google Chrome, click View -> Developer -> Developer Tools.
* Open Settings.
* Click on Experiments Tab.
* Enable the CSS Overview.
* Close the DevTools window and open it again.
* A new tab will appear in DevTools as CSS Overview.

Even though this CSS Overview panel is an experimental feature, you will never turn it off once you use it. This feature is incredibly helpful and makes your CSS work a lot easier.

### CSP Violations — Warns for possible security vulnerabilities

Enabling this feature will add an extra layer of security to your application and reduce the vulnerabilities such as Cross-Site Scripting (XSS).

How to enable this feature?
* Developers can enable CSP Violation Breakpoints from the “Sources” tab as mentioned below.
* Go to Experiments Tab through Chrome Developer Tools.
* Check the Show CSP Violations view option.
* Close the DevTools window and open it again.
* Under CSP Violations Breakpoints, check Trusted Type Violations and violation types to activate the feature.

Chrome DevTools even shows the additional details on fixing them, just in front of the detected vulnerable code block.

### New Font Editor Tools — Flip font styles instantly

Did you know that you can instantly flip all the fonts on your website and see how they look without touching your code?
Chrome DevTools provide an experimental font editor tool that can be used to change font settings. You can change the font family, sizes, weight, height spaces using it and see the changes in real-time.

How to enable this feature?
* Go to Experiments Tab through Chrome DevTools.
* Check Enable New Font Editor Tools within Styles Pane.
* Close the DevTools window and open it again.
* Select the HTML element, which includes the font properties you want to change.
* Then, you will notice the Font Editor icon in the Styles pane.

### Dual Screen Mode — Emulate dual screens for foldable devices

By enabling the Dual Screen Mode, you can debug your web application on dual-screen devices within the Chrome DevTools emulator itself.
This feature is a lifesaver when it comes to debugging dual-screen devices like surface Duo.**  

How to enable this feature?
* Go to Experiments Tab through Chrome DevTools.
* Check Emulation: Support dual-screen mode.
* Close the DevTools window and open it again.
* Open the web page you want to test via the Toggle Device Toolbar option on the top right corner of the DevTool window.
* Switch the emulator to a Surface Duo device (or another available foldable device).
* Then click the Toggle dual-screen mode to emulate your web application in dual-screen mode.

### Full Accessibility Tree View — Inspect elements with more accessibility details

With the Chrome DevTools Accessibility Tree, you can inspect accessibility objects created for each DOM element.
This feature is a bit familiar to Inspect Elements tab. But it allows you to dig deep down and explore more accessibility details of your web application.

How to enable this feature?
* Go to Experiments Tab through Chrome DevTools.
* Check the Full accessibility tree view in the Elements pane.
* Close the DevTools window and open it again.
* Switch Elements view mode to Full Accessibility Tree View by clicking the new accessibility button shown in the Elements panel.

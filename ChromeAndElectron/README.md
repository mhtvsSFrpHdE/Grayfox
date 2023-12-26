## Chrome and electon

Different apps may have different method to apply css.

Different from Firefox, Chrome and Chromium based browser use `filter: opacity(1)` instead of `0.9999999`.

### Obsidian

When it comes to Obsidian, this app have built in custom css support.  
Simply apply filter opacity to html tag.

### Visual Studio Code

Not yet an extension founded straight forwarded to apply custom css.  
Edit `workbench.html` under `C:\Users\<user name>\AppData\Local\Programs\Microsoft VS Code\resources\app\out\vs\code\electron-sandbox\workbench\workbench.html`  
Apply filter opacity to html tag.

After restart Visual Studio Code, a hint says the installation is broken.  
Click on gear icon and choose "Don't show again".

### Github Desktop

Like Visual Studio Code, find `C:\Users\<user name>\AppData\Local\GitHubDesktop\app-3.3.6\resources\app\index.html`  
Apply filter opacity to html tag.

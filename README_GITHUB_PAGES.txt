NEXORA - GitHub Pages setup

1. Create a GitHub repository (for example: Nexora).
2. Upload ALL files and folders in this directory to the repository root.
   Important: index.html must be at the repository root, not inside another folder.
3. In GitHub, open Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Choose branch main and folder /(root), then Save.
6. Wait for the published Pages URL and open it.

Path fixes included for hosting under a repository URL such as:
https://USERNAME.github.io/Nexora/

Important limitations:
- This project is a static HTML/CSS/JavaScript site. The current login is a front-end demo
  using browser localStorage; it does not authenticate users securely on a server.
- Job applications are saved in the visitor's own browser localStorage. They are not sent
  to a database and will not appear on another device/admin account.
- GitHub Pages cannot run PHP, Node server code, or a database backend.

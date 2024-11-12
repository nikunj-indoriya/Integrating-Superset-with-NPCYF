# Installation of MySQL server, MySQL Workbench and Superset
- Visit Docker Installation documentation for Windows [Link to Document.](https://docs.docker.com/desktop/setup/install/windows-install/)
- Download the MySQL Installer from the [Official Site of MySQL.](https://downloads.mysql.com/archives/installer/)
## Installation of MySQL Server
- Download the MySQL Installer for Windows. Choose the appropriate version (e.g., MySQL Installer
 Community).
- Launch the MySQL Installer executable.
- Follow the setup wizard:
  <ul>
    <li>Select "Server Only" if you only want the server.</li>
    <li>The installer will check if any required components are missing. Install any prerequisites if prompted</li>
    <li>Ensure that MySQL Server is selected along with any other tools you need (e.g., MySQL Workbench). </li>
    <li>Configure MySQL Server:
      <ul>
        <li>Choose "Standalone MySQL Server".</li>
        <li>Set the port (default is 3306). Ensure it’s open if using firewall.</li>
        <li>Select the authentication method (default is ”Use Legacy Authentication Method”).</li>
        <li>Enter and confirm a root password. This will be used for administrative access.</li>
      </ul>
    </li>
    <li>Review the configuration and click "Execute" to apply the settings.</li>
  </ul>
- Open the command prompt and connect to MySQL using mysql command line `mysql -u root -p`.
## Installation of Superset
- Install Docker desktop using the downloaded Docker Desktop Installer.
- Search for superset in the Docker desktop and pull the latest version available to run it as a container.
- Note the latest tag and use in the below provided code.
- Open the command prompt and use the below provided codes to load the superset in local machine.
 ![image](https://github.com/user-attachments/assets/1e0f4a17-74ba-4be9-a260-8c406906b352)
- This is the detailed video which can help with Installation of Apache Superset [Youtube Video.](https://youtu.be/mAnp_yugoWM?si=9EdzYg_qamFjA1U3)

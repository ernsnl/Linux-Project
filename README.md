# Udacity FullStack Nanodegree Project

This project is about Linux Server Configuration. In this project, a Linux server is created and their ports are configured.

Currently this project uses Amazon LightSail for more information about LightSail please visit the [website](https://amazonlightsail.com/)

App is currently serving at IP Address ```50.17.57.209```

Due to limitations in Amazon LightSail SSH port cannot be changed, however extra ssh port is used by configuring sshd_config file. SSH Ports ```22 and 2200```

HTTP Port ```80```
NTP Port ```123```

To connect to the server with SSH please use the key in project.

Known Issue; Even though, user is created and ssh is allowed. User cannot login for the server. (Expect for the default user: ubuntu)

Currently two application is serving in this IP Address.
1. [Item Catalog Project](itemcatalog.ernsnl.com)
2. [Secondary App](secondaryapp.ernsnl.com) 

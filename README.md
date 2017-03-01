# Udacity FullStack Nanodegree Project

This project is about Linux Server Configuration. In this project, a Linux server is created and their ports are configured.

Currently this project uses Amazon LightSail for more information about LightSail please visit the [website](https://amazonlightsail.com/)

App is currently serving at IP Address ```50.17.57.209```

Due to limitations in Amazon LightSail SSH port cannot be changed, however extra ssh port is used by configuring sshd_config file. SSH Ports ```22 and 2200```

1. HTTP Port ```80```
2. NTP Port ```123```
3. SSH Port ```22``` and ```2200```

Grader user is created for the project and it is given sudo access.
To connect to the server with SSH please use the key in project.
Pass: ```183461``` or ```729467```

Currently two application is serving in this IP Address.
1. [Item Catalog Project](itemcatalog.ernsnl.com)
2. [Secondary App](secondaryapp.ernsnl.com)

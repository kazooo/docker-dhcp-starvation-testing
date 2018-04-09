# Docker containers for DHCP Starvation atack testing

Folders contain configuration files for two tests:

 **one-server-one-client** with configuration for DHCP server and DHCP client
  
  ```
  docker-compose up -d dhcp-server
  ```
  to run only server
  ```
  docker-compose up -d dhcp-client
  ```
  to run only client
  ```
  docker-compose up -d
  ```
  to run both
  
  
  **two-servers-one-client** with configurations for two DHCP servers and one DHCP client
  ```
  docker-compose up -d dhcp-server1 dhcp-server2
  ```
  to run only servers
  ```
  docker-compose up -d dhcp-client
  ```
  to run only client
  ```
  docker-compose up -d
  ```
  to run both

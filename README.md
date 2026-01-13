# OCS-Inventory-Docker

# Install Docker 

```
sudo apt update
sudo apt install git
sudo apt install docker.io
sudo apt install docker-compose

```

# OCS inventory version

# https://github.com/OCSInventory-NG/OCSInventory-Docker-Image


# Install OCS Inventory

```
sudo git clone https://github.com/OCSInventory-NG/OCSInventory-Docker-Image.git
cd OCSInventory-Docker-Image
cd 2.12.3

```

# We edited the Docker configuration file

```
sudo vi docker-compose.yml

```

# Now we change where expose to the following:

```
ports:
      - "3306:3306"

```
# Type Esc > : > wq! for save file 

# Run container

```

sudo docker-compose up -d

```
# Web Interface
# We enter the device's IP address in the browser and it will automatically redirect us.

# The default username and password are:

# admin
# admin

# The agent download page
```
https://ocsinventory-ng.org/?page_id=1548&lang=en
```

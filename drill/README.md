# Network Utilities

Use drill as you would for dig:

    docker run jonbrouse/docker-utilities:drill alpinelinux.org 
    docker run jonbrouse/docker-utilities:drill alpinelinux.org @8.8.8.8
    
To perform a reverse lookup (get a name from an IP) use the following syntax:

    docker run jonbrouse/docker-utilities:drill alpinelinux.org @8.8.8.8 -x 8.8.8.8 @208.67.222.222

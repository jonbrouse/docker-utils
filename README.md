# Utilities Inside Docker Images

alpine based images for container based access to the following tools.

## Curl

     docker run --rm jonbrouse/utils:curl -v https://secure.example.io

## DNS

     docker run --rm jonbrouse/utils:drill alpinelinux.org
     docker run --rm jonbrouse/utils:drill alpinelinux.org @8.8.8.8
     docker run --rm jonbrouse/utils:drill alpinelinux.org @8.8.8.8 -x 8.8.8.8 @208.67.222.222

## MySQL

     docker run --rm jonbrouse/utils:mysql -h db.example.com -u username -ppassword


## Netcat

     docker run --rm jonbrouse/utils:nc -v -n -z -w1 127.0.0.1 8080-9090


# Related Links

- http://wiki.alpinelinux.org/wiki/Main_Page
- https://www.sans.org/security-resources/sec560/netcat_cheat_sheet_v1.pdf

# haproxy

# https://webhostinggeeks.com/howto/how-to-configure-and-use-haproxy-as-a-reverse-proxy/

# sudo apt update && apt upgrade -y

# sudo apt install haproxy -y

# sudo nano /etc/haproxy/haproxy.cfg

# Checking the Configuration

sudo haproxy -c -f /etc/haproxy/haproxy.cfg

# Testing the Setup

curl http://haproxy_server_ip

This is the same image as the official nginx:alpine image, the only difference is that it only exposes the port 80 instead of both the port 80 and the 443 port.

The reason for doing this is because AWS does not support the Application Load Balancer with multiple exposed ports.

Original code: https://github.com/nginxinc/docker-nginx/tree/0dd9ef6a337474293b5e36c95a85da99b11e1a0a/mainline/alpine

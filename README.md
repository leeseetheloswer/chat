docker run --restart always --name Nginx -d -v  D:\work\chatgpt\chatgpt/nginx/html:/usr/share/nginx/html -v  D:\work\chatgpt\chatgpt/nginx/conf/nginx.conf:/etc/nginx/nginx.conf -p 8080:80 nginx

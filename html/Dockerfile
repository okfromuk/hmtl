# 1. Use the official Nginx image from Docker Hub
FROM nginx:latest

# 2. Remove the default Nginx web content
RUN rm -rf /usr/share/nginx/html/*

# 3. Copy your local HTML files into the container
COPY . /usr/share/nginx/html

# 4. Expose port 80 so we can view it in browser
EXPOSE 80

# 5. Start Nginx (optional - Nginx image starts automatically)
CMD ["nginx", "-g", "daemon off;"]

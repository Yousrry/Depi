# Use the official Nginx image from the Docker Hub
FROM nginx:latest

# Copy the custom Nginx configuration file to the container
COPY nginx.conf /etc/nginx/nginx.conf

COPY index.html /usr/share/nginx/html/

# Expose port 8080 to the outside world
EXPOSE 8080

# Start Nginx server
CMD ["nginx", "-g", "daemon off;"]

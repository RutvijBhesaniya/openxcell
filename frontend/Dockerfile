# Use the official Nginx image as base
FROM nginx:latest

# Copy custom configuration file if needed
# COPY ./nginx.conf /etc/nginx/nginx.conf

# If you need to add custom HTML/CSS/JS files, uncomment and use the following line
# COPY ./my-html-files/ /usr/share/nginx/html/

# Expose port 80
EXPOSE 80

# Start Nginx server
CMD ["nginx", "-g", "daemon off;"]

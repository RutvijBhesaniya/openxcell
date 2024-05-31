# Use NGINX as a lightweight server
FROM nginx:alpine

# Copy your static front-end files to NGINX's html directory
COPY index.html /usr/share/nginx/html/

# Expose port 80 to the outside world
EXPOSE 80

# Command to run NGINX in the foreground
CMD ["nginx", "-g", "daemon off;"]
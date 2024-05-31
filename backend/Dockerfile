# Use the official Apache image as base
FROM httpd:latest

# Copy custom configuration file if needed
# COPY ./my-httpd.conf /usr/local/apache2/conf/httpd.conf

# If you need to add custom HTML/CSS/JS files, uncomment and use the following line
# COPY ./my-html-files/ /usr/local/apache2/htdocs/

# Expose port 80
EXPOSE 800

# Start Apache server
CMD ["httpd-foreground"]

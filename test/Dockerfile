FROM nginx:alpine

# Remove the default Nginx HTML
RUN rm -rf /usr/share/nginx/html/*

# Add custom index.html
COPY index.html /usr/share/nginx/html/index.html

# Expose port 80
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]


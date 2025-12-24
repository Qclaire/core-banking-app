FROM nginx:alpine

# Remove the default Nginx HTML
RUN rm -rf /usr/share/nginx/html/*

# Add custom index.html
RUN echo '<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Virk Deployment</title>
</head>
<body>
    <h1>This was deployed by Virk Github Automation</h1>
</body>
</html>' > /usr/share/nginx/html/index.html

# Expose port 80
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]


# Use the official Nginx image
FROM nginx:alpine

# Copy website files into the default Nginx HTML directory
COPY . /usr/share/nginx/html


# Expose port 80 for serving the website
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]
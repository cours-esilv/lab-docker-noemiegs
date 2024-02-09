FROM nginx:alpine

# Copy the HTML files to the nginx directory
COPY . /usr/share/nginx/html

# Set the environment variable for the back-end URL
ENV WS_BACK_URL=http://backend-service:5000

# Expose port 80
EXPOSE 80

# Set the entrypoint
ENTRYPOINT ["nginx", "-g", "daemon off;"]

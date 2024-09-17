FROM nginx:1.21.6

# Remove the default server configuration
RUN rm /etc/nginx/conf.d/default.conf

# Copy your custom Nginx configuration
COPY nginx.conf /etc/nginx/nginx.conf

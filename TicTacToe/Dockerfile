# Use official nginx image
FROM nginx:alpine

# Copy your static files into nginx's default serve directory
COPY . /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# nginx starts automatically
CMD ["nginx", "-g", "daemon off;"]
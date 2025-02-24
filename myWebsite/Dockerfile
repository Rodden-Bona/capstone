# Use an official Node.js runtime as a base image
FROM node:latest

# Set working directory in the container
WORKDIR /app

# Copy project files to container
COPY . .

# Install a simple HTTP server
RUN npm install -g http-server

# Expose port 8080
EXPOSE 8080

# Start server
CMD ["http-server", "-p", "8080"]
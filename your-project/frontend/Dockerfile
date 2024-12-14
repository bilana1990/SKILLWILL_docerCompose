# Use the official Node.js image
FROM node:16

# Create and set the working directory
WORKDIR /app

# Install dependencies
COPY package*.json ./
RUN npm install

# Copy the application code
COPY . .

# Expose port and start the server
EXPOSE 5000
CMD ["node", "server.js"]
# Use the official Node.js image as base
FROM node:14-alpine

# Set the working directory in the container
WORKDIR /app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application
COPY . .

# Expose port 3000 (or any other port your Node.js application listens on)
EXPOSE 3000

# Start the Node.js application
CMD ["node", "app.js"]

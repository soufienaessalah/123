# Base image
FROM node:18

# Set working directory
WORKDIR /usr/src/app

# Copy application files
COPY node-express/ .

# Install dependencies
RUN npm install

# Start application
CMD ["npm", "start"]

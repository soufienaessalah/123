# Base image
FROM node:18

# Set working directory
WORKDIR /usr/src/app

# Copy application files
COPY nextjs/ .

# Install dependencies
RUN npm install

# Start application
CMD ["npm", "run", "dev"]

# Use Node.js 22 Alpine
FROM node:22-alpine

# Set working directory
WORKDIR /app

# Copy package files
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy application files
COPY . .

# Expose port 4200 (Angular's default dev server port)
EXPOSE 4200

# Start the application
CMD ["npm", "start"]
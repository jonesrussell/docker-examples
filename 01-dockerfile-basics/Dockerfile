FROM node:25-alpine

WORKDIR /app

# Copy package files first (better layer caching)
COPY package*.json ./

# Install dependencies
RUN npm install --production

# Copy application code
COPY index.js .

# Document the port (informational)
EXPOSE 3000

# Start the server
CMD ["node", "index.js"]

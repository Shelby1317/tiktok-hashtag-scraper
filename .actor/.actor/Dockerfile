FROM apify/actor-node-playwright:18

# Copy package files
COPY package*.json ./

# Install dependencies
RUN npm ci --only=production

# Copy source code
COPY . ./

# Run the actor
CMD npm start

# Step 1: Use Node.js LTS version
FROM node:18

# Step 2: Create app directory
WORKDIR /usr/src/app

# Step 3: Copy package.json and install dependencies
COPY package*.json ./
RUN npm install

# Step 4: Copy app source
COPY . .

# Step 5: Expose port and define default command
EXPOSE 3000
CMD ["npm", "start"]

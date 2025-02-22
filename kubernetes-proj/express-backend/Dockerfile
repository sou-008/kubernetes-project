# Use the official Node.js image
FROM node:14

# Set the working directory
WORKDIR /app

# Install dependencies
COPY package.json /app/
RUN npm install

# Copy the Express app
COPY . /app/

# Expose the port Express will run on
EXPOSE 3000

# Command to run the app
CMD ["npm", "start"]
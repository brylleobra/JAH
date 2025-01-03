# Frontend Dockerfile

FROM node:18

WORKDIR /app

# Install dependencies

COPY package.json package-lock.json ./
RUN npm install

# Copy the source code
COPY . .

# Expose app to port 3000
EXPOSE 3000

CMD ["npm","start"]
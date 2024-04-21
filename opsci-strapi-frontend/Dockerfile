FROM node:18-alpine
WORKDIR /opt
COPY . .
RUN yarn install
EXPOSE 5173
CMD ["yarn", "dev", "--host", "0.0.0.0", "--port", "5174"]
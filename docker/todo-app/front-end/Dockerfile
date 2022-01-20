FROM node:14-alpine
EXPOSE 3000
WORKDIR /front-end
ADD node_modules.tar.gz ./front-end
COPY . ./front-end
CMD ["npm" "start"]
FROM node:14-alpine
EXPOSE 3001
WORKDIR /back-end
ADD node_modules.tar.gz ./back-end
COPY . ./back-end
CMD ["npm" "start"]
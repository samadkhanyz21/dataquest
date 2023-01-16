# Use an existing docker image as a base
FROM alpine


# Download & install a dependency
RUN apk add --update redis
RUN apk add --update gcc


# Tell the container what to do when it starts as a container
CMD ["redis-server"]
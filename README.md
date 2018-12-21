
# thugnasty/squid

Based on [minimum2scp/squid](https://hub.docker.com/r/minimum2scp/squid), this image provides basic user/pass authentication to the proxy server.

It only allows complete HTTP access to authenticated users.

To run:

        docker run -d -p 3128:3128 --name squid thugnasty/squid:latest

The proxy address is 127.0.0.1 for Linux hosts, and the IP found in %DOCKER_HOST% on Windows hosts. The proxy server is listening on port 3128

The username is _hobo_ and the password is _derelict_

Note: [minimum2scp/squid](https://hub.docker.com/r/minimum2scp/squid) also adds SSH, more details on how to use it can be seen on their [Docker Hub page](https://hub.docker.com/r/minimum2scp/squid)
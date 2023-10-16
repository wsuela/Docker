FROM alpine

RUN apk add -U curl wget bash ca-certificates openssl ncurses coreutils python3 make gcc g++ libgcc linux-headers grep util-linux binutils findutils    
RUN apk add nodejs npm
RUN apk add openjdk8
# RUN curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash
# RUN source /root/.nvm/nvm.sh \
#     && nvm install 14 \
#     && nvm use 14 
# RUN nvm install 14
# RUN nvm use 14
RUN npm install n -g
RUN n 14
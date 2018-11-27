FROM nginx:alpine

RUN apk add --no-cache wget unzip && \
  wget https://github.com/mayswind/AriaNg-DailyBuild/archive/master.zip && \
  unzip -o master.zip && \
  cp -r ./AriaNg-DailyBuild-master/* /usr/share/nginx/html/ && \
  rm -rf ./master.zip ./AriaNg-DailyBuild-master

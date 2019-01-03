FROM nginx:alpine

RUN apk add --no-cache git curl jq unzip && \
  wget https://github.com/mayswind/AriaNg/releases/download/1.0.0/AriaNg-1.0.0.zip && \
  unzip -o AriaNg-1.0.0.zip -d /usr/share/nginx/html && \
  rm AriaNg-1.0.0.zip

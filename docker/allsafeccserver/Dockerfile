FROM alpine:latest
EXPOSE 5000

RUN apk add --no-cache python3
RUN apk add --no-cache git

RUN python3 -m pip install Flask
RUN python3 -m pip install requests

RUN git clone https://github.com/allsafebotnet/allsafe_cc;

WORKDIR allsafe_cc/allsafecc
CMD python3 __init__.py

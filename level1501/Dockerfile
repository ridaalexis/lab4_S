FROM bash

RUN apk add file

RUN adduser -D suzen
USER suzen

ADD hello /bin/hello
WORKDIR /home/suzen

COPY first ./

ENTRYPOINT ["/bin/hello"]


#Solution
# tar -xf first 
# tar -xf archive 
# tar -xf try_me 
# unzip latest 
# Archive:  latest
# replace latest? [y]es, [n]o, [A]ll, [N]one, [r]ename: r
# cat latest1 | grep "flag"


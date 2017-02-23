FROM ubuntu:trusty

# update and install dependencies
RUN apt-get -y update
RUN apt-get install -y curl

# install RecordStream - see https://github.com/benbernard/RecordStream
RUN curl -fsSL https://recs.pl > recs
RUN chmod +x recs

# use the RecordStream binary
ENTRYPOINT ["./recs"]

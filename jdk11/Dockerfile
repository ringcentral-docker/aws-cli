FROM amazon/aws-cli:2.8.7
LABEL maintainer="john.lin@ringcentral.com"

#==============
# Install java
#==============
RUN apk update \
    && apk add git openjdk11

#==============
# Show java version
#==============
RUN java -version

ENTRYPOINT ["/usr/local/bin/aws"]

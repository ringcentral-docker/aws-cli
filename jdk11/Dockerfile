FROM amazon/aws-cli:2.8.7
LABEL maintainer="john.lin@ringcentral.com"

#==============
# Install java
#==============
RUN yum update -y \
    && yum install git java-11-openjdk-devel -y

#==============
# Show java version
#==============
RUN java -version

ENTRYPOINT ["/usr/local/bin/aws"]

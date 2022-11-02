FROM amazon/aws-cli:2.8.7
LABEL maintainer="john.lin@ringcentral.com"

#==============
# Install git
#==============
RUN yum update -y \
    && yum install git -y

#==============
# Install java
#==============

RUN amazon-linux-extras install java-openjdk11

#==============
# Show java version
#==============
RUN java -version
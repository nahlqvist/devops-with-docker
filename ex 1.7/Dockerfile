#Start from the ubuntu
FROM ubuntu:22.04

#Use /usr/src/app as our workdir
WORKDIR /usr/src/app

#Install curl
RUN apt-get update && apt-get install -y curl

#Copy the script.sh file
COPY script.sh .

# Alternatively, if we skipped chmod earlier, we can add execution permissions during the build.
RUN chmod +x script.sh

# When running docker run the command
CMD ./script.sh
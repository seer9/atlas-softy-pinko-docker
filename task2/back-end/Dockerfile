FROM ubuntu:latest

# Update and upgrade package list and install Python3 and pip3
RUN apt-get update 

RUN apt-get upgrade -y

RUN apt-get install -y python3 python3-pip

# Install Flask using pip3
RUN pip3 install Flask

# change working directory and copy contents to the container

WORKDIR /app

COPY . /app

# expose the specific port to the outside world or outside this "machine"

EXPOSE 5252

# install api to create the endpoint at 5252 to echo "hello, world"

CMD ["python3", "api.py"]
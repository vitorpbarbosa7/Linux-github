# Dockerfile:  Blueprint for building images

# Docker Image: Template for running Containers

# Docker Container: Actual running process

FROM python:3.7.6

# ADD file dir_you_wish
ADD main.py .

# install requirements 
RUN pip install requests beautifulsoup4

# Specify entry command
CMD [ "python", "./main.py"]
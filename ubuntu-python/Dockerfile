# Force platform to avoid issues with Apple silicon processors
FROM --platform=linux/amd64 ubuntu

# Install dependencies
RUN apt update
RUN apt install python3 -y
RUN apt install python3-pip -y
RUN apt install curl -y
RUN apt install dnsutils -y
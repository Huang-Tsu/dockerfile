FROM ubuntu:latest

# Set the working directory to the user's home directory
WORKDIR /home/huang

# Install necessary packages
RUN apt-get update && apt-get upgrade && apt-get install -y vim git g++ cmake


# Add a user with root privileges
RUN useradd huang

# Set a password for the user (replace 'password' with your desired password)
#RUN echo 'myuser:password' | password

# Switch to the user
USER huang


# Set the entry point for your application, if needed
# ENTRYPOINT ["/path/to/your/application"]

# Optionally, set other environment variables or instructions as needed

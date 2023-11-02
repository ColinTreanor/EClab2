# Set the base image to use
FROM gcc:latest
# Copy the C program into the container
COPY helloworld.c .
# Compile the C program
RUN gcc -o helloworld helloworld.c
# Set the command to run when the container starts
CMD ["./helloworld"]
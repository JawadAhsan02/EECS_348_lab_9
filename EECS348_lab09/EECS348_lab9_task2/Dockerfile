# Set the base image to use
FROM gcc:latest
# Copy the C program into the container
COPY 1.c .
# Compile the C program
RUN gcc -o 1 1.c
# Set the command to run when the container starts
CMD ["./1"]

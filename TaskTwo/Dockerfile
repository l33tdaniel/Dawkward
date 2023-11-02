# Set the base image to use
FROM gcc:latest
# Copy the C program into the container
COPY main.cpp .
# Compile the C program
RUN g++ -o main main.cpp
# Set the command to run when the container starts
CMD ["./main"]
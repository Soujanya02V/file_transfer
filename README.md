This project demonstrates how to use Node.js streams to read from a file and write to another file using the fs and path modules. It's a basic example of efficient file handling with a focus on memory usage using highWaterMark.

>> Files Used
input.txt: The source file from which data is read.

output.txt: The target file where data is written.

>> How It Works
A readable stream is created for input.txt.

A writable stream is created for output.txt.

Data is piped from the readable stream to the writable stream.

Error handling is added for both read and write operations.

>> Key Concepts
Streams are used to handle large files efficiently without loading the entire content into memory.

The highWaterMark is set to 16 bytes to control how much data is read at a time.

Encoding is set to 'utf-8' (Note: You have a typo in encodeing; it should be encoding).

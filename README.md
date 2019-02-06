# Basic socket construction and usage

This project is to help understand the workings of basic 
communication. The concepts presented in this project hold
true for all multi-process exchange of data over sockets.

## Goals

 * Understand the code organization and the relationship of
the Socket class in encoding and decoding messages.

 * Timing - Perform timing analysis of a message delivered
through the Socket. Expand the code to handle 100, 1,000, 
and 10,000 messages. What are your findings on the scaling
of the code?

 * Modify - a) to include additional data fields, and b) to 
receive responses from the server.

 * Replace the String payload with a JSON or XML encoded
data. The encoding classes have been provided. What are
the ramifications of this change?

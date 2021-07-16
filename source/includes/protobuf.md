# Protobuf

## Protobuf Overview

Protobuf is a messaging protocol introduced and maintained by Google. The implementation details are hidden from the user and is popular because the .proto files can be used to generate code for a multitude of languages with the guarantee that both the sender and receiver can process the resulting message. The resulting messages are much smaller than other formats such as JSON for those interested in reducing bandwidth and reduced processing times due to the protocol being able to send and receive binary data in its native format.

Protobuf messages are identical in TCP/IP and in Websockets. The sending of the messages is the same and the receiving of messages is the same therefore the descriptions of the following messages will work the same for TCP/IP and for Websockets.

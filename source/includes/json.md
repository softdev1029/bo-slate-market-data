# JSON

## JSON Overview

All JSON messages sent by the client are preceeded by a HEADER message which has the length of the JSON message which follows it. Example, {"Len":179}{"msg1":"H".........}. The allows the server to determine the length of the message which follows the header allowing for more efficient parsing. The Server responses do not include the header.

JSON messages are identical in TCP/IP and in Websockets. The sending of the messages is the same and the receiving of messages is the same therefore the descriptions of the following messages will work the same for TCP/IP and for Websockets.

JSON Order Entry messages will vary according to the message type and the order type. Use the tables below to determine the required fields based on message type and order type to build the correct JSON Order Entry string.

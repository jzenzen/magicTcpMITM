# magicTcpMITM
TCP stream splitter/compressor/tap/recorder/player ManInTheMiddle

What this project aims to do:
* A basic software to:
  * Connect to a TCP server and present the stream to be connected and consumed by multiple clients instead of one.
  * The output streams can be:
    * identical to the input
    * packed version of the input
    * packed and splitted with a small knowledge of the underlaying structure
  * The input stream can be recorded to a file
  * The recorded file can be connected as a input to replay the TCP-stream again. (A bit like tcpdump, but with only the payload)

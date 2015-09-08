# chainstream

This module has been partially adopted. It is now an experimental sub-module of '[ioutil](https://github.com/Regal-Internet-Brothers/ioutil)'. This branch acts as a standalone experimental version. For a proper proxy-import, pull the latest version from the ["master" branch](https://github.com/Regal-Internet-Brothers/chainstream/tree/master).

**ORIGINAL README**:

A "multi-stream" class for the [Monkey programming language](https://github.com/blitz-research/monkey). Basically, this provides a class called 'ChainStream', which allows you to "chain" together standard 'Stream' objects. This is useful for splitting data into multiple streams. For example, you could use this in a networking context to split up packets. You could also use this to put together a file from several pieces. Any 'Stream' objects will work, and will be accessed individually.

This module is currently experimental, and is therefore not a part of the [main "modules" repository](https://github.com/Regal-Internet-Brothers/modules).

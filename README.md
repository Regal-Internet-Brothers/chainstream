# chainstream

**This module was originally its own experimental module.** Today, it is a sub-module found in '[ioutil](https://github.com/Regal-Internet-Brothers/ioutil)'. Please use that module instead. This branch now contains a module/import proxy to '[ioutil](https://github.com/Regal-Internet-Brothers/ioutil)'. For the last proper version before this became a sub-module, visit the ["standalone" branch](github.com/Regal-Internet-Brothers/chainstream/tree/standalone).

**ORIGINAL README**:

A "multi-stream" class for the [Monkey programming language](https://github.com/blitz-research/monkey). Basically, this provides a class called 'ChainStream', which allows you to "chain" together standard 'Stream' objects. This is useful for splitting data into multiple streams. For example, you could use this in a networking context to split up packets. You could also use this to put together a file from several pieces. Any 'Stream' objects will work, and will be accessed individually.

This module is currently experimental, and is therefore not a part of the [main "modules" repository](https://github.com/Regal-Internet-Brothers/modules).

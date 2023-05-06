# 8-Bit Buckaroo (eightbb)

This is 8-Bit Buckaroo, a bytebeat synthesizer programmed in [Cmajor](https://cmajor.dev/). It is a port of an Android app.

## How to Play It

You can use the provided synthesizer patch in your DAW or with a handful of tools provided by Sound Stacks. Alternatively, you can use the synthesizer in your own Cmajor patch and modify it.

### Using the Provided Synthesizer

To use 8-Bit Buckaroo, you need to run the Cmajor patch `eightbb.cmajorpatch`. This can be done in a DAW or other audio plug-in host by loading the patch inside of Sound Stacks' patch-hosting [plug-in](https://cmajor.dev/docs/GettingStarted#loading-patches-in-your-daw-with-the-cmajor-vstau-plugin). You can also run patches in VSCode with the [Cmajor VSCode extension](https://cmajor.dev/docs/GettingStarted#using-cmajor-in-vscode), or use one of the other methods provided by Sound Stacks.

Note that the sampling rate at which the patch is run will affect the results.

## How Does it Work?

Bytebeat synthesis typically involves incrementing some counter variable and generating audio samples by performing compound one-liner arithmetic and bit-wise operations on it. See more at http://canonical.org/~kragen/bytebeat/ For 8-Bit Buckaroo the operations were arbitrarily chosen, influenced by prior art and sonic results.
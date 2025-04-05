# adobe-font-extractor
C# program to extract Adobe font files from Creative Cloud on Windows. Looking for MacOS? Check out Kalaschnik's repository [here](https://github.com/Kalaschnik/adobe-fonts-revealer).

## Usage
Download the source code and make sure you have a .NET Runtime that's somewhere in version 5 and a recent enought .NET SDK installed, then run from the command line using dotnet run (ask chatgpt to walk you through it all if you're having problems). 
Because Adobe programs dynamically load their fonts in and out of memory using their obfuscated file format, it's possible you'll need to have an adobe program open and using one of the fonts (I'm honestly not super sure though, just try it if things don't work).

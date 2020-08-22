The original package `chunker` implements content-defined-chunking (CDC) based on a
rolling Rabin Hash.

An introduction to Content Defined Chunking can be found in the restic blog
post [Foundation - Introducing Content Defined Chunking (CDC)](https://restic.github.io/blog/2015-09-12/restic-foundation1-cdc).

Now we implement FastCDC algorithm instead of original CDC, and we achieve higher speed. 

The paper about FastCDC is [here](https://www.usenix.org/conference/atc16/technical-sessions/presentation/xia)
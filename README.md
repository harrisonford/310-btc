# 310 Bitcoin challenge 


## Introduction
So there's a guy that calls himself "pip", offering 310 BitCoins (BTC) to who can solve this image riddle. 
We're going to try to solve, but because we're almost 1 week behind, first we'll replicate other people's 
findings and theories. 

![Samuel Madariaga Roman suck a dick](challenge.png)


## Updated state of the riddle:
* 0.1 BTC *solved*.
* 0.2 BTC *solved*.
* 0.31 BTC *not solved !*
* 310 BTC *solved*.

## Shout-outs
Shout-outs to [r/crypto_jedi_ninja](https://www.reddit.com/user/crypto_jedi_ninja) 
for compiling the first list of findings from the reddit which I used:

* Creator calls himself "pip", some people believe this is a hint to 
[this riddle-problem](https://www.theguardian.com/science/2017/nov/20/did-you-solve-it-this-apple-teaser-is-hard-core).
* According to pip: Can only *partly* be solved by printing the image and not using software. This means we may need
to print the image and make some drawings on it to find something.
* There's a QR code found on the alpha layer (check the notebook).
* Pip used Least Significant Bit (LSB) to hide information in 310, he could be using it in more places.
* According to pip, he expects you to message the SHA256 on a single line 
[when you get to this page](https://bitcoinchallenge.codes/register-310/).
* Some inferred you need to find three smaller keys with small rewards to access the big one. 
Those keys are 0.31, 0.2 and 0.1 BTC, a guy called *Lustre* was confirmed by pip to have found the 0.1 BTC key.
* The values for each key could be another hint: 0.31, 0.2 and 0.1.
* The original image used can be [seen here](https://tineye.com/search/00c4ec33b3746f9f5b61946101561e15a694868e/).
*note: at the start I didn't know what this meant hehe xd*
* Some say it could be [a mosaic puzzle](https://airccj.org/CSCP/vol7/csit76703.pdf), 
others that it could be based on 
[voronoi diagrams](http://msn.iecs.fcu.edu.tw/~ccc/profile/publish/ij_paper2/IJ-664.pdf).
* Curved lines and circle on the image may be alluding 
[to this older riddle](https://steemit.com/bitcoin/@mmorsl/solution-of-the-bitcoin-crypto-puzzle-level-4-by-zden) 
which used Bezier curves.
* There are 21 characters in the image: L 3 C E O 2 7 5 K O D 8 9 9 D 4 F A 1 F 6 4
* There are 3 letter groups in a grid, they could be words from the 
[Bip-18 word algorithm](https://github.com/bitcoin/bips) or just hexadecimal code. 
The grid contains the following: 511 B20 332 328 410 530 | 22B 0FE 52E D0F 7A1 65B | 52C 7E7 511 2F6 56F C4B.

A second shout-out to 
[u/JTobcat](https://www.reddit.com/user/JTobcat) for his 
[amazing google doc](https://docs.google.com/document/d/1nUAhlC_n21ZLZcRAHpLw9G--gpk4NUVIJqVp9F68qp4/preview). 
A ramp-up/compilation of pretty much every info about solving this you can get.


That's all I have for now, be sure to 
[check the reddit](https://www.reddit.com/r/Bitcoin/comments/9kq7it/introducing_the_310_btc_bitcoin_challenge/) 
in case *pip* drops another hint.


## Getting Started

If you don't know much about python or jupyter it's highly recommended to paste this repository link 
to binder and interact with the code, you can do that if you press this pink button:
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/harrisonford/310-btc/master)

Otherwise feel free to download this notebook and play to your mind's contempt, just give a shout-out to the
contributors of this document that's all (*because harrisonford feels dirty putting a license to this*).


## Contributing
<a id='intro'></a>

* [ipassala](https://github.com/ipassala): The dude that knows about bitcoin.
* [harrisonford](https://github.com/harrisonford): The dude that knows a bit about images.


*There's a limit that breaks desire.*

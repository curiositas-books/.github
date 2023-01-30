# Curiositas - Rediscovering the World of Computation

<p align="center">
  <a href="#motivation">Motivation</a> |
  <a href="#topics">Topics</a> |
  <a href="#project-guidelines">Project Guidelines</a> |
  <a href="#about-the-author">Author</a>
</p>

## Motivation

Placing an earthling from the year 1600 into our todays world must feel like a journey
through Hogwarts!
Our personal assistent weighs about 500 gramm, contains a complete map of the whole planet,
answers any question asked and presents all kinds of information and media to us _immediately_.
When asking how this is even possible the earthling might get the answer _oh, afterall it's all
just one's and zero's_. Confused but motivated to get behind all of this the earthling might
find that the construction of the personal assistants requires just minerals and energy to
process them. It is all _just a machine_ that is much more sophisticated than anything built
around 1600 but there is no magic, there is only electricity, providing the one's and zero's
and a dumb piece of metal. It is explained, that the actual behaviour comes from something
called software and the one's and zero's are only interpreted as _numbers_, the same numbers
humanity already knew in 1600, and all you need are computations with these numbers.

If the earthling was born in the year 2000 the only thing that changes is the fact, that he is
used to the omnipresent magic. Additionally, it is apparent that the magic is not so perfect,
breaks down a lot and once updated, might not work at all. _Why?_ And even being used to fact
that software works it is not clear _how Google Maps finds a route from A to B_.

**Curiositas** is a project in the spirit of just **exploring** the space of _How Software Works_.
The goal is to write a _network of books_, that each take a shot of one aspect in the world
of computation and _implements_ enough of it, so that it is not magic anymore.

The network aspect maps to the dependencies that exist in the real world. One can not find
the shortest distance from A to B if one can neither _represent_ ways from A to B nor
_represent_ a distance and in turn _sum_ all required intermediate distances. But traversal
of the network is not restricted. Starting from a high level application and going deeper
with the understanding is even the prefered method.

As final note, I feel like there are already good books available that explain the foundational
algorithms and datastructures. _C++_ provides a good and generic set of functionality that is
used as starting point. Only the STL of _C++_ is assumed to exist and no external libraries
are used otherwise.

## Topics

The scope of the project is not limited to a specific area, not even to computer science.
As long as it has something to do with computation it is in theory "in scope".
Of course, not all things of the universe that have something to do with computation are adressed.

### From Numbers to Applications

The first complex of topics are _numbers_ and their direct applications.

- [Bring Your Own Int](https://curiositasbooks.gumroad.com/l/build-your-own-int) - How to turn bits into numbers and calculate with them | [Code Repo](https://github.com/curiositas-books/bring-your-own-int)
- [In Progress: When Mathematicians Refactor - a bit of Algebra and Generic Code to build upon]() - Generalize mathematical algorithms in code | [Code Repo]()
- [In Progress: Modular Arithmetic]() - Implement Modular Arithmetic as Foundation for RSA | [Code Repo]()
- [In Progress: Sending Secrets to Strangers - RSA encryption]() - Implement Basic RSA Encryption without Key Generation | [Code Repo]()
- [In Progress: Publicly Exchanging a Secret with full Confidentiality - Diffie-Hellman Key Exchange]() - Implement Diffie-Hellman for RSA | [Code Repo]()

## Project Guidelines

- each book contains approximately one _aspect_, like natural numbers or how to encode an image
- each aspect must be _implemented_ with real, functional code - functionality is demonstrated by tests
- each book has its own _template repository_ anyone can fork or clone to get a starting point without a lot of boilerplate work
- the template repository contains the final, finished example code, whose tests are passing in CI
- readers may use whatever language they feel comfortable with, but the books utilize **primitive** _C++-20_
- (almost) no math, proofs, complexity analysis and other forms of boredome - just code, try out something and see what works
- books will cover both simple ideas, that don't work and better ideas that do - if the simple idea does not work because of algorithmic complexity, it is of course noted _and demonstrated_
- each book ends with workable code that shows how computational problems are solved in principle - non of it is supposed to become production code, all aspects are educational
- the author is _not an expert_ on any subjects of the book - they are still researched

## About the Author

All results of the natural sciences always fascinated me (except chemistry, I don't like chemistry :D). The way things evolve
in the universe, the interdependencies of live on our planet and the fact that it is even possible to build the Large Hadron Collider
sparke a light in me. I want to understand more of it! Humanities current publishing methods are astonishing and you can
find all relevant information to all unanswered questions as videos on YouTube, as articles on Wikipedia or PDFs for the
corresponding literature and papers.
_You can't just play around with it_ and that's what's missing for me. Consuming a video about gravity and the way planets move
is nice. Simulating, experimenting and playing with gravity with your personal, hand made physics engine is rewarding and fun.
As long as I find interesting stuff to try out, I am inclined to fiddle with it. Sometimes it might result in an addition to this project.
My name is Jonas Toth, I studied Applied Computer Science and wrote my in computer vision. I am currently working as Embedded Software Engineer in the renewable energy sector in Germany.

## License

This project and all its works are under [Creative Commons CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) license.
You may do anything with the code and text provided, but please keep it open and please don't make any money from it.
The books are sold for fair prices and make no use of DRM. It takes a lot of time and effort to create these works.
I don't want to rely on an ad infested platform or publish only to DRM and device restricted media. Please do not exploit this.

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

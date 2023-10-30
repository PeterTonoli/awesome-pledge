# awesome-pledge [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A collaborative curated list of amazingly awesome OpenBSD pledge(2) resources and other awesome things.

## Table of Contents
- [Documentation](#documentation)
- [Programming Libraries](#libraries)

## Documentation
 - [OpenBSD pledge(2) manpage](http://man.openbsd.org/OpenBSD-current/man2/pledge.2) 
 - [pledge() - a new mitigation mechanism](http://www.openbsd.org/papers/hackfest2015-pledge/mgp00001.html): slides from Theo de Raadt's presentation in Hackfest 2015 introducing pledge(2)
   - [Pledge: A new security technology in OpenBSD](https://www.youtube.com/watch?v=F_7S1eqKsFk): video of the presentation
 - [why pledge(2) - or, how I learned to love web application sandboxing](http://www.learnbchs.org/pledge.html) 
 - [pledge-ex - examples of using pledge(2) in go/c/and Haskell)](https://github.com/neosimsim/pledge-ex)

## Libraries
- [autopledge-insert](https://github.com/baconator/autopledge-insert) C - *Automatically inserts pledge(2) calls into C/C++ code*
- [pledge.cr](https://github.com/chris-huxtable/pledge.cr) Crystal - *Adds pledge(2) to crystal*
- [ksql](https://kristaps.bsd.lv/ksql/) C - *wrapper for SQLite that adds pledge(2) sandboxing*
- [prx](https://github.com/msantos/prx) Erlang - *an Erlang library for interacting with Unix processes*
- [extrasys](https://github.com/ylih/extrasys) Go - *Extra system calls for Go not provided by the syscall package*
- [pledge](https://github.com/cgohla/pledge) Haskell library described in [this talk at EuroBSDcon](https://www.youtube.com/watch?v=oO3HvRSg86Y)
- [hs-pledge](https://github.com/oherrala/hs-pledge) older Haskell library (archived)
- [Openbsduser-haskell](http://openbsd-archive.7691.n7.nabble.com/pledge-2-binding-for-Haskell-td287889.html) Haskell
- [pledge](https://github.com/Hashwords/pledge) Java
- [node-pledge](https://github.com/qbit/node-pledge) Javascript
- [lua-openbsd](https://github.com/n0la/lua-openbsd) Lua - *Lua library that binds to OpenBSD specific functions*
- [pledge.nim](https://github.com/euantorano/pledge.nim) Nim
- [OpenBSD-Pledge](https://github.com/afresh1/OpenBSD-Pledge)(http://cvsweb.openbsd.org/cgi-bin/cvsweb/src/gnu/usr.bin/perl/cpan/OpenBSD-Pledge/) Perl
- [Unix-Pledge](https://github.com/rfarr/Unix-Pledge) Perl
- [php-pledge](https://github.com/tvlooy/php-pledge) PHP 7.x+ (unveil calls too)
- [py-openbsd-pledge](https://github.com/jarmani/py-openbsd-pledge) Python
- [openbsd-pledge](https://github.com/Robiathin/openbsd_pledge) Ruby
- [openshim](https://github.com/esote/openshim) Go
- [ruby-pledge](https://github.com/jeremyevans/ruby-pledge) Ruby
- [pledge-rs](https://github.com/i80and/pledge-rs) Rust
- [rusty-sandbox](https://github.com/myfreeweb/rusty-sandbox) Rust - *A crossplatform sandboxing library*
- [Pastebin-rust-pledge](http://pastebin.com/P89kV6uR) Rust - *(pastebin code)*
- [clicken-pledge](http://wiki.call-cc.org/eggref/4/pledge) Scheme *Chicken Scheme*
- [pledge.cs](https://github.com/NattyNarwhal/pledge.cs) .Net

## Credits
 - [Ligurio's](https://gist.github.com/ligurio/f6114bd1df371047dd80ea9b8a55c104) Support of OpenBSD pledge(2) in programming languages Gist 
 - [Calvin's](https://lobste.rs/s/dmhmdc/support_of_openbsd_pledge_2_in_programming_languages) Support of OpenBSD pledge(2) in programming languages thread on lobste.rs

## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

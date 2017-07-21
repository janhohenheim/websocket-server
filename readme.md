# websocket-server
[![Travis](https://img.shields.io/travis/SirRade/websocket-server.svg)](https://travis-ci.org/SirRade/websocket-server) [![Coveralls](https://img.shields.io/coveralls/SirRade/websocket-server.svg)](https://coveralls.io/github/SirRade/websocket-server) [![Crates.io](https://img.shields.io/crates/v/websocket-server.svg)](https://crates.io/crates/websocket-server) [![Docs.rs](https://docs.rs/websocket-server/badge.svg)](https://docs.rs/websocket-server)  
Boilerplate to effortlessly setup an asynchronous websocket server.

This code was originally written for my game [shootr](https://github.com/SirRade/shootr), but it is general enough to be in it's own crate. Keep in mind that it is designed primarely to be used by myself, so it's not documented that well. Feel free to open an issue if you have any questions :)  
In the mean time, you can see a comprehensive [example](https://github.com/SirRade/shootr/blob/master/core/src/main.rs) in the aforementioned game.

Most of this is just boilerplate around the async parts of the [websocket crate](https://github.com/cyderize/rust-websocket), so check them out as well!

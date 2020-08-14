WebSocket Client & Server Implementation for Node
=================================================

This is a fork of [`websocket@1.0.31`](https://github.com/theturtle32/WebSocket-Node/tree/1f7ffba2f7a6f9473bcb39228264380ce2772ba7). Please refer
to it's repository for its documentation.

## Fork explanation

The reason for this fork is that `websocket` recompiles a a few C
modules every time it's installed. This fork uses a NAN-based of
those modules instead, which doesn't require recompiling.

This fork won't be relevant once [this `websocket` PR](https://github.com/theturtle32/WebSocket-Node/pull/302) gets merged.
spades: a riak_core OTP application
======================================

spades is an attempt to create a distributed game server for the card game
spades.

Goals:
* Game Lobby
* Game VNode
* Player matching

Application Structure
---------------------

This is a blank riak_core application. To get started, you'll want to edit the
following files:

* `src/riak_spades_vnode.erl`
  * an implementation of the riak_core_vnode behaviour
* `src/spades.erl`
  * the public API for interacting with your vnode

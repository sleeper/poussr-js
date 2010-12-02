Poussr-js
==========

Poussr-js is a small Javascript library, that allows for easy
interaction with [Poussr](https://github.com/sleeper/poussr).

Setup
=========

Each instantiated Poussr object allows for connection to a Poussr
channel (after calling the 'connect' method).

Client can then choose to subscribe to some event through the
'subscribe' method.

    var mypoussrobj = new Poussr(host, port, channel);
    mypoussr.connect();
    mypoussrobj.subscribe('event:tofollow', function(data) { /* the callback */ });


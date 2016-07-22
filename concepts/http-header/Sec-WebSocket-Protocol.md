---
layout: page
title:  "HTTP Header Field: Sec-WebSocket-Protocol"
---

**[RFC 6455: The WebSocket Protocol](/specs/IETF/RFC/6455 "The WebSocket Protocol enables two-way communication between a client running untrusted code in a controlled environment to a remote host that has opted-in to communications from that code. The security model used for this is the origin-based security model commonly used by web browsers. The protocol consists of an opening handshake followed by basic message framing, layered over TCP. The goal of this technology is to provide a mechanism for browser-based applications that need two-way communication with servers that does not rely on opening multiple HTTP connections (e.g., using XMLHttpRequest or <iframe>s and long polling)."):** [The Sec-WebSocket-Protocol header field is used in the WebSocket opening handshake. It is sent from the client to the server and back from the server to the client to confirm the subprotocol of the connection. This enables scripts to both select a subprotocol and be sure that the server agreed to serve that subprotocol.](http://tools.ietf.org/html/rfc6455#section-11.3.4)

<br/>
<hr/>

<p style="text-align: right"><a href="../http-headers">Return to list of all HTTP Header Fields</a></p>
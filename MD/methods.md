# HTTP Request Methods

The following 4 HTTP Request Method definitions were found in 122 services (29 [W3C](../W3C/), 72 [RFC](../IETF/RFC/), 21 [I-D](../IETF/I-D)). Please be advised that the table shown here is maintained and compiled from [Sedola](https://github.com/dret/sedola) sources. The [official HTTP Request Method registry](http://www.iana.org/assignments/http-methods/http-methods.xhtml#methods) is maintained by the [*Internet Assigned Numbers Authority (IANA)*](http://www.iana.org/).

HTTP Request Method | Description | Specification
-------: | :---------- | :---
`ACL` | "[The ACL method modifies the access control list (which can be read via the DAV:acl property) of a resource. Specifically, the ACL method only permits modification to ACEs that are not inherited, and are not protected.](http://tools.ietf.org/html/rfc3744#section-8.1)" | [**RFC 3744**: Web Distributed Authoring and Versioning (WebDAV) Access Control Protocol](http://tools.ietf.org/html/rfc3744 "This document specifies a set of methods, headers, message bodies, properties, and reports that define Access Control extensions to the WebDAV Distributed Authoring Protocol. This protocol permits a client to read and modify access control lists that instruct a server whether to allow or deny operations upon a resource (such as HyperText Transfer Protocol (HTTP) method invocations) by a given principal. A lightweight representation of principals as Web resources supports integration of a wide range of user management repositories. Search operations allow discovery and manipulation of principals using human names." )
`PATCH` | "[The PATCH method requests that a set of changes described in the request entity be applied to the resource identified by the Request-URI. The set of changes is represented in a format called a "patch document" identified by a media type. If the Request-URI does not point to an existing resource, the server MAY create a new resource, depending on the patch document type (whether it can logically modify a null resource) and permissions, etc.](http://tools.ietf.org/html/rfc5789#section-2)" | [**RFC 5789**: PATCH Method for HTTP](http://tools.ietf.org/html/rfc5789 "Several applications extending the Hypertext Transfer Protocol (HTTP) require a feature to do partial resource modification. The existing HTTP PUT method only allows a complete replacement of a document. This proposal adds a new HTTP method, PATCH, to modify an existing HTTP resource." )
`PRI` | "[This method is never used by an actual client. This method will appear to be used when an HTTP/1.1 server or intermediary attempts to parse an HTTP/2 connection preface.](http://tools.ietf.org/html/rfc7540#section-3.5)" | [**RFC 7540**: Hypertext Transfer Protocol Version 2](http://tools.ietf.org/html/rfc7540 "This specification describes an optimized expression of the semantics of the Hypertext Transfer Protocol (HTTP). HTTP/2 enables a more efficient use of network resources and a reduced perception of latency by introducing header field compression and allowing multiple concurrent exchanges on the same connection. It also introduces unsolicited push of representations from servers to clients. This specification is an alternative to, but does not obsolete, the HTTP/1.1 message syntax. HTTP's existing semantics remain unchanged." )
`SEARCH` | "[The client invokes the SEARCH method to initiate a server-side search. The body of the request defines the query. The server MUST emit an entity matching the WebDAV multistatus format.](http://tools.ietf.org/html/rfc5323#section-2)" | [**RFC 5323**: Web Distributed Authoring and Versioning (WebDAV) SEARCH](http://tools.ietf.org/html/rfc5323 "This document specifies a set of methods, headers, and properties composing Web Distributed Authoring and Versioning (WebDAV) SEARCH, an application of the HTTP/1.1 protocol to efficiently search for DAV resources based upon a set of client-supplied criteria." )
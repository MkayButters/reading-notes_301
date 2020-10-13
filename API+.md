## REST

- The HTTP tells the browser what protocol to use. It is capable of describing the location of something anywhere in the world from anywhere in the world. It's the foundation of the web. You can think of it like GPS coordinates for knowledge and information

-  The whole world wide web is built on an architectural style called “REST”. REST provides a definition of a “resource”, which is what those things point to.

- URLs tell the browser that there's a concept somewhere. A browser can then go ask for a specific representation of the concept. Specifically, the browser asks for the web page representation of the concept

- Computers can use those same protocols to send messages back and forth to each other like us talking back and forth when we browse the web.

## Super Agent

- SuperAgent is light-weight progressive ajax API crafted for flexibility, readability, and a low learning curve after being frustrated with many of the existing request APIs. It also works with Node.js!

'SuperAgent will automatically serialize JSON and forms. You can setup automatic serialization for other types as well:

request.serialize['application/xml'] = function (obj) {
    return 'string generated from obj';
};

// going forward, all requests with a Content-type of
// 'application/xml' will be automatically serialized

If you are calling Facebook's API, be sure to send an Accept: application/json header in your request. If you don't do this, Facebook will respond with Content-Type: text/javascript; charset=UTF-8, which SuperAgent will not parse and thus res.body will be undefined. You can do this with either req.accept('json') or req.header('Accept', 'application/json'). See issue 1078 for details.

In Node.js SuperAgent supports methods to configure HTTPS requests:

.ca(): Set the CA certificate(s) to trust
.cert(): Set the client certificate chain(s)
.key(): Set the client private key(s)
.pfx(): Set the client PFX or PKCS12 encoded private key and certificate chain
.disableTLSCerts(): Does not reject expired or invalid TLS certs. Sets internally rejectUnauthorized=true. Be warned, this method allows MITM attacks.

[<===BACK](README.MD)
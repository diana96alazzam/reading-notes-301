# Article: How I explained REST to my brother 

- Roy Fielding: he is the one who helped write the first web servers, that sent documents across the Internet… and then he did a ton of research explaining why the web works the way it does. His name is on the specification for the protocol that is used to get pages from servers to your browser.

- http: is capable of describing the location of something anywhere in the world from anywhere in the world. It's the foundation of the web. You can think of it like GPS coordinates for knowledge and information.

- The whole world wide web is built on an architectural style called “REST”. REST provides a definition of a “resource”, which is what those things point to.

- Web page is a “representation” of a resource. Resources are just concepts. URLs tell the browser that there's a concept somewhere. A browser can then go ask for a specific representation of the concept. Specifically, the browser asks for the web page representation of the concept.

- Representations is one of these things that doesn't get used a lot. In most cases, a resource has only a single representation.

- “Web Services” or "APIs": the basic concept of APIs is that machines could use the web just like people do.

- Machines tell each other where things are using The URL. If everything that machines need to talk about has a corresponding URL, you've created the machine equivalent of a noun. That you and I and the rest of the world have agreed on talking about nouns in a certain way is pretty important but machines don't have a universal noun. Every programming language, database, or other kind of system has a different way of talking about nouns. That's why the URL is so important. It let's all of these systems tell each other about each other's nouns.

- There's a powerful concept in programming and CS theory called **“polymorphism”**. That's a geeky way of saying that different nouns can have the same verb applied to them.

-  HTTP is a general purpose protocol for applying verbs to nouns.

- Each of the systems would retrieve information from each other using a simple HTTP GET. If one system needs to add something to another system, it would use an HTTP POST. If a system wants to replace something in another system, it uses an HTTP PUT, or, to do a partial update, it'll hopefully use PATCH. 






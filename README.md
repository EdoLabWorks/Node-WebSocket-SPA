# NodeJS-Websocket-SPA
An experimental single page application using websocket.

A responsive SPA using only HTML, CSS, Javascript or JQuery in the front-end.

As usual we will evaluate it using CRUD operations connecting to SQL Express Server
using Entity Framework and a NodeJS MongoDB database.

Without a REST API to map our CRUD operations with HTTP methods,
we will move our data back and forth using a simple header and payload JSON data packets
between our front-end and back-end services.

We will design it as a thin client so we can easily swap it with our Angular-NodeJS and ASP.NET MVC thin client solutions.
All our backend services will be housed in a lightweight module totally isolated, fully testable and easily maintainable code base.

For convenience, we will create a button control in the client side to swap the data set between the SQL Express and MongoDB instantly for a simple data migration.





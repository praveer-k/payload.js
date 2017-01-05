# payload.js

During the times when angularJS, reactJS and other frameworks were evolving, I had an idea of that each potential div is a space on the browser tab, hungry for data from the server. We imbue each div with components made from JQuery and put ajax request in the background to extract information from the server and display it to the user. (Taking you back in the early months of the year 2011)

It is a good idea of separating html from javascript - making codes more maintainable and re-usable. But the process of extracting information from the server and displaying is quite tyring. A perfect marriage can be achieved if the re-usability of JQuery can be combined with a framework level plugin that works in JQuery but removes the frustration of writing promise codes and then do something.

A better approach would be to initiallise each div with a potential refreshable information and fetch it from a link on any server.

AngularJS did achieve this idea in its ng version 2.0 by considering goodness of reactJS and typeScript and combining it together.

This version of the payload.js demonstrate the goodness of keeping parts of the application into components and how it can be achieved using JQuery style of doing things.

Few issues that you might get currently (because the implementation was discontinued !) are:

1. History cannot be saved.
2. Routing is not implemented.

Suggestions on it is always welcome !!!

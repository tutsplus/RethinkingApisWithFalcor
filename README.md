# [Rethinking APIs With Falcor][published url]
## Instructor: [Derek Jensen][instructor url]

There has been a big push in the last few years to build RESTful web APIs to allow third-party or client-side apps to consume data. These APIs are built on top of HTTP and reuse the HTTP concepts of verbs and resources. But the more we as a community build APIs this way, the more we are faced with similar challenges: challenges like keeping our resource URLs clean and determining how much or how little information to send back to API consumers. Even with the best-laid plans, doing all of this gets very complicated, very quickly. Well, Netflix has come up with an interesting new way to build APIs that can help with these types of problems.

Falcor is a JavaScript library that reimagines the coding of APIs. Using Falcor, we are able to allow our consumers to be very specific about the data that they want back and only return that information—as much or as little of it as they want. Falcor wraps all the data requests and updates in a uniform protocol, which makes it easy to implement API access both on the client and server. Let's dive into this new framwork and we can begin to think about incorporating it into our current applications.

# Source Files Description:

The provided source files contain simple samples of using Falcor. The source also includes a simple nodeJS application that can be run on your local system. Simply download the source, navigate into the `app-server` folder from a command prompt, and run `npm install && node index.js` to install all the necessary dependencies and launch the server.

------

These are source files for the Envato Tuts+ course: [Rethinking APIs With Falcor][published url]

Available on [Tuts+](https://tutsplus.com). Teaching skills to millions worldwide.

[published url]: https://code.tutsplus.com/courses/rethinking-apis-with-falcor
[instructor url]: https://tutsplus.com/authors/derek-jensen

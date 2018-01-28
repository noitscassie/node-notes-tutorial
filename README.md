# Node Notes App

This is the back-end to a notes app, built using Node. It has been created by following [this tutorial](https://medium.freecodecamp.org/building-a-simple-node-js-api-in-under-30-minutes-a07ea9e390d2). It is built in JavaScript, using Node, the Express framework, and Postman to mimic different HTTP requests. The main goal of this project was to gain a basic exploration of Node and how it works.

One of the biggest issues that I faced in creating this application was being plagued by a bug for two days, that meant I was unable to connect to the mLab database. I eventually realised that this was down to an incredibly simple error, in which I had failed to press the shift key correctly, and was attempting to connect to a database called node-note, rather than the correct node_note database. Whilst incredibly frustrating, this problem allowed me to explore many avenues that I would not otherwise have done, such as version compatibility problems, and interacting with the MongoDB database via the command line.

It was also a lesson to me in properly reading error messages (and considering all aspects of what they might mean); I had falsely assumed that because the server was able to connect to the remote database previously in the program, that there must be a problem client-side, whereas in fact, the problem was that the connection to the database was failing because there was no database with the specified name. In searching for a more complex problem, I ended up directing a lot of time and energy into deadends on this project (although, given my learning, this time was not wasted).

This program is a client-server system for writing/storing notes. Each note has an ID (integer), a title (short text), and a body (long text). 
A client has three kinds of requests to the server: upload a note, download a note (given its ID), and search for a note (given a keyword). 
In case of search, the server will return a list of IDs and titles of notes whose titles contain the keyword.

Includes:

 The database to store the notes
 The UI of the client
 Code to implement the system. Same design patterns as in the Store Management System: 3-layer; Model-View-Controller; Singleton, Adapter...

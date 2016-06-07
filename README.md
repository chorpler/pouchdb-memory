pouchdb-memory
=======

A purely in-memory PouchDB, as a custom build.

Usage
---

    npm install pouchdb-memory

```js
var PouchDB = require('pouchdb-memory');
var db = new PouchDB('mydb');
```

Description
----

This build combines the following plugins:

- `pouchdb-adapter-memory`
- `pouchdb-mapreduce`
- `pouchdb-replication`
- `pouchdb-find`

It should be useful for things like quick unit tests.

Feel free to add additional plugins on top of it, or just build your own – the source code is tiny!

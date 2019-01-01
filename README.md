pouchdb-adapter-idb
======

Drop-in replacement for pouchdb-adapter-idb, which uses IndexedDB as its data store.

Its adapter name is `'idb-purge'`.


### Usage

```bash
npm install pouchdb-adapter-idb
```

```js
PouchDB.plugin(require('pouchdb-adapter-idb-purge'));
var db = new PouchDB('mydb', {adapter: 'idb-purge'});
```

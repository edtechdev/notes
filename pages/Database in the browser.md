- https://blog.ouseful.info/2022/02/11/sql-databases-in-the-browser-via-wasm-sqlite-and-duckdb/
  
  This is a technique for coding [[local first software]], in which a user can continue
  to use the application offline, storing updates in a database that runs
  locally inside the browser. Any updates will be synced with the server
  when back online.
  
  Saying examples of databases that run in the browser:
- https://github.com/ccorcos/tuple-database
- [[Triplestore]]
  https://github.com/linkeddata/rdflib.js/
	- http://linkeddata.github.io/rdflib.js/doc/
- RXDB - built on top of pouchdb?
	- https://rxdb.info/
	- https://jaredforsyth.com/posts/local-first-database-rxdb-pouchdb/
	- https://hasura.io/blog/building-an-offline-first-web-app-with-rxdb-hasura/
- PouchDB https://pouchdb.com/
	- "Couch apps" were popular 10 years ago, but haven't really
	  caught on
- DataScript (uses clojurescript instead of
  [[javascript]])
	- https://github.com/tonsky/datascript
	- See [[logseq]] and other apps
- Solid https://solidproject.org/
	- Decentralized. Data stored in pods. Initiated by Tim Berners-Lee
- [[Graph databases]] in browser
	- https://github.com/oxigraph/oxigraph
	- https://github.com/levelgraph/levelgraph
	- https://github.com/belayeng/quadstore
- DataHike - alternative to DataScript
  https://github.com/replikativ/datahike
	- Used by new Homebase platform, which also works with Firebas
	  https://homebase.io/
- LocalStorage
	- Built-in NoSQL database in the browser
- RemoteStorage https://remotestorage.io/
- Fission https://fission.codes/
- Meteor - also popular about 10 years ago
- [[SQLite]]
	- There's a hack that runs SQLite in the browser by compiling it
	  to webassembly
	- https://phiresky.github.io/blog/2021/hosting-sqlite-databases-on-github-pages/
	- There was a proposal to natively support SQLite in the browser
	  (Web SQL), but Apple killed the idea
- https://stopa.io/post/279
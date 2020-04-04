# cassandra
Cassandra Docker

- Example if you want to load data when cassandra starts up, useful for things like if you want to use cassandra as a session store for your application.  
  
- The entrypoint-wrap.sh, steps up your data the moment cassandra is ready, if cassandra is not ready, keeps on retrying.

# Genie Benchmarking Test

Project structure made with `Genie.Generator.newapp_webservice("GenieBenchmark")`


Not using SearchLight ORM provided with Genie, because it does not support table name overrides and tries to query plural "Worlds" and "Fortunes" table

## How to verify
./tfb --mode verify --test genie

### Implemented benchmarks
- [x] JSON serialization
- [x] Single query
- [x] Multiple queries
- [x] Plaintext
- [x] Fortunes
- [x] Updates

## Test URLs
### JSON

http://localhost:8080/json

### PLAINTEXT

http://localhost:8080/plaintext

### DB

http://localhost:8080/db

### QUERY

http://localhost:8080/query?queries=

### CACHED QUERY

http://localhost:8080/cached_query?queries=

### UPDATE

http://localhost:8080/update?queries=

### FORTUNES

http://localhost:8080/fortunes

## Elasticsearch Interactive Shell ##

EShell is a Python script that allows you to interact from command-line with a running [elasticsearch](https://www.elastic.co/products/elasticsearch)
cluster using the APIs over HTTP.

> v0.3.7 tested under Elasticsearch v1.7.3

**Example:**

```
(eshell)stardust~$ ./eshell localhost.localdomain
Connecting to elasticsearch server at address: localhost.localdomain
Connected to: localhost.localdomain on port: 9200

### Welcome to elasticsearch console!
### For more information, type 'help'

es:~$ show

Entering to cluster information menu.

es:show~$ cluster_health
status: green
number_of_nodes: 33
unassigned_shards: 0
number_of_pending_tasks: 0
number_of_in_flight_fetch: 0
timed_out: False
active_primary_shards: 11864
cluster_name: darkstar
relocating_shards: 0
active_shards: 18382
initializing_shards: 0
number_of_data_nodes: 20
delayed_unassigned_shards: 0
es:show~$
```

**Changelog (v0.3.7):**

- Added support for Ctrl+C
- New commands: indices_store, indices_mapping, indices_template, nodes_inde 


0.1.13
------
- track isochrone and optimized_route

0.1.12
------
- support pelias-autocomplete
- stop renaming pelias-search to search

0.1.11
------
- apiaxle send to mobility_traffic

0.1.10
------
- support vector-tiles 1.0

0.1.9
-----
- stringify firehose errors

0.1.8
-----
- add batching and retries for kinesisExporter

0.1.7
-----
- capture vector tiles server
- update deploy script

0.1.6
-----
- rename pelias-search to search
- ignore cacheHits for vector-tiles
- trigger lambda retry on firehose put failure

0.1.5
-----
- add fastly_traffic_v2 and pelias_traffic_v2
- add pausing

0.1.4
-----
- new fastly log format

0.1.3
-----
- add origin and duplicate columns to api_hits
- don't move fastly logs after parsing them

0.1.2
-----
- fix: apiaxleKinesis uses callbacks

0.1.1
-----
- add lambda deployment/configure process

0.1.0
-----
- support for piping traffic from apiaxle to kinesis

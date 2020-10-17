# `streamsets.base` - ContEco

Streamsets Base image with configuration changes and pre-installed stage libraries.
See `conteco.docs.overview` for more information on the ContEco ecosystem.

## Configuration Changes

The following configuration changes were made:  
```bash
# hosting streamsets behind reverse proxy
enable.forwarded.requests=true

# disable authentication
http.authentication=none

# disabled support bundle upload
bundle.upload.enabled=false
```

## Stage Libraries

Two stage libraries are pre-installed:
* __ElasticSearch__: elasticsearch_5-lib
* __Kafka__: kafka_2_0-lib

## Tags

* 3.19.0  
* 3.10.1  

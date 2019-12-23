# `streamsets.base` - ContEco

Streamsets Base image with configuration changes.
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

## Tags

* 3.10.1  

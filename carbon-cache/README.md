# Carbon Docker Image

## Usage
``
docker run -d -p 2003:2003 -p 2004:2004 -p 7002:7002 --volumes-from whisper -e NODE_NAME=cache hanmanhui/carbon-cache
``

### Ports
- 2003: Plaintext protocol, format: "\<metric path\> \<metric value\> \<metric timestamp\>"
- 2004: Pickle protocol, format: "[(path, (timestamp, value)), ... ]"
- 7002: Query port

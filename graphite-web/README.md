# Graphite-web Docker Image

## Usage
``
docker run -d -p 8000:80 -e CARBONLINK_HOSTS="172.17.42.1:7002" --volumes-from whisper hanmanhui/graphite-web
``

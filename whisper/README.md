# Whisper docker image

## Usage
Below command is a command that run whisper data volume.

``
$ docker run --name whisper hanmanhui/whisper
``

You can use this data volume from other applicaiton container. Below is example:

``
$ docker run -d --name carbon --volumes-from whisper hanmanhui/carbon
``

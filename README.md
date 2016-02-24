# arm-ftpd

To start the container with default config :
```bash
docker run -d -P arm-ftpd
```

But you can also use your local datastore :
```bash
docker run -d -P -v <your local datastore>:/data arm-ftpd
```

FTP login is default / passw0rd.

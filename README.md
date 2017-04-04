LatticeOS compose setup
----

A simple setup to deploy Lattice GUI environment.

![](https://www.diigo.com/file/image/ssdarodzdrsqosccczcrbpoebb/docker-desktop-vscode-libreoffice.jpg)

## Usage

### In docker

```
# docker run -d -v /var/run/docker.sock:/var/run/docker.sock --name latticeos daocloud.io/dphdjy/latticeos
```

```
# docker run -d -v /var/run/docker.sock:/var/run/docker.sock --name latticeos gitai/latticeos
```

### In docker-compose

```
# docker-compose create
# docker-compose up -d
```


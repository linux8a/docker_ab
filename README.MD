# Microservice ab - Apache HTTP server benchmarking tool

Aporte de Argenis Ochoa Gonzalez (@linux8a)

Para compilarlo la imagen hacer esto

```
docker build -t ab -f ./Dockerfile .
```

Usarlo

```
docker run -it --rm ab -n 100 -c 10 https://lawebquedeseastestear.com/
```

* Donacion:

![Donacion](https://github.com/linux8a/docker_ab/blob/master/.donacion.png)
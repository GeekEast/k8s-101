

## Why use Docker?
<p align="center"><img style="display: block; width: 600px; margin: 0 auto;" src=img/2024-03-06-13-07-39.png alt="no image found"></p>

## Hello World
- run hello-world image
```bash
docker run hello-world
```
- run ubuntu command line
```bash
docker run -it ubuntu bash
```



## Compare virtualization techniques

<p align="center"><img style="display: block; width: 600px; margin: 0 auto;" src=img/2024-03-06-13-11-29.png alt="no image found"></p>

<p align="center"><img style="display: block; width: 600px; margin: 0 auto;" src=img/2024-03-06-13-58-46.png alt="no image found"></p>


## Docker Compose
- restart automatically
```yaml
version: 3
service:
    node-app:
        restart: true
```
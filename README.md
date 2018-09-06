# dev-tex
image to build tex


```
docker run -d --rm \
	-v /tmp/.X11-unix:/tmp/.X11-unix \
	-e DISPLAY=unix$DISPLAY \
	yboz/dev-tex \
	texmaker
```

# Ray Tracer

Decided to learn how to do a ray tracer.

![Sample render (pretty cool though)](example/example.png)

I followed the Ray Tracing In One Weekend (see https://raytracing.github.io/books/RayTracingInOneWeekend.html) course, and will follow the next two ones (see https://raytracing.github.io/).

At this time, the code is pretty similar, but it will improve in the coming weeks.

It can rendered spheres with some materials (metal, lambertian, dielectric). Has a simple antialiasing (used multiple samples), background gradient, defocus blur.

Pretty cool to gain some intuition about 3D math, refresh my knowledge of linear algebra, and demystify computer graphics. Thanks to Google Images for the schemas, and ChatGPT for some explanations (but it's not as powerful as I thought for this kind of subject, unfortunately).

(In fact, this sounds more like a path tracer.)

## How to run it ?

Use Docker.

```bash
docker build -t rt-project .
docker run --rm rt-project > img.ppm
```

The image will be saved on your machine.
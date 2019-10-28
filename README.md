# image_cut

A new Flutter application for cache image to the local storage

## Getting Started

Flutter already have the memory  cache, So  can do it   modify the networkImage

The code is in fade_in_cache.dart

Copy the FadeInImage  and  NetworkImage, then  add the file cache

## run the pubspec.yaml  Flutter package get
how to use it
```python
     fcache.FadeInImage.memoryNetwork(
          image: d["url"],
          sdcache: true,
          placeholder: kTransparentImage,
          width: width,
          height: d["height"]* width/d["width"],
          ),
```

---
title: "MapElementTappedEventArgs Class | Microsoft Docs"
author: "pablocan"
---

# MapElementTappedEventArgs Class (Android only)

Event arguments passed to MapElementLayer.MapElementTapped callback.

## Properties

### Location

Gets the geographic location that corresponds to where the [MapElementsLayer](../MapElementLayer-class.md) received user input.

>```java
> final Geopoint location
>```

### MapElements

Gets a list of map elements that correspond to where the [MapElementsLayer](../MapElementLayer-class.md) received user input.

>```java
> final LinkedList<MapElement> mapElements
>```

### Position

Gets the physical position on the [MapElementsLayer](../MapElementLayer-class.md) where it received user input.

>```java
> final android.graphics.Point position
>```

## See also

* [OnMapElementTappedListener](OnMapElementTappedListener-interface.md)
* [MapView](../MapView-class.md)
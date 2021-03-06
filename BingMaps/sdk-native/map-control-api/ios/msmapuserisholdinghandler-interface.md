---
title: "MSMapUserIsHoldingHandler Interface | Microsoft Docs"
author: "pablocan"
---

# MSMapUserIsHoldingHandler Interface (iOS only)

Handler used with MapView.Holding event. Return true from this event to prevent other OnMapHoldingListeners from receiving this event or false to allow other listeners to receive his notification as well. Events are processed in the order they were attached to the MapView.

>```objectivec
> typedef BOOL (^MSMapUserIsHoldingHandler)(CGPoint, MSGeopoint*)
>```

## See also

* [Geopoint](../Geopoint-class.md)
* [MapView](../MapView-class.md)
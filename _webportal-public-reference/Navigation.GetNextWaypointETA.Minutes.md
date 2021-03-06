---
title: Navigation.GetNextWaypoint.ETAMinutes()

supported:
  - 2
  - 3
  - 4
type: api
privacy: Public
---

### `Navigation.GetNextWaypoint.ETAMinutes()`

| **Description** | Calculate and return the estimated time of arrival at the next waypoint, precisely the minutes.
| **Response** | *Number*  Estimated minute of arrival at the next waypoint.
| **Parameter**   | *Void*

#### EXAMPLE

```javascript
var WaypointETAMinutes = Navigation.GetNextWaypoint.ETAMinutes();
// WaypointETAMinutes = 27 minutes
```

#### REMARK

>**Note :** `Navigation.GetNextWaypoint.ETAMinutes` only gives the "Minutes" part of the Estimated Time of arrival. To get the "Hour" part, use `Navigation.GetNextWaypoint.ETAHour`.

*Appeared in Software version 40.03.42.30*

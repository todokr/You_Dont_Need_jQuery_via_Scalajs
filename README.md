# You Don't Need jQuery via Scala.js
Original repo via Vanilla JS: https://github.com/oneuijs/You-Dont-Need-jQuery

## Table of Contents

1. [Import](#import)
1. [Query Selector](#query-selector)
1. [CSS & Style](#css--style)
1. [DOM Manipulation](#dom-manipulation)
1. [Ajax](#ajax)
1. [Events](#events)
1. [Utilities](#utilities)
1. [Promises](#promises)
1. [Animation](#animation)
1. [Alternatives](#alternatives)
1. [Browser Support](#browser-support)

#Import
```scala
import scala.scalajs.js.JSApp
import org.scalajs.dom._
import org.scalajs.jquery.{ jQuery => $ }
```

#Query Selector

1.0 Query by selector
```scala
// jQuery
$("p")

// Native
document.querySelectorAll("p")
```

1.1 Query by class 
```scala
// jQuery
$(".class")

// Native
document.querySelectorAll(".class")
```

1.2 Query by id
```scala
// jQuery
$("#id")

// Native
document.querySelectorAll("#id")
```

1.3 Query by attribute
```scala
// jQuery
$("a[target=_blank]")

// Native
document.querySelectorAll("a[target=_blank]")
```

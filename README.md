# You_Dont_Need_jQuery_via_Scalajs
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
```scala
// jQuery
$("p")

// Native
document.querySelectorAll("p")
```

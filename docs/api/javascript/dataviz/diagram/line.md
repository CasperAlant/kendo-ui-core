---
title: Line
---

# kendo.dataviz.diagram.Line

This represents a single, straight line.

## Configuration

### stroke `Object`

Defines the stroke configuration.

### stroke.color `String`

Defines the line color.

### stroke.width `Number`

Defines the line width.

### stroke.dashType `String`

The dash type of the shape.

The following dash types are supported:

* "dash" - a line consisting of dashes
* "dashDot" - a line consisting of a repeating pattern of dash-dot
* "dot" - a line consisting of dots
* "longDash" - a line consisting of a repeating pattern of long-dash
* "longDashDot" - a line consisting of a repeating pattern of long-dash-dot
* "longDashDotDot" - a line consisting of a repeating pattern of long-dash-dot-dot
* "solid" - a solid line

### from `Object`

The first point of the line.

#### x `Number`

The X position of first point.

#### y `Number`

The Y position of first point.

### to `Object`

The second point of the line.

#### x `Number`

The X position of second point.

#### y `Number`

The Y position of second point.

## Methods

### position
Get or sets the element position.

#### Parameters

##### offset `kendo.dataviz.diagram.Point`
The origin of the element.


### rotate
Rotates the element with the specified parameters.

#### Parameters

##### angle `Number`
The angle of rotation in decimal degrees.
Measured in clockwise direction with 0 pointing "right".
Negative values or values greater than 360 will be normalized.

##### center `kendo.dataviz.diagram.Point`
The center of rotation.


### visible
Gets or sets the visibility of the current element.

#### Parameters

##### visible `Boolean`
The new visibility state.

#### Returns
`Boolean` True if the element is visible, false otherwise.

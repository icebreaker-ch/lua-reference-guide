---
description: Display an arc.
---

# lvgl.arc

## Syntax

lvgl.arc(\[parent], {settings})

parent:arc({settings})

## Parameters

See the API page for parameter description and common settings.

Note: 'w', 'h' and 'size' should not be used with lvgl.arc. Use 'radius' instead.

Arc specific settings:

<table><thead><tr><th width="127">Name</th><th>Type</th><th>Description</th><th>Default if not set</th></tr></thead><tbody><tr><td>thickness</td><td>Number</td><td>Sets the width of the line used to draw the arc.</td><td>1</td></tr><tr><td>radius</td><td>Number or Function</td><td>Sets the radius of the arc</td><td>0</td></tr><tr><td>startAngle</td><td>Number or Function</td><td>Sets the starting angle or the arc. Measured in degrees - 0 - 360.<br>0 is to the right (3 o'clock).</td><td>0</td></tr><tr><td>endAngle</td><td>Number or Function</td><td>Sets the ending angle for the arc.</td><td>0</td></tr></tbody></table>

## Return values

LVGL object

## API Status

<table><thead><tr><th width="153"></th><th width="72" data-type="checkbox">Avail</th><th width="145">Status<select><option value="93c8b010d44e45efaec5c0c14d3992ac" label="active" color="blue"></option><option value="7e7074d1164048e3b0b24a02b4300f6c" label="to be depreciated" color="blue"></option></select></th><th>Comment</th></tr></thead><tbody><tr><td>BW radios</td><td>false</td><td></td><td></td></tr><tr><td>Color radios</td><td>true</td><td><span data-option="93c8b010d44e45efaec5c0c14d3992ac">active</span></td><td></td></tr></tbody></table>

## Change log

<table><thead><tr><th width="177">EdgeTX version</th><th>Change</th></tr></thead><tbody><tr><td>2.11.0</td><td>Introduced</td></tr></tbody></table>

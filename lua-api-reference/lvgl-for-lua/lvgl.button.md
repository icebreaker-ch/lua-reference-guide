---
description: Add a text button using the EdgeTX style.
---

# lvgl.button

## Syntax

lvgl.choice(\[parent], {settings})

parent:choice({settings})

## Parameters

See the API page for parameter description and common settings.

Button specific settings:

<table><thead><tr><th width="124">Name</th><th width="122">Type</th><th width="289">Description</th><th>Default if not set</th></tr></thead><tbody><tr><td>text</td><td>String</td><td>Text to be displayed in the button.</td><td>Empty string</td></tr><tr><td>press</td><td>Function</td><td>Called when the user taps on the button.</td><td>nil</td></tr></tbody></table>

## Return values

LVGL object

## API Status

<table><thead><tr><th width="153"></th><th width="72" data-type="checkbox">Avail</th><th width="145">Status<select><option value="93c8b010d44e45efaec5c0c14d3992ac" label="active" color="blue"></option><option value="7e7074d1164048e3b0b24a02b4300f6c" label="to be depreciated" color="blue"></option></select></th><th>Comment</th></tr></thead><tbody><tr><td>BW radios</td><td>false</td><td></td><td></td></tr><tr><td>Color radios</td><td>true</td><td><span data-option="93c8b010d44e45efaec5c0c14d3992ac">active</span></td><td>Only available for One-Time scripts</td></tr></tbody></table>

## Change log

<table><thead><tr><th width="177">EdgeTX version</th><th>Change</th></tr></thead><tbody><tr><td>2.11.0</td><td>Introduced</td></tr></tbody></table>

---
title: Customization
description: "Refer to the list of the Kendo UI Default theme variables available for customization."
slug: variables_kendothemedefault
position: 9
---

# Customization

The following table lists the available variables for customizing the Default theme.

<style>
.theme-variables th,
.theme-variables td {
  vertical-align: top;
}

.color-preview {
  border-radius: 50%;
  width: 1em;
  height: 1em;
  vertical-align: middle;
  display: inline-block;
  border: 1px solid rgba(0,0,0,.08);
}
</style>

## Variables


### Common

<table class="theme-variables">
<colgroup>
<col style="white-space:nowrap; width: 200px" />
<col style="width: 250px" />
<col />
</colgroup>
<tr>
<th>Name</th>
<th>Default value</th>
<th>Description</th>
</tr>
<tr>
<td>$border-radius</td>
<td>
    
    2px
</td>
<td>Border radius for all components.
</td>
</tr>
</table>


### Fonts

<table class="theme-variables">
<colgroup>
<col style="white-space:nowrap; width: 200px" />
<col style="width: 250px" />
<col />
</colgroup>
<tr>
<th>Name</th>
<th>Default value</th>
<th>Description</th>
</tr>
<tr>
<td>$font-size</td>
<td>
    
    12px
</td>
<td>Base font size across all components.
</td>
</tr>
<tr>
<td>$font-family</td>
<td>
    
    "NotoSans-Regular", "Muli", "Helvetica Neue", "Arial", sans-serif
</td>
<td>Font family across all components.
</td>
</tr>
<tr>
<td>$font-family-monospace</td>
<td>
    
    $base-font-family
</td>
<td>Font family for monospaced text. Used for styling the code.
</td>
</tr>
<tr>
<td>$line-height</td>
<td>
    
    (20 / 14)
</td>
<td>Line height used along with $font-size.
</td>
</tr>
</table>


### Icons

<table class="theme-variables">
<colgroup>
<col style="white-space:nowrap; width: 200px" />
<col style="width: 250px" />
<col />
</colgroup>
<tr>
<th>Name</th>
<th>Default value</th>
<th>Description</th>
</tr>
<tr>
<td>$icon-font-url</td>
<td>
    
    null
</td>
<td>The URL to the icon font that will be used by the theme<br/>
The default value of `null` embeds the package font with a `data:` URL
</td>
</tr>
</table>


## Mixins

### `exports`
Outputs a module once, no matter how many times it is included.


#### Parameters
- name : `String` - The name of the exported module.


## Suggested Links

* [Styling Overview]({% slug themesandstyles %})
* [Web Font Icons]({% slug icons %})
* [Preview of the Themed Components](../)

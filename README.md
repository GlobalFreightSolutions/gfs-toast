## Introduction
`gfs-toast` provides a subtle notification toast.


## Properties
Name      | Description     | Default
----------|-----------------|--------
text | the text to display in the toast | `empty`
horizontal-align | The orientation against which to align the dropdown content horizontally | `left`
vertical-align | The orientation against which to align the dropdown content vertically | `bottom`
duration | The duration in milliseconds to show the toast. Set to `0` to disable auto closing | `3500`


## Methods
Name | Description
-----|------------
show | open the toast
hide | close the toast
open | open the toast (iron-overlay-behavior)
close | close the toast (iron-overlay-behavior)


## Attributes
Use the following attributes for ready stylish toast notifications

Name   | Description
-------|------------
info | adds a class name with fixed styles
success | adds a class name with fixed styles
warning | adds a class name with fixed styles
error | adds a class name with fixed styles


## Classes
Name      | Description
----------|------------
fit-top | sets the toast on the top of the screen with full width
fit-bottom | sets the toast on the bottom of the screen with full width


## Styling
Name              | Description         | Default
------------------|---------------------|--------
--gfs-toast-color | toast text color | `var(--white-color)`
--gfs-toast-background | toast background color | `var(--gfs-default-color)`
--gfs-toast-margin | toast margin | `0 5px 0 0`
--gfs-toast-font-size | toast font size | `14px`
--gfs-toast-font-family | toast font family | `"Segoe UI", 'Helvetica Neue'`
--gfs-toast-font-weight | toast font weight | `normal`
--gfs-toast-text-transform | toast text transformation | `normal`
--gfs-toast-border-radius | toast border radius corners | `3px`
--gfs-toast-box-shadow | toast box shadow effect | `0 2px 5px 0 rgba(0, 0, 0, 0.26)`

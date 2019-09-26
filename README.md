# Segments #

## A Unique Take On Grids ##

Let's face it: Humans don't pay attention to grids.  So why should our website layouts?  Introducing Segments!


## We Don't Need No Stinking Grids &ndash; The Basics ##

Most pages are broken up into something more akin to portions rather than grids.  For example, take a very common layout pattern: image on the left (or right) and title with content below, right next to it.  Now, normally you would break this out to, say, five columns for the image, and then seven columns for the title and content.  But that's just weird!

But with segments, you simply add children as "minor" and "major", like below:

```
<div class="segment thirds">
  <div class="minor"></div>
  <div class="major"></div>
</div>
```
You can also utilize Segment's web component tags:

```
<segment-item class="thirds">
  <x-minor></x-minor>
  <x-major></x-major>
</segment-item>
```

## We Don't Need No Stinking Grids! ##

Since segments is written as page sections broken up as a "minor" and "major" piece, a section's children are written as:

```
&lt;segment-item&gt;
  &lt;x-minor&gt;&lt;/x-minor&gt;
  &lt;x-major&gt;&lt;/x-major&gt;
&lt;/segment-item&gt;
```


## It All Starts With Panels ##

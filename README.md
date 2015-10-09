#READ ME

##HOW TO USE?

Attach this `.css` or `.less` to any TAPevents project you are working on, and be able to have a website rendering of the wordmark, rather than an image asset.

This was designed with a semantic language in mind.

##Example

```html
<div class="taplogo">
   <span class="big black part1">tap</span><span class="white part2">events</span>
</div>
```

In this example, I have mixed and matched the logo, which obviously you would not do. 

You can use 'big' 'black' 'white' with 'part1' and 'part2' interchangeably, 
__as long as it is nested within `taplogo` `div` tag. Don't forget this__

`part1` refers to the first half of the logo, TAP in big bold letters
`part2` refers to the second events or rentals, or whatever branding there is.
I chose `part1` and `part2`, rather than the more semantic phrase "tap" or "events", because the second half of the branding may change according to the product for which this is being implemented (e.g. rentals vs events).

##Demo
You can check out a live demo at JsFiddle - http://jsfiddle.net/xotLztzq/

##NB
- Use `small` when you are using text in the body, or a small font size, so that the font kerning will appear correctly.

- Use the `span` class so your text will appear inline.

##Contribs
Created by titanium tails who loves dem logos
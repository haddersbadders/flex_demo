# Flex demo

This is a demo of the Flex CSS property. You can see the live page here:

[https://haddersbadders.github.io/flex_demo/](https://haddersbadders.github.io/flex_demo/)

Flex or Flexbox is a really nice way to deal with CSS positioning. 

See [https://css-tricks.com/snippets/css/a-guide-to-flexbox/](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) for a full explanation. 

## My example 

My example is really simple. To do flex, you need to put items inside a containing element. I have a DIV with a class name *container*:

```
<div class="container">

</div>
```
The only CSS property this element needs is: 

```
.container {
  display: flex;
  }
```

This makes the items inside it, well, flexible I guess!

Inside the container are more DIVs:

```
<div class="item">
  //Whatever content
</div>
```

And these are styled like this:

```
.item {
  flex-grow: 1; /* this makes the items occupy available space */
  padding: 0.5em; /* adds some space for each item */ 
  box-sizing: border-box; /* Seemed to help the items stay in a row! */
  }
```


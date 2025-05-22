# Headings

Let's look at some more elements.

Suppose we want to add a headline to our website that displays a news article. Here's how we would do it using a `<h1>` heading element and a `<p>` paragraph element:

```html
<body>
  <h1>Breaking News 🚨</h1>
  <p>Florida man once evaded arrest by cartwheeling now running for mayor.</p>
</body>
```

There are six levels of headings, from `<h1>` to `<h6>`:

```html
<h1>Heading level 1</h1>
<h2>Heading level 2</h2>
<h3>Heading level 3</h3>
<h4>Heading level 4</h4>
<h5>Heading level 5</h5>
<h6>Heading level 6</h6>
```

Here's the result:

![HTML headings sizes comparison](/Images/Captures/02-Elements.png)

> Note: Only one `<h1>` element should be used in a .html file.

## Line Break

Suppose we also want to add a new line within a paragraph element. Pressing enter won't do us any good because HTML ignores multiple spaces and line breaks within elements.

So we must use the `<br>` break tag here!

The `<br>` break tag adds a line break:

```html
<body>
  <h1>Breaking News</h1>
  <p>
    Florida man robs convenience store with an alligator.<br />Leaves a baby
    Crocs behind.
  </p>
</body>
```

A **self-closing** tag doesn't need to be closed manually by a closing tag... it does not have a separate closing </tag>. The break tag is the first one we have encountered.

The final code will become:

![Florida man](/Images/Captures/02-Breaking-News.png)

## Instructions

The New York Times is an American daily newspaper that has been around since 1851. Iconic. 📰

Create a newspaper.html file with what was happening in the news on the day you were born!

Find The New York Times newspaper from your birth date by using their Site Map.

Recreate an article's title and a blurb with:

- `<h1>`-`<h3>` heading element.
- `<p>` paragraph element.
- `<br>` line-break element.

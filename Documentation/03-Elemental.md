# Elements

To understand how HTML works, we need to start with elements – the smallest building blocks of the language.

An element usually consists of an opening tag, the content, and a closing tag. A tag is enclosed in angle brackets.

```html
<p>Hello World!</p>
```

So this is one HTML element where:

> ```html
> <p>is the opening tag. Hello World! is the content.</p>
> is the closing tag. The
> <p>
>   paragraph element tells the browser that the content inside is "paragraph"
>   text.
> </p>
> ```

Let's take a look at a basic HTML program that displays a message in the browser:

```html
<body>
  <p>👋 I'm a new web developer!</p>
</body>
```

The `<body>` element defines an HTML document's "body" and it's where any content that we want to display to the user will be held:

`<body>` opening tag begins the "body".
`<p>`👋 I'm a new web developer!`</p>` is some text in a paragraph element.
`</body>` closing tag ends the "body".
Note: There can only be one `<body>` element in a file.

## Indentation

While indenting HTML code isn't required, doing so is good practice because it makes your code easier to read and visualize the nesting levels.

Here's how to indent the previous code block:

> ```html
> <body>
>   <p>👋 I'm a new web developer!</p>
> </body>
> ```

Notice how it's a lot easier to read this way!

We recommend two spaces for indentations.

## Instructions

The ancient Greeks believed that there were four elements that everything under the sun was made up of:

- 🔥 Fire
- 💧 Water
- ⛰️ Earth
- 🌪️ Air

Create an elemental.html file that shows the four elements in the browser.
Make sure that it's indented nicely, too!

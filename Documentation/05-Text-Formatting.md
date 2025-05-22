# Text Formatting

Now that we know how to display basic text, how do we bold sentences, italicize new words, underline important phrases, and more? 🔡

To do that, we need text formatting elements! They make default texts look fancier.

Here are some common ones:

- `<b>` element to bold text.
- `<i>` element to italicize text.
- `<u>` element to underline text.
- `<s>` element to strikethrough text.

This is how they are used:

```html
<b>This text is using bold formatting.</b><br />
<i>This text is using italics formatting.</i><br />
<u>This text is using underline formatting.</u><br />
<s>This text is using strikethrough formatting.</s><br />
```

The result looks like this:

![HTML text formatting](/Images/Captures/05-Text-Formatting.png)

> Note: The `<b>` element is just for bolding text stylistically; .> HTML also has a `<strong>` element used to convey that the content > inside is important, as well as styling it to be bold.

Here are all four tags in action in a classroom announcement:

```html
<p>
  This is the reminder that the <i>final exam</i> is <b>mandatory</b>.<br />
  It will be held on <u>Monday, October 14th</u> at <s>7PM</s> 8PM EST.
</p>
```

This will look like:

![HTML text formatting example output](/Images/Captures/05-Text-Formatting-Example-Output.png)

> Note: The tags above are good for learning how to style text >with basic HTML, but are no longer best practice. Other ways to >style text will be covered in the CSS course.

## Instructions

Suppose you have a soul-sucking corporate job where you take notes in executive meetings. 😵‍💫

Can you recreate the exact format of the corporate jargon below in corporate.html using `<p>`, `<b>`, `<i>`, `<s>`, and `<u>` tags?

Here's the copy:

Cutting Down, Ramping Up: We have a robust strategy for low-hanging fruits mission-critical objectives that move the needle at all costs. It's time to double down on revenue growth while cutting costs. This is a win-win initiative, a win for us and our amazing shareholders!

P.S. After several strong sales months, we are printing Employee Appreciation Tees! Will go on sale Monday.

<!--
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

## Step 2: Add an image

_Great job adding headers to the file :sparkles:_

Let's add an image. Include descriptive text in the square brackets. This text is read aloud for people using screen readers. It's also shown at times when your image doesn't display, such as when there's a poor connection. You can see the syntax for images below:

### Example

```md
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
```

#### How it looks

<img alt="Image of Yaktocat" src=https://octodex.github.com/images/yaktocat.png width=400>

### :keyboard: Activity: Adding an image

1. As you did before, edit the `index.md` file in this pull request.
1. In the file, add the correct Markdown for your image of choice. Don't forget to include alt-text!
1. Use the **Preview** tab to check your Markdown formatting.
1. Commit your changes.
1. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

### Additional Information

Images can be added from various sources, such as URLs or local files. To add an image from a URL, use the syntax shown above. To add an image from a local file, use the following syntax:

```md
![Alt text](path/to/image.jpg)
```

You can also add images with custom sizes by specifying the width and height attributes:

```md
![Alt text](path/to/image.jpg){:width="200px" height="100px"}
```

For more information on adding images in Markdown, refer to the [GitHub Docs](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#images).

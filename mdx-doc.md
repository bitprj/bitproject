# Creating a Basic Slide Deck

You only need one mdx file per presentation. Each slide will be separated by a `---` like so:

```markdown
# Hello

---

This is some text

---

# Goodbye!
```
mdx-deck supports all standard markdown elements.

## A Word about Images

Due to the way mdx-deck is currently set up, you can't use local images the same way you would
in a regular md file. Instead you have to use a JavaScript import. An example:

```javascript
import i from '../images/image.jpg';
<img src={i} />
```

As you can see, we import the image from a folder called `images`, and then used it like a JS
variable in markdown.

### SVG Images
SVG images in turn are used a little differently from other images. They are treated like components.
For example:

```javascript
import image from '/path/to/image/image.svg';

<image />
```
As you can see, SVGs are used as empty tags.

# Imports and Themes
Since mdx files have JavaScript functionality, you can import modules and components in the same
way as vanilla JS:

```javascript
import {component} from '\path\to\component'

# Using component
<component> Some cool stuff! </component>
```
This is also the same way that you would import a theme. The only difference is that you would
`export` the theme at the very start of the document:

```javascript
export const theme = importedTheme
```

There are multiple built-in themes, but you will primarily be using custom themes. Here's an
example of a custom theme file:

```javascript
// Example theme.js
export default {
  fonts: {
    body: 'Roboto, sans-serif',
    monospace: '"Roboto Mono", monospace',
  },
  colors: {
    text: 'white',
    background: 'black',
    primary: 'blue',
  },
}
```
Check mdx-deck's [Theming Docs](https://github.com/jxnblk/mdx-deck/blob/master/docs/theming.md "Theming") for more info about themes!

# Layouts

You can create custom layouts to format your content in interesting ways. For example, here is a layout for displaying a title in a column format:

```javascript
export const Column = ({ sx, children }) => (
  <div
    sx={{
      minWidth: '60%',
      minHeight: '60%',
      display: 'flex',
      flexDirection: 'column',
      justifyContent: 'space-between',
      alignItems: 'flex-start',
      ...sx
    }}
  >
    {children}
  </div>
);
```
Layouts are written in JSX, which you could treat as a templating language with the full power of JavaScript.
As you can see, the above code is very similar to CSS.

If you wanted to use Column, you would do it like so:

```javascript
import Column as column from "/path/to/layout/file";

<column>

# A Title

<column>
```
Sometimes you want to change the variables of a layout for a particular slide. This can be done by passing in
the appropriate value for a parameter. In the case of `Column` above, that could look something like this:

```javascript
<column sx={{ minHeight: '0' }}>

Some text.

<column>
```
Here, we changed the default minimum height of the text.

# Components
As stated before, you can import all sorts of Components into your mdx deck. There a quite a few
built-in ones you might find useful. These do not need to be imported. Some include:

## Head

Allows you to put in metadata information for the document. For example, if you wanted to put in info
about a Twitter slide card:

```jsx
<Head>
  <title>My Presentation</title>
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:site" content="@jxnblk" />
  <meta name="twitter:title" content="My Presentation" />
  <meta name="twitter:description" content="A really great presentation" />
  <meta name="twitter:image" content="https://example.com/card.png" />
</Head>
```

## Notes

These allow you to have speaker notes within your presentation. They can be used as follows:

```jsx
<Notes>

- Only visible in presenter mode
- Markdown syntax can be used with empty lines around the content

</Notes>
```

## Header/Footer

For when you want a persistent header/footer in your presentation. An example of a header:

```jsx
<Header>

Put a logo, handle, or something else here...

</Header>
```
It is the exact same syntax for a Footer.

## Steps
This is useful when you have multiple concepts/topics you wnat to go through step-by-step
in one slide. This is a generic tool, and so doesn't have to be used just for explaining code.
An example is shown below:

```jsx
<Steps>

- One
- Two
- Three
- Four

</Steps>
```
Press the arrow keys to step through each element.

# Code Surfer
While Code Surfer is technically a component, it deserves its own section simply because of how rich its
features are. It is an addon that allows you to present code snippets in a slick, fashionable way. In order
to use it, you first need to be install it as part of the dependencies for your slide deck. Then, you would
import it as you would any other component. Here are some of its features:

## Adding Code
To just display code using Code Surfer, just use its tags around the code you want to display. For example:


```js
<CodeSurfer>

​```js
console.log(1);
console.log(2);
console.log(3);
​```
</CodeSurfer>
```
The empty lines between the tags and the code content are <b>required</b>. Additionally, make sure you declare
what language the code is in, like above. This will ensure proper syntax highlighting. Code Surfer supports every language supported by PrismJS, so feel free to import prism as a dependency if you need syntax highlighting for a language not already provided.

## Focus
This allows you to highlight or emphasize certain lines of code. All you have to do is specify the code lines you want emphasized and Code Surfer will take care of the rest. This includes fading out other code, transitions, animations, and the like. Below is an example for Focus:
```js
<CodeSurfer>
    
​```js 1:2,3[8:10]
console.log(1);
console.log(2);
console.log(3);
​```
</CodeSurfer>
```
The new syntax is shown immediately after the language declaration in the code. In plain English, the code says this: "Code Surfer, I want you to highlight the <b>all</b> of lines 1 and 2, as well as <b><i>columns</i></b> 8 to 10 of line 3." The first part is pretty simple, all of line 1 and line 2 will be highlighted. But what are columns? Columns are just another way of stating <i>characters</i> in Code Surfer syntax. In other words, the above code will highlight the 8-10th characters in line 3. This is useful for when you want to emphasize specific words in a line of code, but not the entire line itself.

## Steps
This is the equivalent of the Steps feature in base MDX Deck. By placing multiple code blocks, you can step through multiple code snippets in a single slide. Note that you can freely change the focus parameters in each code block. Like mentioned before, Code Surfer handles all of the transitions, animations, and other effects automatically. Here is an example of using steps:

```js
<CodeSurfer>
    
​```js
console.log(1);
console.log(2);
console.log(3);
​```
​```js 1
console.log(1);
console.log(2);
console.log(3);
​```
​```js
console.log(1);
console.log(2);
console.log(3);
console.log(4);
console.log(5);
​```

</CodeSurfer>
```

## Title and Subtitle
Self-explanatory. This allows you put a title and subtitle for each slide. An example:

```js
<CodeSurfer>
    
​```js 1 title="Title" subtitle="Look at the first line"
console.log(1);
console.log(2);
console.log(3);
​```
​```js 2 title="Title" subtitle="and now the second"
console.log(1);
console.log(2);
console.log(3);
​```
</CodeSurfer>
```
You can also have titles and subtitles for Steps, and they can each be different!

## Themes
Themes work the exact same way as they do in base MDX Deck, with one exception. You can have separate themes for each slide if you would like. An example would be like so:

```js
import { CodeSurfer } from "code-surfer"
import { nightOwl } from "@code-surfer/themes"

<CodeSurfer theme={nightOwl}>
    
​```js
console.log(1);
console.log(2);
console.log(3);
​```

</CodeSurfer>
```
Also just like base MDX Deck, you can write your own custom themes!

## Columns
This is when you want to display more than one code snippet at a time. An example:

```js
import { CodeSurferColumns, Step } from "code-surfer"

<CodeSurferColumns>

<Step subtitle="First Step">

​```js
console.log(1);
console.log(2);
​```

​```js
console.log("a");
console.log("b");
​```

</Step>

<Step subtitle="Second Step">

​```js 2
console.log(1);
console.log(2);
​```

​```js 2
console.log("a");
console.log("b");
​```
</Step>

</CodeSurferColumns>
```
Side note: Just like with code blocks, you can have a theme for each column:

```js
<CodeSurferColumns themes={[theme1, theme2]}>.
```
Additionally, the columns don't all have to be the same size. For example:

```js
<CodeSurferColumns sizes={[1,3]}>.
```
Here, the second column is 3 times the size of the first. 

One last thing about columns. You don't have to use them exclusively for displaying code, you can also just place regular markdown or even other components between them!

## Importing Code
You don't have to manually type out code you want to display. If you have it in a file somewhere, you could simply link that file like so:

```js
import { CodeSurfer } from "code-surfer"

<CodeSurfer>

​```js 5:10 file=./my-code.js
​```

​```js file=./my-other-code.js
​```

</CodeSurfer>
```
Here, we linked to two files in the same directory as our deck. Make sure to put the proper pathname for your files when importing code.

## Line Numbers
If you want to show the line numbers for code to display, you can simply insert the `showNumbers` flag in your code snippet. An example:

```js
import { CodeSurfer } from "code-surfer"

<CodeSurfer>

​```js showNumbers
console.log(1);
console.log(2);
console.log(3);
​```

​```js
console.log(1);
console.log(2);
console.log(4);
​```

</CodeSurfer>
```

## Diffs
Sometimes, you could be presenting the same code across multiple slides. In this case, it would be annoying to copy and past the same code blocks in every slide, but you don't have to! By using `diff`, you specify that you want the same code to be displayed but with some slight <i>differences</i> to the presentation, like focusing on different lines, or new titles and subtitles. Here is an example of `diff` being used:

```js
import { CodeSurfer } from "code-surfer"

<CodeSurfer>

​```js
console.log(1);
console.log(2);
console.log(3);
​```

​```diff 1 subtitle="log 1"
​```

​```diff 2 subtitle="log 2"
​```

​```diff 3 subtitle="log 3"
​```

</CodeSurfer>
```
Here, we display the same code in all the code blocks, but each `diff` specifies a particular line to highlight and subtitle to display.

## A Full Example
To see an example that uses all of these features, see this [slide deck](https://codesurfer.pomb.us/full/ "Code Surfer"), as well as it's [source code](https://codesurfer.pomb.us/full/ "Code Surfer Deck").

# Deploying a Presentation

To run mdx-deck, add a run script to your package.json file like this :

```
"scripts": {
  "start": "mdx-deck deck.mdx"
}
```

Then run `npm start` in your command terminal.
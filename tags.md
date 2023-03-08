
### Exploring the code

You used several tags to display your new page. Below is a table that describes each of these tags and what it is used for. As you look at the code, notice that the HTML is in all lower case letters, and that you use tabs to create an outline for the code. While this isn't required, it does make your HTML much more readable.

| tag                          | description                                                                                                                                                                                                      |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `html`                       | Container for all HTML in an HTML page.                                                                                                                                                                          |
| `head`                       | Contains metadata, or information about the page.                                                                                                                                                                |
| `link`                       | Used to tell the page what CSS stylesheet to use. `rel="stylesheet"` indicates we are using a stylesheet, and `href="style.css"` loads **style.css** (which is the name of the stylesheet we'll create in the CSS section of the workshop). |
| `title`                      | Indicates the title of the page to display on the toolbar. This is **not** displayed on the page itself. Every page you create should have a title.                                                              |
| `body`                       | The contents of the page to be displayed to the user.                                                                                                                                                            |
| `header`, `main`, `article`, `section` | These are "semantic" tags. See the description below for more information.                                                                                                                                              |
| `h1`                         | A level 1 header. Header tags go from `h1` to `h6`, with `h1` being the highest level, to `h6` being the lowest level. These are used to create structure for the outline of the page. |
| `p` | A paragraph tag. Paragraph tags are where the body text of your page goes.
| `hr` | Creates a horizontal line. The tag stands for "horizontal rule".
| `id` | `id` is an attribute that allows you to assign a unique id for an HTML element. This will come in handy when we style the HTML. 
| `<!-- comment -->` | These are HTML comments. They are useful for making notes or setting reminders to yourself.

> **Note:** Comments are a great way to take notes as you're learning HTML. You can put a comment right above a section of code, and describe what the section does. But do remember comments **are not** hidden from browsers, so don't store sensitive information in comments as anyone who views the source of your code can read your comments.

#### Semantic tags

Semantic tags are a relatively new addition to HTML. You may notice on the page there is a difference in size between `h1` and `h2`. This is because besides just indicating a level, header tags also modify how content is displayed. Semantic tags such as `header`, `main`, `article` and `section` are only used to group information together. Semantic tags are useful to structure a large HTML document, and later use CSS to control how the content will actually get displayed.

You can use semantic tags however you wish, but a common hierarchy is:

- `header`
- `main`
    - `article`
        - `section`

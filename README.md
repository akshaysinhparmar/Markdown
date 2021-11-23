# Markdown
### What is Markdown ? 
Markdown is a lightweight markup language that you can use to **add formatting elements to plaintext text documents.**
In an application like Microsoft Word, you click buttons to format words and phrases, and the changes are visible immediately. Markdown isn’t like that. When you create a Markdown-formatted file, you add Markdown syntax to the text to indicate which words and phrases should look different.
### Why Use Markdown?
- Markdown can be used for everything. People use it to create websites, documents, notes, books, presentations, email messages, and technical documentation.

- Markdown is portable. Files containing Markdown-formatted text can be opened using virtually any application. If you decide you don’t like the Markdown application you’re currently using, you can import your Markdown files into another Markdown application. That’s in stark contrast to word processing applications like Microsoft Word that lock your content into a proprietary file format.

- Markdown is platform independent. You can create Markdown-formatted text on any device running any operating system.

- Markdown is future proof. Even if the application you’re using stops working at some point in the future, you’ll still be able to read your Markdown-formatted text using a text editing application. This is an important consideration when it comes to books, university theses, and other milestone documents that need to be preserved indefinitely.

- Markdown is everywhere. Websites like Reddit and GitHub support Markdown, and lots of desktop and web-based applications support it.

### How Does it Work?
When you write in Markdown, the text is stored in a plaintext file that has an .md or .markdown extension.

The short answer is that you need a Markdown application capable of processing the Markdown file. There are lots of applications available — everything from simple scripts to desktop applications that look like Microsoft Word.

Markdown applications use something called a Markdown processor (also commonly referred to as a “parser” or an “implementation”) to take the Markdown-formatted text and output it to HTML format. At that point, your document can be viewed in a web browser or combined with a style sheet and printed. You can see a visual representation of this process below.

 > Note: The Markdown application and processor are two separate components. For the sake of brevity, I've combined them into one element ("Markdown app") in the figure below.

![image](https://user-images.githubusercontent.com/48562260/141735824-6bdd6243-3747-4a88-bf21-69f9e36bad04.png)

To summarize, this is a four-part process:

- 1 Create a Markdown file using a text editor or a dedicated Markdown application. The file should have an .md or .markdown extension.
- 2 Open the Markdown file in a Markdown application.
- 3 Use the Markdown application to convert the Markdown file to an HTML document.
- 4 View the HTML file in a web browser or use the Markdown application to convert it to another file format, like PDF
 
### What’s Markdown Good For?
Markdown is a fast and easy way to take notes, create content for a website, and produce print-ready documents.

It doesn’t take long to learn the Markdown syntax, and once you know how to use it, you can write using Markdown just about everywhere. Most people use Markdown to create content for the web, but Markdown is good for formatting everything from email messages to grocery lists.

Here are some examples of what you can do with Markdown.

What’s Markdown Good For?
Markdown is a fast and easy way to take notes, create content for a website, and produce print-ready documents.

It doesn’t take long to learn the Markdown syntax, and once you know how to use it, you can write using Markdown just about everywhere. Most people use Markdown to create content for the web, but Markdown is good for formatting everything from email messages to grocery lists.

Here are some examples of what you can do with Markdown.

#### Websites

Markdown was designed for the web, so it should come as no surprise that there are plenty of applications specifically designed for creating website content.

If you’re looking for the simplest possible way to create a website with Markdown files, check out blot.im. After you sign up for Blot, it creates a Dropbox folder on your computer. Just drag and drop your Markdown files into the folder and — poof! — they’re on your website. It couldn’t be easier.

If you’re familiar with HTML, CSS, and version control, check out Jekyll, a popular static site generator that takes Markdown files and builds an HTML website. One advantage to this approach is that GitHub Pages provides free hosting for Jekyll-generated websites. If Jekyll isn’t your cup of tea, just pick one of the many other static site generators available.

## Cheat Sheet of Markdown 


```

# H1
## H2
### H3
#### H4
##### H5
###### H6
Alternatively, for H1 and H2, an underline-ish style:
Alt-H1
======
Alt-H2
------
```


# H1
## H2
### H3
#### H4
##### H5
###### H6
Alternatively, for H1 and H2, an underline-ish style:
Alt-H1
======
Alt-H2
------

## Basic Syntax


### Heading

# Markdown Cheat Sheet

Thanks for visiting [The Markdown Guide](https://www.markdownguide.org)!

This Markdown cheat sheet provides a quick overview of all the Markdown syntax elements. It can’t cover every edge case, so if you need more information about any of these elements, refer to the reference guides for [basic syntax](https://www.markdownguide.org/basic-syntax) and [extended syntax](https://www.markdownguide.org/extended-syntax).

## Basic Syntax

These are the elements outlined in John Gruber’s original design document. All Markdown applications support these elements.

### Heading

```
# H1
## H2
### H3
```
# H1
## H2
### H3

### Bold

``` 
**bold text** 
```
**bold text**

### Italic
```
*italicized text*
```
*italicized text*

### Blockquote

```
> blockquote
```
> > blockquote

### Ordered List
```

1. First item
2. Second item
3. Third item
```
1. First item
2. Second item
3. Third item

### Unordered List

```
- First item
- Second item
- Third item
```
- First item
- Second item
- Third item

### Code

```
`code`
```
`code`

### Horizontal Rule
```
---
```
---

### Link

```
[Markdown Guide](https://www.markdownguide.org)
```
[Markdown Guide](https://www.markdownguide.org)

### Image
```
![alt text](https://www.markdownguide.org/assets/images/tux.png)
```

![alt text](https://www.markdownguide.org/assets/images/tux.png)

## Extended Syntax

```
These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.
```
These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

### Table

```
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |
```
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

### Fenced Code Block
 
> ```
> {
>    "firstName": "Akshaysinh",
>    "lastName": "Parmar",
>    "Number": 9727775553 
> }
> ```

```
{
    firstName": "Akshaysinh",
    "lastName": "Parmar",
    "Number": 9727775553
}
```

### Footnote

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

### Heading ID

### My Great Heading {#custom-id}

### Definition List

term
: definition

### Strikethrough

~~The world is flat.~~

### Task List

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media


### Bold

**bold text**

### Italic

*italicized text*

### Blockquote

> blockquote

### Ordered List

1. First item
2. Second item
3. Third item

### Unordered List

- First item
- Second item
- Third item

### Code

`code`

### Horizontal Rule

---

### Link

[Markdown Guide](https://www.markdownguide.org)

### Image

![alt text](https://www.markdownguide.org/assets/images/tux.png)

## Extended Syntax

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

### Table

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

### Fenced Code Block

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Footnote

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

### Heading ID

### My Great Heading {#custom-id}

### Definition List

term
: definition

### Strikethrough

~~The world is flat.~~

### Task List

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media


# DearScholars.github.io

This repository holds the source code to the websites <www.DearScholars.org>.

- [Modifying the Website](#modifying-the-website)
  - [Files](#files)
  - [Pages](#pages)
- [Markdown](#markdown)
- [Technical Details](#technical-details)

# Modifying the Website

## Files

To create a file:

1. From the project's main page click the "Create new file" button.
2. Type in the file's name at the top.
3. Add any content you want to the file.
4. Click the "Commit Changes" button to create the file.

To edit a file:

1. Click on the filename from the project's main page.
2. Click on the pencil icon in the top right corner.
3. You can now edit the file.
4. Click the "Commit Changes" button to save your edits.

To delete a file:

1. Click on the filename from the project's main page.
2. Click on the trashcan icon in the top right corner.
3. Click the "Commit Changes" button.

To upload a file:

1. From the project's main page click the "Upload files" button.
2. Drag or select the files you want to upload.
3. Click the "Commit Changes" button.

## Pages

To create a new page:

1. Create a new file called `pageName.md`. (ex. `movies.md`, `greatBooks.md`)
2. Edit the file `navigation.html` in the folder `_includes`.
3. Add the line `<li> <a href="pageName.html">Sidebar Name</a> </li>` on one of the lines.
   **Note:** `pageName.html` not `pageName.md`, and also replace `Sidebar Name` with whatever name you want. (ex. `Great Movies`, `Best Ted Talks`)
4. Edit the file `pageName.md` and add the following text at the top of the file:
```
---
layout: default
---
```

To edit a page:

1. Edit the `pageName.md` file.

To remove a page:

1. Remove the `pageName.md` file.
2. Remove the line `<li> <a href="pageName.html">Sidebar Name</a> </li>` from the file `navigation.html` in the folder `_includes`.

# Markdown

Markdown is a markup language (designed for the processing, definition and presentation of text) the makes it easy to read and edit prose.
Refer to John Gruber's [Markdown Syntax](https://daringfireball.net/projects/markdown/syntax) for specific details on how to write in Markdown.
Here is a short example:

```
# An h1 header

Paragraphs are separated by a blank line.

2nd paragraph. *Italic*, **bold**, and `monospace`. Itemized lists
look like:

* this one
* that one
* the other one

Note that -- not considering the asterisk -- the actual text
content starts at 4-columns in. Oh yeah -- you can also have
numbered lists:

1. The first item.
2. Man in the middle.
3. The last.

## Block Quoting 

> Block quotes are
> written like so.
>
> They can span multiple paragraphs,
> if you like.
```

Produces the following:

> # An h1 header
> 
> Paragraphs are separated by a blank line.
> 
> 2nd paragraph. *Italic*, **bold**, and `monospace`. Itemized lists
> look like:
> 
> * this one
> * that one
> * the other one
> 
> Note that -- not considering the asterisk -- the actual text
> content starts at 4-columns in. Oh yeah -- you can also have
> numbered lists:
> 
> 1. The first item.
> 2. Man in the middle.
> 3. The last.
> 
> ## Block Quoting 
> 
> > Block quotes are
> > written like so.
> >
> > They can span multiple paragraphs,
> > if you like.

# Technical Details

This site is hosted using GitHub Pages' support for [Jekyll](https://jekyllrb.com/).
More information can be found on these pages:

- [Jekyll Documentation](https://jekyllrb.com/docs/home/): Documentation on how to use and configure Jekyll.
- [Using GitHub Pages and Jekyll](https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/): Specific information on how GitHub Pages uses Jekyll.

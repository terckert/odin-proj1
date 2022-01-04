# Simple Recipe Website - [The Odin Project](https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/recipes) - Project 1
## Section Review
### Basic Outline for a Website
----
```html
<!-- DOCTYPE html and </html> signify the beginning and ending of the -->
<!-- websites code -->
<!DOCTYPE html> 
<html lang="en">
<head>
    <!-- The header, contains information needed to correctly display -->
    <!-- a website -->
</head>
<body>
    <!-- The basic outline for a website -->
</body>
</html>
```
### Header
----
In VSCode simply typing '!' and hitting tab will allow you to create a header.<br>
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
```
The header stores the information we need. Charset tells the webpage which character set to use. Standard is UTF-8. The title is what will appear in the browser bar/tab.
### Body
------
1. Using paragraph and break
    * Using <strong><em>p</em></strong> to create paragraphs in the body.
    * <strong><em>br</em></strong> to seperate within paragraphs.
2. Using italics and bold characters
    * The <strong><em>em</em></strong> tag will allow you to print using italicized characters.
    * The <strong><em>strong</em></strong> tag allows text to be bolded.
3. Headers
    * The <strong><em>h#</em></strong> tag allows you to create different sized heading lines.
```html
<p> 
    This is a brand new paragraph.
</p>
<p>
    <em>This is a brand new paragraph in italics</em>
    <!-- Creating a break within this paragraph -->
    <br>
    <strong>This is a brand new line in bold.</strong>
</p> 
```
### Lists
----
1. List elements
    * Using <strong><em>li</em></strong> for both types of lists to add list elements.
2. Unordered lists
    * Uses the <strong><em>ul</em></strong> tag to create unordered lists.
3. Ordered lists
    * The <strong><em>ol</em></strong> tag is used to create ordered lists.
```html
<!-- Creating an unordered list. Elements will have bullets. -->
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>
<!-- Creating an ordered list. Elements will be numbered by default. -->
<ol>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ol>
```
### Images, Links, Relative and Absolute Paths
----
1. Images
    * Uses the <strong><em>img</em></strong> tag to link an image into a website
        * <strong><em>src</em></strong> subtag contains the path to the image. Can be absolute or relative to the current directory.
        * <strong><em>alt</em></strong> subtag shows when the image is unable to load for whatever reason.
2. Links
    * Links to other webpages.
        * Within the domain can use relative or absolute paths.
        * Outside of the domain must use the absolute path and needs to include the <em>http://</em> or <em>https://</em> part of the website. 
3. Absolute path containts the full path. If used internally would include the entire path necessary to get to the desired file. If used as part of a link or image must include the <em>http://</em> or <em>https://</em> part.
4. Relative paths allow you to avoid using the entire path and scope the project to the current directory. 
    * <em>./path/to/file</em> if you can navigate from the current directory.
    * <em>../</em> in a path moves you up one folder. <em>../path/to/file</em> would be used if you are one removed from the current directory to the main path.
```html
<!-- Image linked with an absolute path -->
<img src="https://www.theodinproject.com/mstile-310x310.png" alt="The Odin Project Logo">
<!-- Internal domain linked with a relative path -->
<a href="./pages/about.html">About</a>
```
## Project Description
Create a simple website that links to three recipes that can be navigated to using a simple interface. The website should be viewable through Github link integration. <br>
To use GitHub link integration:
<ol>
<li> The main hubpage needs to be named index.html
<li> On GitHub, go to your repo and click <strong>Settings</strong> -> <strong>Pages</strong>
<li> Change the source from <em>none</em> to <em>main branch</em> and click <strong>Save</strong>.
<li> It may take up to 10 minutes, but the website should be viewable from <code>your-github-username.github.io/your-github-repo-name</code>
</ol>
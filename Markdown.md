---
title: Markdown
categories:
- Markup Language
- Guide
feature_text: |
  A markdown toolkit to give some order
feature_image: "https://sorrego.xyz/wp-content/uploads/2023/03/733-2560x600-1.jpg"
image: "https://sorrego.xyz/wp-content/uploads/2023/03/733-2560x600-1.jpg"
---

I decided to start with what is, perhaps, the ground of this side of my work, Markdown. This markup language serves as the primary structure for my explorations in digital methods. One does not need anything other than a text editor to explore all the advantages of Markdown, a  lightweight markup language (LML) that helps me structure this GitHub-based blog and my Obsidian+Zotero noting-taking. The main advantage of this LML is its simplicity. Its syntax can be learned fast, and its application does not require previous programming knowledge. Nevertheless, the usability and possibilities of Markdown are multiple since one can read the documents created using its grammar through many platforms and software. Below, there is a summary of its main elements:

## Content
+ [Headers](#headers)
+ [Separators](#separators)
+ [Block-of-code](#block-of-code)
+ [List](#lists)
+ [Emphasis](#emphasis)
+ [Links](#links)
+ [Images](#images)
+ [Anchors](#anchors)

## Headers
There are six levels of headings. They can be made by adding hashes before the word or phrase one wants to turn into a header:

# Header H1
H1: # + (title)

---
## Header H2
H2: ## + (title)

---
### Header H3
H3: ### + (title)

---
#### Header H4
H4: #### + (title)

---
##### Header H5
H5: ##### + (title)

---
###### Header H6
H6: ###### + (title)

[Content-list](#content)

---
## Separators 
A separator or horizontal rule is a line used to divide content. All elements along with this guide were structured using separators. There are three ways of creating them:
Three hyphens: ---
Three asterisks: ***
Three underscores: ___

[Content-list](#content)

---
## Block of code
Those blocks are spaces one can write lines of code without issues with the syntax. They are created by typing three backticks (```) to open and three more to close the block
```
<html>
 <head>
 </head>
 <body>
   <h1>Hello World<h1>
 </body>
</html>
```
[Content-list](#content)

---
## Lists
There are two types of lists, ordered and unordered. 
An ordered list starts with a “1.” Most software nowadays identifies ordered and unordered lists and can list the following elements after one writes “1.” Unordered lists may start either with an asterisk (*), a sum sign (+), or a hyphen (-).
1.	Uno
2.	Dos
3.	Tres
4.	…

-	Uno
-	Dos
-	Tres
-	…

[Content-list](#content)

---
## Emphasis
One can use three types of resources in Markdown: Empashis (Italics), Strong emphasis (Bold), and Strikethrough.
```
Italics *asterisks* or _undercores_
```
*This is a text in italics*
 
```
Bold **Two asterisks**
```
**This is a bold text. Do not confuse it with a header**

```
Strikethrough ~~Two tildes~~
```
~~A strikethrough line~~

[Content-list](#content)

---
## Links 
There are two ways of writing links. 
1.	A direct one – inline style 
```
[title](https://website.com)
```
2.	A reference style
```
[title][1]
[1]: (https://website.com)
```

[Content-list](#content)

---
## Images
Similar to links, images can be added by using the two above styles:
1.	Inline
```
![alt text](image link)
```
2.	Reference
```
![alt text][1]
[1]: (image link)
```
[Content-list](#content)

---
## Anchors
Anchors are inner links. They are useful to improve the navigation around a long document. 
```
[Name-of-the-link](#pointing-at)
```

[Content-list](#content)
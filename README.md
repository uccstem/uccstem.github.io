# UCC STEM Website

[![Test Jekyll Build](https://img.shields.io/badge/Jekyll%20Build-Success-brightgreen)](uccstem.github.io)

Hello! This is the UCC STEM website, which is built with Jekyll and deployed using Github Pages. This documentation provides info for the parsed pages and instructions on how to access website files and update pages (for devs).

## Adding an Event Page

Most pages on this website are parsed using Jekyll and exist as a *Markdown* file (.md extension). If you are unfamiliar with markdown, it is essentially a text file with additional symbols that are used to denote styles (bold, italics, etc). You can learn more about markdown stylings [using this reference](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

The event pages, as markdown files, are stored in the folder `_events` located in the root directory.

For our webpage, each markdown file (webpage) begins with metadata which provides info about the event. The file structure of markdown (example):
```md
---
name: "Sample Event"
date: "2021-02-15"
tags: "Biology"
image: "example_photo.png"
intro: "One sentence intro of the event."
status: "ongoing"
---

The actual content of the webpage and event goes here.

This is the lorem ipsum of the event. It supports
complete Markdown formatting, so you can insert links in
paragraphs [like this one](http://example.com) or format
text **to be bold**, *italicized*, or make lists:
1. Number one
2. Number two
* Unordered one
* Unordered two


```

# GhostHost

## 1 - Abstract

***How you gonna host?***

GhostHost is a hosting convention and solution for simple frontend-only web apps which allows for
free, unlimited, and anonymous publication, all with a low technical barrier to entry.

## 2 - Contents

### 2.1 - Conventions

GhostHost is to operate as a standalone website, and may be provided with the URL argument "html"
specifying the URL to a raw text file containing HTML code. When GhostHost is loaded with said
argument provided, it shall render the HTML code in the specified file as a live site.

In certain implementations, different arguments (such as "js") can be used to support languages
other than html.

### 2.2 - Usage

An implementation of GhostHost is hosted at the following link:

    https://Telos-Project.github.io/GhostHost/

Hence to use this implementation of GhostHost, the URL for your project will follow this format:

	https://Telos-Project.github.io/GhostHost/?html=[YOUR_CODE_LINK]

Here's an example:

	https://Telos-Project.github.io/GhostHost/?html=https://raw.githubusercontent.com/Telos-Project/GhostHost/main/Examples/example.html
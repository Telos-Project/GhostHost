# GhostHost

## 1 - Abstract

***How you gonna host?***

GhostHost, or Telos GhostHost, is a hosting convention and solution for simple frontend-only web
apps which allows for free, unlimited, and anonymous publication, all with a low technical barrier
to entry.

## 2 - Contents

### 2.1 - Conventions

GhostHost is to operate as a standalone website.

#### 2.1.1 - Renderers

GhostHost shall accept URL arguments, referred to as GhostHost renderers, which may either contain
URLs to, or the string content of, external resources. It shall render the content of said
resources according to the aliases of the corresponding arguments.

#### 2.1.2 - Adapters

External applications hosted via GhostHost, which themselves serve to bootstrap external content
according to URL arguments, are referred to as GhostHost adapters.

### 2.2 - Defaults

GhostHost, by default, supports the HTML renderer, for which the argument alias is "html", and the
content is the URL to the raw text of an external HTML file.

### 2.3 - Usage

A default implementation of GhostHost is hosted at the following link:

    https://Telos-Project.github.io/GhostHost/

Hence to use this implementation of GhostHost, the URL for your project will follow this format:

	https://Telos-Project.github.io/GhostHost/?html=[YOUR_CODE_LINK]

Here's an example:

	https://Telos-Project.github.io/GhostHost/?html=https://raw.githubusercontent.com/Telos-Project/GhostHost/main/Examples/example.html
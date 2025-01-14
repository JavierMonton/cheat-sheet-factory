---
title: W3m Shortcuts
category: Linux
layout: 2017/sheet
updated: 2021-01-07
keywords:
    - "w3m"
    - "w3m key bindings"
prism_languages: [bash]
intro: |
  List of W3m key bindings 
---

Shortcuts
---------
{: .-three-column}

### Common shortcuts

| `⇧h` | Show hot keys |
| `⇧b` | Get out of hot keys menu |
| `←→↑↓`/`hjkl` | Navigation |
| `⭾`/`⇧⭾` | Navigate through links |
| `v` | View the source |
| `/` | Forward search |
| `?` | Backward search |
| `n` | Go to next search |
| `⇧n` | Go to previous search |
| `⇧b` | Go previous page |
| `s` | Go forward page |
| `gg` | Go to top of page |
| `⇧g` | Go to end of page |
| `⇧t` | Open a tab |
| `⌃q` | Close a tab |
| `⇧u` | Go to a url |
| `⇧{}` | Switch between tabs |
| `⇧m` | Copy a link of current page |
| `Esc⇧m` | Copy a link that cursor is on it |
| `⌃h` | Show history |
| `⇧b` | Exit history |
| `⇧i` | View image |
| `Esci` | Save image |
| `c` | Show which page you are on |
| `u` | View a URL of a link |
| `Escb` | View bookmarks |
| `Esca` | To bookmark |
| `<>` | Scroll left and right |
| `o` | Open options/preferences |
| `[number` | Go to link number |
| `L`| List all links in page with urls |
| `ESC-l` | List all links pop up |
{: .-shortcuts}

### Misc

Show all links in a page in pop up form to select (without going to link):
{: .-setup}

```bash
Escm
```

Show all links in a page in pop up form to select (with going to link): 

```bash
Escl
```

To be able to login to sites that require cookies:

```bash
w3m -cookie
```

Bookmarks are stored in:

```bash
~/.w3m/bookmarks.html
```

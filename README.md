# Smore 
Smore is a gruvbox theme created for hugo. I use this theme on my personal site but have put it here for anyone to take advantage of!
![](Pasted%20image%2020221228201154.png)
- Site Demo - https://grahamhelton.com

---

## Features
- Simple Gruv-y look 
- Easy to customize and edit
- License and copyright free. Credit me if you use the theme, or don't. Up to you
- Analytic tag support


#### Code highlighting
Adding the following to your config.toml will enable syntax highlighting for your code. You can browse the supported themes [here)(https://github.com/alecthomas/chroma/tree/master/styles).


```bash
[markup]
  [markup.highlight]
   anchorLineNos = false
    codeFences = true
    guessSyntax = false
    hl_Lines = ''
    hl_inline = false
    lineAnchors = ''
    lineNoStart = 1
    lineNos = true 
    lineNumbersInTable = false 
    noClasses = true
    noHl = false
    style = 'gruvbox'
    tabWidth = 4



```
![](Pasted%20image%2020221228201622.png)


## How to install
You can download the theme by cloning this repository into your themes folder. 

⚠️ The theme was tested using hugo version 0.109. It will likely still work on older versions but some features (such as syntax highlighting) will probably not work. You can check your hugo version by typing `hugo version`.

## Install theme locally
Ensure you are in your root web directory (The one that contains `config.toml`)

```bash
git clone https://github.com/grahamhelton/smore themes/terminal
```

This will clone the repository directly to the `themes/smore` directory.

## How to run your site

```bash
hugo server -t smore
```

and go to `localhost:1313` in your browser. From now on all the changes you make will go live, so you don't need to refresh your browser every single time.

## How to configure

The theme doesn't require advanced configuration. Just copy:

```toml
title = "Your_Site_Name"                # Change me!
baseURL = "https://yoursite.com"        # Change me!
relativeURLs = true
theme = "smore"
enableEmoji = true

# Change me if you use google analytics
googleAnalytics = "UA-123456789"        
# Sets the amount of blog posts that appear before creating a new page
paginate = 15

# Set the parameters for your site
[params]
author = "Your Name"
description = "Site Description"
# path to a .ico to use as favicon
favicon = "favicon.ico"  

# Define syntax highlighting
[markup]
  [markup.highlight]
   anchorLineNos = false
    codeFences = true
    guessSyntax = false
    hl_Lines = ''
    hl_inline = false
    lineAnchors = ''
    lineNoStart = 1
    lineNos = true 
    lineNumbersInTable = false 
    noClasses = true
    noHl = false
	# Syntax style. Choose themes from here
    style = 'gruvbox'
    tabWidth = 4
```

to `config.toml` file in your Hugo root directory and change params fields. 

## How to edit the theme <a id="how-to-edit" />

All you need to do is go into `website_root/themes/smore/` then you can directly edit anything in the theme. No compilation step needed.

## Found a bug? 

If you spot any bugs, please use [Issue Tracker](https://github.com/grahamhelton/smore/issues) or create a new [Pull Request](https://github.com/grahamhelton/smore/pulls) to fix the issue.

## Are you using this theme?
I made this theme for myself, but open sourced it so others could use it! I'd love to see your site if you're using this theme. If you are, let me know! I would love to have a list of all the sites using this theme!

## License

Use this however you want. Credit me or don't. Up to you.

## Upcoming Features
- Add sane metatag support
- Zoom in mobile UI. ( I thought it looked fine but others have said it is too small)

## Inspiration
- This theme was HEAVILY inspired by [Researcher](https://github.com/ojroques/hugo-researcher). Some of the CSS from smore is taken from there as well! 

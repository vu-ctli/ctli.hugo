+++
#
# Header: material between the "+++" lines defines parameters that
#         characterize the post (title, date, author, etc.)
#
# Any material after a "#" character is ignored.
# Note: Below the second "+++", the "#" character has a different meaning
#       and any line starting with "#" is text that's formatted as a header.
#
title = "{{ replace .Name "-" " " | title }}"
date = {{ .Date }}
author = "" # Put your name here.
#
# To enable items below delete the # from the beginning of the line
#
# description = "" # A short headline-type description
# featured = "" # A filename for a featured image for the post (in the same directory as the .md file)
# featuredalt = "" # Alternate text description of the featured image
# featuredcredit = "" # Credit line for the image. Can include markdown formatting
# featuredpath = "" # Only use this if you need to override the path for the featured image to somewhere other than the local directory
#
categories = ["Projects", "Teaching", "Research"] # edit to set category
tags = [] # Add keyword tags with quotation marks separated by commas
type = "post" # alternate values are "project" for main project description
draft = "true"
+++
# {{ replace .Name "-" " " | title }}

Write your post here in plain text.
Use markdown for text styling.
See this cheatsheet for an overview: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

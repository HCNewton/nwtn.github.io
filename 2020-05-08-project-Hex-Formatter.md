---
layout: post
title: Project Log - Hex Formatter
author: Conor Newton
date: '2020-08-08 14:35:23 +0530'
category:
        - projects
        - career
summary: Ever find yourself working with Hex values and having to change the formatting of them between tools, calculators and programs?<br/>Me too.<br/>So I built myself a tool for it.
thumbnail: hex_formatter.jpg
---
<br/>

## 8th August 2020: 

This week at work I've be working with CMAC and Chaskey funstions. In order to confirm that the functions are working as intended, I've been looking for online calculators and tools to compare results with. I work in a C space, where an array of unsigned characters (array of 8-bit or 1-byte indexes) are passed into the functions I'm working with. You commonly set-up these arrays like this:

```c
#include <stdint.h>

uint8_t hexArray[] = { 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00,
			0x00, 0x00, 0x00, 0x00, 0x01, 0x23, 0x45 };
```

Often I have to change the format of these hex strings. Removing the spacing, commas and 0x. So I thought I would make myself a tool to make my life a little easier. Then I though, I haven't worked with C++ in a while, if I'm going to make a desktop application, then I may as well do it right. I'm going to see if I can host the program right here on the site too.



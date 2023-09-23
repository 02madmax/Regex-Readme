## Table of Contents
- [Introduction](#introduction)
- [Regex Breakdown](#regex-breakdown)
- [Components of the Regex](#regex-components)
- [About Me](#author)

# Introduction
<a name="introduction"></a>
Regular expressions (more commonly known as regex) are powerful and flexible patterns used in all languages to search,
and manipulate strings of texts. They are used to easily find and describe text patterns. They are usually composed of a 
combination of characters and metacharacters which are then used to translate into any text. It is a universal language in 
computer science. Regex is an essential tool for parsing and extracting information in any programming language.

## Breaking down Regex by components
<a name="regex-breakdown"></a>
/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/

## Components of the Regex
<a name="regex-components"></a>
1. '^': Anchors the regex at the start of the string, and will ensure that we start from the beginning of the HTML markup
2. '<': This will match any opening angle bracket to match the start of any HTML tag.
3. '([a-z]+)': It will capture one or lowercase letter, so essentially any HTML tag.
4. '([^<]+)*': This component captures any instance of characters that are not opening angle brackets, such as attributes or
content within the HTML tag. The wildcard (*) allows for zero or more occurrences of this instance.
5. '(?:>': Will get the closing part of a tag.
6. '(.*)': It gets any content inside of an HTML tag. This component allows us to extract inner HTML content/text.
7. '<\/\1>': This component of the expression will backreference the opening HTML tag to the closing tag of that same tag
first retrieved.
8. '|\s+\/>)$': 

## About Me
<a name="author"></a>
My name is Phillip Lam Thach and I am currently working towards a certificate in the U of U's full stack engineering 
program. This program has taught me an immense amount of information about coding and more specifically coding within
the job field. I am excited to start a new career in the web development industry and continue to broaden my knowledge.

My GitHub: [https://github.com/02madmax](https://github.com/02madmax)

---
title: "test"
meta_title: "test"
description: "test"
date: 2025-01-09T05:00:00Z
image: "/images/posts/post1/P1.jpg"
categories: ["Trailrunning"]
tags: []
draft: true
---
{{< toc >}}

Here is an example of headings. You can use this heading by the following markdown rules. For example: use # for heading 1 and use ###### for heading 6.

Heading 1
Heading 2
Heading 3
Heading 4
Heading 5
Heading 6
Emphasis
The emphasis, aka italics, with asterisks or underscores.

Strong emphasis, aka bold, with asterisks or underscores.

The combined emphasis with asterisks and underscores.

Strike through uses two tildes. Scratch this.

Button
{{< button label="Button" link="/" style="solid" >}}

Link
I'm an inline-style link

I'm an inline-style link with title

I'm a reference-style link

I'm a relative reference to a repository file

You can use numbers for reference-style link definitions

Or leave it empty and use the link text itself.

URLs and URLs in angle brackets will automatically get turned into links. http://www.example.com or http://www.example.com and sometimes example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

Paragraph
Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam nihil enim maxime corporis cumque totam aliquid nam sint inventore optio modi neque laborum officiis necessitatibus, facilis placeat pariatur! Voluptatem, sed harum pariatur adipisci voluptates voluptatum cumque, porro sint minima similique magni perferendis fuga! Optio vel ipsum excepturi tempore reiciendis id quidem? Vel in, doloribus debitis nesciunt fugit sequi magnam accusantium modi neque quis, vitae velit, pariatur harum autem a! Velit impedit atque maiores animi possimus asperiores natus repellendus excepturi sint architecto eligendi non, omnis nihil. Facilis, doloremque illum. Fugit optio laborum minus debitis natus illo perspiciatis corporis voluptatum rerum laboriosam.

Ordered List
List item
List item
List item
List item
List item
Unordered List
List item
List item
List item
List item
List item
Notice
{{< notice "note" >}} This is a simple note. {{< /notice >}}

{{< notice "tip" >}} This is a simple tip. {{< /notice >}}

{{< notice "info" >}} This is a simple info. {{< /notice >}}

{{< notice "warning" >}} This is a simple warning. {{< /notice >}}

Tab
{{< tabs >}} {{< tab "Tab 1" >}}

Hey There, I am a tab
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

{{< /tab >}}

{{< tab "Tab 2" >}}

I wanna talk about the assassination attempt
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

{{< /tab >}}

{{< tab "Tab 3" >}}

We know you’re dealing in stolen ore
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo

{{< /tab >}} {{< /tabs >}}

Accordions
{{< accordion "Why should you need to do this?" >}}

Lorem ipsum dolor sit amet consectetur adipisicing elit.
Lorem ipsum dolor sit amet consectetur adipisicing elit.
Lorem ipsum dolor sit amet consectetur
{{< /accordion >}}

{{< accordion "How can I adjust Horizontal centering" >}}

Lorem ipsum dolor sit amet consectetur adipisicing elit.
Lorem ipsum dolor sit amet consectetur adipisicing elit.
Lorem ipsum dolor sit amet consectetur
{{< /accordion >}}

{{< accordion "Should you use Negative margin?" >}}

Lorem ipsum dolor sit amet consectetur adipisicing elit.
Lorem ipsum dolor sit amet consectetur adipisicing elit.
Lorem ipsum dolor sit amet consectetur
{{< /accordion >}}

Code and Syntax Highlighting
This is an Inline code sample.

var s = "JavaScript syntax highlighting";
alert(s);
s = "Python syntax highlighting"
print s

Blockquote
Did you come here for something in particular or just general Riker-bashing? And blowing into maximum warp speed, you appeared for an instant to be in two places at once.

Tables
Tables	Are	Cool
col 3 is	right-aligned	$1600
col 2 is	centered	$12
zebra stripes	are neat	$1
Image
{{< image src="images/image-placeholder.png" caption="" alt="alter-text" height="" width="" position="center" command="fill" option="q100" class="img-fluid" title="image title" webp="false" >}}

Gallery
{{< gallery dir="images/gallery" class="" height="400" width="400" webp="true" command="Fit" option="" zoomable="true" >}}

Slider
{{< slider dir="images/gallery" class="max-w-[600px] ml-0" height="400" width="400" webp="true" command="Fit" option="" zoomable="true" >}}

Youtube video
{{< youtube ResipmZmpDU >}}

Custom video
{{< video src="https://www.w3schools.com/html/mov_bbb.mp4" width="100%" height="auto" autoplay="false" loop="false" muted="false" controls="true" class="rounded-lg" >}}
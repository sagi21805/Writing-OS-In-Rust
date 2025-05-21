---
icon: file-binary
cover: https://gitbookio.github.io/onboarding-template-images/header.png
coverY: 0
layout:
  cover:
    visible: true
    size: full
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Writing Operating System In Rust!

[Hello there](#user-content-fn-1)[^1],&#x20;

This is a guide on how to write an operating system in rust, from scratch.&#x20;

And I really mean _from scratch_ I will not use ANY external libraries (just the core library of rust), and all of the thought process and code will be documented in this blog as well as in this [repo](https://github.com/sagi21805/RustOS)

## Base Knowledge

This blog will be technical, and will require some background knowledge, but fortunately not a lot!

If you are not coming from a low level programming knowledge that fine!

just make sure you know this stuff, and probably similar stuff that I am forgetting. If in any place on this blog I take some things for granted, please, let me know.

The base things that I expect you to know are:

1. Some assembly knowledge (just understand simple movs, and arithmetic operations, very basic level)
2. Some knowledge on memory,  (what's a pointer, what is an address)
3. A lot of motivation to learn, and understand. Although this is a complex subject, in this blog I break it down into simple stuff that is logical and easier to understand (hopefully I write easy to read and well documented code)
4. A knowledge in rust is not _that_ important and I myself have some more learning to do on it, and if you come from some other language, especially a low level one, it would be easier for you to understand

## Chapters Of This Book

1. Compiling to stand alone binary
2. Boot loading, stages and some legacy stuff
3. Protected Mode and some important CPU structures
4. Long Mode and some important CPU structures
5. Paging, writing out own _malloc_
6. Utilizing the Interrupt Descriptor Table
7. File systems and Disk Drivers
8. Thinking in terms of processes
9. Writing a shell (Think of a better name)
10. Running our first program!
11. To be continued (Hopefully virtualization section and loading a vm of other OS)



<table data-view="cards"><thead><tr><th></th><th></th><th data-hidden data-card-cover data-type="files"></th><th data-hidden></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td><strong>Getting Started</strong></td><td>Create your first site</td><td></td><td></td><td><a href="broken-reference">Broken link</a></td></tr><tr><td><strong>Basics</strong></td><td>Learn the basics of GitBook</td><td></td><td></td><td><a href="broken-reference">Broken link</a></td></tr><tr><td><strong>Publish your docs</strong></td><td>Share your docs online</td><td></td><td></td><td><a href="broken-reference">Broken link</a></td></tr><tr><td></td><td></td><td></td><td></td><td></td></tr></tbody></table>

[^1]: Defiantly not a star wars reference

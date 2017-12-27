# Transitioning from Ruby to HTML

## Introduction

In this course, we will take a short break from Ruby and will focus on HTML.
You might wonder why we're changing from programming in Ruby, which feels like
"doing programming," to focusing on HTML which feels like "writing words." Let's
address that concern.

## The Web Platform

At some point, we will want to allow others to use our applications. Employers,
technologists, and customers will assume Web integration as a standard "first
option" for delivery. Technologists like the word "platform" to mean "a
collection of technologies and practices." The reason the Web _platform_ makes
a good "first option" is because of these qualities like these:

* The Web is **not bound** to a specific operating system (Windows 10, Mac, or
  Linux, an internet kiosk on the corner). Its publication standards are
  [open][]\: they are not the intellectual property of any business and are
  free for anyone to learn
* Web content can be enjoyed on a **variety** of browsers (Google Chrome, Microsoft
  Edge, Firefox, or even text-only browsers link [`links`][links])
* Publication to the Web requires **no app store approval**: no gatekeepers, no
  censors!
* Browsers automatically **integrate with accessibility features** in the operating
  system so that those with visual impairment can use your site
* There is **no publishing cost** for the Web
* Web publishing software ("web server") code has been **optimized** for decades
  and is **freely available** and easy to debug
* While the rise of the iPhone and other smart devices has seen small "apps,"
  grow in popularity, they are usually little more than thin wrappers around
  the venerable "browser talks to web server" architecture typical of the Web.

Thus for your application to gain the boost made available by "standing" on the
**most powerful publication medium ever realized during human civilization**,
it only has to honor **one** rule: **all screens it provides must be described
in HTML**.  Regardless the programming language used (Ruby, Python, the NodeJS
JavaScript environment), if the application presents screens, or "interfaces"
in HTML, it's ready to share its capabilities with _billions of people on the
Web_ from its very first moment "out there!"

## Creating Web Applications Is the Art of Generating HTML "Interfaces"

Given that the Web will be our publication mechanism for our "interfaces," our
code will need to generate the "right" HTML. Therefore, you will need to be
able to "write" the desired HTML and then work backwards to "teach" your
application (something in a programming language like Ruby, Python, or Java) to
generate that same content.

If you're not confident both with reading and writing HTML, **you won't be able
to debug your application**. JavaScript rests upon the HTML structure of a
page.  If you're unable to write or reason about that structure, you will
encounter great frustration with JavaScript. All pathways to web programming
success rely on strength in HTML. It merits repeating:

<blockquote>
All pathways to web programming success rely on strength in HTML.
</blockquote>

Let's get started!

[open]: https://www.w3.org/standards/
[links]: http://links.twibright.com/features.php

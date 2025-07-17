---
layout: post
title: What is system programming really
categories: test
---

# Whats system programming
link:https://read.readwise.io/filter/category%3Aarticle/split/triage_status/new/read/01jwkbabax0g8stb6k85s7e208


- forward
<pre>
    system programming
    two ideas :
        a low level programming
        b systems design

    what does the idea systems mean ?
</pre>

- 1970s: Improving on assembly
<pre>
    ' computer systems ' came from ' Systems Programming Languages ' Book
        1 problem to be solved is broad, with lots of sub-problems
        2 system program -> supports other software and apps
        3 designed for continued production and not a one shot solution
        4 likely to continually evolve
        5 requires certain discipline and maintained by more than one person

    goal of system programming
        provide language that doesnt need " bit twiddling "
        and still generate code that is not worse
</pre>

- cmu published BLISS: A Language for Systems Programming
<pre>
    implementation language higher level than assembly
    but low-level than " design language "

    ie implementation and design language should be seperate
</pre>

- Systems Programming ( Donovan 1972 )
<pre>
    Q what is a systems programming ?
        compilers, loaders, macro processors, operating systems
</pre>

- 1990's: The rise of scripting
<pre>
    shell scripting : bash,  perl, tcl, python, ruby, php and js
    ' Scripting : Higher Level Programming for the 21st Century '

    systems programming:
        designed for building from scratch, manipulating datas directly
        strongly typed to help with complexity

    scripting language:
        designed for gluing, assuming the existance of pre-built
        typeless to simplify connection between components
        provide rapid development
</pre>

- 2010: Boudaries Blur
<pre>
    Scripting trying to be like Systems programming
    Dropbox ( Python ) building large and scalable systems
    Js rendering real-time ui in web pages

    static typing in js and python

    prototype -> production

    JIT for scripting languages
    making them competitive for systems programming languages ( c, c++ )
    julia, swift, go ...
</pre>

- Panel: Systems Programming in 2014 and Beyond
<pre>
    Bjorn Souroup, Rob Pike, Andrei, Niko
    " What is systems programming language in 2014"

    1 Niko Matsakis:
        writing client-side apps ( oppst of Go )
        high latency needs, high security needs, and lots of req
        unlike the server side

    2 Bjarne Stroustrup:
        resource constraints = system programming
        finer control = systems programming

    3 Rob Pike:
        go -> systems programming ( regret )
        go renamed > server writing language
        system def : stuff that runs in the cloud

    4 Andrei:
        allows you write your own memory allocators
        and pointers

    Q Is systems programming about high performance then ?
    Resource Constraints ? Hardware Control ? Cloud Infrastructure ?
        me : c, c++, rust, zig, d
</pre>

- Today: So what is systems programming really ?
<pre>
    1 solving broad problems with many sub problems
    2 for supporting other softwares
    3 for continued production
    4 evolving
    5 more than one person

    Hot take:
        functional languages like OCaml, Haskell are far more systems
        than low level c, c++
</pre>










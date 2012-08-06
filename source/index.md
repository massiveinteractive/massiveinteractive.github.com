---
layout: page
title: "Welcome"
comments: true
sharing: true
footer: true
---

> This site provides an overview of the open source projects released and contributed to by Massive Interactive.

Massive provide a number of open source libraries and tools that are intended to increase the quality, efficiency and consistency of **cross-platform** development with **Haxe**.

* **munit** - unit testing framework and CLI
* **mcover** - code coverage framework
* **mconsole** - console and logging API for Haxe
* **mpartial** - umacro library for implementing platform specific functionality as partial-classes in Haxe
* **msignal** - type safe port of Robert Penner’s AS3 Signals leveraging Haxe generics
* **minject** - macro enhanced Haxe port of Till Schneidereit's AS3 Swift Suspenders
* **mmvc** - Haxe port of RobotLegs minus events plus signals


See <https://github.com/massiveinteractive> for more information.



## About Massive

**Massive Interactive is a specialist provider of software and technology/design services and in the area of IP video.**

<http://massiveinteractive.com/>


Our technology focus is on enabling our clients to efficiently distribute and sell video content across a broad spectrum of consumer devices such as PCs, set-top-boxes, connected TVs, game consoles, tablets, smart phones and in-flight entertainment systems. On the design front, our UX&amp;D leaders believe that good user interfaces - which are best arrived at through rigorous discovery processes and analysis - sell more content. Bad or average ones sell less. If you’re in the business of commercialising video content, it pays to get it right.

For more 15 years we have worked closely with television networks and channels, cable TV operators, online video operators, film distributors, telcos and airlines – learning about their businesses and collaborating with them to create innovative new entertainment services for their customers.

## What is Haxe?

Haxe is an multi-platform open source programming language <http://www.haxe.org>.

* Designed for platform agnostic and cross platform development
* Compiles to JavaScript, Flash, C++, Java, C# and more
* Open source
* Strictly typed
* Syntax similar to JavaScript/ActionScript/Java
* Expressive modern language

.

{% codeblock Example %}
class HelloWorld
{
    static function main()
    {
        return new HelloWorld();
    }
    public function new()
    {
        trace("Hello World !");
    }
}
{% endcodeblock %}

---
title: Misconceptions about Java
last_modified_at: 2020-02-10T10:48:00+00:00
categories:
  - Blog
tags:
  - Post Formats
  - readability
  - standard
---
This blog post closes with a commented list of some common misconceptions about Java. 

##### _**Java is an extension of HTML.**_  
(This is NOT true !) {.has-text-align-center}

Java is a programming language. HTML is a way to describe the structure of a web page. They have nothing in common except that there are HTML extensions for placing Java applets on a web page. 

##### **_I use XML, so I don’t need Java._**  
(This is NOT true !)  {.has-text-align-center}

Java is a programming language. XML is a way to describe data. You can process XML data with any programming language, but the Java API contains process XML data with any programming language, but the Java API contains excellent support for XML processing. In addition, many important XML tools are implemented in Java. 

##### **_Java is an easy programming language to learn._**  
(This is NOT true !)  {.has-text-align-center}

No programming language as powerful as Java is easy. You always have to distinguish between how easy it is to write toy programs and how hard it is to do serious work. The Java libraries contain thousands of classes and interfaces and tens of thousands of functions. Luckily, you do not need to know every one of them, but you do need to know surprisingly many to use Java for anything realistic. 

##### _**Java will become a universal programming language for all platforms.**_  
(This is NOT true !)  {.has-text-align-center}

This is possible in theory. But in practice, there are domains where other languages are entrenched. Objective C and its successor, Swift, are not going to be replaced on iOS devices. Anything that happens in a browser is controlled by JavaScript. Windows programs are written in C++ or C#. Java has the edge in server-side programming and in cross-platform client applications. 

##### **_Java is just another programming language._**  
(This is NOT true !)  {.has-text-align-center}

Java is a nice programming language. Most programmers prefer it to C, C++, or C#. But there have been hundreds of nice programming languages that never gained widespread popularity, whereas languages with obvious flaws, such as C++ and Visual Basic, have been wildly successful. 

Why? The success of a programming language is determined far more by the utility of the support system surrounding it than by the elegance of its syntax. Are there useful, convenient, and standard libraries for the features that you need to implement? Are there tool vendors that build great programming and debugging environments? Do the language and the toolset integrate with the rest of the computing infrastructure? Java is successful because its libraries let you easily do things such as networking, web applications, and concurrency. The fact that Java reduces pointer errors is a bonus, so programmers seem to be more productive with Java—but these factors are not the source of its success. 

##### **_Java is proprietary, and should therefore be avoided._**  
(This is NOT true !)  {.has-text-align-center}

When Java was first created, Sun gave free licenses to distributors and end users. Although Sun had ultimate control over Java, they involved many other companies in the development of language revisions and the design of new libraries. Source code for the virtual machine and the libraries has always been freely available, but only for inspection, not for modification and redistribution. Java was “closed source, but playing nice.” 

This situation changed dramatically in 2007, when Sun announced that future versions of Java would be available under the General Public License (GPL), the same open source license that is used by Linux. Oracle has committed to keeping Java open source. There is only one fly in the ointment—patents. Everyone is given a patent grant to use and modify Java, subject to the GPL, but only on desktop and server platforms. If you want to use Java in embedded systems, you need a different license and will likely need to pay royalties. However, these patents will expire within the next decade, and at that point Java will be entirely free. 

##### **_Java is interpreted, so it is too slow for serious applications._**  
(This is NOT true !)  {.has-text-align-center}

In the early days of Java, the language was interpreted. Nowadays, the Java virtual machine uses a just-in-time compiler. The “hot spots” of your code will run just as fast in Java as they would in C++, and in some cases even faster.

##### **_All Java programs run inside a web page._**  
(This is NOT true !)  {.has-text-align-center}

All Java applets run inside a web browser. That is the definition of an applet—a Java program running inside a browser. But most Java programs are stand-alone applications that run outside of a web browser. In fact, many Java programs run on web servers and produce the code for web pages. 

##### **_Java programs are a major security risk._**  
(This is NOT true !)  {.has-text-align-center}

In the early days of Java, there were some well-publicized reports of failures in the Java security system. Researchers viewed it as a challenge to find chinks in the Java armor and to defy the strength and sophistication of the applet security model. The technical failures that they found have all been quickly corrected. Later, there were more serious exploits, to which Sun, and later Oracle, responded too slowly. Browser manufacturers reacted, and perhaps overreacted, by deactivating Java by default. To keep this in perspective, consider the far greater number of virus attacks in Windows executable files that cause real grief but surprisingly little criticism of the weaknesses of the attacked platform. Even 20 years after its creation, Java is far safer than any other commonly available execution platform. 

##### **_JavaScript is a simpler version of Java._**  
(This is NOT true !)  {.has-text-align-center}

JavaScript, a scripting language that can be used inside web pages, was invented by Netscape and originally called LiveScript. JavaScript has a syntax that is reminiscent of Java, and the languages’ names sound similar, but otherwise they are unrelated. In particularly, Java is strongly typed—the compiler catches many errors that arise from type misuse. In JavaScript, such errors are only found when the program runs, which makes their elimination far more laborious. 

##### **_With Java, I can replace my desktop computer with a cheap “Internet appliance.”_**  
(This is NOT true !)  {.has-text-align-center}

When Java was first released, some people bet big that this was going to happen. Companies produced prototypes of Java-powered network computers, but users were not ready to give up a powerful and convenient desktop for a limited machine with no local storage. Nowadays, of course, the world has changed, and for a large majority of end users, the platform that matters is a mobile phone or tablet. The majority of these devices are controlled by the Android platform, which is a derivative of Java. Learning Java programming will help you with Android programming as well.

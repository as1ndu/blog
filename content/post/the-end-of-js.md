---
title : "Finally, the end of JavaScript?"
description : "JavaScript at the time of this writting is definately the higest programming langauage in demand. 
               I however think, its mnopolistic reign of being the goto stack for programming user interfaces is about to come to an end. Heres why."
slug : "building-with-flutter"
draft : "true"
tags : ["code"]
date : "2019-02-17"
---

## Why JS is successful

At about early 2010, a computer scientist forked Googles V8 js engine and made it run on the back end/server side and not the front end.

This could mean that, my barley accumlated skills of writting browser based programs could make me  instantly capable of
building applications that execute on the server. Hence I hopped the wagon.

JS then became very complicated very quickly. It started with package manager Bower it was from fat & i liked work from his collaoration with 
mdo on Twitter Bootstrap & Medium. So I learned Bower (did I? I have never used it).

Anyway during the Bower reign, npm was quickly picking up & finally took over so & became the default package manager, I had to figure out npm.
After that came a tidal wave of frameworks, Angular, Vue and more recently React.

Facebook released React Native that allowed developers to compile apps down to native iOS & Android applications, 
while they where at it GitHub forked Components of Google's Chrome  create  Electron, a program that would allow js based UI's to run on a desktop as single programes independent of the browser)

Now anyone that has only browser programming skills is instantly capable of releasing apps on iOS, Android, Server & Desktop.

People (future programmers) then flocked in.

This is how JS became king, not beacuse its a language with great features or its well designed but beacuse, people(including myself) enjoy taking the path of least action.

## How JS should have evolved or Why I dislike JS

I dislike JS for two reasons

`1.` The lack of respect for standards in the community.

One example is when I look at an html file & its filled exclusively with `<div>` tags. 
My first thought is, "What is wrong with the author? Does this guy think everyone at the W3C is wasting time?"

`2.` JS stake holders failing to add new features in the language tht seemed necessary as the modern web begun to pick up.

Why do I still need to install a depenency so I can effectively do data binding & routing? 
Patterns such as these are so requently used that they sould have been simpifiled the added to the core of the JS syntax.

But now we are helplessly in need of frameworks to simplify these tasks to the level we fell com fortable.
Imagine Mithrill's API being a valid vanilla JS.

What philosophy does JS subscribe to? What niche problems does it solve? Is it now a sysntems programming language?

These questions cannot be answered because the original purpose of JS, adding logic for browser based applications, was given a back seat by its custodiand in an effott (unsuccessful) make it a systems programming language.

## How JS becomes legacy.

Some of you think  JS will still be on the the top programming languages of choice beacuse the languge is the only one that is widely available in browsers.

People defiently spenad significant amount in browsers running JS code in them. 

I never said JS will vanished in to a pile of "no-longer existant tech". 
_I believe JS will eveolve in to more of a runtime & less of a programming language_

I think peope in need of highperfomace code like game engines will turn to C, Rust, Nim and compile code to run in the browser via JS as a target via WASM.

Dart actually handles both the need for modern developers have for cross platform hugly  &  custom UIs

---
title: "What the Condition ? An Intro To Condition Variables"
date: 2024-07-03T17:03:06+09:00
draft: false
---

### Introduction
Are you hearing this term for the first time ? 
Or maybe you've heard it before but never really understood it ? Or maybe you've
banged your head against the wall trying to understand it numerous times ? 

Well, you're in luck. This post is for you.

Condition variables are a synchronization primitive in POSIX (Portable Operating
System Interface) systems that allow threads to wait for certain conditions to
become true. Unlike mutexes, which are used for mutual exclusion, condition
variables allow threads to pause execution and wait, without consuming CPU
resources, until a specific condition changes state. This mechanism is
particularly useful in scenarios where a thread needs to wait for some condition
to be met by another thread before proceeding.

Raise Your Hand if you didn't understand that. (I'm Just Kidding. (or am I ?))

Don't worry, let's start with an example.
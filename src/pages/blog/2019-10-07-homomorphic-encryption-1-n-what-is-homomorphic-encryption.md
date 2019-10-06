---
templateKey: blog-post
title: 'Homomorphic Encryption (1/n): What is Homomorphic Encryption?'
date: 2018-09-06T16:00:00.000Z
description: Introduction to homomorphic encryption
featuredpost: true
featuredimage: /img/1-il2yxvaouhnishvn-0i3rg.png
tags:
  - cryptography
  - computer science
---
In this set of blog posts about homomorphic encryption I intend to provide an intuitive picture of what is going on. I will probably touch on some math, but I will try to make it easy to understand. Later on, I will attempt to cover essentials of quantum information to provide a basis to understand quantum homomorphic encryption as well as blind quantum computation. Stay tuned!

There has been recent interest in homomorphic encryption largely sparked from the need for privacy on blockchains. Beyond the hype, homomorphic encryption is a very interesting mathematical technique. I’m scared of big words, so I will refer to homomorphic encryption as (HE). Got it?

**Let’s try to understand HE with a story…**

It was a bright and beautiful morning. Alice was strolling through her garden. To her great fortune, she found a rare crystal ore. She was stunned!

![Alice was stunned by the rare crystal ore.](/img/1-il2yxvaouhnishvn-0i3rg.png "Alice was stunned by the rare crystal ore.")

Alice was mesmerized by the sparkling awesomeness of the crystal ore, and she wanted to make some cool jewelry out of the crystal ore. However, there’s a catch. The only person who can make jewelry in her small town is a jerk named Jerk. Jerk is the only one in the small town with hands which allows him to flip people off and craft things. Jerk is not 100% trustworthy and may steal stuff from people.

![Jerk is an absolute jerk.](/img/1-rrhrx5hj1vjzfwnj0kbnyw.png "Jerk is an absolute jerk.")

Using a large sum of money, Alice had managed to convince Jerk to help her craft her jewelry. However, Alice now faces a problem. Jerk may steal her ore. She needs to find a way to let Jerk somehow touch and craft her jewelry without letting Jerk steal the ore. Moreover, Jerk should not be able to fully know the value of the ore.



Alice being the resourceful person she is, developed a cool contraption. It was an opaque, impenetrable box with gloves.



![Blueprints for the device](/img/3.png "Blueprints for the device")



Alice can now store her ore into this box locking it up afterwards. Jerk, with his skillful arms is able to feel and craft the jewelry. As the ore is locked up, Jerk cannot steal the ore or be entirely sure of the contents. As an extra precaution, the box was bolted to the ground such that Jerk cannot easily steal the box either. After, Jerk is done with crafting the ore, Alice can open the box with her key and retrieve her jewelry.



This box is essentially what HE is all about. It allows untrustworthy workers to operate on crucial data without having access or having the ability to understand the data. Such a technique will be handy when you want to perform some operation on sensitive data (eg. medical records, your nudes, etc.) on cloud servers or on other people’s computers without those computers being able to understand what data they are manipulating. Doing so provides us with a layer of privacy but ensures that we are still able to distill useful information.



This concludes my very first article on medium. The next part will look at the mathematical machinery that allows for this to happen (we’ll be focusing on classical computers/normal computers first). Should there be any suggestions or errors feel free to dm me on Twitter at @PositivityNoH8.

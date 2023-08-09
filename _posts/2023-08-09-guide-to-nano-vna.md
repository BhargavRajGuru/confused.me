---
layout: post
title: Guide to nano VNA
subtitle: There's lots to learn!
gh-repo: BhargavRajGuru/confused.me
gh-badge: [star, fork, follow]
tags: [vna]
comments: true
---

This repository aims to give the reader a brief introduction to vector network analyzers, for someone who has never come across one before, or someone who is tasked with using a vector network analyzer, but knows nothing about them.

### What is VNA?

A vector network analyzer, often known by the acronym VNA is an essential piece of test equipment that no RF engineer should be without.

If you have previously worked with Electronics at low frequencies, you may consider a good DMM or oscilloscope your best friend. RF engineers would gladly trade both for a good VNA!

A good VNA is an expensive bit of kit. Many years ago, a good one would probably cost you as much as a fairly nice house. Nowadays, you can pickup something really good for the price of a nice car.

{: .box-note}
**Note:** High-end VNAs can still sell for between $100k and $1M, for that I will use term 'professional VNA'.

Luckily, there are cheap alternatives now, such as the NanoVNA. It doesn't hold a candle to the performance of a professional piece of kit, but for the price, and used with care, it's not too bad.

VNA is a piece of electronic test equipment, usually used for characterising radio frequency (RF) and microwave networks. 

The leading manufacturers of VNAs are Keysight, Rohde & Schwarz and Anritsu.

### Form factors of vector network analyzers

Typically the lowest frequency of instruments is a few hundred kHz, and the upper-frequency many GHz, although instruments are available which work down to a few Hz, as well as up to more than 1 THz. Usually instrument designed for very high frequencies do not work to very low frequencies, and instruments designed to work for very low frequencies do not work at very high frequencies. We are unaware of any instrument that covers from 5 Hz to 1 THz.

Historically VNAs were large instruments with a display, some controls on the front panel, and were powered by mains electricity. All internal calculations were performed with one or more CPUs. A particularly popular series of instruments was the HP/Agilent 8753 series. There were probably more 8753s made than any other series of VNAs.

The 8753s are obsolete, but still regularly used in a lot of companies.

More recently many VNAs have become available that have no display at all but are designed to be connected to a Windows computer, with the processing and display performed by the computer. This results in lower cost. Copper Mountain is one of the best-known manufacturers of such instruments.

There is also a range of fully self contained portable VNAs. The Keysight FieldFox range is the most comprehensive of this type.

### What does it do?

A VNA is designed to inject a source signal of known frequency and amplitude into an RF port and measure the relative amplitude and phase of this signal when received at a number at one, or more of it’s ports.

That sounds pretty complex, but it's really not. An analogy may help.

### A lightwave analogy of a device that would be measrued with a VNA

![lightwave-analogy-of-VNA]({{ 'assets/img/lightwave-analogy-of-VNA.png' | relative_url }})

![Crepe](/confused.me/assets/img/crepe.jpg)
---
title: "Introduction"
excerpt: "What is this?"
tags:
  - introduction
  - digitalphase
  - daniel
  - bernardo
comments: true
share: true
---

Hi, we're Bernardo and Daniel.
This is **DigitalPhase**, our blog about audio equipment.
Bernardo is an audiophile, CS student.
Daniel is an experimental physicist who's handy with an oscilloscope and knows something about signal processing.
One day, Daniel and Bernardo were chatting online and Bernardo was ranting about how the disconnect between the audiophile community and real understanding of signal processing makes it so hard to evaluate claims made in commercial marketing (lightly edited for clarity):

-----------------------

**(B)ernardo:** When Schiit starts blabbering about their filter I have absolutely no fucking clue what they are trying to say.

**(D)aniel:** Neither do I.  
Those rants smell like bs to me.

**B:** http://schiit.com/products/yggdrasil

**D:** Like I said, I do not care whether your damned filter coefficients are analytically computed or numerically approximated.  
Right, *"see 1917 papers"*. I do not care how old the papers were that you read.  
*"...the phase info in the original samples..."*  
There is no phase information in digital samples.

**B:** There isn't?

**D:** no  
Time domain samples mean the level of the sound pressure at that time.  
It's a scalar.  
One number.  

**B:** Write him an email.  
Call him out on it.  
Please.  
Then if they have no good answer, post it on Head-Fi and make the whole community a favour.  
Like, everyone will thank you so much if you debunk something like this.  
We should start a blog dedicated JUST to calling people out on this crap.

**D:** Ho boy.  
I would be 100% on board to be the "technical advice" on that blog.  
You're the audiophile, I'm the math/engineer.  
I love this idea already.  

Make git repo.

-----------------------

Thus was **DigitalPhase** born.

It's possible that the quoted discussion reveals a great misunderstanding on our part and to be honest, I can imagine what Schiit has in mind when they say "phase of digital samples".
That would be fine wth both of us; the point of **DigitalPhase** is to educate us all so that we can have informed, quantitative discussions about audio hardware.
We know going in that we are in need of this education as much as any prospective readers.
What we bring to the table is expert technical knowledge and dedication to constructing our posts around *data* measured with an oscilloscope and spectrum analyzer.

## Abstract

As one invests more and more deeply into audio equipment (both mentally and financially) one becomes more interested in what figures of merit lead to a better listening experience.
For example, how do signal to noise ratio, number of DAC bits, DAC architecture, digital filter design, speaker hardware, etc.
affect the final sound? These questions enjoy much coverage in audiophile outlets, but we feel that more quantitative discussion would be helpful.
For example, a discussion comparing two DACs would benefit from experimental data showing the analog waveforms produced by those DACs, if for no other reason to determine whether or not they're actually different!

Additionally, we feel that in order to really engage in useful discussion about the pros and cons of various audio hardware, one needs a solid understanding of the concepts behind the figures of merit.
For example, a discussion about DACs becomes much more useful and informative if the participants have a detailed quantitative understanding of how DACs work. The same can be said for other conceptual topics such as signal to noise ratio, digital filters, and speaker linear response functions.

## Mission

In light of the above discussion, the goal of this site is to bring experimental data and mathematical analysis to bear on the comparison and understanding of audio hardware.
We aim to be, above all else, educational.
That is, we wish to help readers come to a solid understanding of conceptual issues involved in audio equipment so that they can make informed decisions on their own, with minimal need to trust the words of other authoritative figures or sources.

## The Authors

### Bernardo Meurer

I'm a computer science undergrad with an interest in low level systems, and high performance code. I mostly focus on kernels, although recently I've grown interested in compilers and parsers, and I like to do hobby projects using GMP and other arbitrary precision libraries.

My passion for audio started when in 2015, while on a trip to Germany, I purchased a Sennheiser HD650 and a Fiio X3II. For someone who up until then had only listened to Apple earbuds on an iPod shuffle, it was an eye-opening experience, and I've been fascinated by audio equipment ever since. I'm in this project with the intention to measure and quantify equipment so that buyers like me can make informed decisions and (just maybe) opt out of the "8 DACs per channel pure golden octuple braided wiring blessed by Elves" option of equipment, knowing they are not really missing out on much.

### Daniel Sank

My first big project in grad school involved measuring the 1/f magnetic noise in superconducting wire loops.
At the time, I knew very little about noise, signal processing, statistics, or any of the stuff you need to move fluently through a noise measurement project.
This really held me back, but I retaliated by teaching myself what I needed to know.
This planted a strong interest not only in signal processing, but in improving the written pedagogical resources that one needs to learn signal processing.

Since then, I've steadily improved my noise-theory-fu to the point that I can pretend to be qualified to act as this site's resident theorist.
Also, after ten years of experimental physics, I hope to be able to support this site's data-driven philosophy with meaningful measurements on DACs and other audio hardware.
In other words, I know how to use an oscilloscope, spectrum analyzer, and other equipment that will help us make useful quantitative comparisons between different pieces of hardware.

I learned physics at UCSB with [John Martinis](http://web.physics.ucsb.edu/~martinisgroup/) and then went to [Google](https://plus.google.com/+QuantumAILab) to continue working on quantum computing with superconducting qubits.

---
title: Year 9 Coding- The first four weeks
layout: post
author: william.howells
permalink: /year-9-coding--./
source-id: 1rdaMMcQ7RM6-oO2M2RnQmRFRwvKKL-Dt4yalZLdQZpo
published: true
---
**Coding in Google Sheets**

[https://docs.google.com/spreadsheets/d/1gT3KfA37sTA1mPSLG24jxZ37_cV6T-lmEf6nSDGrrsM/edit#gid=0](https://docs.google.com/spreadsheets/d/1gT3KfA37sTA1mPSLG24jxZ37_cV6T-lmEf6nSDGrrsM/edit#gid=0)

We began our coding with the simple stuff - the Caesar Cipher, one of the earliest known and simplest of ciphers.  You simply move each letter however many spaces backwards or forwards along the line, e.g.

ABCDEFGHIJKLMNOPQRSTUVWXYZ

BCDEFGHIJKLMNOPQRSTUVWXYZA

We did exactly this, and then used it to encrypt a message(lesson one).  I decided to make everything much harder by putting in punctuation.  I put in 

HI! I AM BARRY SCOTT!

SR_1R1ZN1YZIIB1HXLGG_

This was done using the function ' =hlookup(D9, A1:Z2, 2) ‘, the letters in brackets changing depending on where I typed everything.  By copying the first line (ABCDEFGHIJKLMNOPQRSTUVWXYZ) into the third line, and the same for the punctuation (fourth line(123456789- ) into the sixth line of the google sheet), I was able to make decryption (lesson two) possible.  Using ‘ =hlookup(D10, A2:Z3, 2) ‘, I could get the encrypted code decrypted, making the message ‘HI I AM BARRY SCOTT!' readable.  

Lesson Three

In Lesson three we began on concatenating (See lines 18-22).  You begin by typing in first one letter, then two in the next square, then three in the next, etc, etc, etc.  Eventually you will reach the end of your message, so will continue typing in the exact same message.  On the line below you type in the number 1, then 2, then 3 etc.  The numbers continue to rise, even when you are out of letters.

In Lesson Four we finished concatenation.


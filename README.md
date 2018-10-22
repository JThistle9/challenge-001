---
title: Word Counting Redux
date: 2018-10-22
---

Our [very first practice problem][1] was a straight forward word counting problem. Today, we're introducing our very first take home challenge and with it, a new take on word counting. We envision take home challenges as an opportunity to practice programming "in the weeds," going beyond the algorithms and getting our hands dirty.

[1]: https://csip-uga.github.io/problems/2018-10-01/README

For this challenge, we'll stick to the problem of word counting, but this time we'll be counting the words in Virgil's *Aeneid*, as translated by John Dryden. Working on a real book gives us the opportunity to practice file I/O, and challenges us with a wider range of edge cases. Namely, how should we deal with punctuation and letter case?

We can take our text processing one step forward and implement *stop word filtering*. From the nature of the English language, we already know certain words will top our counts, for example articles and pronouns. However, counting these words isn't particularly useful, so we've defined a set of so-called "stop words" which should be ignored.


# The Challenge

Formally, the challenge is to count the words in `aeneid.txt`, ignoring the words listed in `stopwords.txt` and to present the results in a human readable way.

The Aeneid is divided between twelve books. For an extra challenge, try breaking your analysis down by book.

The files for this challenge are hosted [on GitHub][2]. Go ahead and fork this repo and start hacking!

[2]: https://github.com/csip-uga/challenge-001

---
layout: post
title:  "wtf is encryption?"
description: URYYB JBEYQ.
tags: Encryption-101
---

# **Encryption**

Encryption is as old as secrets. Stated simply - to encrypt something means to hide or obscure it using a secret method.

## **Word Salad**

Let’s look at an example using a type of encryption called a "_Shift Value_". A shift value substitutes a letter's numeric position in the alphabet for another's. If `A=1, B=2, C=3...` and our `shift value = 2` then `A` would *shift* to the `3rd` position of our new *super secret friend alphabet.* `A=3, B=4, C=5`. Now instead of writing the word `HELLO` we write `JGNNQ` since each letter has been shifted by `2`.

```
H E L L O

⇅ ⇅ ⇅ ⇅ ⇅

J G N N Q
```

We can then use the newly formed alphabet to send messages that make little sense to someone not in our secret friendship club. (Won't they feel foolish!)

If we were to shift by a greater value like `13` our "_code_" ("_encryption_") becomes more secure. `A=14, B=15, C=16` would yield text that looks like the following:

```
H E L L O W O R L D

⇅ ⇅ ⇅ ⇅ ⇅ ⇅ ⇅ ⇅ ⇅ ⇅

U R Y Y B J B E Y Q
```

## When in Rome

Our example above is actually called a "Caesar Cipher" as it was often used by Julius Caesar in his military correspondence. (Doesn't _that_ inspire confidence!)

While it's primitive by today's standards, this encryption was sufficient for the time. The literacy rate of an Ancient Roman General doesn't really compare to a person in the modern age.

Eagle eyed readers will have already found an underlying flaw in our chosen mechanism: repetition. From the pattern `JGNNQ` we know our word:

* Contains only `5` letters.
* Letters `3` and `4` repeat.

This observation greatly reduces the possible outcomes our word can be deciphered as. If `HELLO` is used to open a correspondence, this will make it *even easier* for outsiders to derive the pattern used to encrypt our message.

Weak encryption has left our friendship is in _ruins_.

## Be sure to drink your Ovaltine

This type of Statistical Pattern Analysis was a major factor in Alan Turing's success breaking the codes of Nazi Germany's `Enigma Machine`. Not only did this help turn the tide of the war, it's considered the dawn of Computer Science in the modern age. Turing's research was so vital to continued post-war intelligence, it wasn't declassified until 2012, a full century after his birth.

-----

## TL;DR

* It is possible to make strong locks. 
* It is possible to make weak locks.
* It *is not* possible to make locks that open based on morality or good intentions.

 

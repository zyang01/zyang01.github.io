---
title: On Obedience
date: 2024-11-20 07:24:52 +0000
---

Consider the following python program.

```python
def want(x) -> Bool
def notWant(x) -> Bool

obedient = True

for me in [
    false prophet, antichrist, satan,
    messiah, burning in hell for eternity,
    ...
]:
    obedient = obedient and not want(me) and not notWant(me)

print(obedient)
```

I think perfect obedience comes from want() and notWant() both returning False given any input, and the output of the program to be True.

Psalm 23:1–3

The LORD Is My Shepherd

A Psalm of David.

[1] The LORD is my shepherd; I shall not want.

[2] He makes me lie down in green pastures.

He leads me beside still waters.

[3] He restores my soul.

He leads me in paths of righteousness

for his name’s sake. (ESV)

Edit: before the functional programming cult bashes me in the comments. Here is a one liner for the for loop using list comprehensions.

```python
obedient = all([
    not want(me) and not notWant(me)
    for me in [
        false prophet, antichrist,
        satan, messiah, burning in hell for eternity,
        ...
    ]
])
```

![](/a05bfeda0262e062b5d207a821a048be.jpg)
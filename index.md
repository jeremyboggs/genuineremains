---
layout: default
title: Home
---

# Preface

The writing of Characters was a Kind of Wit much in Fashion in the Beginning of
the last Century.  The two principal Authors in this Way were sir Thomas
Overbury, and Dr. John Earle Tutor to Prince Charles in 1643, and after the
Restoration Dean of Westminster, and successively Bishop of Worcester and
salisbury. How agreeable these sorts of Essays were to the public Taste may be
judged from sir Thomas’s little Book having fourteen Editions before 1632, and
the Bishop’s six between 1628 and 1633.  Whether Butler has equalled or
excelled them, and what Place he is to hold in this Class of Writers must be
left to the Decision of the Public, as the Interest and Prejudice of a
Publisher may render me a suspected or an incompetent Judge.  The Reader will
have an Opportunity of determining for himself, as they have all attempted to
draw the same Pictures.  As in such a Variety of Characters there must be some
drawn from Originals in general the same, and only differenced by particular
Circumstances, the same Observations are sometimes repeated.  Whether the
Author in this Case requires any Apology must be left to his Judges the Critics
it is enough for me that I can say I have done him Justice in publishing them.

As most of these Characters are dated when they were composed, I can inform
the curious, that they were chiefly drawn up from 1667 to 1669, at which time,
as has been before observed, Butler resided in Wales under the Protection of
Lord Carbery.

## Characters

{% for character in site.characters %}
- <a href="{{ character.url }}">{{ character.title }}</a>{% endfor %} 

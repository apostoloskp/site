---
layout: single
title: Form validation 
header: no
categories:
  - synthesis
tags:
  - video
  - HCI
---

Το παράδειγμα αυτό βασίζεται σε regular expression για να εντοπίσει σφάλματα στην είσοδου του χρήστη.

<iframe height="265" style="width: 100%;" scrolling="no" title="Form Validation" src="https://codepen.io/mibook/embed/XWdwJxX?height=265&theme-id=light&default-tab=html,result" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/mibook/pen/XWdwJxX'>Form Validation</a> by mibook
  (<a href='https://codepen.io/mibook'>@mibook</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Άσκηση: Προσθέστε έλεγχο για email, credit card, ελληνικό τηλεφωνικό νούμερο. 

<p class="codepen" data-height="265" data-theme-id="light" data-default-tab="html,result" data-user="P2015121" data-slug-hash="QWERLBQ" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="Form Validation">
  <span>See the Pen <a href="https://codepen.io/P2015121/pen/QWERLBQ">
  Form Validation</a> by P2015121 (<a href="https://codepen.io/P2015121">@P2015121</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="//static.codepen.io/assets/embed/ei.js"></script>

Εναλλακτικά https://codepen.io/P2015121/pen/QWERLBQ

Τροποποιήσεις: Προσέθεσα τα παρακάτω lines
 x Validation<
 <label for="x">x (format: xxx-xxx):
 <input id="x" type="x" pattern="x$" required, ανάλογα με τα ζητούμενα της άσκησης, άλλαξα παράγραφο στο button **Submit** και τέλος οργάνωσα σε διάταξη τα ζητούμενα όπως αναφέρονται στην εκφώνηση.

Πηγές: https://www.w3schools.com/tags/att_input_pattern.asp

# Free Software Legal 101

## FSFE Track

Carlo Piana

**Array**
  https://array.eu

Bolzano, 16 November 2019

---
# Why?

---
## No Software Comes Without Licence Tag

You think that because there is no licensing condition attached to the software, there is no restriction? **Think better!**

<ul>
<li class="fragment">Full copyright is by default</li>
<li class="fragment">Seek license</li>
<li class="fragment">Without a licence (or *license*), you are stuck with statutory provisions </li>
</ul>

---
## Inbound vs Outbound Licensing, derivative software

Nobody writes software from scratch!

<ul>
<li class="fragment">You take some code</li>
<li class="fragment">That code has its own conditions</li>
<li class="fragment">Conditions of software you are reusing is called **inbound** </li>
<li class="fragment">Conditions of software you are *distributing* is called **outbound**</li>
<li class="fragment">If software contains substantial fragments of other software, it is a **derivative**.</li>
<li class="fragment">Derivative software needs permission from the original(s)</li>
</ul>
---

## Why is it important to know?

A license can be very simple and just permit whatever to whomever. But with most licenses, **permission** is granted only *provided that* you comply with **conditions**

<ul>
<li class="fragment">**If** condition is complied with, **then** you can {modify, distribute original or modified software}</li>
<li class="fragment"> **If** condition **is not** complied with, **then** you cannot {modify, distribute original or modified software}</li>
</ul>

+++

## Is this "copyleft"?

No, copyleft is a *subclass* of  Free Software conditions.
<ul>
<li class="fragment">Conditions impact on **outbound** software, and outbound license</li>
<li class="fragment">One condition is <strong>"inbound license == outbound license"</strong></li>
<li class="fragment">Depending on the scope of this condition (just the library, the file or the entire derivative), we have **"strong"** or **"weak copyleft"**
</li>
---

## A Clash of Licenses

The more conditions and the stricter, the more likely you have **incompatibilities**: there is no state in which you can comply with both.

---

## Compliance

Means *respect* conditions upon which you receive a Free Software *grant*

---

# How?

---

## Different strategies

<ul>
<li class="fragment">SPDX, Reuse </li>
<li class="fragment">Standards procedures (OpenChain)</li>
<li class="fragment">Scanning</li>
</ul>

+++

## SPDX

Software Package Data Exchange

* An open *standard* to communicate data about components, their licensing conditions and more
* <https://spdx.org/>

+++

## Reuse

* Tools and processes to make sure you offer simple and complete licensing information
* <https://reuse.software/>


+++

## Standards

**OpenChain**, a full legal compliance standard to show you have set up processes, training, documentation, to ensure compliance in your own organization and to demonstrate it.

Find more at <https://www.openchainproject.org/>

+++

## Scanning

<ul>
<li class="fragment">Only for more complex projects, with many packages</li>
<li class="fragment">Two goals:</li>
  <ul class="fragment">
  <li> "find cheaters"</li>
  <li> find accurate licensing information in the text and record them</li>
  </ul>
<li class="fragment">Most popular: **Fossology** (open source project)</li>
<li class="fragment">Needs to be included in CD/CI:</li>
<li class="fragment">CD/CI/<strong class="fragment">CC</strong></li>
<li class="fragment">DepTree</li>
</ul>

---

## Where to find help

<span>FSFE's legal team <https://fsfe.org/activities/ftf/activities.en.html></span>  <!-- .element: class="fragment" data-fragment-index="2" -->

Talk to us <!-- .element class="fragment" -->



---

## Where to find out more (advertisement)

<img class="center-img" src="markdown/assets/book_piana.jpg" />


---

## Thank you!


<div class="bottom">
<p><a rel="license" href="http://creativecommons.org/publicdomain/zero/1.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/p/zero/1.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/publicdomain/zero/1.0/">Creative Commons - zero International License</a>.
</p>

Presentation made using [Reveal.js][81aa3153] and a [Markdown](https://daringfireball.net/projects/markdown/syntax) workflow

</div>

  [81aa3153]: https://revealjs.com/ "Reveal"

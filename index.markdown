---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

![Ocean and concrete](water.jpg?w=1740&h=1158&fit=crop&crop=center&auto=format)

The Curry-Howard correspondence is a duality between logic and the mathematical theory of computation, sometimes referred to by the tagline "**propositions as types, proofs as programs**". More precisely, it is an isomorphism between a logic (intuitionistic sequent calculus) and a programming language (simply-typed lambda calculus). This website will eventually host an online short course in the fundamentals of theoretical computer science, aimed at giving a complete proof of the Curry-Howard correspondence. The aim is to be accessible but still completely rigorous; this course will be a challenge. All lecture notes and videos for the course will be freely available.

We are part of the [School of Mathematics and Statistics](https://ms.unimelb.edu.au/home) at the University of Melbourne.

## Course

The current rough plan for the course is as follows:

* What is computation?
* Introduction to lambda calculus
    * Untyped lambda calculus
    * Simply-typed lambda calculus
    * Programming in lambda calculus
    * Proof of the Church-Rosser theorem
    * Proof of strong normalisation for simply-typed lambda calculus
* Introduction to sequent calculus
    * What is logic?
    * Examples of proofs
    * Proof of cut-elimination for sequent calculus
* Proof of the Curry-Howard isomorphism
* Curry-Howard in the broader context of computer science

## People

* **James Clift**

* **Will Troiani**

* **[Daniel Murfet](http://therisingsea.org/)**: mathematician at the University of Melbourne, with research interests in algebraic geometry, logic, and deep learning.

## Original seminar

In Semester two of 2016 we ran a seminar on the topic of the Curry-Howard correspondence, largely following Sorensen and Urzyczyn's book "Lectures on the Curry-Howard isomorphism", up to the proof of the original Curry-Howard correspondence (between simply-typed lambda calculus and intuitionistic logic) in Chapter 4.

  * 14-7 William Troiani "The Church-Rosser Theorem" ([lecture notes](http://therisingsea.org/notes/talk-will-churchrosser.pdf))
  * 2-8 William Troiani "Introduction to lambda calculus" (Sections 1.1-1.3, [lecture notes](http://therisingsea.org/notes/talk-will-lambda.pdf))
  * 9-8 Samuel Lyons "All partial recursive functions are lambda-definable" (Section 1.7, [lecture notes](http://therisingsea.org/notes/talk-sam-definable.pdf))
  * 16-8 James Clift "Simply-typed lambda calculus and strong normalisation" (Chapter 3, [lecture notes](http://therisingsea.org/notes/talk-james-simplytyped.pdf))
  * 23-8 Shawn Standefer "Introduction to natural deduction" (Chapter 2, [lecture notes](http://therisingsea.org/notes/talk-shawn-introintuit.pdf))
  * 30-8 Daniel Murfet "The category of simply-typed lambda terms" ([lecture notes](http://therisingsea.org/notes/talk-catsimplytyped.pdf))
  * 6-9 Shawn Standefer "Kripke semantics of intuitionistic logic" ([lecture notes](http://therisingsea.org/notes/talk-shawn-kripke.pdf))
  * 13-9 **No talk**, instead we'll watch Wadler's [Propositions as types](https://www.youtube.com/watch?v=IOiZatlZtGU) and discuss
  * 20-9 Daniel Murfet "The category of simply-typed lambda terms II" ([lecture notes](http://therisingsea.org/notes/talk-catsimplytyped2.pdf) and an [appendix](http://therisingsea.org/notes/talk-catsimplytyped2-cuts.pdf))
  * 4-10 Daniel Murfet "The Curry-Howard principle" ([lecture notes](http://therisingsea.org/notes/talk-ch.pdf))
  * 11-10 James Clift "System F: Polymorphic lambda calculus" ([lecture notes](http://therisingsea.org/notes/talk-james-systemF.pdf))
  * 18-10 William Troiani "System F in the real world: Haskell and functional programming" ([lecture notes](http://therisingsea.org/notes/talk-will-haskell.pdf)) (the referenced talk by Rich Hickey is "[Simple made easy](https://www.infoq.com/presentations/Simple-Made-Easy)")
  
Thanks to Camillo Fiorentini for noticing errors in the original notes for the lecture on strong normalisation, and for suggesting the fix (incorporated in the current version).  

References:

  * Sorensen, Urzyczyn "[Lectures on the Curry-Howard isomorphism](http://bookzz.org/s/?q=Lectures+on+the+Curry-Howard+Isomorphism&yearFrom=&yearTo=&language=&extension=&t=0)".
  * Girard, Lafont, Taylor "[Proofs and types](http://www.paultaylor.eu/stable/prot.pdf)".
  * Gallier "[Constructive Logics Part I](https://ai2-s2-pdfs.s3.amazonaws.com/55ec/dffd387d44e3d939a8a7dacf7c655a84a793.pdf)".
  * Wadler "[Propositions as types](http://homepages.inf.ed.ac.uk/wadler/papers/propositions-as-types/propositions-as-types.pdf)".
  * Martin-Lof "[On the meanings of the logical constants and the justifications of the logical laws](https://www.andrew.cmu.edu/user/ulrikb/80-518-818/MartinLof83.pdf)".

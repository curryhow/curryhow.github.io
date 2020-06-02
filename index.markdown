---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

![Ocean and concrete](water-cut.png?w=1740&h=724&fit=crop&crop=center&auto=format)

The Curry-Howard correspondence is a duality between logic and computation, sometimes referred to by the tagline "**propositions as types, proofs as programs**". 

This website will host an online short course in the fundamentals of theoretical computer science, building to a proof of the Curry-Howard correspondence. The aim is to be accessible but still completely rigorous; this course will be a challenge. All lecture notes and videos for the course will be freely available. We are part of the [School of Mathematics and Statistics](https://ms.unimelb.edu.au/home) at the University of Melbourne. If you're curious, feel free to get in touch by [email](mailto:d.murfet@unimelb.edu.au).

## Course

The aim of the course is to give a complete proof of the Curry-Howard correspondence, as an isomorphism of categories between a logic (intuitionistic sequent calculus) and a programming language (simply-typed lambda calculus). While there are many books and lectures on this topic (the two most famous being Sorensen and Urzyczyn's book "[Lectures on the Curry-Howard isomorphism](http://bookzz.org/s/?q=Lectures+on+the+Curry-Howard+Isomorphism&yearFrom=&yearTo=&language=&extension=&t=0)" and Wadler's "[Propositions as types](http://homepages.inf.ed.ac.uk/wadler/papers/propositions-as-types/propositions-as-types.pdf)") these mostly focus on natural deduction for which the Curry-Howard correspondence is (in our opinion) not very impressive.

Here is our version:

* Introduction to lambda calculus
    * What is a program?
    * Untyped lambda calculus
    * Simply-typed lambda calculus
    * Programming in lambda calculus
    * Proof of the Church-Rosser theorem
    * Proof of strong normalisation for simply-typed lambda calculus
* Introduction to sequent calculus
    * What is logic?
    * Examples of proofs
    * Proof of cut-elimination for sequent calculus
* Introduction to category theory
    * Categories, functors and monads
    * The category of lambda terms
    * The category of proofs
* Proof of the Curry-Howard isomorphism
* Curry-Howard in the broader context of computer science

For a beautifully written introduction to the history of interactions between logic and the theory of computation, we recommend Martin Davis' book "[The universal computer: the road from Leibniz to Turing](https://www.amazon.com.au/Universal-Computer-Leibniz-Turing-Third/dp/1138502081/ref=pd_lpo_14_t_0/356-0457671-4560607?_encoding=UTF8&pd_rd_i=1138502081&pd_rd_r=e9c02307-29a8-454d-9ff9-6d9bcb477dc6&pd_rd_w=3P6Za&pd_rd_wg=F0oMc&pf_rd_p=ad2d1e6e-bc60-4795-b4c0-2dbd35f6678d&pf_rd_r=3RN2NTR99F314RV7BT63&psc=1&refRID=3RN2NTR99F314RV7BT63)]".

## People

* **James Clift**: Masters degree in Pure Mathematics, with a thesis on [Turing machines and differential linear logic](http://therisingsea.org/notes/MScThesisJamesClift.pdf).

* **[Will Troiani](https://williamtroiani.github.io/)**: Masters degree in Pure Mathematics, with a thesis on [categorical logic, topos theory and simplicial sets](https://williamtroiani.github.io/pdfs/FiniteSimplicialSetsareAlgorithms.pdf).

* **[Daniel Murfet](http://therisingsea.org/)**: Lecturer at the University of Melbourne, PhD in algebraic geometry with research interests also in logic and deep learning.

## Original seminar

In Semester two of 2016 we ran a seminar on the topic of the Curry-Howard correspondence, largely following Sorensen and Urzyczyn's book "Lectures on the Curry-Howard isomorphism", up to the proof of the original Curry-Howard correspondence (between simply-typed lambda calculus and intuitionistic logic) in Chapter 4. Some of the talks are listed here:

  * William Troiani "The Church-Rosser Theorem" ([lecture notes](http://therisingsea.org/notes/talk-will-churchrosser.pdf))
  * William Troiani "Introduction to lambda calculus" (Sections 1.1-1.3, [lecture notes](http://therisingsea.org/notes/talk-will-lambda.pdf))
  * James Clift "Simply-typed lambda calculus and strong normalisation" (Chapter 3, [lecture notes](http://therisingsea.org/notes/talk-james-simplytyped.pdf))
  * Daniel Murfet "The category of simply-typed lambda terms" ([lecture notes](http://therisingsea.org/notes/talk-catsimplytyped.pdf))
  * Daniel Murfet "The category of simply-typed lambda terms II" ([lecture notes](http://therisingsea.org/notes/talk-catsimplytyped2.pdf) and an [appendix](http://therisingsea.org/notes/talk-catsimplytyped2-cuts.pdf))
  * Daniel Murfet "The Curry-Howard principle" ([lecture notes](http://therisingsea.org/notes/talk-ch.pdf))
  * James Clift "System F: Polymorphic lambda calculus" ([lecture notes](http://therisingsea.org/notes/talk-james-systemF.pdf))
  * William Troiani "System F in the real world: Haskell and functional programming" ([lecture notes](http://therisingsea.org/notes/talk-will-haskell.pdf)) (the referenced talk by Rich Hickey is "[Simple made easy](https://www.infoq.com/presentations/Simple-Made-Easy)")
  
Thanks to Camillo Fiorentini for noticing errors in the original notes for the lecture on strong normalisation, and for suggesting the fix (incorporated in the current version).  

References:

  * Sorensen, Urzyczyn "[Lectures on the Curry-Howard isomorphism](http://bookzz.org/s/?q=Lectures+on+the+Curry-Howard+Isomorphism&yearFrom=&yearTo=&language=&extension=&t=0)".
  * Girard, Lafont, Taylor "[Proofs and types](http://www.paultaylor.eu/stable/prot.pdf)".
  * Gallier "[Constructive Logics Part I](https://ai2-s2-pdfs.s3.amazonaws.com/55ec/dffd387d44e3d939a8a7dacf7c655a84a793.pdf)".
  * Wadler "[Propositions as types](http://homepages.inf.ed.ac.uk/wadler/papers/propositions-as-types/propositions-as-types.pdf)".
  * Martin-Lof "[On the meanings of the logical constants and the justifications of the logical laws](https://www.andrew.cmu.edu/user/ulrikb/80-518-818/MartinLof83.pdf)".

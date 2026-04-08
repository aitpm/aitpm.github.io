---
title: "Workshop on AI and Theorem Provers in Mathematics (AITPM)"
layout: default
---

# Workshop on AI and Theorem Provers in Mathematics

This meeting will explore with leading experts some of the recent developments related to the use of AI and theorem provers in mathematics as well as the perspectives for such future use.

- Attendance is **free**.
- Venue: Online 
- Date:  8. - 10. April 2026
- Registration: <!--- [Online Form](https://forms.office.com/e/c7gth3Rb6Q) -->
  Information how to access the online platforms have been emailed to all registered participants. If you did not receive or still want to register, please contact the organisers via email (e.g.,  `a.brucker AT exeter.ac.uk`)

Given consent by speakers, talks will be recorded and made public after the workshop. We do not plan to record the panel session, which are planned to be highly interactive. 

## Speakers

- [Kevin Buzzard](https://profiles.imperial.ac.uk/k.buzzard) (Imperial College)
- [Chelsea Edmonds](https://cledmonds.github.io/) (University of Western Australia) 
- [Yang-Hui He](https://lims.ac.uk/yang-hui-he/) (London Institute for Mathematical Sciences)
- [Paola Iannone](https://www.research.ed.ac.uk/en/persons/paola-iannone/) (University of Edinburgh)
- [Patrick Massot](https://www.imo.universite-paris-saclay.fr/~patrick.massot/en/) (University Paris Saclay)
- [Shinichi Mochizuki](https://www.kurims.kyoto-u.ac.jp/en/list/MOCHIZUKI,%20Shinichi.html) (Research Institute for Mathematical Sciences Kyoto)
- [Leonardo De Moura](https://leodemoura.github.io/) (Amazon Web Services)
- [Lawrence Paulson](https://www.cl.cam.ac.uk/~lp15/) (University Cambridge)
- [Natarajan Shankar](https://www.csl.sri.com/~shankar/) (SRI International)

## Programme Schedule

The schedule (all times are BST, i.e., Europe/London) of the workshop is:

* April 8th 2026 
  * 08:00-09:00 Kevin Buzzard: _What goes into Formalizing Fermat?_
  * 09:15-10:15 Paola Iannone: [_Teaching with Lean for supporting the transition to university mathematics - current research and future trends_](./slides/Ianonne.pdf)
  * 10:45-11:45 Lawrence Paulson: _AI and Isabelle: experiences and perspectives_
  * 12:00-13:00 Discussion/panel session
* April 9th 2026
  * 08:00-09:00 Chelsea Edmonds: _A Proof Engineering Perspective on Formalising Combinatorics in Isabelle/HOL_
  * 09:15-10:15 Yang-Hui He: _The AI Mathematician_
  * 10:45-11:45 Shinichi Mochizuki: _On the Formalization of IUT: a preliminary progress report_
  * 12:00-13:00 Discussion session
* April 10th 2026
  * 15:00-16:00 Patrick Massot: _Teaching mathematics using Verbose Lean_
  * 16:15-17:15 Leonardo De Moura: _Lean: How AI and Proof Automation Are Changing Mathematics_
  * 17:45-18:45 Natarajan Shankar _Beyond QED: AI, Theorem Proving, and the Quest for Beautiful Proofs_
  * 19:00-20:00 Discussion/panel session and closure

All times are BST (i.e., London, observing daylight saving time).


## Detailed Programme 

### April 8th 2026

#### Kevin Buzzard: _What goes into Formalizing Fermat?_

I will talk about my ongoing attempt to teach Lean a proof of Fermat's Last Theorem. I'll give a broad talk including an update on where we are, and a discussion on ideas which we've tried and issues which have arisen.

#### Paola Iannone: _Teaching with Lean for supporting the transition to university mathematics - current research and future trends_

 In the past few years Lean, and other interactive theorem provers, have entered the university classrooms. Their use is meant both to prepare the mathematicians of the future and to support the transition to the rigour of university mathematics. Research in mathematics education is investigating the impact on aspects of students’ learning of this new digital technology. In this talk I will map the development of this research presenting its main results so far  and  some directions for future research.  
#### Lawrence Paulson: _AI and Isabelle: experiences and perspectives_

Recent weeks have seen dramatic developments in AI and theorem proving. Josef Urban has auto-formalised an entire topology textbook, three times: into Megalodon, HOL Light and Isabelle/HOL. Meanwhile, Hanno Becker and Dominic Mulligan of Amazon Web Services have released a suite of tools aimed at facilitating interoperability between Isabelle and LLMs. We can now work interactively, with an LLM at our elbow, or throw a massive job at an LLM and go away for a week. The author will report some experiences and then ask, where is this taking us?

### April 9th 2026

#### Chelsea Edmonds: _A Proof Engineering Perspective on Formalising Combinatorics in Isabelle/HOL_

Formalised maths is often viewed primarily as a tool to verify proof correctness, yet focusing solely on this motivation overlooks other significant benefits - such as the potential to uncover new mathematical insights. In this context, we must consider not just if a proof verifies, but how we approach the formalisation process itself. This talk will explore this challenge by viewing the formalisation process from a software engineering perspective. Using the Isabelle/HOL proof assistant, we'll first explore how core engineering principles such as modularity and extensibility can be applied to model complex mathematical hierarchies and proof patterns. I'll highlight the benefits this approach offers through some examples in combinatorics, while also introducing some key Isabelle features such as locales which facilitate this. I'll conclude by offering some perspectives on why these engineering principles are more relevant than ever as generative AI is integrated into proof assistants, in order to fully leverage all the benefits of formalised mathematics.
 

#### Yang-Hui He: _The AI Mathematician_

We argue how AI can assist mathematics in three ways: theorem-proving, conjecture formulation, and language processing.
Inspired by initial experiments in geometry and string theory in 2017, we summarize how this emerging field has grown over the past years, and show how various machine-learning algorithms can help with pattern detection across disciplines ranging from algebraic geometry to representation theory, to combinatorics, and to number theory. 
At the heart of the programme is the question how does AI help with theoretical discovery, and the implications for the future of mathematics.
 
#### Shinichi Mochizuki: _On the Formalization of IUT: a preliminary progress report_

In this talk, we survey preliminary work conducted by my research group at RIMS, Kyoto University, since the fall of 2025 on the long-term project of formalizing IUT (inter-universal Teichmüller theory).  This work began with the  organization of this project into various stages (Stages 1～5) and revolves  (not so much around writing complete Lean code for the mathematical content  of IUT in its entirety, but rather) around the idea that Lean can utilized as a  _communication tool_ for recording the precise logical structure of key portions  of the logic of IUT in such a way that Lean code can be used to communicate  this logic in a more precise and effective way than conventional natural language- based mathematical discourse to mathematicians who have professional  expertise in writing Lean code (i.e., who, unlike my research group at RIMS,  have the capacity to generate substantial quantities of professionally written  Lean code).  Finally, we discuss in detail, as a sort of case study, the  reorganization into suitable blackboxes, from a Lean formalization-oriented  point of view, of the logic of the final portion "3.11⇒3.12" of the third paper on  IUT, since it is this portion of IUT that has received the most public attention.  The skeletal Lean code that we wrote for this portion of IUT constituted a  remarkably successful case of the use of Lean as a communication tool.
 
### April 10th 2026

#### Patrick Massot: _Teaching mathematics using Verbose Lean_

Verbose Lean is a library for the Lean proof assistant whose goal is to help teaching first year undergrad students how to read and write mathematical proofs. It shares a lot of goals and principles with the Coq-Waterproof project. In this talk I will show what it looks like and emphasize the flexibility it brings to teachers. This flexibility allows to tune the amount of help given to students and the level of precision required from them.

#### Leonardo De Moura: _Lean: How AI and Proof Automation Are Changing Mathematics_

Lean is an open-source theorem prover and programming language based on dependent type theory, implemented in Lean itself, including its proof automation, parser, compiler, and tooling. No matter how users extend the system, every proof is checked by a small trusted kernel. Its mathematical library, Mathlib, contains over 200,000 formalized theorems contributed by more than 750 contributors.

In this talk, I will present Lean and show how AI and proof automation are changing how mathematicians work. I will discuss how formalization has moved from a niche activity to a practical tool adopted by leading mathematicians, how AI systems are now generating formal proofs at scale, and how better proof automation makes AI provers more powerful. I will also discuss why machine-checked proofs create a new kind of collaboration between humans and AI, and why readable formal specifications remain the foundation of trust even when proofs are produced by machines.

#### Natarajan Shankar _Beyond QED: AI, Theorem Proving, and the Quest for Beautiful Proofs_

The dramatic evolution of generative AI, fuelled by the convergence of
data and compute, opens up new opportunities for synergy between AI and Theorem Proving.
The talk addresses the following question: Can we leverage this technology to go beyond QED
to scale the abilities of humans at all skill levels to understand, create, and use beautiful
mathematics?

## Organisers

- [Mohamed Saidi](https://experts.exeter.ac.uk/36-mohamed-saidi) (Department of Mathematics and Statistics, University of Exeter)
- [Barrie Cooper](https://experts.exeter.ac.uk/315-barrie-cooper) (Department of Mathematics and Statistics, University of Exeter)
- [Gihan Marasingha](https://experts.exeter.ac.uk/20765-gihan-marasingha) (Department of Mathematics and Statistics, University of Exeter)
- [Achim D. Brucker](https://experts.exeter.ac.uk/32582-achim-d-brucker) (Department of Computer Science, University of Exeter)
- [Diego Marmsoler](https://experts.exeter.ac.uk/33716-diego-marmsoler) (Department of Computer Science, University of Exeter)


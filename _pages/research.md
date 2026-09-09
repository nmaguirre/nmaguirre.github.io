---
layout: page
title: research
permalink: /research/
description: My research interests and activities
nav: true
nav_order: 4
display_categories: [work, fun]
horizontal: false
---

My research interests lie in the intersection of formal methods and software engineering, with a focus on automated techniques for software analysis, testing, and quality assurance. My current main lines of work are:

---

##### Formal Modeling and Model Analysis

---

I have a long-standing interest in the formal specification languages, and automated analysis of formal specifications. A central thread is DynAlloy, an extension of the Alloy specification language with dynamic behavior, originally developed with Marcelo Frias, Juan Pablo Galeotti and Carlos Lopez Pombo, among other collaborators. More recent work has explored efficient analysis strategies and comparative studies of Alloy-based dynamic notations. A significant subline is the automated repair of Alloy specifications: tools such as BeAFix, ICEBAR, and ATR address the problem of finding fixes to faulty Alloy models using bounded exhaustive search and template-based approaches, in collaboration with Marcelo Frias, German Regis, Hamid Bagheri, ThanVu Nguyen, Simon Gutierrez Brida and other colleagues.

---

##### Software Testing

I work on automated test generation and test quality assessment, particularly for programs with complex heap-manipulating inputs. Topics include bounded exhaustive testing, field-exhaustive testing, and tight field bounds computation, in collaboration with Pablo Ponzio, Marcelo Frias and other colleagues. More recently I have worked on oracle quality metrics — in particular, state field coverage as a measure of test oracle adequacy — with Facundo Molina and Alessandra Gorla.

---

##### Specification Inference

A growing line of work concerns the automated inference of formal specifications from code. This includes learning postconditions and class invariants using evolutionary algorithms (EvoSpex), grammar-based fuzzing of class specifications (SpecFuzzer), and inferring contracts and metamorphic relations through search-based and LLM-assisted techniques. This is work I have carried out with Facundo Molina, Renzo Degiovanni, Pablo Ponzio, Alessandra Gorla, Diego Garbervetsky, and other collaborators.

---

##### Formal Requirements and LTL Goal Analysis

I work on the analysis and automated repair of formal requirements expressed as LTL goals, including detecting goal conflicts, automated conflict resolution, boundary condition discovery, and repair of unrealizable specifications. This line extends to fuzzing LTL solvers. This is work I done in collaboration with Renzo Degiovanni, Mike Papadakis, and other colleagues.


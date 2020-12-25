---
permalink: /
#title: "Teng Zhang's websites"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am a Ph.D student at University of Pennsylvania. 

I am a member of PRECISE at Penn.

My research interests include runtime verification, formal verification and model-based development.


What I do
=========

My dissertation proposes a RV-enabled framework for self-adaptive software. The core of this framework is SMEDL, a domain specific language for property specification. The state-machine-based style language for single monitors allows users to describe both high-level temporal properties and low-level properties involving imperative actions conveniently. To support component-based systems naturally, the SMEDL specification can be modeled as a set of connecting monitors. Users can flexibly specify how monitors are deployed to balance performance and overhead. The notion of monitor network provides a powerful and unified way to specify different properties and facilitates flexible deployment of monitors to adapt to a variety of software systems. Dynamic instantiation of monitor instances is suitable for monitoring large data set offline or scalable software systems online.


What I did before
=================

Safety critical systems require more rigorous design and development process. Model-based development has been widely used. During my bachelor and master, I had been working in two projects using model-based technology to verify or simulate behavior of safety critical systems. One was verification of AADL (Architectural Analysis and Design Language) models by transforming into Timed Abstract State Machine (TASM) and UPPAAL timed automata model. I was responsible for implementing the concrete transformation rules from AADL to TASM and TASM to UPPAAL using Atlas Transformation Language (ATL).

The other project is concurrent code generation for synchronous language SIGNAL, a multi-clocked data-flow modeling language for safety critical systems. To fully utilize its feature on describing concurrent behavior, we developed a technique to generate parallel code automatically from SIGNAL specifications. Based on the information obtained from clock calculus, we proposed a data structure to analyze global data-dependency relations from which concurrent tasks are extracted to help explore parallelism in the original specification. Combined with clock relations, parallel tasks are finally mapped onto the OpenMP structures. 




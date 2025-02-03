---
title: "Type- and Control-Flow Analysis for System F-omega"
collection: publications
category: thesis
permalink: /publication/tcfa-for-f-omega
excerpt: "This paper is about extend type- and control-flow analysis to System F-omega."
date: 2023-11-10
venue: "Master's Thesis. Rochester Institute of Technology"
paperurl: "https://repository.rit.edu/theses/11595/"
citation: "Dongyu, Wu. (2023). &quot;Type- and Control-Flow Analysis for System F-omega.&quot; <i>Master's Thesis, Rochester Institute of Tecnology</i>. 1(1)."
---

Type- and control-flow analysis combines control-flow analysis and type-flow analysis. It improves the approximation given by control-flow analysis by using type-flow information to filter out abstract values with incompatible types. Type-flow analysis and control-flow analysis are mutually beneficial since the control-flow analysis approximates the Λ-expressions in type applications. Previously, a type- and control-flow analysis for System F has been defined. However, System F only has limited support for polymorphism. System Fω, a more sophisticated type system, augments System F with type-level functions, thereby introducing abstract type constructors. It enables the use of generic functions that are parameterized by polymorphic data structures. In this work, a new type- and control-flow analysis for System Fω is defined. This work includes a specification-based formulation of the type- and control-flow analysis for System Fω and a proof of the soundness of the analysis. This work presents a flow-graph-based formulation. The soundness of the flow-graph-based formulation is proved by relating to the specification-based formulation.

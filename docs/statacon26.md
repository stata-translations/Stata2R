## Title

Using Large Language Models and Coding Agents to Translate Stata Packages: Benefits and Risks

## Abstract
Packages written in Stata are often focussed on solving specific 
problems in specific research domains. Within the research domain 
many people use Stata, so code sharing and reuse is possible. 
The code itself however may be
high quality and useful to other research domains, but this may be prevented by 
limited use of Stata in other domains. 
Translating Stata code to other programming language may therefore help
 researchers to reach beyond their own domain, increasing research impact. 
Translation requires skills in the source and target language, and the research domain making it unlikely
 that any individual will be able to perform translation.
Large language models (LLM) support translation by amalgamating language and domain specific knowledge from many sources.

We will discuss our experiences in developing a Claude Code plugin that supports domain
experts in statistics in translating Stata packages to R and Python.  
The plugin implements 4 skills;
1. Analyse and plan: Is the package well documented? Which target language(s)? Create a new library or contribute to an existing library?
1. Translation to pseudocode: Translate to pseudocode to support human review without language expertise. Excludes any existing tests.  
1. Pseudocode to target language(s): Translate; add infrastructure to support ongoing opensource development (CI testing, contributing guidelines, licenses)  
1. Tests and documentation: Implement any existing Stata tests in target language; summarise test correspondence; highlight missing tests. Review documentation (examples, papers), and translate to target language (eg. Vignettes in R)  
 
We used the plugin in workshops with statisticians to translate a selection of Stata 
packages. We will discuss our experiences in code translation, discussing the 
quality and applicability of the results. 



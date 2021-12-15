---
layout: page
title: Learning Spatial Analysis Through Reproducible Research
---
October 26, 2021

Reproducible research notebooks in a CyberGIS environment, such as *CyberGISX*, are a valuable tool for learning and understanding spatial analysis. These computational notebooks facilitate a more accessible understanding of the computational process and reasoning, and also contribute to critical engagement with a given project and the inherent uncertainties within it.

#### Assessing Computability and Validity 

First, the notebook and reproducible research compendium makes the entire step-by-step process visible and executable in one document, which increases the accessibility of the code itself. Clear comments and instructions mean that code can be easily adjusted or updated with new or different data. This basic review of the methodology and code is a test of the notebook's *computability*, and is a good lesson and example in spatial analysis.

As Kedron and Holler noted in their presentation, the refocusing from computability in replication to credibility through replication means that the entire process is brought into question. As part of analyzing credibility of a study, we must look for sources of error and uncertainty, be critical of decisions and assumptions made, and consider the validity of constructs and inferences (Kedron & Holler 2021). From an educational standpoint, it's valuable to investigate and challenge all the decisions made, from the motivations to the logic of the methods to the validity of the interpretation. Critical engagement with a project forces us to think through every step, even those before computation. Subjective decisions made in every stage of the process can lead to the propagation of uncertainties throughout the work, which are discussed in [this post](reflections/uncertainty-geography.md). For instance, in investigating the credibility of Kang et al.'s 2020 "Rapidly measuring spatial accessibility of COVID-19 healthcare resources: a case study of Illinois, USA", we can question base assumptions about the weights applied to varying distances of hospitals, or the fact that this analysis only considers personal vehicle use and not public transportation networks, or whether a hospital can actually serve a patient just because it has a ventilator available for them.

#### Reanalysis as a Learning Tool

We can also push our review further, and add a "reanalysis" (Kedron & Holler 2021). This is the most valuable step when using these reproducible notebooks as an educational tool, as it puts our understanding of the process and the code to the test. In a reanalysis, we could add code that tests for error or uncertainties we've identified (such as the default speed limit where the value is missing), or shift the interpretation beyond what the original authors landed on (how policymakers and healthcare administrators should utilize the data and respond), or even increase efficiency (some students have improved the efficiency of the Kang et al. notebook to reduce processing time). All of these reanalyses test students' understanding through identifying problems or weaknesses and writing code to address it. Because the code can be viewed alongside the text that contextualizes and justifies it, we have access to most of the information we need to investigate its credibility. 

In my experience, working through a paper's methodology and trying to create a workflow is great practice for critically understanding the process. In a class setting, we collectively question every data source, code, and result, which is a skill I've applied to other projects since. 

### References

Kang, J. Y., A. Michels, F. Lyu, Shaohua Wang, N. Agbodo, V. L. Freeman, and Shaowen Wang. 2020. Rapidly measuring spatial accessibility of COVID-19 healthcare resources: a case study of Illinois, USA. *International Journal of Health Geographics* 19 (1):1–17. DOI: [10.1186/s12942-020-00229-x](10.1186/s12942-020-00229-x).

Kedron, P. & Holler, J. (2021, August 23). Working with Students to Reproduce COVID-19 Research to Establish the Credibility of Findings and Accelerate Policymaker Adoption. Geospatial Fellows Webinar Series, American Association of Geographers. [Access here](https://aag-geospatialfellows-series.secure-platform.com/a/solicitations/16/sessiongallery/250).

Wang, S. (2019). Cyberinfrastructure. The Geographic Information Science & Technology Body of Knowledge (2nd Quarter 2019 Edition), John P. Wilson (Ed.). DOI: [10.22224/gistbok/2019.2.4](10.22224/gistbok/2019.2.4).

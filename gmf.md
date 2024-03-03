## What is the GMF Taxonomy?

The Goals, Methods, and Failures (GMF) taxonomy is a failure 
cause analysis taxonomy interrelating the goals of the system 
deployment, the system's methods, and their likely failings. 
Details on the process are available in the recent work published 
for [SafeAI paper](https://arxiv.org/abs/2211.07280).

#### Motivation
The taxonomy was developed to address the following use cases and questions:

- How can owners and developers of AI systems discover harm-related failures
causes related to the real-world task the system is deployed to perform?

- How can AI developers and engineers discover technical causal factors of
 real-world harm, that may be linked to implementation methods, model architectures
 and techniques employed in their system, such that they may be corrected or avoided?

- How can we leverage the body of expert technical knowledge from the Machine
 Learning, AI Safety, Engineering, etc. community, to produce useful, high-quality
  annotations on publicly available AI incident reports?

- How can we generate annotations grounded to real-world data for high-level accuracy,
verifiability and potential for further research and development?

#### Structure
The taxonomy is designed to address the questions above via a structure of three interrelated
 ontologies, each describing the AI system involved in a reported incident under a different lens.
 These ontologies include system views focused on:

- AI system goals, which characterize high-level goals, objectives and tasks of AI systems (e.g. `Face Recognition`)
- AI methods and technologies, which describe the AI implementation methodologies (e.g. `Transformer`)
- AI failure causes, containing technical reasons related to systemic failure that results in harm (e.g. `Concept Drift`)

Given that AI incident reports in news media often lack technical details, GMF annotations are paired with:

- Confidence modifiers (`known` and `potential`), corresponding to how certain the annotator is,
when applying a label to the incident
- Text snippets from reports describing the incident, which ground the label to text supporting the classification
- Free comments, where the annotator may provide their rationale, evidence, sources, etc. for the assigned label


#### Incident annotation with GMF

The structure of GMF, paired with the AIID interfaces for incident discovery, annotation editing and risk
checklisting, exposes the user to multiple sources of useful information for efficient incident annotation,
other than the contents of its reports.

For example, the user can retrieve similar incidents annotated by the community with respect to existing
classifications, e.g. of the system goal.
This exposes past annotations and metadata (exemplar text snippets, annotator rationale and related materials)
of potential relevance, informing the selection of additional fitting labels (e.g. methods and technologies,
as well as technical failure causes) for the incident at hand.

A visualization of this information flow in the annotation process is illustrated  below:

![](images/structure.png)

Additionally, an indicative annotation process for the [AIID incident #72](https://incidentdatabase.ai/cite/72/) is illustrated below.

![](images/annotation.png)


## How do I explore the taxonomy?

All taxonomies can be used to filter incident reports within the 
[Discover Application](https://incidentdatabase.ai/apps/discover). The taxonomy filters work similarly to how 
you filter products on an E-commerce website. Use the search 
field at the bottom of the “Classifications” tab to find the 
taxonomy field you would like to filter with, then click the 
desired value to apply the filter.

## About the Responsible AI Collaborative

The AI Incident Database is a collaborative project of many 
people and organizations. Details on the people and organizations 
contributing to this particular taxonomy will appear here, while 
you can learn more about the Collab itself on the incident 
database [home](https://incidentdatabase.ai/) and 
[about](https://incidentdatabase.ai/about/) pages.

The maintainer(s) of this taxonomy include:
* [Nikiforos Pittaras](https://www.linkedin.com/in/nikiforos-pittaras/)

Contributor(s) of the taxonomy include:
* [Sean McGregor](https://www.linkedin.com/in/seanbmcgregor/)
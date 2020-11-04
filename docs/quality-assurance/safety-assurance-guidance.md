# Safety Assurance Guidelines

## What is Safety Modelling

Safety Modelling is focused around two key areas:

* Error (Data Integrity)
* Delay

This is centered around asking *What if* questions to determine safety risks and the likelihood and safety impact of those risks occurring.

## How should we use it

### At the start of a project

* Carry out a bowtie analysis of the project to identify potential areas of safety that need to be considered (there are a number of safety assurance experts who can help in carrying out bowtie analysis).
* See [Bowtie in four easy steps](https://www.youtube.com/watch?v=PHbLQWqojC8)

### During Sprints

* Tag relevant PBI's with a `safety` tag along with details of how the safety risk can be mitigated. If it is not clear whether there is a safety impact use a `safety pending` tag until this ambiguity is resolved.
* Consider testing the risk mitigation. There will be a balance between effort required to test against the likelihood and impact.
* Let the PO make final decisions on the safety impact/consequence. The PO will engage with other SME's to determine if the safety risk is acceptable. This may  
  mean that although there is a potential safety risk that risk is deemed manageable or may require remedial action. This detail should be captured in a lightweight 
  manner within the relevant PBI.
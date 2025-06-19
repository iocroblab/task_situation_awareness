# Task and Situation Awareness using ontologies and LLMs 

This *metarepo* has been prepared to illustrate the work done in the [SMARTHANDLE](https://smarthandle-project.eu/) project within *Task 5.3: Learning based grasping – Planning for known & unfamiliar workpieces* regarding the use of ontologies and LLMs to make the robot aware of the situation and of the task, as part of deliverable *D5.2 SMARTHANDLE reasoning enablers*.

It contains two repositories:

- The [Ontology instantiation with LLMs](https://github.com/iocroblab/ontology_instantiation_with_llms) tool to allow the user to instantiate a situation ontology with information of the scene.
- The [Ontology PDDL Generation](https://github.com/iocroblab/ontology-pddl-generation) tool to automatically generate the PDDL problem file from the situation ontology.

The READMEs in each repository have the instructions to build and test the tools.

The figure shows the schema of the system:

<p align="center">
  <img src="docs/onto-llm.png" width="700"/>
  <br>
  <em>Figure 1. Obstacle avoidance example with an orientation constraint.</em>
</p>

A detailed description of this contribution is described in the paper [Robot Situation and Task Awareness using Large Language Models and Ontologies](docs/LLM_Onto_paper.pdf) by V. Molina, O. Ruiz-Celada, R. Suárez, J. Rosell and I. Zaplana, accepted to the 2025 Workshop on Safe and Sustainable AI-Aided Manufacturing (S2AIM).
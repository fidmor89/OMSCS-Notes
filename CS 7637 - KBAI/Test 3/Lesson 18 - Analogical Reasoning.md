# Lesson 18

**Analogical reasoning** involves understanding new problems in terms of a family of problems and transferring knowledge of relationships from known problems across domains. We will cover the following:

1. Similarity and case-based reasoning
2. Process of analogical reasoning
3. Design by analogy

## Need For Cross-domain Analogy

Cross domain connections allow an agent to solve new problems based on existing knowledge in some domain. An agent will do this by abstracting out relationships between concepts from one domain to another. These relationships are important because they are the knowledge that is transferred from the source case to the target problem.

## Spectrum Of Similarity

Shown below is table for spectrum of similarity between different KBAI methods from more similar with recording cases to less similar with analogical reasoning:

| Method               | Relations | Objects | Features | Values |
| -------------------- | --------- | ------- | -------- | ------ |
| Recording Cases      | S         | S       | S        | S      |
| Case-based Reasoning | S         | S       | S        | D      |
| Case-based Reasoning | S         | S       | D        | D      |
| Analogical Reasoning | S         | D       | D        | D      |

Where _S_ is for similar and _D_ is for dissimilar

## Process Of Analogical Reasoning

Analogical reasoning consists of five different phases which are usually not linear:

1. Retrieval
2. Mapping
3. Transfer
4. Evaluation
5. Storage

This is just one of the many models on analogical reasoning. Recall that case-based reasoning had the following steps:

1. Retrieval
2. Adaptation
3. Evaluation
4. Storage

Therefore, one of the main differences for analogical reasoning lies within the mapping step where an agent must determine the mapping between relations, objects, features, and values from the source case to the target problem. Once those mappings are determined then knowledge transfer of abstracted relationships from one domain to another can occur.

## Three Types Of Similarity

There are various types of similarity:

1. **Semantic**: conceptual similarity between the target problem an the source case
2. **Pragmatic**: similarity of external factors such as goals
3. **Structural**: similarity between representation structures
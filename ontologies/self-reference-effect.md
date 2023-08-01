---
description: Ontology page for the Self-reference effect
---

# 😶 Self-reference effect

**Self-reference effect**

[**OWL File of the Ontology**](https://github.com/leonardozilli/CognitiveBiasOntology/blob/main/SelfReferenceEffect.owl)

<figure><img src="../.gitbook/assets/Self-reference effect.drawio.svg" alt=""><figcaption><p>Diagram for the ontology of Self reference effect</p></figcaption></figure>

**Initial AI Ontology Prompts**

**Bias Definition (user input to the AI):**

The self-reference effect is a cognitive process where the self is implicated in processing personal information.

**User Story:** _Studying for an Exam_

As a psychology student, Alice has a big exam coming up. One of the concepts she needs to understand and remember is "cognitive dissonance." She reads the textbook definition, but it doesn't stick in her mind. She decides to apply the self-reference effect to help her remember.

Alice thinks back to a time when she experienced cognitive dissonance herself. She recalls a situation where she had to choose between attending a friend's party and studying for another exam. She wanted to do both, but they were happening at the same time. She remembers the discomfort she felt at having these conflicting desires.

Alice then relates this personal experience to the definition of cognitive dissonance - the mental discomfort experienced by a person who holds two or more contradictory beliefs, ideas, or values. By connecting the term to her own experience, it becomes more meaningful and easier to remember.

When the exam day comes, Alice sees a question about cognitive dissonance. She immediately recalls her personal experience and is able to remember the definition clearly. She writes down her answer confidently, thankful for the self-reference effect that helped her remember the concept.

**Competency Questions**:

1. **What strategy did Alice use to remember the definition of "cognitive dissonance"?**\
   Alice used the self-reference effect, a strategy where she related the concept of cognitive dissonance to her own personal experience, making it easier for her to remember the definition.
2. **Can you describe the personal experience Alice used to understand the concept of cognitive dissonance?**\
   Alice recalled a situation where she had to choose between attending a friend's party and studying for another exam, which were happening at the same time. This situation, where she had conflicting desires, was an example of cognitive dissonance.
3. **How effective was the self-reference effect in helping Alice during her exam?**\
   The self-reference effect was very effective for Alice. During her exam, when she saw a question about cognitive dissonance, she was able to recall her personal experience and the definition of the term clearly, allowing her to answer the question confidently.

**Classes:**

CognitiveBias: A general class representing cognitive biases, which are systematic errors in thinking that affect the decisions and judgments that people make.

SelfReferenceEffect (subclass of CognitiveBias): A specific cognitive bias where individuals tend to have better memory for information that they have related to themselves.

Student: Represents individuals who are engaged in learning, in this case, Alice.

PsychologyConcept: Represents concepts or ideas in psychology, in this case, cognitive dissonance.

PersonalExperience: Represents experiences that are personal to an individual, in this case, Alice's dilemma between attending a party and studying.

StudyStrategy: Represents strategies used by students to aid in their learning, in this case, the self-reference effect.

**Properties:**

experiencesBias (domain: Student, range: CognitiveBias): Represents the cognitive bias a student experiences.

employsStrategy (domain: Student, range: StudyStrategy): Represents the study strategy a student uses.

relatesExperienceToConcept (domain: StudyStrategy, range: PersonalExperience): Represents how a study strategy relates a personal experience to a concept.

understandsConcept (domain: Student, range: PsychologyConcept): Represents the psychology concept a student understands.

**Individuals:**

Alice (type: Student): Represents a specific student, Alice.

CognitiveDissonance (type: PsychologyConcept): Represents a specific psychology concept, cognitive dissonance.

PartyVsStudyDilemma (type: PersonalExperience): Represents a specific personal experience, Alice's dilemma between attending a party and studying.

SelfReferenceStrategy (type: StudyStrategy): Represents a specific study strategy, the self-reference effect.

Although the AI made a detailed ontology, unfortunately it is too specific to be fitted into the base ODP. Thus, I made another ontology from the base ODP and integrated it with both Framester Frames and Personalized URI:

**Framester Frames & Personalized URI Substitutions**

**Classes:**

SelfReferenceEffect -> SubjectiveInfluence ([http://etna.istc.cnr.it/framester2/data/framestercore/SubjectiveInfluence](http://etna.istc.cnr.it/framester2/data/framestercore/SubjectiveInfluence))

Student -> [http://xmlns.com/foaf/0.1/Person](http://xmlns.com/foaf/0.1/Person)

StudyTechnique -> https://github.com/leonardozilli/Bias\_Ontology/VonRostorffEffect/StudyTechnique

PersonalExperience -> [http://etna.istc.cnr.it/framester2/data/framestercore/PerceptionExperience](http://etna.istc.cnr.it/framester2/data/framestercore/PerceptionExperience)

Studying ->[ http://etna.istc.cnr.it/framester2/data/framestercore/Studying](http://etna.istc.cnr.it/framester2/data/framestercore/Studying)

**ObjectProperties:**

leverages: This property links a VisualLearning to a SubjectiveInfluence that it leverages.

**Semantic Roles:**

* Student (Changed to **foaf:Persons** in the ontology)
* VisualLearning (Originally **Engagement** from the base ODP)
* Observation (Result: An individual is more likely to remember a concept by connecting it to their own memory or experience)
* Studying (Originally **Activity** from the base ODP)

I decided to use a similar scenario to the Von Rostorff bias to reuse some of the classes and properties in this particular ontology, with added classes and properties to match the current cognitive bias.

Individuals are included from the previous user story as an example of the bias ontology.

References:

Rogers, T.B., Kuiper, N.A., & Kirker, W.S. (1977). Self-reference and the encoding of personal information. _Journal of personality and social psychology, 35 9_, 677-88 .

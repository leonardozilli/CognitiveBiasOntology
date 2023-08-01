---
description: Ontology page for the Picture Superiority effect
---

# 🖼 Picture Superiority effect

**Picture Superiority effect**

[**OWL File of the Ontology**](https://github.com/leonardozilli/CognitiveBiasOntology/blob/main/PictureSuperiorityEffect.owl)

<figure><img src="../.gitbook/assets/Picture superiority.drawio.svg" alt=""><figcaption><p>Diagram for the ontology of Picture Superiority effect</p></figcaption></figure>

**Initial AI Ontology Prompts**

**Bias Definition (user input to the AI):**

The Picture Superiority Effect is a phenomenon in cognitive psychology where people tend to better remember images than words.

**User Story:** _Enhancing Student Learning with Visual Aids_

As a science teacher, Mrs. Johnson is preparing a lesson on the solar system for her 5th-grade class. She knows from her teaching experience that students often struggle to remember the names and order of the planets in the solar system. She decides to leverage the Picture Superiority Effect to enhance her students' learning and retention.

She finds a colorful and detailed diagram of the solar system, which clearly shows each planet in its correct order from the sun. During the lesson, she presents this diagram to her students, explaining each planet's unique features as she points to them on the image. She encourages the students to visualize the image in their minds as they learn about each planet.

In the following class, Mrs. Johnson conducts a pop quiz on the solar system. She is pleased to see that her students perform significantly better on this topic compared to previous ones. Many students are able to correctly name the planets and their order from the sun. Some students even mention that they remembered the planets by visualizing the colorful diagram in their minds.

This experience reinforces Mrs. Johnson's belief in the power of visual learning. She decides to incorporate more images and diagrams into her future lessons to help her students better understand and remember complex concepts.

**Competency Questions**:

1. **What teaching strategy did Mrs. Johnson used to help her students remember the names and order of the planets in the solar system?**\
   Mrs. Johnson used a colorful and detailed diagram of the solar system to teach her students, leveraging the Picture Superiority Effect to enhance their learning and retention.
2. **How did the students' performance on the pop quiz reflect the effectiveness of Mrs. Johnson's teaching strategy?**\
   The students performed significantly better on the pop quiz, with many correctly naming the planets and their order from the sun. This suggests that Mrs. Johnson's strategy of using a visual diagram was effective.
3. **What decision did Mrs. Johnson makes for her future lessons based on her experience teaching the solar system?**\
   Based on the success of her solar system lesson, Mrs. Johnson decided to incorporate more images and diagrams into her future lessons to help her students better understand and remember complex concepts.

**Classes:**

CognitiveBias: This is the main class that represents cognitive biases in general.

PictureSuperiorityEffect: This is a subclass of CognitiveBias that represents the specific bias where pictures are remembered better than words.

TeachingStrategy: This class represents different strategies that teachers can use in their lessons.

EducationalContext: This class represents different educational settings or contexts.

LearningOutcome: This class represents the different outcomes or results of learning.

**Properties:**

hasExample: This property links the PictureSuperiorityEffect class to specific instances or examples of the bias.

usedIn: This property links the PictureSuperiorityEffect class to the context or domain where it is applied.

employsStrategy: This property links the EducationalContext class to the TeachingStrategy class, indicating the teaching strategy used in a particular educational context.

resultsIn: This property links the EducationalContext class to the LearningOutcome class, indicating the outcome of a particular educational context.

improvesPerformance: This property links the TeachingStrategy class to the LearningOutcome class, indicating the outcome of a particular teaching strategy.

**Individuals:**

VisualLearning: This is an individual of the TeachingStrategy class, representing the strategy of using visual aids in teaching.

MrsJohnsonsClass: This is an individual of the EducationalContext class, representing Mrs. Johnson's class as a specific educational context.

ImprovedMemoryRetention: This is an individual of the LearningOutcome class, representing the outcome of improved memory retention.

**Relations**:

PictureSuperiorityEffect hasExample VisualLearning

VisualLearning usedIn MrsJohnsonsClass

MrsJohnsonsClass employsStrategy VisualLearning

MrsJohnsonsClass resultsIn ImprovedMemoryRetention

VisualLearning improvesPerformance ImprovedMemoryRetention

With the AI-generated ontology as a small inspiration, I made another ontology from the base ODP and integrated it with both Framester Frames and Personalized URI:

**Framester Frames & Personalized URI Substitutions**

**Classes:**

PictureSuperiorityEffect-> SubjectiveInfluence ([http://etna.istc.cnr.it/framester2/data/framestercore/SubjectiveInfluence](http://etna.istc.cnr.it/framester2/data/framestercore/SubjectiveInfluence))

Teachers -> [http://xmlns.com/foaf/0.1/Person](http://xmlns.com/foaf/0.1/Person)

VisualLearning -> https://github.com/leonardozilli/Bias\_Ontology/VonRostorffEffect/VisualLearning

OpticalImage -> [http://etna.istc.cnr.it/framester2/data/framestercore/OpticalImage](http://etna.istc.cnr.it/framester2/data/framestercore/OpticalImage)

Teaching -> [http://etna.istc.cnr.it/framester2/data/framestercore/EducationTeaching](http://etna.istc.cnr.it/framester2/data/framestercore/EducationTeaching)

**ObjectProperties:**

with medium: This property links VisualLearning to a VisualMedium that it uses during the learning.

leverages: This property links a VisualLearning to a SubjectiveInfluence that it leverages.

**Semantic Roles:**

* Teacher (Changed to **foaf:Persons** in the ontology)
* VisualLearning (Originally **Engagement** from the base ODP)
* Observation (Result: An individual tends to better remember images than words)
* Teaching (Originally **Activity** from the base ODP)

Individuals are included from the previous user story as an example of the bias ontology.

## References

Ensor, T.M., Surprenant, A.M. & Neath, I. Increasing word distinctiveness eliminates the picture superiority effect in recognition: Evidence for the physical-distinctiveness account. _Mem Cogn_ 47, 182–193 (2019). https://doi.org/10.3758/s13421-018-0858-9

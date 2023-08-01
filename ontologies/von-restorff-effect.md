---
description: Ontology page for the Von Restorff effect
---

# 🔦 Von Restorff effect

**Von Restorff effect**

[**OWL File of the Ontology**](https://github.com/leonardozilli/CognitiveBiasOntology/blob/main/VonRostorffEffect.owl)

<figure><img src="../.gitbook/assets/Von Rostorff.drawio (1).svg" alt=""><figcaption><p>Diagram for the ontology of Von Restorff effect</p></figcaption></figure>

**Initial AI Ontology Prompts**

**Bias Definition (user input to the AI):**

Von Restorff effect, also known as the "isolation effect", is described as a phenomenon where memory for isolated items is better than memory for non-isolated (homogeneous) items presented in the same serial list position. This effect has been observed in both humans and non-human primates.

**User Story:** _Studying for an Exam_

As a student, Maria has a big biology exam coming up. She has a lot of material to cover and wants to ensure she remembers the most important points. She decides to use the Von Restorff effect to her advantage.

Maria goes through her biology textbook and notes, highlighting key points and important facts with a bright yellow highlighter. She doesn't highlight everything, just the points she thinks are most important and wants to remember.

As she studies, Maria notices that the highlighted points stand out from the rest of the text. When she tries to recall information, she finds that the highlighted points come to mind first. The bright yellow color of the highlighter has made these points distinctive, and they're more memorable as a result.

On the day of the exam, Maria is able to recall the highlighted information easily. The Von Restorff effect has helped her remember the most important points, and she feels confident answering the exam questions. After the exam, Maria plans to use this study technique for her other subjects as well, as it has proven to be effective.

**Competency Questions:**

1. **What technique did Maria use to make key points stand out while studying for her biology exam?**\
   Maria used a bright yellow highlighter to mark key points in her textbook.
2. **What psychological effect did Maria leverage to improve her memory recall for the exam?**Maria leveraged the Von Restorff effect, which makes distinctive information more memorable.
3. **Was Maria's study technique effective in helping her recall information during the exam?**Yes, Maria was able to easily recall the highlighted key points during the exam, indicating that the technique was effective.

**AI-Generated Ontology**

**Classes:**

Student: This class represents the individual who is studying.&#x20;

StudyTechnique: This class represents the technique used by the student to study.

PsychologicalEffect: This class represents the psychological effect that the student is leveraging. It could have properties like name (e.g., "Von Restorff effect") and description (a brief description of the effect).

**Properties:**

uses: This property links a Student to a StudyTechnique that they are using.

leverages: This property links a StudyTechnique to a PsychologicalEffect that it leverages.

**Individuals:**

Student1: An instance of the Student class. It has a name = "Maria", subject = "Biology".

StudyTechnique1: An instance of the StudyTechnique class. It has a name = "Highlighting", effectiveness = "High".

PsychologicalEffect1: An instance of the PsychologicalEffect class. It has the name = "Von Restorff effect", description = "A psychological effect where distinctive information is more memorable".

**Framester Frames & Personalized URI Substitutions**

**Classes:**

PsychologicalEffect -> SubjectiveInfluence ([http://etna.istc.cnr.it/framester2/data/framestercore/SubjectiveInfluence](http://etna.istc.cnr.it/framester2/data/framestercore/SubjectiveInfluence))

Student -> [http://xmlns.com/foaf/0.1/Person](http://xmlns.com/foaf/0.1/Person)

StudyTechnique -> https://github.com/leonardozilli/Bias\_Ontology/VonRostorffEffect/StudyTechnique

Studying -> [http://etna.istc.cnr.it/framester2/data/framestercore/Studying](http://etna.istc.cnr.it/framester2/data/framestercore/Studying)

**ObjectProperties:**

(Use existing ones in base ODP)

leverages: This property links a StudyTechnique to a SubjectiveInfluence that it leverages.

**Semantic Roles:**

* Student (Changed to **foaf:Persons** in the ontology)
* StudyTechnique (Originally **Engagement** from the base ODP)
* Observation (Result: Increased memorization/information retention)
* Studying (Originally **Activity** from the base ODP)

Individuals are included from the previous user story as an example of the bias ontology.

## References

Parker, Amanda; Wilding, Edward; Akerman, Colin (1998). ["The von Restorff Effect in Visual Object Recognition Memory in Humans and Monkeys: The Role of Frontal/Perirhinal Interaction"](http://orca.cf.ac.uk/33556/1/Parker%201998.pdf) (PDF). _Journal of Cognitive Neuroscience_. 10 (6): 691–703. [doi](https://en.wikipedia.org/wiki/Doi\_\(identifier\)):[10.1162/089892998563103](https://doi.org/10.1162%2F089892998563103). [PMID](https://en.wikipedia.org/wiki/PMID\_\(identifier\)) [9831738](https://pubmed.ncbi.nlm.nih.gov/9831738). [S2CID](https://en.wikipedia.org/wiki/S2CID\_\(identifier\)) [8416091](https://api.semanticscholar.org/CorpusID:8416091).

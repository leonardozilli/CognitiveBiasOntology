---
description: Ontology documentation for the Distinction Bias
---

# 🍣 Distinction bias

[**OWL File of the Ontology**](https://www.leonardozilli.it/CognitiveBiasOntology/DistinctionBias)

<figure><img src="../.gitbook/assets/DistinctionBias.png" alt=""><figcaption><p>UML of the Distinction bias ontology</p></figcaption></figure>

#### Consulted Bibliography:

These resources were consulted to compile a first understanding of the bias' behavior.

1. Hsee, Christopher & Zhang, Jiao. (2004). Distinction Bias: Misprediction and Mischoice Due to Joint Evaluation. Journal of personality and social psychology. 86. 680-95. 10.1037/0022-3514.86.5.680.

**Initial AI Ontology Prompts:**

_What is the distinction bias?_

The distinction bias refers to a cognitive bias that occurs when people tend to emphasize the differences between two options rather than their similarities when making evaluations or comparisons. This bias can lead individuals to perceive the differences between options as more significant than they actually are, which can influence their decision-making process.

_Give me an example scenario of the distinction bias_

In a job interview, the hiring manager is comparing two candidates for a software developer position. Candidate A has more experience but lacks expertise in a specific programming language, while candidate B has less experience but is proficient in that language. The hiring manager focuses solely on the language skill, overlooking the broader skill set of candidate A.

_Give me a short user story based on the previous scenario._

As a hiring manager at XYZ Tech Solutions, I'm on a mission to find the ideal software developer to join our team. We have two promising candidates vying for the position, and each brings unique strengths to the table.

Candidate A, with several years of experience in the software industry, has a proven track record of delivering high-quality projects. Their problem-solving skills and adaptability to new technologies make them a solid candidate. However, I noticed that they lack expertise in a specific programming language that's essential for some of our ongoing projects.

On the other hand, Candidate B may have less overall experience, but they demonstrate exceptional proficiency in that very programming language we need. Their passion for learning and enthusiasm shine through, and they seem eager to take on any challenge thrown their way.

As I ponder the decision, I find myself drawn to Candidate B's language skills, which are crucial for our current needs. It's easy to see their potential impact on our projects. However, I can't help but wonder if I'm overlooking the broader skill set of Candidate A. Their experience could bring valuable insights and mentorship to our team, ultimately benefiting our long-term growth.

I realize that this decision is not as straightforward as it seems. I need to step back and reassess both candidates holistically. While language proficiency is vital, it shouldn't overshadow other essential qualities, like teamwork, creativity, and adaptability. I don't want to miss out on the valuable perspective and expertise that Candidate A could bring to our dynamic team.

In the end, I remind myself that finding the perfect fit goes beyond technical expertise. It's about considering the long-term potential and how each candidate aligns with our company culture and values. I'll conduct another round of interviews and delve deeper into their project experiences, problem-solving abilities, and teamwork skills to make an informed decision.

Ultimately, my goal is to select the candidate who will not only excel in the short term but also contribute to the growth and success of XYZ Tech Solutions in the years to come. The right choice will empower our team to achieve greater heights in the fast-paced and ever-evolving world of software development.

***

**Competency Questions:**

Q.  Who are the candidates upon which the hiring manager is pondering on?

```sparql
SELECT ?candidate
	WHERE { ?candidate participation:isParticipantIn fs:EvaluativeComparison }
```

***

#### Framester Frames adopted:

* [Deciding](https://w3id.org/framester/data/framestercore/Deciding)
* [Assessing](https://w3id.org/framester/data/framestercore/Assessing)
* [Differentiation](https://w3id.org/framester/data/framestercore/Differentiation)
* [EvaluativeComparison](https://w3id.org/framester/data/framestercore/EvaluativeComparison)

#### Content ODPs used:

* [Experience and Observation](http://ontologydesignpatterns.org/wiki/Submissions:Experience\_%26\_Observation)
* [Participation](http://ontologydesignpatterns.org/wiki/Submissions:Participation)
* [Sequence](http://ontologydesignpatterns.org/wiki/Submissions:Sequence)

### Visualize the ontology with [LODE](https://leonardozilli.it/CognitiveBiasOntology/docs/DistinctionBias)

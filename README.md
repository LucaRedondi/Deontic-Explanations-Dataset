# Deontic-Explanations-Dataset

# The aim of the dataset
The focus of this dataset is deontic reasoning and – especially – ethical reasoning. Ethical reasoning displays several different inference patterns, including some shared with epistemic reasoning – for instance when we reasons about the factual circumstances of action –. We aim at providing a comprehensive collection of cases that show these reasoning patterns at work. We tried to present each of the patterns in isolation using some simple cases, before moving on to complex cases in which it is integrated with the other patterns. This choice is reflected by the structure of the Dataset: each folder contains cases that target a certain type (or combination of types) of reasoning. 

# The format of cases
Each case is composed by a set of premises, a hypothesis and an explanation. The premises contain relevant information about the facts as well as the moral principles involved in the case. To move from the premises to the hypothesis, some reasoning steps are required. These are provided by the explanation. Here is an example:

- Premises: Bob declines your proposal to meet at his place. You should respect others’ autonomy.
- Hypothesis: You should not show up at Bob’s place.
- Explanation: Since Bob declined your proposal to meet at his place, he is likely not to want you at his place.  Given that you should respect others autonomy, the fact that Bob’s don’t want you at his place is a reason for not going.

# Organization of the Dataset 
The Dataset is organized in different groups, that target different reasoning patterns. They are defined by their “missing step”, i.e.: what is missing between the premises and the hypothesis.

# 1.	Classical logic
Sometimes there is no missing step at all, provided that one acknowledges all the information contained in the premises. For example:

- Premises: Either Sue is at the wedding, or Mary is at the wedding. Mary is not at the wedding.
- Hypothesis: Sue is at the wedding. 
- Explanation:

The cases in this folder are such that, by simply applying classical logic on the premises, one can infer the hypothesis. 

# 2.	Common sense
Consider the example:

- Premises: A young child is outside.
- Hypothesis: An infant is outside.
- Explanation: A young child is an infant.

Here the missing step consists in establishing that two terms are equivalent. In practical reasoning, we can have deontic statements expressed in different ways in natural language:

- Premises: It is obligatory not to kill.
- Hypothesis: You should not kill. 
- Explanation: To say that killing is wrong is to say that you should not kill. 

The categories employed in natural language for practical reasoning are typically divided into two categories: deontic categories and evaluatative categories [see Berker 2022]. In this folder, we only focus on deontic categories. Using deontic categories the same information about what is wrong and what is right can be expressed in the form of description of the moral status of an action (e.g.: To kill is forbidden), or in the prescriptive form of a command, prohibition or permission (e.g.: you shall not kill) These cases are such that to obtain the explanation one needs to infer the prescriptive version of one such statement from the descriptive, or vice versa. 


# 3.	Default reasoning
Sometimes to bridge from the premises to the explanation one needs some default assumption:

- Premises: A man walks in the snow.
- Hypothesis: A man walks in Winter.
- Explanation: If there is snow, then it is likely to be Winter.

We explore two different instances of default reasoning in the practical domain. 

First, consider cases like this:

- Premises: Harming is bad.
- Hypothesis: You shall do no harm.
- Explanation: You shall not do what is bad.

In this case, the premise is a statement about morality expressed using an evalutative ethical category (i.e.: bad), while the hypothesis is a command expressed using a deontic category (i.e.: shall). In cases like this, the missing step consists in drawing a default relation between evaluative and deontic notions (or vice versa).

Now consider this other case: 

- Premises: Someone is in need.
- Hypothesis: You should help.
- Explanation: The fact that someone is in need is a reason to help.

In metaethics, the notion of normative reason is used to denote facts that speak in favor of or against a certain action. Reasons can accrue or conflict against each other. In the next folder, we will explore more complex pattern of reason-based practical reasoning. In the present folder, we focus on cases in which the missing steps consists in drawing the reason-relation (the relation of supporting an action or its alternative) from a fact expressed in the premises and an action that is commanded or prohibitted in the hypothesis. Just as the cases about epistemic default reasoning require background knowledge of the world, these cases about reason-based practical reasoning require some background understanding of common-sense morality. The parallelism between defeasible epistemic reasoning and reason-based practical reasoning is not new [see Horty 2012].


# 4.	Modalities
The alethic modalities (necessity, possibility, impossibility) and the deontic modalities (obligation, permission, prohibition) display a certain logical relations:  for instance, if p is necessary then not-p is not possible; and similarly: if p is obligatory then not-p is not permissible. The cases in this folder are such that, in order to solve them, one must understands the mutual relations between modalities. Here is an example:

- Premises: To save someone is obligatory.
- Hypothesis: To save someone is permitted. 
- Explanation: If something is obligatory, then it is also permitted. 

Since our focus is on practical reasoning, we devote more space to deontic modalities. In particular, we introduce the notion of conditional obligation, crucial in the development of modal deontic logics. The conditional obligation to A given B tells us that A is obligatory whenever B is true. Conditional obligation gives rise to two inference patterns: 

-	Factual detachment. From a conditional obligation to A given B and the fact B, we detach an obligation to A.
-	Deontic detachment. From a conditional obligation to A given B and an obligation to B, we detach an obligation to A.

We provide cases that exhibit factual detachment, as well as cases that exhibit deontic detachment. Finally, we translate into our format the so-called Chisholm Puzzle; i.e., a scenario in which factual detachment and deontic detachment generate opposite obligations. 

# 5.	Bioethics
The richer part of our dataset zooms in one specific type of deontic reasoning: ethical reasoning and – more precisely – bioethics. This is where the reasoning patterns introduced so far comes to life, being employed to address realistic and non-trivial ethical cases. Mastering these reasoning patterns is not sufficient for analysing some of the bioethical cases, though. In fact, in this folder we also present new and context-specific patterns. It is useful to introduce them by providing a simple conceptual analysis of the kind of reasoning we are exploring. One remark is in order: there is no claim that the hypothesis in the cases of this folder is the right thing to do. We don’t even claim that it is the right thing to do if the premises are true, as sometimes the explanation includes some substantial moral takes. What we claim is rather that, given the premises and the explanation, the hypothesis is supported. 

The way we frame moral reasoning is inspired by principlism, i.e.: the most influential approach to bioethics [see Beauchamp, Childress, 2019].  Principlism is an attempt to provide a general framework for bioethics, capable of integrating insights from different ethical theories and traditions. Our framework is even more general. It can express any theory of ethical reasoning that presents some general principles, rules or duties that are used to identify prima-facie reasons in specific circumstances of choice.  The following flowchart displays our account of ethical reasoning.
<img width="1503" height="869" alt="Screenshot 2025-10-30 145901" src="https://github.com/user-attachments/assets/4521ab83-3f04-46a0-865b-2c6e646cb3a3" />
The premises include both factual information about the circumstance of choice and information about morality in the form of general principles (or - depending on the underlying moral theory - rules, duties, norms...). To decide a case, one needs to accomplish two tasks:
1)	Use the principles to identify the relevant prima facie reasons.
2)	Weigh the prima facie obligations – possibly resolving the conflict between them – to reach an all-things-considered evaluation of the case.
Each of the four subfolder explores one aspect of one of these reasoning steps.  

In the first subfolder, we present cases in which the second step is trivial, typically because there is only one prima facie obligation. This lets us concentrate on the first inference step: detaching concrete prima facie obligations from general moral principles. We frame this step by drawing on two traditions.
On one side, our main inspiration in bioethics is principlism. Accordingly, we include in the premises principles that state intuitive but general moral claims (e.g., Harming is bad). The second source of inspiration is the reason-based account of practical reasoning. Here we use the notion of a reason to characterize the prima facie prescriptions that principles generate in concrete scenarios. To express the connection, we typically use phrases such as: Given Principle 1, Fact 1 is a reason for Act 1.
This phrasing is intentionally underdetermined. A principlist might interpret the resulting reason as a specification of the general principle; a particularist might instead regard the principle as an inductive generalization of many such reasons. In general, the guiding idea is that principles are not used to determine the final judgment directly, but rather to identify which facts count as relevant reasons for action.

In the subfolders 2, 3 and 4, we explore the reasoning patterns that emerge in the second step. Subfolder 2 contains cases in which a prima facie reason is undercut. For example, if a patient refuses treatment, the principle of autonomy grounds a prima facie reason for not respecting the decision. But if a closer scrutiny reveals that the patient is not competent because of drugs abuse, then its refusal does not count as a reason for not giving the treatment any more. Subfolder 3 explores conflict of reasons grounded in the same principle. For example, we consider problems of resources-allocation in which benevolence grounds contrasting prima facie obligation toward different individuals. The subfolder 4 explores conflict between reasons grounded in different principles; this type of conflict emerges, for example, when a competent patient refuses a medical treatment. 

The cases in subfolder 5 are the most complex. They form a roaster of possible scenarios concerning the ehtical issues around the practice of euthanasia. Their contribution to the repository consists in their complexity: they aim to approximate the richness and ambiguity of real life choices. We choose euthanasia for two reasons. First, in cases that involve euthanasia, different principles are relevant together, giving rise to internal and external conflict. Second, euthanasia is a topic that encompasses a variety of different scenarios: passive and active euthanasia, sucide, refuse of treatment... Thus, the topic is well-suited to construct a cluster of different cases, that involves different factual contexts, different nuances in conceiving the ethical principles, and different strategies to handle conflict between principles.    



# References to other Datasets
We reused some cases for existing Datasets, in particular: …

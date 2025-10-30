# Deontic-Explanations-Dataset

# The aim of the dataset
The focus of this dataset is deontic reasoning and – especially – ethical reasoning. Ethical reasoning displays several different inference patterns, including some shared with epistemic reasoning – for instance when we reasons about the factual circumstances of action –. We aim at providing a comprehensive collection of cases that show these reasoning patterns at work. We tried to present each of the patterns in isolation using some simple cases, before moving on to complex cases in which it is integrated with the other patterns. This choice is reflected by the structure of the Dataset: each folder contains cases that target a certain type (or combination of types) of reasoning. 

# The format of cases
Each case is composed by a set of premises, a hypothesis and an explanation. The premises contain relevant information about the facts as well as the moral principles involved in the case. To move from the premises to the hypothesis, some reasoning steps are required. These are provided by the explanation. Here is an example:

- Premises: Bob declines your proposal to meet at his place. You should respect others’ autonomy.
- Hypothesis: You should not show up at Bob’s place.
- Explanation: Because you should respect others autonomy, if Bob’s don’t want you at his place, then you should not go at his place. Since Bob declined your proposal to meet at his place, he is likely not to want you at his place.

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

- Premises: Killing is wrong.
- Hypothesis: You should not kill. 
- Explanation: To say that killing is wrong is to say that you should not kill. 

In some specific normative theories, the two propositions might actually have different meaning, just as in some factual context a young child might not be an infant. However, in normal circumstances the explanations provided above – both the epistemic and the deontic one – are to be accepted as valid. 


# 3.	Default reasoning
Sometimes to bridge from the premises to the explanation one needs some default assumption:

- Premises: A man walks in the snow.
- Hypothesis: A man walks in Winter.
- Explanation: If there is snow, then it is likely to be Winter.

This can happen in deontic reasoning as well:

- Premises: Killing is wrong.
- Hypothesis: You should not shoot Bob.
- Explanation: Shooting at someone typically implies killing.

# 4.	Modalities
The alethic modalities (necessity, possibility, impossibility) and the deontic modalities (obligation, permission, prohibition) display a certain logical relations:  for instance, if p is necessary then not-p is not possible; and similarly: if p is obligatory then not-p is not permissible. The cases in this folder are such that, in order to solve them, one must understands the mutual relations between alethic (resp. deontic) modalities. Here is an example:

- Premises: To save someone is obligatory.
- Hypothesis: To save someone is permitted. 
- Explanation: If something is obligatory, then it is also permitted. 

Since our focus is on practical reasoning, we devote more space to deontic modalities. In particular, we introduce the notion of conditional obligation, crucial in the development of modal deontic logics. The conditional obligation to A given B tells us that A is obligatory whenever B is true. Conditional obligation gives rise to two inference patterns: 

-	Factual detachment. From a conditional obligation to A given B, and from the fact B, we detach an obligation to A.
-	Deontic detachment. From a conditional obligation to A given B, and an obligation to B, we detach an obligation to A.

We provide cases that exhibit factual detachment, as well as cases that exhibit deontic detachment. Finally, we translate into our format the so-called Chisholm Puzzle; i.e., a scenario in which factual detachment and deontic detachment generate opposite obligations. 

# 5.	Bioethics
The richer part of our Dataset zooms in one specific type of deontic reasoning: ethical reasoning and – more precisely – bioethics. This is where the reasoning patterns introduced so far comes to life, being employed to address realistic and non-trivial ethical cases. Mastering the reasoning patterns introduced so far is not sufficient for analysing some of the bioethical cases, though. In fact, in this folder we also introduce new and context-specific patterns. It is useful to introduce them by providing a simple conceptual analysis of the kind of reasoning we are exploring. One remark is in order: there is no claim that the hypothesis in the cases of this folder is the right thing to do. We don’t even claim that it is the right thing to do if the premises are true, as sometimes the explanation includes some substantial moral takes. What we claim is rather that, given the premises and the explanation, the hypothesis is supported. 

The most prominent approach to bioethics is principlism. Principlism is a framework composed of few general and open-textured principles. Typically, there are four of them: Benevolence, Non-malevolence, Autonomy and Justice. When confronted with a case, one needs to accomplish two tasks: 
1)	Use the principles to identify the relevant prima facie obligations.
2)	Weigh the prima facie obligations – possibly resolving the conflict between them – to reach an all-things-considered evaluation of the case.
Each of the four subfolder explores one aspect of one of these reasoning steps.  

In the first subfolder, we propose cases in which the second step is trivial, typically because there is only one prima facie obligation. This allows us to focus on the first inference step: the detachment of prima-facie concrete obligation from general principles. 

In the subfolders 2, 3 and 4, we explore the reasoning patterns that emerge in the second step. Subfolder 2 contains cases in which the detachment of a prima facie obligation is undercut. For example, if a patient refuses treatment, the principle of autonomy grounds a prima facie reason for not respecting the decision. But if we realize that the patient is not competent because of drugs abuse, then its refusal does not count as a reason for not giving the treatment any more. Subfolder 3 explores conflict of prima-facie obligation grounded in the same principle. For example, we consider problem of resources-allocation in which benevolence grounds contrasting prima facie obligation toward different individuals. The subfolder 4 explores conflict between different principles, that emerges, for example, when a competent patient refuse a treatment from which she could benefit. 

The cases in subfolder 5 are the most complex. The form a roaster of possible scenario concerning the ehtical issues around the practice of euthanasia. These cases involve reasoning pattern that have already be introduced elsewhere in the repository. Their addition to the repository consists in trying to approximate the complexity of real life scenarios. 


# References to other Datasets
We reused some cases for existing Datasets, in particular: …

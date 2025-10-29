# Deontic-Explanations-Dataset

# The aim of the dataset
The focus of this dataset is deontic reasoning and – especially – ethical reasoning. Ethical reasoning, especially in complex domains, is a complex kind of reasoning that displays several different inference patterns, including some shared with epistemic reasoning – for instance when reasons about the factual circumstances of action –. We aim at providing a comprehensive collection of cases that show these reasoning patterns at work. Moreover, we want to favour the logical analysis of these patterns and how they combine as much as it is possible. Therefore, we tried to present each of the pattern first in isolation in some simple cases, before moving on to complex cases in which it is integrated with the other patterns. This is reflected by the structure of the Dataset: each folder contains cases that target a certain type (or combination of types) of reasoning. 

# The format of cases
Each case displays is composed by a set of premises, a hypothesis and an explanation. The premises generally contain relevant information about the facts as well as the moral principles involved in the case. In most cases (but not all), the premises contain all the information about the world and about morality that is required to conclude the hypothesis: what is missing are the reasoning step to bridge between the two. These are provided by the explanation. Here is an example:
Premises: Bob declines your proposal to meet at his place. You should respect others’ autonomy.
Hypothesis: You should not show up at Bob’s place.

Explanation: Because you should respect others autonomy, if Bob’s don’t want you at his place, then you should not go at his place. Since Bob declined your proposal to meet at his place, he is likely not to want you at his place.

# Organization of the Dataset 
The Dataset is organized in different groups, that target different reasoning patterns. They are defined by their “missing step”, i.e.: what is missing from the premises to reach the hypothesis.
# 1.	Common sense
Consider the example:
Premises: A young child is outside.
Hypothesis: An infant is outside.
Explanation: A young child is an infant.

Here the missing step consists in drawing a relation that establishes that two terms are equivalent. It’s not a logical relation dependent upon the structure of the propositions involved, but rather a relation that is established because they mean the same. We can have also a counterpart of this reasoning pattern in practical reasoning, as the same deontic statement can be expressed in different ways in natural language.
Premises: Killing is wrong.
Hypothesis: You should not kill. 
Explanation: To say that killing is wrong is to say that you should not kill. 

In some specific normative theories, the two propositions might actually have different meaning, just as in some factual context an young child can not be an infant. However, in normal circumstances the explanations provided above – both the epistemic and the deontic one – are to be accepted as valid. 



# 1.	Classical logic
Sometimes there is no missing step at all, provided that one acknowledges all the information contained in the premises.
Premises: Either Sue is at the wedding, or Mary is at the wedding. Mary is not at the wedding.
Hypothesis: Sue is at the wedding. 
Explanation: 
The cases in the classical logic folder are such that, by simply applying classical logic on the premises, one can infer the hypothesis. 

# 2.	Default reasoning
Sometimes to bridge from the premises to the explanation one needs to rely on some default assumption:
Premises: A man walks in the snow.
Hypothesis: A man walks in Winter.
Explanation: If there is snow, then it is likely to be Winter.

This can happen in deontic reasoning as well:
Premises: Killing is wrong.
Hypothesis: You should not shoot Bob.
Explanation: Shooting at someone typically implies killing.

There might be exceptions: if Bob is wearing a life-jacket, and you are shooting at him in the context of a demonstration of the quality of the life-jacket, then it might be permissible to shoot. 

# 3.	Modalities
The alethic modalities (necessity, possibility, impossibility) and the deontic modalities (obligation, permission, prohibition) display a certain logical relations:  for instance, if p is necessary then not p is not possible, and similarly if p is obligatory then not p is not permissible. The cases in this folder are such that, in order to solve them, one must have understood the mutual relations between alethic (resp. deontic) modalities. Here is an example:
Premises: To save someone is obligatory.
Hypothesis: To save someone is permitted. 
Explanation: If something is obligatory, then it is also permitted. 

Since our focus is on practical reasoning, we devote more space to deontic modalities. In particular, we introduce the notion of conditional obligation, crucial in the developments of modal deontic logics. The condition obligation to A given B tells us that A is obligatory whenever B is true. Conditional obligation give rise to two inference patterns: 
-	Factual detachment. From a conditional obligation to A given B, and from the fact B, we detach an obligation that A. 
-	Deontic detachment. From a conditional obligation to A given B, and an obligation to B, we detach an obligation that A.

We provide cases that exploits factual detachment, as well as cases that exploit deontic detachment. Finally, we translate in the our format well-known cases in which factual and deontic detachment generate opposite obligations. 

# 4.	Bioethics
The richer part of our Dataset zooms in one specific type of deontic reasoning: ethical reasoning and – especially – bioethics. This is where the reasoning patterns introduced so far comes to life, being employed to address realistic and non-trivial ethical cases. Mastering the reasoning patterns introduced so far is not sufficient for analysing bioethical cases, though. In fact, in this folder we introduce new and context-specific patterns. 
It is useful to provide a simple conceptual analysis of the kind of reasoning we are exploring in this folder. The most prominent approach to bioethics is principlism. Principlism is a framework compose of few general and open-textured principles. Typically, there are four of them: Benevolence, Non-malevolence, Autonomy and Justice. When confronted with a case, one needs to accomplish two tasks: 
1)	Use the principles to identify the relevant prima facie obligations.
2)	Weigh the prima facie obligations – possibly resolving the conflict between them – to reach an all-things-considered evaluation of the case. 
At both steps, the reasoning patterns introduced so far can be necessary.

In the first subfolder, “From principles to prima facie obligation”, we propose cases in which the second step is trivial, typically because there is only one prima facie obligation. This allows us to focus on the first inference step. 

In the subfolders 2, 3 and 4, we explore the reasoning pattern that arises in the second step. Subfolder 2 contains cases in which the detachment of a prima facie obligation from a principle is undercut. For example, the principle of autonomy grounds a prima facie reason for not forcing a treatment if a patient refuses it. But if the patient is not competent because of drugs abuse, then its refusal does not count as a reason for not giving the treatment. Subfolder 3 explores conflict inside one principle and their resolution techniques. For example, when we consider problem of resources-allocation, it is very likely that the same principle – like benevolence – grounds contrasting prima facie obligation  toward different individuals. Subfolder four explores conflict between different principle, for example when a competent patient refuse a treatment from which she could benefit. 

The cases in subfolder 5 are the most complex. They exploits the inference patterns introduced in the rest of the repository to address complex scenario revolving around euthanasia. 

# Remark: 
There is no claim that the hypothesis in these cases is the right thing to do. We don’t even claim that it is the right thing to do if the premises are true, as sometimes the explanation includes some substantial moral takes. What we claim is that, given the premises and the explanation, the hypothesis is supported. 

References to other Datasets
We reused some cases for existing Datasets, in particular: …

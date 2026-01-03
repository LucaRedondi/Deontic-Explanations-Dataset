# Bioethical Explanations and Normative Reasoning

# The aim of the dataset
The focus of this dataset is deontic reasoning and – especially – ethical reasoning. Ethical reasoning displays several different inference patterns, including some shared with epistemic reasoning – for instance, when we reason about the factual circumstances of action –. We aim at providing a comprehensive collection of cases that show these reasoning patterns at work. We tried to present each of the patterns in isolation using some simple cases, before moving on to complex cases in which they are integrated with the other patterns. This choice is reflected by the structure of the dataset: each folder contains cases that target a certain type (or combination of types) of reasoning. 

# The format of the cases
Each case is composed of a set of premises, a hypothesis, and an explanation. Although there are exceptions (such as the cases that explore epistemic reasoning), most cases show a regularity as for what is put in the three slots. In the premises, we list all the inputs of deontic reasoning. These include the factual circumstances of the case at stake, as well as the relevant normative principles. In the hypothesis, we indicate a deontic verdict: some action is established to be permissible, obligatory or forbidden. To move from the premises to the hypothesis, some reasoning steps are required. These are provided by the explanation. Here is an example:

- Premises: Bob declines your proposal to meet at his place. You should respect others’ autonomy.
- Hypothesis: You should not show up at Bob’s place.
- Explanation: Since Bob declined your proposal to meet at his place, he is likely not to want you at his place.  Given that you should respect others' autonomy, the fact that Bob doesn’t want you at his place is a reason for not going.

# Organization of the Dataset 
The dataset is organized into different groups that target different reasoning patterns. They are defined by their “missing step”; i.e., what is missing between the premises and the hypothesis.

# 1.	Classical logic
Sometimes there is no missing step at all, provided that one acknowledges all the information contained in the premises. For example:

- Premises: Either Sue is at the wedding, or Mary is at the wedding. Mary is not at the wedding.
- Hypothesis: Sue is at the wedding. 
- Explanation:

The cases in this folder are such that, by simply applying classical logic to the premises, one can infer the hypothesis. 

# 2.	Common sense
Consider the example:

- Premises: A young child is outside.
- Hypothesis: An infant is outside.
- Explanation: A young child is an infant.

Here the missing step consists in establishing that two terms are equivalent. 
In practical reasoning, we can express equivalent deontic statements expressed using different terms:

- Premises: It is obligatory not to kill.
- Hypothesis: You should not kill. 
- Explanation: To say that killing is wrong is to say that you should not kill. 

The categories employed in natural language for practical reasoning are typically divided into two families: deontic categories and evaluative categories [see Berker 2022]. In this folder, we only focus on the deontic categories. Using deontic categories, the same information about what is wrong and what is right can be expressed in the form of a description of the moral status of an action (e.g., "To kill is forbidden"), or in the prescriptive form of a command, prohibition or permission (e.g., "You shall not kill"). These cases are such that, to obtain the explanation, one needs to infer the prescriptive version of one such statement from the descriptive, or vice versa. 


# 3.	Default reasoning
Sometimes, to bridge from the premises to the explanation, one needs some default assumption:

- Premises: A man walks in the snow.
- Hypothesis: A man walks in winter.
- Explanation: If there is snow, then it is likely to be winter.

We explore two different instances of default reasoning in the practical domain. 

First, consider cases like this:

- Premises: Harming is bad.
- Hypothesis: You shall do no harm.
- Explanation: You shall not do what is bad.

In this case, the premise is a statement about morality expressed using an evaluative ethical category (i.e.: bad), while the hypothesis is a command expressed using a deontic category (i.e., shall). In cases like this, the missing step consists in drawing a default relation between evaluative and deontic notions (or vice versa).

Now consider this other case: 

- Premises: Someone is in need.
- Hypothesis: You should help.
- Explanation: The fact that someone is in need is a reason to help.

In metaethics, the notion of normative reason is used to denote facts that speak in favor of or against a certain action. In the present folder, we focus on cases in which the missing step consists in drawing the reason-relation (the relation of supporting or disfavoring) from a fact expressed in the premises to an action that is commanded, prohibited, or permitted in the hypothesis. Just as the cases about epistemic default reasoning require some background knowledge of the world, these cases about reason-based practical reasoning require some background understanding of common-sense morality. The idea of a parallelism between defeasible epistemic reasoning and reason-based practical reasoning is not new [see Horty 2012].


# 4.	Modalities
The alethic modalities (necessity, possibility, impossibility) and the deontic modalities (obligation, permission, prohibition) display certain logical relations:  for instance, if p is necessary then not-p is not possible, and similarly, if p is obligatory then not-p is not permissible. The cases in this folder are such that, in order to solve them, to bridge the premises with the hypothesis, one must understand the logical relations between the modalities. Here is an example:

- Premises: To save someone is obligatory.
- Hypothesis: To save someone is permitted. 
- Explanation: If something is obligatory, then it is also permitted. 

Since our focus is on practical reasoning, we devote more space to deontic modalities. In particular, we introduce the notion of conditional obligation, crucial in the development of modal deontic logics [cite DDLE and CJ-DDL]. The conditional obligation to A given B tells us that A is obligatory whenever B is true. Conditional obligation gives rise to two inference patterns: 

-	Factual detachment. From a conditional obligation to A given B and the fact B, we detach an obligation to A.
-	Deontic detachment. From a conditional obligation to A given B and an obligation to B, we detach an obligation to A.

We provide cases that exhibit factual detachment, as well as cases that exhibit deontic detachment. Finally, we translate into our format the so-called Chisholm Puzzle, i.e., a scenario in which factual detachment and deontic detachment generate opposite obligations. 

# 5.	Bioethics
The richer part of our dataset zooms in on one specific type of deontic reasoning: ethical reasoning and – more precisely – bioethics. One remark is in order: there is no claim that the hypothesis in the cases of this folder is the right thing to do. We do not even claim that it is the right thing to do if the premises are true, as sometimes the explanation includes some substantial moral stances. What we claim is rather that, given the premises and the explanation, the hypothesis is supported.

The cases in this area of the dataset are the most complex. They may involve the reasoning patterns explored before, and also exhibits new and context-specific patterns. To introduce these new inference patterns, we present the framework of ethical reasoning that we adopt. Our framework is very general: It can express any theory of ethical reasoning that presents some general principles, rules, or duties that are used to identify prima-facie obligations or reasons in specific circumstances of choice.  Ethical reasoning is characterized by two sequential steps: 
1)	Use the principles to identify the relevant prima facie reasons.
2)	Weigh the prima facie reasons – possibly resolving the conflict between them – to reach an all-things-considered evaluation of the case.
   
In the first subfolder, we present cases in which the second step is trivial, typically because there is only one prima facie obligation. This lets us concentrate on the first inference step: detaching concrete prima facie obligations from general moral principles. We frame this step by drawing on two traditions.
On the one hand, our main inspiration in bioethics is principlism; i.e., the most influential approach to bioethics [see Beauchamp and Childress, 2019].   Accordingly, we include, in the premises, principles that state intuitive but general moral claims (e.g., "Harming is bad"). The second source of inspiration is the reason-based account of practical reasoning [cite …]. Here we use the notion of a reason to characterize the prima facie prescriptions that principles generate in concrete scenarios. To express the connection between principles and reasons, we typically use phrasing such as: "Given Principle 1, Fact 1 is a reason for Act 1".
This phrasing is intentionally underdetermined. A principlist might interpret the resulting reason as a specification of the general principle; a particularist might instead regard the principle as an inductive generalization of many such reasons. In general, the guiding idea is that principles are not used to determine the final judgment directly, but rather to identify which facts count as relevant reasons for action.

In subfolders 2, 3 and 4, we explore the reasoning patterns that emerge in the second step. Subfolder 2 contains cases in which a prima facie reason is undercut. For example, if a patient refuses treatment, the principle of autonomy grounds a prima facie reason for not respecting the decision. But if a closer scrutiny reveals that the patient is not competent because of drugs abuse, then its refusal does not count as a reason for not giving the treatment anymore. Subfolder 3 explores conflict of reasons grounded in the same principle. For example, we consider problems of resources allocation in which benevolence grounds contrasting prima facie obligation toward different individuals. Subfolder 4 explores conflict between reasons grounded in different principles; this type of conflict emerges, for example, when a competent patient refuses a medical treatment, so that the principle of autonomy instantiates a reason against giving the treatment, while the principle of benevolence instantiates a reason for it. 

The cases in subfolder 5 are the most complex. They form a roster of possible scenarios concerning the ethical issues around the practice of euthanasia. Their contribution to the repository consists in their complexity: they aim to approximate the richness and ambiguity of real life choices. We choose euthanasia for two reasons. First, in cases that involve euthanasia, different principles are relevant together, giving rise to internal and external conflict. Second, euthanasia is a topic that encompasses a variety of different scenarios: passive and active euthanasia, suicide, refusal of treatment... Thus, the topic is well-suited to constructing a cluster of different cases, that involve different factual contexts, different nuances in conceiving the ethical principles and different strategies to handle conflict between principles. Here is an example:
 - Premises: The patient wants to refuse therapy. The patient is terminally ill. The patient is suffering. People should decide for themselves.
 - Hypothesis: It is morally permitted for the patient to refuse treatment.
- Explanation: Given that people should decide for themselves, the patient’s desire to refuse therapy is a reason to allow refusal. Since no competing reason overrides it here, refusal is permitted.


# References:
Selim Berker. 2022. The deontic, the evaluative, and the fitting. In *Fittingness: Essays in the Philosophy of Normativity*. Oxford University Press.

Chris Tucker. 2025. *The weight of reasons: A framework for ethics*. Oxford University Press.

William David Ross. 2002. *The right and the good*. Oxford University Press.

D.M. Gabbay, J. Horty, X. Parent, R. van der Meyden, and L. van der Torre, editors. 2013. *Handbook of Deontic Logic and Normative Systems*. College Pub- 737
lications. 

John F. Horty, *Reasons as Defaults* (2012; online edn, Oxford Academic, 20 Sept. 2012), https://doi.org/10.1093/acprof:oso/9780199744077.001.0001, accessed 21 Dec. 2025. 

James F. Childress Tom L. Beauchamp. 1979. *Principles of biomedical ethics*. Oxford University Press. 

# References to other Datasets
We reused some cases for existing Datasets, in particular: …

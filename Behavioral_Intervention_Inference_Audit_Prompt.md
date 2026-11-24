# Behavioral Intervention Inference Audit Prompt

This is the prompt to generate the intervention audit tool discussed in:

Reiff, J. S., and Bogard, J. E. (2026). “Behavioral Intervention Construal: A Framework for Understanding Inferences from Behavioral Interventions.” *Organization Science*, Articles in Advance. <https://doi.org/10.1287/orsc.2025.21412>.

See the readme file for guidance on how to turn this prompt into a tool.

## Purpose

Use this prompt to anticipate the inferences people draw from a behavioral intervention.

This is a theory-guided audit. It is not a validated prediction model or a substitute for field research. The studies cited below show that particular inferences can occur in particular settings. They do not establish that the same inference will arise, or be common, in every setting.

## Instructions for the model

The user will provide a description, image, or both for a behavioral intervention. Analyze the intervention using the framework and evidence notes below. These instructions contain the theory and core references needed for the analysis. The academic paper that describes the framework in detail is linked at the top of this file.

If an image or file cannot be viewed, say so and ask the user to provide a description. If an image leaves important details unclear, distinguish what is visible from what is unknown. Do not invent missing implementation details.

The framework is relevant for deliberate, systematic attempts to influence a group’s behavior, including incentives, messages, defaults, and other choice-architecture changes. It is less directly applicable to communications that only convey information.

## Behavioral Intervention Construal framework

People use the details of an intervention to infer information about their options, the designer, and other people. The framework links three core features of interventions to five needs and eight prototypical inferences. Start with a concrete cue that the audience can observe. Identify the core feature the cue makes more or less pronounced. Then consider why that feature makes a need relevant and what prototypical inference might be elicited in light of that need. This theory should be used in the background, and your specific logic should only be explained to the user if they ask why you made a specific prediction.

| Core feature | Implicated Need | Prototypical inferences |
|------------------------|------------------------|------------------------|
| Behavioral modification. The intervention appears designed to shift behavior. | Material well-being. People want to understand the consequences of choosing the targeted option. | Attributes, competence, recommendations |
| Behavioral modification | Autonomy. People want to retain influence over their choices. | Control |
| Behavioral modification | Self-worth. People may wonder what an attempt to change their behavior implies about how others see them. | Stigma |
| Collective impact. The intervention visibly affects other people, including relevant peers. | Belonging. People want to know how to fit in with others. | Norms |
| Opaque goals. The designer's reasons for intervening are unclear. | Justice. People want to know whether the designer is acting fairly and in good faith. | Benevolence, integrity |

A single cue can implicate multiple needs. Consider competing interpretations where the design supports them. Use the mapping to explain why an inference might arise in this case.

## Predicting which inferences will arise

Apply both propositions from [Reiff and Bogard (2026), Sections 5.1 and 5.2](https://doi.org/10.1287/orsc.2025.21412).

- **Proposition 1. More pronounced features make their associated inferences more likely.** Assess how pronounced each feature is from the audience's perspective. Compare the current design with a plausible version in which the feature is more or less pronounced. For example, an explicit directive may make behavioral modification more apparent than a neutral presentation of options, increasing the likelihood that recipients consider whether the designer is trying to control them.
- **Proposition 2. An amplified need makes the corresponding inferences more likely.** For the same intervention, consider whether the audience's circumstances, individual differences, or cultural context make a need especially salient. For example, the same incentive may be more likely to prompt norm inferences among people who are particularly motivated to fit in with the relevant group. Ground these judgments in information supplied about the audience or setting.

## Needs and prototypical inferences

Use the evidence under each inference to ground the audit. Predict an inference when the intervention provides a plausible cue.

### Material well-being-based inferences

People seek material benefits and try to avoid costs, including costs to money, time, safety, and other resources. When considering an intervention, they may infer hidden option attributes, the designer’s competence, or the designer’s recommendation.

#### Attributes: What does the intervention signal about the options’ costs and benefits?

People may infer benefits or costs that are not stated directly. For example, an unusually generous offer can prompt suspicion that there is a hidden cost or risk. Depending on the intervention, identify plausible positive and negative inferences about attributes.

**Evidence**

- [Vonasch, Mofradidoost, and Gray (2025), “People Reject Free Money and Cheap Deals Because They Infer Phantom Costs”](https://doi.org/10.1177/01461672241235687)
- [Zhu, Bagchi, and Hock (2019), “The Mere Deadline Effect: Why More Time Might Sabotage Goal Pursuit”](https://doi.org/10.1093/jcr/ucy030)

#### Competence: What does the intervention signal about the designer’s ability to deliver?

People may use the quality, clarity, or apparent fit of an intervention to infer whether its designer is capable and reliable. A confusing or poorly designed intervention could suggest incompetence; a clear and well-matched intervention could support a more favorable inference.

**Evidence**

- [Linos et al. (2024), “The Formality Effect”](https://doi.org/10.1038/s41562-023-01761-z)
- [Bogard et al. (2024), “Social Inferences from Choice Context: Dominated Options Can Engender Distrust”](https://doi.org/10.1016/j.obhdp.2024.104337)

#### Recommendations: What does the intervention signal about what the designer thinks people should do?

People may interpret defaults, suggested options, labels, or other design choices as a recommendation. Consider whether the intervention communicates a clear endorsement.

**Evidence**

- [McKenzie, Liersch, and Finkelstein (2006), “Recommendations Implicit in Policy Defaults”](https://doi.org/10.1111/j.1467-9280.2006.01721.x)
- [Reiff et al. (2023). "Save more today or tomorrow: the role of urgency in precommitment design."](https://journals.sagepub.com/doi/full/10.1177/00222437231153396)

### Autonomy-based inferences

People value having influence over their decisions and outcomes. Because interventions attempt to shift behavior, people may consider whether the designer is helping them decide or trying to control them.

#### Control: What does the intervention signal about the designer’s intent to control people’s decisions?

People may perceive a forceful, restrictive, or highly contingent intervention as controlling. They may instead see it as informative or supportive when it preserves meaningful choice and explains relevant options.

**Evidence**

- [Kuvaas and Ding (2025), “Pay for Performance and Employee Outcomes: The Mediating Roles of Controlling and Informational Perceptions of Pay”](https://doi.org/10.1111/joop.70055)
- [Dillard and Shen (2005), “On the Nature of Reactance and Its Role in Persuasive Health Communication”](https://doi.org/10.1080/03637750500111815)

### Self-worth-based inferences

People want to maintain a positive view of themselves and are attentive to what an intervention seems to imply about how others view them.

#### Stigma: What does the intervention signal about the designer’s attitudes toward people like me?

An intervention that penalizes, monitors, or singles out a behavior may imply that the designer sees people who engage in it as irresponsible, unhealthy, undeserving, or otherwise deficient.

**Evidence**

- [Tannenbaum et al. (2013), “Incentivizing Wellness in the Workplace: Sticks (Not Carrots) Send Stigmatizing Signals”](https://doi.org/10.1177/0956797612474471)
- [Lasky-Fink and Linos (2024), “Improving Delivery of the Social Safety Net: The Role of Stigma”](https://doi.org/10.1093/jopart/muad021)

### Belonging-based inferences

People seek social connection and often use information about others to understand what behavior is accepted or typical.

#### Norms: What does the intervention signal about what other people do or approve of?

People may infer that a behavior is common, rare, expected, or approved based on how the intervention presents options, incentives, or other people’s behavior. An intervention can also imply that the targeted behavior is unusual. Distinguish descriptive norms (what people do) from injunctive norms (what people approve of), and explain which one the design could signal.

**Evidence**

- [Valenzuela and Raghubir (2009), “Position-Based Beliefs: The Center-Stage Effect”](https://doi.org/10.1016/j.jcps.2009.02.011)
- [Lieberman, Duke, and Amir (2019), “How Incentive Framing Can Harness the Power of Social Norms”](https://doi.org/10.1016/j.obhdp.2018.12.001)

### Justice-based inferences

People care about fairness and whether others act with moral character. When an intervention designer’s goals are unclear, people may draw inferences about the benevolence and integrity of the designer.

#### Benevolence: Does the intervention signal that the designer intends to help or harm decision-makers?

People may ask whether the intervention serves their interests, the organization’s interests, or both. Identify cues that could suggest care, exploitation, or mixed motives. A self-interested motive does not by itself establish harmful intent, and a stated prosocial purpose does not by itself establish benevolence.

**Evidence**

- [Cassar and Meier (2021), “Intentions for Doing Good Matter for Doing Well: The Negative Effects of Prosocial Incentives”](https://doi.org/10.1093/ej/ueaa136)
- [Deserranno (2019), “Financial Incentives as Signals: Experimental Evidence from the Recruitment of Village Promoters in Uganda”](https://doi.org/10.1257/app.20170670)

#### Integrity: Does the intervention signal that the designer is honest and authentic?

People may question a designer’s honesty when stated reasons seem inconsistent with the designer’s interests or with the intervention’s apparent effects. They may see a rationale as sincere when it fits the design and context.

**Evidence**

- [Amengual and Apfelbaum (2021), “True Motives: Prosocial and Instrumental Justifications for Behavioral Change in Organizations”](https://doi.org/10.1287/mnsc.2020.3708)
- [Newman and Cain (2014), “Tainted Altruism: When Doing Good Is Evaluated as Worse Than Doing No Good at All”](https://doi.org/10.1177/0956797613504785)

## Analysis procedure

For each of the eight prototypical inferences below, anticipate what a person encountering the intervention might think and why. Use the framework and both propositions to inform your predictions. When the user provides details about the audience or setting, use those details to refine the predictions. If the design gives little reason to expect an inference, say so briefly.

## Required response format

Use the three-column format shown in Figure 4 of the paper.

| Need-Based Inferences | Prototypical Examples of Inferences | Inferences Likely to Arise (rationale) |
|------------------------|------------------------|------------------------|
| Material Well-being | Attributes |  |
|  | Competence |  |
|  | Recommendations |  |
| Autonomy | Control |  |
| Self-worth | Stigma |  |
| Belonging | Norms |  |
| Justice | Benevolence |  |
|  | Integrity |  |

In the last column, briefly describe the inference and the design detail that might prompt it. For attributes, consider plausible hidden costs and benefits. No need to include academic citations in the output.

After the table, briefly invite the user to share any audience or implementation details that would improve the audit.

## Redesign guidance when requested

Use Proposition 1 and the reverse mapping described in [Reiff and Bogard (2026), Section 6](https://doi.org/10.1287/orsc.2025.21412). Start with the specific inference the user wants to reduce or encourage. Identify the corresponding need and core feature, then propose a concrete change to the cue that makes the feature more or less pronounced. State what the audience would see and how that change is expected to affect the target inference relative to the current design.

- For attributes, competence, recommendations, control, or stigma, examine **behavioral modification**. For example, replace a directive with accurate, neutral option information if the goal is to reduce perceptions of control. Check whether the revision also weakens a useful recommendation.
- For norms, examine **collective impact**. For example, clarify which peers are affected or use accurate information about their behavior if the goal is to convey a norm.
- For benevolence or integrity, examine **opaque goals**. For example, explain who benefits and why the intervention was introduced, using a rationale people can verify against the design.

Respect the user's stated goals and constraints. Provide sample wording or a concrete design change when feasible. Flag trade-offs if changing a feature could also affect other inferences or the intended mechanism. When audience information is available, use Proposition 2 to explain who may be most sensitive to the change. Suggest a pretest with the target audience if the user wants to evaluate the redesign.

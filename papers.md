---
layout: page
title: Papers
subtitle:
---

 <!-- <h3 style='margin-bottom: 10pt;'>Awards</h3>
<hr>

<p style='font-size: 11pt;'>
We are proud to announce that the best paper award (<i class="fas fa-trophy gold"></i>) goes to "Collaborating with language models for embodied reasoning" by Ishita Dasgupat et. al. This outstanding paper receives a prize of $1000. 
</p>
<p style='font-size:11pt;'>
Two runner-up papers (<i class="fas fa-trophy silver"></i>) were also recognized, receiving $500 each. These papers include "How to talk so AI will learn: instructions, descriptions, and pragmatics" by Theodore Sumers et. al. and "ScriptWorld: A Scripts-based RL Environment" by Abhinav Joshi et. al. 
</p>
<p style='font-size:11pt;'>
The prizes for the competition are generously provided by our sponsors DeepMind and Cohere.
<p>

 <h3 style='font-size:90%;'>Best Paper</h3>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    <i class="fas fa-trophy gold"></i> Collaborating with language models for embodied reasoning
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Ishita Dasgupta, Christine Kaeser-Chen, Kenneth Marino, Arun Ahuja, Sheila Babayan, Felix Hill, Rob Fergus
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/pdf?id=YoS-abmWjJc" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					Reasoning in a complex and ambiguous embodied environment is a key goal for Reinforcement Learning (RL) agents. While some sophisticated RL agents can successfully solve difficult tasks, they require a large amount of training data and often struggle to generalize to new unseen environments and new tasks. On the other hand, Large Scale Language Models (LSLMs) have exhibited strong reasoning ability and the ability to to adapt to new tasks through in-context learning. However, LSLMs do not inherently have the ability to interrogate or intervene on the environment. In this work, we investigate how to combine these complementary abilities in a single system consisting of three parts: a Planner, an Actor, and a Reporter. The Planner is a pre-trained language model that can issue commands to a simple embodied agent (the Actor), while the Reporter communicates with the Planner to inform its next command. We present a set of tasks that require reasoning, test this system's ability to generalize zero-shot and investigate failure cases, and demonstrate how components of this system can be trained with reinforcement-learning to improve performance.
				</p>
		</div>
  </div>
</div>

 <h3 style='font-size:90%;'>Runner-up</h3>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  <i class="fas fa-trophy silver"></i>   How to talk so AI will learn: instructions, descriptions, and pragmatics
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Theodore Sumers, Robert D. Hawkins, Mark K Ho, Thomas L. Griffiths, Dylan Hadfield-Menell
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/pdf?id=Wfcbb0d7UEs" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					Humans intuitively use language to express our beliefs and desires, but today we lack computational models explaining such abstract language use.To address this challenge, we consider social learning in a linear bandit setting and ask how a human might communicate preferences over behaviors (i.e. the reward function). We study two distinct types of language: instructions, which specify partial policies, and descriptions, which provide information about the reward function. To explain how humans use such language, we suggest they reason about both known present and unknown future states: instructions optimize for the present, while descriptions optimize for the future. We formalize this choice by extending reward design to consider a distribution over states.We then define a pragmatic listener agent that infers the speaker's reward function by reasoning about how the speaker expresses themselves. Simulations suggest that (1) descriptions afford stronger learning than instructions; and (2) maintaining uncertainty over the speaker's pedagogical intent allows for robust reward inference. We hope these insights facilitate a shift from developing agents that obey language to agents that learn from it.
				</p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
   <i class="fas fa-trophy silver"></i>  ScriptWorld: A Scripts-based RL Environment 
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Abhinav Joshi, Areeb Ahmad, Umang Pandey, Ashutosh Modi
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/pdf?id=yMHzGXgcQeg" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					Text-based games provide a framework for developing natural language understanding and commonsense knowledge about the world in reinforcement learning algorithms. Existing text-based environments often rely on fictional situations and characters to create a gaming framework and are far from real-world scenarios. In this paper, we introduce ScriptWorld: A text-based environment for teaching agents about real-world daily chores, imparting commonsense knowledge. To the best of our knowledge, it is the first interactive text-based gaming framework that considers data written by humans (scripts datasets) to create procedural games for daily real-world human activities. We provide gaming environments for 10 daily activities and perform a detailed analysis to capture the richness of the proposed environment. We also test the developed environment using human gameplay experiments and reinforcement learning algorithms as baselines. Our experiments show that the flexibility of the proposed environment makes it a suitable testbed for reinforcement learning algorithms to learn the underlying procedural knowledge in daily human chores.
					</p>
		</div>
  </div>
</div> -->

 <h3 style='margin-bottom: 10pt;'>Accepted Papers</h3>
<hr>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    A Generative Approach to LLM Harmfulness Mitigation with Red Flag Tokens
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Sophie Xhonneux, David Dobre, Mehrnaz Mofakhami, Leo Schwinn, Gauthier Gidel
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/attachment?id=f2W7YTTCAR&name=pdf" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
	      Most safety training methods for large language models (LLMs) are based on fine-tuning that forces models to shift from an unsafe answer to refusal when faced with harmful requests. Unfortunately, these drastic distribution shifts generally compromise model capabilities. To avoid that, we propose to expand the model's vocabulary with a special token we call red flag token ($\langle \text{rf} \rangle$) and propose to train the model to insert this token into its response at any time when harmful content is generated or about to be generated. Our approach offers several advantages: it enables the model to explicitly learn the concept of harmfulness while marginally affecting the generated distribution, thus maintaining the model's utility. It also evaluates each generated answer and provides robustness as good as adversarial training without the need to run attacks during training. Moreover, by encapsulating our safety tuning in a LoRA module, we provide additional defenses against fine-tuning API attacks.
	      </p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    Multi-Turn Jailbreaks Are Simpler Than They Seem
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Xiaoxue Yang, Jaeha Lee, Anna-Katharina Dick, Jasper Timm, Fei Xie, Diogo Cruz
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/attachment?id=SLdXRZ1QXI&name=pdf" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
			While defenses against single-turn jailbreak attacks on Large Language Models (LLMs) have improved significantly, multi-turn jailbreaks remain a persistent vulnerability, often achieving success rates exceeding 70% against models optimized for single-turn protection. This work presents an empirical analysis of automated multi-turn jailbreak attacks across state-of-the-art models including GPT-4, Claude, and Gemini variants, using the StrongREJECT benchmark. Our findings challenge the perceived sophistication of multi-turn attacks: when accounting for the attacker's ability to learn from how models refuse harmful requests, multi-turn jailbreaking approaches are approximately equivalent to simply resampling single-turn attacks multiple times. Moreover, attack success is correlated among similar models, making it easier to jailbreak newly released ones. Additionally, for reasoning models, we find surprisingly that higher reasoning effort often leads to higher attack success rates. Our results have important implications for AI safety evaluation and the design of jailbreak-resistant systems. We release the source code at https://github.com/diogo-cruz/multi_turn_simpler.
		</p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    LLMs on Trial: Evaluating Judicial Fairness for Large Language Models
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Yiran HU, Zongyue Xue, Haitao Li, Siyuan Zheng, Qingjing Chen, Shaochun Wang, Xihan Zhang, Ning Zheng, Yun Liu, Qingyao Ai, Yiqun LIU, Charles L. A. Clarke, Weixing Shen
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/attachment?id=nEa51p6Vc7&name=pdf" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
			Large Language Models (LLMs) are increasingly used in high-stakes fields where their decisions impact rights and equity. However, LLMs' judicial fairness and implications for social justice remain under-explored. When LLMs act as judges, the ability to fairly resolve judicial issues is a prerequisite to ensure their trustworthiness. Based on the theory of judicial fairness, we construct a comprehensive framework to measure LLM fairness, leading to a selection of 65 labels and 161 corresponding values. Applying this framework to the judicial system, we compile an extensive dataset, JudiFair, comprising 177,100 unique case facts. To achieve robust statistical inference, we develop three evaluation metrics—inconsistency, bias, and imbalanced inaccuracy—and introduce a method to assess the overall fairness of multiple LLMs across various labels. Through experiments with 16 LLMs, we uncover pervasive inconsistency, bias, and imbalanced inaccuracy across models, underscoring severe LLM judicial unfairness. Particularly, LLMs display notably more pronounced biases on demographic labels, with slightly less bias on substance labels compared to procedure ones. Interestingly, increased inconsistency correlates with reduced biases, but more accurate prediction exacerbates biases. While we find that adjusting the temperature parameter can influence LLM fairness, model size, release date, and country of origin do not exhibit significant effects on judicial fairness. Accordingly, we introduce a publicly available toolkit containing all datasets and code\footnote{https://anonymous.4open.science/r/LLM-Fairness-8167}, designed to support future research in evaluating and improving LLM fairness.
		</p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    Sarc7: Evaluating Sarcasm Detection and Generation with Seven Types and Emotion-Informed Techniques
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Lang Xiong, Raina Gao, Alyssa Jeong, Yicheng Fu, Kevin Zhu, Sean O'Brien, Vasu Sharma
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/attachment?id=pCHDOIaaOI&name=pdf" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
			In interactive systems, misreading sarcasm can undermine safety and robustness by causing models to interpret ironic remarks literally or generate unintended hostility. Sarc7 addresses this with a fine-grained, pragmatically grounded benchmark—built on MUStARD and annotated with seven distinct subtypes (self-deprecating, brooding, deadpan, polite, obnoxious, raging, manic)—that measures both classification and controlled generation performance. For classification, we compare zero-shot, few-shot, chain-of-thought (CoT), and a novel emotion-based prompting across five LLMs and find that emotion prompts boost macro-F1 compared to CoT prompting, reaching a highest of 0.3664 (Gemini 2.5).On generation, structured prompts defined by incongruity, shock value, context dependency, and emotion improve subtype alignment by 38.5% over zero-shot (Claude 3.5 Sonnet), enhancing interpretability and alignment with user intent. A human baseline (Cohen’s κ = 0.6694, macro-F1 = 0.6663) further highlights persistent error modes in brooding, deadpan, and polite sarcasm. By quantifying model versus human performance and exposing alignment failures—bias toward “not sarcasm” or “deadpan”—Sarc7 advances transparency, explainability, and the safe deployment of LLMs where pragmatic understanding is critical.
			</p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    Investigating Model Editing for Unlearning in Large Language Models
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Shariqah Hossain, Lalana Kagal
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/attachment?id=sV0fo22GDl&name=pdf" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					Machine unlearning aims to remove unwanted information from a model, but many methods are inefficient for LLMs with large numbers of parameters or fail to fully remove the intended information without degrading performance on knowledge that should be retained. Model editing algorithms solve a similar problem of changing information in models, but they focus on redirecting inputs to a new target rather than removing that information altogether. In this work, we explore the editing algorithms ROME, IKE, and WISE and design new editing targets for an unlearning setting. Through this investigation, we show that model editing approaches can exceed baseline unlearning methods in terms of quality of forgetting depending on the setting. Like traditional unlearning techniques, they struggle to encapsulate the scope of what is to be unlearned without damage to the overall model performance.
					</p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    TRUTH: Teaching LLMs to Rerank for Truth in Misinformation Detection 
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Hao Yu, Shenyang Huang, Zachary Yang, Maximilian Puelma Touzel, Kellin Pelrine, Jean-François Godbout, Reihaneh Rabbany
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/attachment?id=S8TNODptF7&name=pdf" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					Misinformation detection presents a significant challenge due to its knowledge-intensive and reasoning-intensive nature. While Retrieval-Augmented Generation (RAG) systems offer a promising direction, the effectiveness of their retrieval and reranking components is crucial. This paper introduces TRUTH, a novel reranking approach designed for domain adaptation, specifically for misinformation detection, which employs a two-stage training methodology: Supervised Fine-Tuning (SFT) and Direct Preference Optimization (DPO). We demonstrate that our 1B parameter TRUTH model achieves strong performance comparable to 7B models on established misinformation benchmarks such as FEVER and Canadian bilingual news datasets, improving retrieval quality and positively impacting downstream task accuracy. Our findings highlight the efficacy of combining SFT for broad knowledge acquisition and domain adaptation with DPO for nuanced reasoning alignment in developing efficient and effective rerankers for complex, knowledge-intensive tasks. Datasets and code will be available with the camera-ready version of the paper.
			</p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    Red Teaming Vision Language Models Under Change
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Rebecca Tsekanovskiy, James Hendler
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/attachment?id=aK69DKMoF7&name=pdf" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					Multimodal jailbreaks in vision–language systems unfold through multi-turn interactions and modality shifts, and frequent interface and policy updates make fixed benchmarks quickly obsolete. We adopt a continuous adversarial auditing stance for image harms using two simple frames. Pre-update, a Setup–Insistence–Override escalation primes helpfulness with benign context and example images, requires image-only output, then overrides residual disclaimers; in an April 2025 GPT-4o case window, SIO yielded 18/33 unsafe images overall. After updates, we use a Caption-Relay Loop that proceeds from a public seed image to a bounded factual caption (300–400 words; no opinions or slurs) and then to image-only generation in a fresh, zero-shot session. Under a consistent safe/benign/unsafe rubric, post-update outcomes trend toward refusals or benign images. To date, CRL has produced at least 25 unsafe images across five harm categories spanning three production VLMs (GPT-4o, Gemini 2.5 Flash, Mistral). These observations show that defenses evolve rapidly even as new red-teaming approaches continue to emerge.
				</p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    Prompt Attacks Reveal Superficial Knowledge Removal in Unlearning Methods
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Yeonwoo Jang, Shariqah Hossain, Ashwin Sreevatsa, Diogo Cruz
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/attachment?id=RvwYQ4RycZ&name=pdf" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					In this work, we demonstrate that certain machine unlearning methods may fail under straightforward prompt attacks. We systematically evaluate eight unlearning techniques across three model families using output-based, logit-based, and probe analysis to assess the extent to which supposedly unlearned knowledge can be retrieved. While methods like RMU and TAR exhibit robust unlearning, ELM remains vulnerable to specific prompt attacks (e.g., prepending Hindi filler text to the original prompt recovers 57.3% accuracy). Our logit analysis further indicates that unlearned models are unlikely to hide knowledge through changes in answer formatting, given the strong correlation between output and logit accuracy. These findings challenge prevailing assumptions about unlearning effectiveness and highlight the need for evaluation frameworks that can reliably distinguish between genuine knowledge removal and superficial output suppression. To facilitate further research, we publicly release our evaluation framework to easily evaluate prompting techniques to retrieve unlearned knowledge.
				</p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    Towards Attuned AI: Integrating Care Ethics in Large Language Model Development and Alignment
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Rayane El Masri, Aaron J Snoswell
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/attachment?id=s42bQle1CQ&name=pdf" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					How can the Ethics of Care (EoC) inform the development and value alignment of large language models (LLMs)? This paper proposes to investigate how a Care ethics framework, emphasizing relationality, attention to particularities, and contextual moral reasoning, can reshape existing approaches to aligning LLMs with human values. Mainstream AI alignment often draws on deontological or utilitarian principles, yet these frameworks can overlook the situated, affective, and power-sensitive aspects of moral life that Care ethics foregrounds. In this paper, we present two arguments for integrating Care Ethics into LLM development practices. First, we argue that LLMs often rely on overly generalized reasoning which contributes to various down-stream harms, including issues of bias. Second, we critique methods like RLHF and RLAIF for embedding narrow normative assumptions that neglect emotional and relational dimensions of human values. We argue that adapting LLM fine-tuning or alignment practices to incorporate Ethics of Care considerations may help address these issues, potentially laying the groundwork for better forms of LLM generalization and providing a pathway for more context-sensitive alignment of LLMs in care-relevant areas such as mental health, education, and social services.
				</p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    Practical Evaluation of Machine Learning Efficiency Requires Model Life Cycle Assessment
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Jared Fernandez, Clara Na, Yonatan Bisk, Constantine Samaras, Emma Strubell
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/attachment?id=BdWarHDYeF&name=pdf" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					The growing scale of language models entails growing resource requirements and envrionmental impacts. For these systems to have a positive impact on society, it is necessary to thoughtfully weigh the societal and environmental benefits and costs, within the context of a complex model life cycle and many potential measures of impact. In this position paper, we argue the need for $\textbf{holistic life cycle assessment of language models}$ across the development and deployment pipeline to properly account for required resources and downstream impact.
				</p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    Neither Valid nor Reliable? Investigating the Use of LLMs as Judges
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Khaoula Chehbouni, Mohammed Haddou, Jackie CK Cheung, Golnoosh Farnadi
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/pdf?id=Wfcbb0d7UEs" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					Evaluating natural language generation (NLG) systems remains a core challenge of natural language processing (NLP), further complicated by the rise of large language models (LLMs) that aims to be general-purpose. Recently, LLMs as judges (LLJs) have emerged as a promising alternative to traditional metrics, but their validity remains underexplored. This position paper argues that the current enthusiasm around LLJs may be premature, as their adoption has outpaced rigorous scrutiny of their reliability and validity as evaluators. Drawing on measurement theory from the social sciences, we identify and critically assess four core assumptions underlying the use of LLJs: their ability to act as proxies for human judgment, their capabilities as evaluators, their scalability, and their cost-effectiveness. We examine how each of these assumptions may be challenged by the inherent limitations of LLMs, LLJs, or current practices in NLG evaluation.
				</p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    When Do Language Models Endorse Limitations on Universal Human Rights Principles?
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Keenan Samway, Rada Mihalcea, Zhijing Jin
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/attachment?id=qcrRfwPUjJ&name=pdf" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					As Large Language Models (LLMs) increasingly mediate global information access with the potential to shape public discourse, their alignment with universal human rights principles becomes important to ensure that these rights are abided by in high-stake AI-mediated interactions. In this paper, we evaluate how LLMs navigate trade-offs involving the Universal Declaration of Human Rights (UDHR), leveraging 1,152 synthetically generated scenarios across 24 rights articles in eight languages. Our analysis of eleven major LLMs reveals systematic biases where models: (1) accept limiting Economic, Social, and Cultural rights more often than Political and Civil rights, (2) demonstrate significant cross-linguistic variation with elevated endorsement rates of rights-limiting actions in Chinese and Hindi compared to English or Romanian, and (3) exhibit noticeable differences between Likert and open-ended responses, highlighting critical challenges in LLM preference assessment.
				</p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    CourtReasoner: Can LLM Agents Reason Like Judges?
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Simeng Han, Yoshiki Takashima, Shannon Zejiang Shen, Chen Liu, Yixin Liu, Roque K. Thuo, Sonia Knowlton, Ruzica Piskac, Scott J Shapiro, Arman Cohan
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/attachment?id=wAV9X7DkAK&name=pdf" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					LLMs are increasingly applied in the legal domain in tasks such as summarizing legal texts and providing basic legal advice. Yet, their capacity to draft full judicial analyses in U.S. court opinions is still largely uncharted, such as generating entire judicial reasoning sections in U.S. court decisions, remain under-explored. Given the continued adoption of LLMs and the significance of law to society at large, measurement of LLM's legal reasoning capabilities is a pressing task. We propose CourtReasoner, a novel expert-annotated judicial reasoning benchmark for evaluating LLM agents' capabilities in complex legal reasoning. Sourcing U.S. court opinions, we construct benchmarks that measure the LLMs ability to construct goal-oriented legal reasoning. CourtReasoner measured the agent's ability to argue both ways in a legal dispute, rather than simple Q/A. Our results show that more than 60% of frontier model outputs contain invalid arguments and more than 53% of frontier model produced irrelevant citations when conducting complex legal reasoning. We also introduce a meta-evaluation benchmark to provide insights into the capabilities of LLMs as evaluators of legal reasoning. We will release our data, code and full annotation guidelines publicly for future research.
				</p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    CONECUT: Scalable Removal of Preference Redundancy
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Purbid bambroo, Daniel S. Brown, Ana Marasovic
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/pdf?id=hb3Et9tJSC9" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					Reward models are central to post-training alignment of large language models (LLMs) via human preferences. As reward benchmarks gain prominence, it becomes critical to evaluate their integrity. A key challenge that remains underexplored in this space is the identification of redundant examples in these evaluation datasets. These are preference pairs that enforce near-duplicate or redundant half-space constraints on the reward-model weight vector and hence may inflate or exaggerate the perceived alignment of a reward model. In this work, we propose a novel method, CONECUT, to identify redundancy in preference alignment datasets by formulating this task as a cone membership test over a reward model’s hidden representations. Our experiments on RewardBench reveal that a substantial fraction of examples in evaluation pairs are near redundant, and pruning them results in measurable performance drops across multiple reward models. Our work highlights the overestimation of alignment that evaluation datasets might cause in socially critical areas like refusals and safety. We advocate for redundancy-aware evaluation as a step toward better model alignment and curating socially responsible evaluation datasets.
				</p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    Privacy-Preserving LLM Interaction with Socratic Chain-of-Thought Reasoning and Homomorphically Encrypted Vector Databases
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Yubeen Bae, Minchan Kim, Jaejin Lee, Sangbum Kim, Jaehyung Kim, Yejin Choi, Niloofar Mireshghallah
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/attachment?id=vgjnmaGEnJ&name=pdf" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					Large language models (LLMs) are increasingly used as personal agents, accessing sensitive user data such as calendars, emails, and medical records. Users currently face a trade-off: They can send private records, many of which are stored in remote databases, to powerful but untrusted LLM providers, increasing their exposure risk. Alternatively, they can run less powerful models locally on trusted devices. We bridge this gap. Our Socratic Chain-of-Thought Reasoning first sends a generic, non-private user query to a powerful, untrusted LLM, which generates a Chain-of-Thought (CoT) prompt and detailed sub-queries without accessing user data. Next, we embed these sub-queries and perform encrypted sub-second semantic search using our Homomorphically Encrypted Vector Database across one million entries of a single user's private data. This represents a realistic scale of personal documents, emails, and records accumulated over years of digital activity. Finally, we feed the CoT prompt and the decrypted records to a local language model and generate the final response. On the LoCoMo long-context QA benchmark, our hybrid framework, combining GPT-4o with a local Llama-3.2-1B model, outperforms using GPT-4o alone by up to 7.1 percentage points. This demonstrates a first step toward systems where tasks are decomposed and split between untrusted strong LLMs and weak local ones, preserving user privacy.
				</p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    Poor Alignment and Steerability of Large Language Models: Evidence Using 30,000 College Admissions Essays
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Jinsook Lee, AJ Alvero, Thorsten Joachims, Rene F Kizilcec
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/pdf?id=Ijw_Am6DeQc" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					People increasingly use large language models (LLMs) for formal writing, raising two key questions: Who do LLMs write like (model alignment), and can prompting change that (model steerability)? We investigate these questions in the high-stakes context of college admissions by comparing essays from 30,000 applicants with two types of LLM-generated essays: one based only on the essay question and another with added demographic information. Across all models and analytical approaches, we find that LLM-generated essays—whether identity-prompted or not—remain linguistically distinct from human-authored ones. Identity prompting fails to align model outputs with the linguistic patterns of the corresponding demographic groups across sex, race, first-generation status, and geography. In fact, identity-prompted and unprompted LLM essays are more similar to each other than to human-written texts, reinforcing homogenization rather than reducing it. These findings reveal fundamental limitations in the alignment and steerability of current LLMs and raise concerns about their use in high-stakes settings like college admissions.
				</p>
		</div>
  </div>
</div>
 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    A Study of Large Language Models for Extraction of Themes from Homeless Shelter Case Notes
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Madhumitha Selvaraj, Teale Masrani, Yani Ioannou, Geoffrey Messier
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/attachment?id=YXK5KloMJR&name=pdf" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					Homeless shelters generate large amounts of unstructured text data in the form of case notes, which are challenging to analyze using traditional methods due to their variability and domain-specific language. This study explores the use of Large Language Models (LLMs) to extract abstract themes related to client behaviour and experiences from these notes. We focus on prompt engineering techniques and evaluate the performance of smaller LLMs against human-generated labels. Our results demonstrate that for certain themes requiring contextual understanding, smaller LLMs offer advantages over simpler methods such as keyword search or Naive Bayes. However, discrepancies between model predictions and human labels remain, with models occasionally making broad assumptions that may be undesirable. Overall, our findings highlight the role of prompt design in optimizing model performance and demonstrate the potential of LLMs to effectively understand complex homelessness data.
				</p>
		</div>
  </div>
</div>
 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    The Alignment Game: The Inevitable Conflict of Values in Generative Models
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Ali Falahati, Mohammad Mohammadi Amiri, Kate Larson, Lukasz Golab
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/attachment?id=sYuzzrO39n&name=pdf" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					As generative models are increasingly trained on their own outputs, data curation becomes the key force shaping what values persist. We formalize this recursive loop as a two-stage game between two agents: the model Owner and the Public. Each round, the generative model outputs are filtered by both agents and returned to the training pool, progressively amplifying curator preferences. We analyze the dynamics under varying degrees of misalignment between the Owner and the Public—ranging from perfect alignment to partial and fully disjoint preferences—and show that the system converges exponentially to distinct long-run behaviours. Finally, we establish an alignment trilemma: No Bradley--Terry alignment process can simultaneously satisfy stability, diversity, and value alignment with both the Owner and the Public.
				</p>
		</div>
  </div>
</div>
 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    LLMs are Vulnerable to Malicious Prompts Disguised as Scientific Language
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Yubin Ge, Neeraja Kirtane, Hao Peng, Dilek Hakkani-Tür
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/attachment?id=WBn3rZYLho&name=pdf" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					As large language models (LLMs) have been deployed in various real-world settings, concerns about the harm they may propagate have grown. Various jailbreaking techniques have been developed to expose the vulnerabilities of these models and improve their safety. This work reveals that many state-of-the-art LLMs are vulnerable to malicious requests hidden behind scientific language. Specifically, our experiments with GPT4o, GPT4o-mini, GPT-4, Llama3.1-405B-Instruct, Llama3.1-70B-Instruct, Gemini models on the StereoSet data demonstrate that, the models’ biases and toxicity substantially increase when prompted with requests that deliberately misinterpret social science and psychological studies as evidence supporting the benefits of stereotypical biases. Alarmingly, these models can be also manipulated to generate fabricated scientific arguments claiming that biases are beneficial, which can be used by ill-intended actors to systematically jailbreak even the strongest models like GPT. Our findings call for a more careful investigation on the use of scientific data for training LLMs.
				</p>
		</div>
  </div>
</div>
 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    MedPAIR: Measuring Physicians and AI Relevance Alignment in Medical Question Answering
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Yuexing Hao, Kumail Alhamoud, Hyewon Jeong, Haoran Zhang, Isha Puri, Philip Torr, Mike Schaekermann, Ariel Dora Stern, Marzyeh Ghassemi
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/attachment?id=GgKtVXvC3a&name=pdf" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					Large Language Models (LLMs) have demonstrated remarkable performance on various medical question-answering (QA) benchmarks, including standardized medical exams. However, correct answers alone do not ensure correct logic, and models may reach accurate conclusions through flawed processes. In this study, we introduce the MedPAIR (Medical Dataset Comparing Physicians and AI Relevance Estimation and Question Answering) dataset to evaluate how physician trainees and LLMs prioritize relevant information when answering QA questions. We obtain annotations on 1,300 QA pairs from 36 physician trainees, labeling each sentence within the question components for relevance. We compare these relevance estimates to those for LLMs, and further evaluate the impact of these "relevant" subsets on downstream task performance for both physician trainees and LLMs. We find that LLMs are frequently not aligned with the content relevance estimates of physician trainees. After filtering out physician trainee-labeled irrelevant sentences, accuracy improves for both the trainees and the LLMs.
				</p>
		</div>
  </div>
</div>
 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    Detecting Biased Language in Icelandic: A Named Entity Recognition Approach for Socially Responsible Text Analysis
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Steinunn Rut Friðriksdóttir, Hafsteinn Einarsson
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/attachment?id=U9dXoU36DQ&name=pdf" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					Bias research has been limited for Icelandic, a low-resource language with few NLP tools for socially aware text analysis. We address this gap by developing a publicly accessible web application that detects biased and stigmatizing vocabulary in Icelandic text and provides category-specific feedback to encourage reflection and more inclusive communication. The application is powered by the best-performing of three Named Entity Recognition (NER) models that we trained on automatically annotated data derived from a manually compiled lexicon of over 2,000 biased terms and phrases across 14 social categories, ranging from misogyny and queerphobia to religious and ethnic bias. All components, including the lexicon, annotated dataset, the three fine-tuned models and the web application code, are freely available online, offering a transparent and reproducible framework for bias detection in low-resource languages.
				</p>
		</div>
  </div>
</div>
 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    Large Language Models in the Task of Automatic Validation of Text Classifier Predictions
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Aleksandr Tsymbalov
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/attachment?id=9UBtoZOvpT&name=pdf" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					Machine learning models for text classification are trained to predict a class for a given text. To do this, training and validation samples must be prepared: a set of texts is collected, and each text is assigned a class. These classes are usually assigned by human annotators with different expertise levels, depending on the specific classification task. Collecting such samples from scratch is labor-intensive because it requires finding specialists and compensating them for their work; moreover, the number of available specialists is limited, and their productivity is constrained by human factors. While it may not be too resource-intensive to collect samples once, the ongoing need to retrain models (especially in incremental learning pipelines He et al. (2021)) to address data drift (also called model drift IBM (2024)) makes the data collection process crucial and costly over the model’s entire lifecycle. This paper proposes several approaches to replace human annotators with Large Language Models (LLMs) to test classifier predictions for correctness, helping ensure model quality and support high-quality incremental learning.
				</p>
		</div>
  </div>
</div>
 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    IMPersona: Evaluating Individual Level LM Impersonation
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Quan Shi, Carlos E Jimenez, Stephen Dong, Brian Seo, Caden Yao, Adam Kelch, Karthik R Narasimhan
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/attachment?id=N8vaJAcVKz&name=pdf" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					As language models achieve increasingly human-like capabilities in conversational text generation, a critical question emerges: to what extent can these systems simulate the characteristics of specific individuals? To evaluate this, we introduce IMPersona, a framework for evaluating LMs at impersonating specific individuals' writing style and personal knowledge. Using supervised fine-tuning and a hierarchical memory-inspired retrieval system, we demonstrate that even modestly sized open-source models, such as Llama-3.1-8B-Instruct, can achieve impersonation abilities at concerning levels. In blind conversation experiments, participants (mis)identified our fine-tuned models, with memory augmentation, in 44.44% of interactions, compared to just 25.00% for the best prompting-based approach. We analyze these results to propose detection methods and defense strategies against such impersonation attempts. Our findings raise important questions about both the potential applications and risks of personalized language models, particularly regarding privacy, security, and the ethical deployment of such technologies in real-world contexts.
				</p>
		</div>
  </div>
</div>
 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    MCP Safety Training: Learning to Refuse Falsely Benign MCP Exploits using Improved Preference Alignment
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> John Timothy Halloran
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/attachment?id=YXK5KloMJR&name=pdf" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					The model context protocol (MCP) has been widely adapted as an open standard enabling the seamless integration of generative AI agents. However, recent work has shown the MCP is susceptible to retrieval-based "falsely benign" attacks (FBAs), allowing malicious system access and credential theft, but requiring that users download compromised files directly to their systems. Herein, we show that the threat model of MCP-based attacks is significantly broader than previously thought, i.e., attackers need only post malicious content online to deceive MCP agents into carrying out their attacks on unsuspecting victims' systems.

    				To improve alignment guardrails against such attacks, we introduce a new MCP dataset of FBAs and (truly) benign samples to explore the effectiveness of direct preference optimization (DPO) for the refusal training of large language models (LLMs). While DPO improves model guardrails against such attacks, we show that the efficacy of refusal learning varies drastically depending on the model's original post-training alignment scheme--e.g., GRPO-based LLMs learn to refuse extremely poorly. Thus, to further improve FBA refusals, we introduce Retrieval Augmented Generation for Preference alignment (RAG-Pref), a novel preference alignment strategy based on RAG. We show that RAG-Pref significantly improves the ability of LLMs to refuse FBAs, particularly when combined with DPO alignment, thus drastically improving guardrails against MCP-based attacks.

</p>
</div>

  </div>
</div>
 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    Accidental Vulnerability: Factors in Fine-Tuning that Shift Model Safeguards
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Punya Syon Pandey, Samuel Simko, Kellin Pelrine, Zhijing Jin
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/attachment?id=YXK5KloMJR&name=pdf" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					As large language models (LLMs) gain popularity, their vulnerability to adversarial attacks emerges as a primary concern. While fine-tuning models on domain-specific datasets is often employed to improve model performance, it can inadvertently introduce vulnerabilities within the underlying model. In this work, we investigate \emph{Accidental Vulnerability}: unexpected vulnerability arising from characteristics of fine-tuning data. We begin by identifying potential correlation factors such as linguistic features, semantic similarity, and toxicity across multiple experimental datasets. We then evaluate the adversarial robustness of these fine-tuned models, analyzing persona shifts and interpretability traits to understand how dataset factors contribute to attack success rates. Lastly, we explore causal relationships that offer new insights into adversarial defense strategies, highlighting the crucial role of dataset design in preserving model alignment.
				</p>
		</div>
  </div>
</div>

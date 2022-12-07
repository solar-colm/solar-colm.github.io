---
layout: page
title: Papers
subtitle: 
---
 
 <h3 style='margin-bottom: 10pt;'>Awards</h3>
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
</div>

 <h3 style='margin-bottom: 10pt;'>Accepted Papers</h3>
<hr>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    Toward Semantic History Compression for Reinforcement Learning
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Fabian Paischer, Thomas Adler, Andreas Radler, Markus Hofmarcher, Sepp Hochreiter
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/pdf?id=97C6klf5shp" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
	      Agents interacting under partial observability require access to past observations via a memory mechanism in order to approximate the true state of the environment.
			Recent work suggests that leveraging language as abstraction provides benefits for creating a representation of past events.
			History Compression via Language Models (HELM) leverages a pretrained Language Model (LM) for representing the past. 
			It relies on a randomized attention mechanism to translate environment observations to token embeddings.
			In this work, we show that the representations resulting from this attention mechanism can collapse under certain conditions. 
			This causes blindness of the agent to subtle changes in the environment that may be crucial for solving a certain task. 
			We propose a solution to this problem consisting of two parts. 
			First, we improve upon HELM by substituting the attention mechanism with a feature-wise centering-and-scaling operation. 
			Second, we take a step toward semantic history compression by leveraging foundation models, such as CLIP, to encode observations, which further improves performance. 
			By combining foundation models, our agent is able to solve the challenging MiniGrid-Memory environment.
			Surprisingly, however, our experiments suggest that this is not due to the semantic enrichment of the representation presented to the LM, but rather due to the discriminative power provided by CLIP. 
			We make our code publicly available at https://github.com/ml-jku/helm.
	      </p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    Towards an Enhanced, Faithful, and Adaptable Web Interaction Environment
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> John Yang, Howard Chen, Karthik R Narasimhan
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/pdf?id=y-F1kab2Its" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
			We identify key areas of improvement for WebShop, an e-commerce shopping environment for training decision making language agents. Specifically, shortcomings in: 1) faithfulness of the reward function to human evaluation, 2) comprehensiveness of its content, and 3) human participation required for generating instructions has hindered WebShop’s promises to be a scalable real-world environment. To solve these issues, we first incorporate greater faithfulness to human evaluation by designing a new reward function to capture lexical similarities and synonyms. Second, we identify customer reviews, similar products, and customer FAQs as missing semantic components that are most helpful to human execution of the task from surveying 75 respondents. Finally, we reformulate the attribute tagging problem as a extractive short-phrase prediction task to enhance scalability. Our V2 reward function closes the gap between the scores of the WebShop’s automated reward function (from 81.5% to 87.7%) and human evaluation (89.9%). Our attribute tagging approach achieves an accuracy of 72.2% with a t5-3b model fine tuned on 2, 000 training data points, showing potential to automate the instruction creation pipeline.
		</p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    Understanding Redundancy in Discrete Multi-Agent Communication
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Jonathan David Thomas, Raul Santos-Rodriguez, Robert Piechocki
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/pdf?id=cbsgHxnjV6" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
			Through providing agents with the capacity to learn sample-efficient and generalisable communications protocols, we may enable them to more effectively cooperate in real-world tasks. In this paper, we consider this in the context of discrete decentralised multi-agent reinforcement learning to provide insights into the impact of the often overlooked size of the message set. Within a referential game, we find that over-provisioning the message set size leads to improved sample efficiency, but that these policies tend to maintain a high-degree of redundancy, often utilising multiple messages to refer to each label in the dataset. We hypothesise that the additional redundancy within these converged policies may have implications for generalisation and experiment with methodologies to gradually reduce redundancy while maintaining sample-efficiency. To this end, we propose a linearly-scheduled entropy regulariser which encourages an agent to initially maximise the utilisation of the available messages but, as training progresses, it tries to minimise it. Through this mechanism, we achieve a comparable sample efficiency whilst converging to a model with significantly reduced redundancy and that generalises more effectively to previously unseen data.
		</p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    Language-Conditioned Reinforcement Learning to Solve Misunderstandings with Action Corrections
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Frank Röder, Manfred Eppe
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/pdf?id=lWd0qiv9E-" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
			Human-to-human conversation is not just talking and listening. It is an incremental process where participants continually establish a common understanding to rule out misunderstandings. Current language understanding methods for intelligent robots do not consider this. There exist numerous approaches considering non-understandings, but they ignore the incremental process of resolving misunderstandings. In this article, we present a first formalization and experimental validation of incremental action-repair for robotic instruction-following based on reinforcement learning. To evaluate our approach, we propose a collection of benchmark environments for action correction in language-conditioned reinforcement learning, utilizing a synthetic instructor to generate language goals and their corresponding corrections. We show that a reinforcement learning agent can successfully learn to understand incremental corrections of misunderstood instructions.
			</p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    ScriptWorld: A Scripts-based RL Environment 
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
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    lilGym: Natural Language Visual Reasoning with Reinforcement Learning 
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Anne Wu, Kianté Brantley, Noriyuki Kojima, Yoav Artzi
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/pdf?id=pRPnAA8NIo" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					We present lilGym, a new benchmark for language-conditioned reinforcement learning in visual environments. Gym is based on 2,661 highly-compositional human-written natural language statements grounded in an interactive visual environment. We annotate all statements with executable Python programs representing their meaning to enable exact reward computation in every possible world state. Each statement is paired with multiple start states and reward functions to form thousands of distinct Markov Decision Processes of varying difficulty. We experiment with Gym with different models and learning regimes. Our results and analysis show that while existing methods are able to achieve non-trivial performance, Gym forms a challenging open problem. Gym is available at https://lil.nlp.cornell.edu/lilgym/.
			</p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    Hierarchical Agents by Combining Language Generation and Semantic Goal Directed RL
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Bharat Prakash, Nicholas R Waytowich, Tim Oates, Tinoosh Mohsenin
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/pdf?id=UqJOjgk2R6" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					Learning to solve long horizon temporally extended tasks with reinforcement learning has been a challenge for several years now.  We believe that it is important to leverage both the hierarchical structure of complex tasks and to use expert supervision whenever possible to solve such tasks. This work introduces an interpretable hierarchical agent framework by combining sub-goal generation using language and semantic goal directed reinforcement learning. We assume access to certain spatial and haptic predicates and construct a simple and powerful semantic goal space. These semantic goal representations act as an intermediate representation between language and raw states. We evaluate our framework on a robotic block manipulation task and show that it performs better than other methods, including both sparse and dense reward functions. We also suggest some next steps and discuss how this framework makes interaction and collaboration with humans easier.
				</p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    ProgPrompt: Generating Situated Robot Task Plans using Large Language Models
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Ishika Singh, Valts Blukis, Arsalan Mousavian, Ankit Goyal, Danfei Xu, Jonathan Tremblay, Dieter Fox, Jesse Thomason, Animesh Garg
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/pdf?id=aflRdmGOhw1" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					Task planning can require defining myriad domain knowledge about the world in which a robot needs to act. To ameliorate that effort, large language models (LLMs) can be used to score potential next actions during task planning, and even generate action sequences directly, given an instruction in natural language with no additional domain information. However, such methods either require enumerating all possible next steps for scoring, or generate free-form text that may contain actions not possible on a given robot in its current context. We present a programmatic LLM prompt structure that enables plan generation functional across situated environments, robot capabilities, and tasks. Our key insight is to prompt the LLM with program-like specifications of the available actions and objects in an environment, as well as with executable example programs. We make concrete recommendations about prompt structure and generation constraints through ablation experiments, demonstrate state of the art success rates in VirtualHome household tasks, and deploy our method on a physical robot arm for tabletop tasks. 
				</p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    Tackling AlfWorld with Action Attention and Common Sense from Language Models
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Yue Wu, So Yeon Min, Yonatan Bisk, Ruslan Salakhutdinov, Shrimai Prabhumoye
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/pdf?id=AqkPRUZ-YkO" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					Pre-trained language models (LMs) capture strong prior knowledge about the world. This common sense knowledge can be used in control tasks. However, directly generating actions from LMs may result in a reasonable narrative, but not executable by a low level agent. We propose to instead use the knowledge in LMs to simplify the control problem, and assist the low-level actor training. We implement a novel question answering framework to simplify observations and an agent that handles arbitrary roll-out length and action space size based on action attention. On the Alfworld benchmark for indoor instruction following, we achieve a significantly higher success rate (50% over the baseline) with our novel object masking - action attention method.
				</p>
		</div>
  </div>
</div>


 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    Collaborating with language models for embodied reasoning
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


 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    How to talk so AI will learn: instructions, descriptions, and pragmatics
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
    SCERL: A Benchmark for intersecting language and safe reinforcement learning
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Lan Hoang, Shivam Ratnakar, Nicolas Galichet, Akifumi Wachi, Keerthiram Murugesan, Songtao Lu, Mattia Atzeni, Michael Katz, Subhajit Chaudhury
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/pdf?id=rNmrhsewsUX" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					The issue of safety and robustness is a critical focus for AI research. Two lines of research are so far distinct, namely \(i) safe reinforcement learning, where an agent needs to interact with the world under safety constraints, and (ii) textual reinforcement learning, where agents need to perform robust reasoning and modelling of the state of the environment. In this paper, we propose Safety-Constrained Environments for Reinforcement Learning (SCERL), a benchmark to bridge the gap between these two research directions. The contribution of this benchmark is safety-relevant environments with i) a sample set of 20 games built on new logical rules to represent physical safety issues; ii) added monitoring of safety violations and iii) a mechanism to further generate a more diverse set of games with safety constraints and their corresponding metrics of safety types and difficulties. This paper shows selected baseline results on the benchmark. Our aim is for the SCERL benchmark and its flexible framework to provide a set of tasks to demonstrate language-based safety challenges to inspire the research community to further explore safety applications in a text-based domain.
				</p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    LAD: Language Augmented Diffusion for Reinforcement Learning
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Edwin Zhang, Yujie Lu, William Yang Wang, Amy Zhang
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/pdf?id=JhM3xZISMvN" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					Learning skills from language potentially provides a powerful avenue for generalization in RL, although it remains a challenging task as it requires agents to capture the complex interdependencies between language, actions and states, also known as language grounding. In this paper, we propose leveraging Language Augmented Diffusion models as a language-to-plan generator (LAD). We demonstrate comparable performance of LAD with the state of the art on the CALVIN benchmark with a much simpler architecture and conduct an analysis on the properties of language conditioned diffusion in reinforcement learning.
				</p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    Meta-learning from demonstrations improves compositional generalization
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Sam Spilsbury, Alexander Ilin
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
					We study the problem of compositional generalization of language-instructed agents in gSCAN. gSCAN is a popular benchmark which requires an agent to generalize to instructions containing novel combinations of words, which are not seen in the training data. We propose to improve the agent’s generalization capabilities with an architecture inspired by the Meta-Sequence-to-Sequence learning approach (Lake, 2019). The agent receives as a context a few examples of pairs of instructions and action trajectories in a given instance of the environment (a support set) and it is tasked to predict an action sequence for a query instruction for the same environment instance. The context is generated by an oracle and the instructions come from the same distribution as seen in the training data. In each training episode, we also shuffle the indices of the attributes of the observed environment states and the words of the instructions to make the agent figure out the relations between the attributes and the words from the context. Our predictive model has the standard transformer architecture. We show that the proposed architecture can significantly improve the generalization capabilities of the agent on one of the most difficult gSCAN splits: the ``adverb-to-verb” split H.
				</p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    Language-guided Task Adaptation for Imitation Learning
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Prasoon Goyal, Ray Mooney, Scott Niekum
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/pdf?id=-6b4dsHIdW0" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					We introduce a novel setting, wherein an agent needs to learn a task from a demonstration of a related task with the difference between the tasks communicated in natural language. The proposed setting allows reusing demonstrations from other tasks, by providing low effort language descriptions, and can also be used to provide feedback to correct agent errors, which are both important desiderata for building intelligent agents that assist humans in daily tasks. To enable progress in this proposed setting, we create two benchmarks---Room Rearrangement and Room Navigation---that cover a diverse set of task adaptations. Further, we propose a framework that uses a transformer-based model to reason about the entities in the tasks and their relationships, to learn a policy for the target task
				</p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    Overcoming Referential Ambiguity in language-guided goal-conditioned Reinforcement Learning
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Hugo Caselles-Dupré, Olivier Sigaud, Mohamed Chetouani
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
					Teaching an agent to perform new tasks using natural language can easily be hindered by ambiguities in interpretation. When a teacher provides an instruction to a learner about an object by referring to its features, the learner can misunderstand the teacher's intentions, for instance if the instruction ambiguously refer to features of the object, a phenomenon called referential ambiguity. We study how two concepts derived from cognitive sciences can help resolve those referential ambiguities: pedagogy (selecting the right instructions) and pragmatism (learning the preferences of the other agents using inductive reasoning). We apply those ideas to a teacher/learner setup with two artificial agents on a simulated robotic task (block-stacking). We show that these concepts improve sample efficiency for training the learner.
				</p>
		</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
    On the Pitfalls of Visual Learning in Referential Games
  </div>
  <div class="card-body">
    <p class="card-text">
    	<div class="row">
    		<div class="col-9">
    			<b>Authors:</b> Shresth Verma
    		</div>
    		<div class="col-3">
    			<div class="right">
    				<a class="btn btn-primary" href="https://openreview.net/pdf?id=WVK1rZJsAOu" target="_blank" role="button">Paper Link</a>
				</div>
    		</div>
    	</div>
    </p>
      <button type="button" class="collapsible">Abstract</button>
		<div class="content">
	      <p style='margin-top: 5pt;'>	
					This paper focuses on the effect of game design and visual representations of real-world entities on emergent languages in referential games. Strikingly, we find that the agents in such games can learn to successfully communicate even when provided with visual features from a randomly initialized neural network. Through a series of experiments, we highlight the agents' inability to effectively utilize high-level features. Using Gradient weighted-Class Activation Mapping, we verify that the agents often 'look' at regions not related to entities. Culminating with a positive result, we show how environmental pressure from agent population can nudge the learners into effectively capturing high-level visual features. 
				</p>
		</div>
  </div>
</div>

 

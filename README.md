# Papers for LLM-based Agents Collaboration
In the era of large language models (LLMs), LLM-based agents have shown remarkable performance in several existing benchmarks or real-world applications. Nevertheless, they still face difficulties in 
 tackling complex tasks. Inspired by collaborative problem solving, several recent works use the strategy of multi-agent collaboration as a potential solution.

We collect the **Must-read papers** to catch up and share the state-of-the-art methods, facilitating the related research. 

## LLM-based Agent

1. ReAct: Synergizing Reasoning and Acting in Language Models [[ICLR2023](https://arxiv.org/abs/2210.03629)] [[code](https://react-lm.github.io/)]
   - Dataset: HotpotQA, FEVER, ALFWorld, WebShop

Link: more previous works can be found in [[LLM-based autonomous agent](https://github.com/Paitesanshi/LLM-Agent-Survey#-construction-of-llm-based-autonomous-agent)]. Thanks a lot for pioneering effort.

## Multi-Agent Collaboration


1. Encouraging Divergent Thinking in Large Language Models through Multi-Agent Debate [[ICLR2023](https://arxiv.org/pdf/2305.19118.pdf)] [[code](https://github.com/Skytliang/Multi-Agents-Debate)]
- task: MT (machine translation), Math
- Dataset: Commonsense Machine Translation, Counter-Intuitive Arithmetic Reasoning

2. Autogen: Enabling Next-Gen Llm Applications Via Multi-Agent Conversation[[ICLR2024](https://openreview.net/pdf?id=tEAF9LBdgu)][[code](https://anonymous.4open.science/r/autogen-iclr2024/README.md)]
- task:Math, QA, Decision, Coding, Chat, Chess
- Dataset: MATH, Natural Questions, ALFWorld

3. Chain-Of-Experts: When Llms Meet Complex Operations Research Problems[[ICLR2024](https://openreview.net/pdf?id=HobyL1B9CZ)][[code](https://github.com/nl4opt/nl4opt-competition)]
- task: Math(LP)
- Dataset: LPWP, ComplexOR

4. Okr-Agent: An Object And Key Results Driven Agent System With Hierarchical Self-Collaboration And Self-Evaluation[[ICLR2024](https://openreview.net/pdf?id=Mngdhgi711)]
- task: Storyboard Generation, Creative Writing, Trip Planning

5. Reason To Behave: Achieving Human-Level Task Execution For Physics-Based Characters[[ICLR2024](https://openreview.net/pdf?id=Y6PVsnkKVV)][[code](https://sites.google.com/view/reasontobehave)]
- task: Path Planning
- Dataset: MoCap

6. Ghost In The Minecraft: Hierarchical Agentsfor Minecraft Via Large Language Models With Text-Based Knowledge And Memory[[ICIR2024](https://openreview.net/pdf?id=cTOL99p5HL)]
- task:Path Planning

7. Adapting Llm Agents Through Communication[[ICIR2024](https://openreview.net/pdf?id=wOelVq8fwL)]
- task:Path Planning, QA,Math reasoning
- Dataset:ALFWorld, HotpotQA, GSM8k

8. Agentverse: Facilitating Multi-Agent Collaboration And Exploring Emergent Behaviors[[ICIR2024](https://openreview.net/pdf?id=EHg5GDnyq1)][[code](https://github.com/OpenBMB/AgentVerse.)]
- task:Conversation, Mathematical Calculation, Logical Reasoning, Coding
- Dataset:FED, Commongen-Challenge, MGSM, BigBench, Humaneval

9.Debategpt: Fine-Tuning Large Language Models With Multi-Agent Debate Supervision[[ICIR2024](https://openreview.net/pdf?id=ChNy95ovpF)]
- task:Reasoning, Math
- Dataset:AlpacaEval, MMLU, Arithmetic, Winogrande, AI2 Reasoning Challenge

10. Corex: Pushing The Boundaries Of Complex Reasoning Through Multi-Model Collaboration[[ICIR2024](https://openreview.net/pdf?id=GDdxmymrwL)][[code](https://anonymous.4open.science/r/Corex)]
- task:Reasoning
- Dataset:GSM8K, MultiArith, SingleOP/SingleEQ, AddSub, AQuA, SVAMP,GSMHard,StrategyQA, CommonsenseQA, BoolQ ,AI2 Reasoning Challenge (ARC-c),BigBench,FinQA, ConvFinQA, TAT-QA

11. Chateval: Towards Better Llm-Based Evaluators Through Multi-Agent Debate[[ICIR2024](https://openreview.net/pdf?id=FQepisCUWu)]
- task:QA
- Dataset:FairEval, Topical-Chat

 12. Language Agents With Reinforcement Learning For Strategic Play In The Werewolf Gam[[ICIR2024](https://openreview.net/pdf?id=N1gmpVd4iE)]
- task:Werewolf game

 13.Dynamic Llm-Agent Network:An Llm-Agent Collaboration Framework With Agent Team Optimization[[ICIR2024](https://openreview.net/pdf?id=i43XCU54Br)]
- task:arithmetic reasoning, general reasoning, code generation.
- Dataset:MATH, MMLU, HumanEval

14. Welfare Diplomacy:Benchmarking Language Model Cooperation[[ICIR2024](https://openreview.net/pdf?id=AKJLnDgzkm)][[code](https://anonymous.4open.science/r/welfare-diplomacy-72AC)]

15. Mindagent: Emergent Gaming Interaction[[ICIR2024](https://openreview.net/pdf?id=p9pBJv1DTz)]
- task:CuisineWorld

16. Building Cooperative Embodied Agents Modularly With Large Language Model[[ICIR2024](https://openreview.net/pdf?id=EnXJfQqy0K)][[code](https://llm-co.github.io/CoELA/.)]
- Dataset:ThreeDWorld Multi-Agent Transport (TDW-MAT)

17. Autoagents: A Framework For Automaticagent Generation [[ICIR2024](https://openreview.net/pdf?id=PhJUd3mbhP)][[code](https://anonymous.4open.science/r/AutoAgents-747C.)]
- task:Open-ended Question Answer task,Trivia Creative Writing

18. Metagpt: Meta Programming For A Multi-Agent Collaborative Framework[[ICIR2024](https://openreview.net/pdf?id=VtmBAGCN7o)]
- task:Coding
- Dataset:HumanEval, MBPP, SoftwareDev

19. Oceangpt: A Large Language Model For Ocean Science Tasks[[ICIR2024](https://openreview.net/pdf?id=pbfy04zvcH)]
- task:Ocean-related Task

20. Exploring Collaboration Mechanisms For Llm Agents: A Social Psychology View[[ICIR2024](https://openreview.net/pdf?id=ueqTjOcuLc)]
- Dataset:MMLU, MATH, Chess Move Validity

21. Playing Repeated Games With Large Language Models[[ICIR2024](https://openreview.net/pdf?id=CSpWgKo0ID)]
- task:cooperation and coordination games.

22.Large Language Models Can Design Gametheoretic Objectives For Multi-Agent Planning[[ICIR2024](https://openreview.net/pdf?id=DnkCvB8iXR)]
- task: Embodied Intelligence 
- Dataset:ThreeDWorld Transport Challenge

23.Metaagents: Simulating Interactions Of HuMan Behaviors For Llm-Based Task-Oriented Coordination Via Collaborative Generative Agents[[ICIR2024](https://arxiv.org/pdf/2310.06500.pdf)]
- task: Task-oriented Social

24.GameGPT: Multi-agent Collaborative Framework For Game Development[[ICIR2024](https://arxiv.org/pdf/2310.08067.pdf)]
- task: Coding

## Datasets
We gather information on commonly used datasets for reference. Please be aware that there may be slight difference in the dataset due to different versions.

| Name (link) | Task | Number | Evaluation* | Paper |
|-------------|------|--------|-------------|-------|
|   [Hotpot-QA](https://github.com/facebookresearch/KILT)  | open-domain QA   |   train/dev/test:  88k/5.6k/5.6k    |    Exactly Match (EM)    |   [Paper](https://aclanthology.org/D18-1259.pdf)    |
|   [mmlu](https://huggingface.co/datasets/cais/mmlu)|multiple-choice questions|train/dev/test:  99.8k/285/1.531k||[paper](https://arxiv.org/pdf/2009.03300.pdf)|
|   [math](https://github.com/hendrycks/math/)|reasoning|||[paper](https://github.com/hendrycks/math/)|
|             |      |        |             |       |



## Acknoledgement
Acknowledging all the paper authors for their excellent works. We also extend our thanks to all contributors.

**For Contribution**: There are cases where we miss important works in this field, please contribute to this repo! Thanks for the efforts in advance.


## Contact
For any question, feel free to contact us. We also welcome any form of collaboration.

Email: shizhl@mail.sdu.edu.cn

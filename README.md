# Papers for LLM-based Agents Collaboration
In the era of large language models (LLMs), LLM-based agents have shown remarkable performance in several existing benchmarks or real-world applications. Nevertheless, they still face difficulties in tackling complex tasks. Inspired by collaborative problem solving, several recent works use the strategy of multi-agent collaboration as a potential solution.

We collect the **Must-read papers** to catch up and share the state-of-the-art methods, facilitating the related research. 

## LLM-based Agent

1. ReAct: Synergizing Reasoning and Acting in Language Models [[ICLR2023](https://arxiv.org/abs/2210.03629)] [[code](https://react-lm.github.io/)]
- Dataset: HotpotQA, FEVER, ALFWorld, WebShop

Link: more previous works can be found in:
- [[LLM-based autonomous agent](https://github.com/Paitesanshi/LLM-Agent-Survey#-construction-of-llm-based-autonomous-agent)]
- [[Awesome-Agent-papers]](https://github.com/lafmdp/Awesome-Papers-Autonomous-Agent)
- [[Fdu-LLM-Agent-Paper-List]](https://github.com/WooooDyy/LLM-Agent-Paper-List)

Thanks a lot for pioneering effort.

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

4. OKR-Agent: An Object And Key Results Driven Agent System With Hierarchical Self-Collaboration And Self-Evaluation[[ICLR2024](https://openreview.net/pdf?id=Mngdhgi711)]
- task: Storyboard Generation, Creative Writing, Trip Planning
- Dataset: (case study)

5. Reason To Behave: Achieving Human-Level Task Execution For Physics-Based Characters[[ICLR2024](https://openreview.net/pdf?id=Y6PVsnkKVV)][[code](https://sites.google.com/view/reasontobehave)]
- task: Path Planning
- Dataset: MoCap

6. Co-NavGPT: Multi-Robot Cooperative Visual Semantic Navigation using Large Language Models [[paper]](https://arxiv.org/pdf/2310.07937.pdf) [[code]](https://sites.google.com/view/co-navgpt)
- task: Visual Semantic Navigation
- Dataset: HM3D

7. Cognitive Architectures For Language [[paper]](https://arxiv.org/pdf/2309.02427.pdf)

8. Multi-agent Consensus Seeking Via Large Language Models [[paper]](https://arxiv.org/abs/2310.20151)

9. Openagi: When LLM Meets Domain Experts [[paper]](https://arxiv.org/abs/2304.04370)

10. Evaluating Multi-agent Coordination Abilities In Large Language Models [[paper]](https://arxiv.org/pdf/2310.03903.pdf)

11. Communicative Agents For Software Development [[paper]](https://arxiv.org/abs/2307.07924)

12. Describe, Explain, Plan And Select: Interactive Planning With Large Language Models Enables Open-world Multi-task Agents [[paper]](https://arxiv.org/abs/2302.01560)

13. Exploring Collaboration Mechanisms For Llm Agents: A Social Psychology View [[paper]](https://arxiv.org/abs/2310.02124)

14. When Large Language Model Based Agent Meets User Behavior Analysis: A Novel User Simulation Paradigm [[paper]](https://arxiv.org/abs/2306.02552)

15. Ghost In The Minecraft: Hierarchical Agentsfor Minecraft Via Large Language Models With Text-Based Knowledge And Memory[[ICIR2024](https://openreview.net/pdf?id=cTOL99p5HL)]
- task:Path Planning

16. Adapting Llm Agents Through Communication[[ICIR2024](https://openreview.net/pdf?id=wOelVq8fwL)]
- task:Path Planning, QA,Math reasoning
- Dataset:ALFWorld, HotpotQA, GSM8k

17. Agentverse: Facilitating Multi-Agent Collaboration And Exploring Emergent Behaviors[[ICIR2024](https://openreview.net/pdf?id=EHg5GDnyq1)][[code](https://github.com/OpenBMB/AgentVerse.)]
- task:Conversation, Mathematical Calculation, Logical Reasoning, Coding
- Dataset:FED, Commongen-Challenge, MGSM, BigBench, Humaneval

18. Debategpt: Fine-Tuning Large Language Models With Multi-Agent Debate Supervision[[ICIR2024](https://openreview.net/pdf?id=ChNy95ovpF)]
- task:Reasoning, Math
- Dataset:AlpacaEval, MMLU, Arithmetic, Winogrande, AI2 Reasoning Challenge

19. Corex: Pushing The Boundaries Of Complex Reasoning Through Multi-Model Collaboration[[ICIR2024](https://openreview.net/pdf?id=GDdxmymrwL)][[code](https://anonymous.4open.science/r/Corex)]
- task:Reasoning
- Dataset:GSM8K, MultiArith, SingleOP/SingleEQ, AddSub, AQuA, SVAMP,GSMHard,StrategyQA, CommonsenseQA, BoolQ ,AI2 Reasoning Challenge (ARC-c),BigBench,FinQA, ConvFinQA, TAT-QA

20. Chateval: Towards Better Llm-Based Evaluators Through Multi-Agent Debate[[ICIR2024](https://openreview.net/pdf?id=FQepisCUWu)]
- task:QA
- Dataset:FairEval, Topical-Chat

21. Language Agents With Reinforcement Learning For Strategic Play In The Werewolf Gam[[ICIR2024](https://openreview.net/pdf?id=N1gmpVd4iE)]
- task:Werewolf game

22. Dynamic Llm-Agent Network:An Llm-Agent Collaboration Framework With Agent Team Optimization[[ICIR2024](https://openreview.net/pdf?id=i43XCU54Br)]
- task:arithmetic reasoning, general reasoning, code generation.
- Dataset:MATH, MMLU, HumanEval

23. Welfare Diplomacy:Benchmarking Language Model Cooperation[[ICIR2024](https://openreview.net/pdf?id=AKJLnDgzkm)][[code](https://anonymous.4open.science/r/welfare-diplomacy-72AC)]

24. Mindagent: Emergent Gaming Interaction[[ICIR2024](https://openreview.net/pdf?id=p9pBJv1DTz)]
- task:CuisineWorld

25. Building Cooperative Embodied Agents Modularly With Large Language Model[[ICIR2024](https://openreview.net/pdf?id=EnXJfQqy0K)][[code](https://llm-co.github.io/CoELA/.)]
- Dataset:ThreeDWorld Multi-Agent Transport (TDW-MAT)

26. Autoagents: A Framework For Automaticagent Generation [[ICIR2024](https://openreview.net/pdf?id=PhJUd3mbhP)][[code](https://anonymous.4open.science/r/AutoAgents-747C.)]
- task:Open-ended Question Answer task,Trivia Creative Writing

27. Metagpt: Meta Programming For A Multi-Agent Collaborative Framework[[ICIR2024](https://openreview.net/pdf?id=VtmBAGCN7o)]
- task:Coding
- Dataset:HumanEval, MBPP, SoftwareDev

28. Oceangpt: A Large Language Model For Ocean Science Tasks[[ICIR2024](https://openreview.net/pdf?id=pbfy04zvcH)]
- task:Ocean-related Task

29. Exploring Collaboration Mechanisms For Llm Agents: A Social Psychology View[[ICIR2024](https://openreview.net/pdf?id=ueqTjOcuLc)]
- Dataset:MMLU, MATH, Chess Move Validity

30. Playing Repeated Games With Large Language Models[[ICIR2024](https://openreview.net/pdf?id=CSpWgKo0ID)]
- task:cooperation and coordination games.

31. Large Language Models Can Design Gametheoretic Objectives For Multi-Agent Planning[[ICIR2024](https://openreview.net/pdf?id=DnkCvB8iXR)]
- task: Embodied Intelligence 
- Dataset:ThreeDWorld Transport Challenge

32. Metaagents: Simulating Interactions Of HuMan Behaviors For Llm-Based Task-Oriented Coordination Via Collaborative Generative Agents[[ICIR2024](https://arxiv.org/pdf/2310.06500.pdf)]
- task: Task-oriented Social

33. GameGPT: Multi-agent Collaborative Framework For Game Development[[ICIR2024](https://arxiv.org/pdf/2310.08067.pdf)]
- task: Coding

34. AgentCF: Collaborative Learning with Autonomous Language Agents for Recommender Systems [[paper]](https://arxiv.org/abs/2310.09233)
- task: Recommendation

35. [2023/10] AutoAgents: A Framework for Automatic Agent Generation. (Peking University) [[paper](https://arxiv.org/abs/2309.17288)] [[code](https://github.com/Link-AGI/AutoAgents)]

36. [2023/08] CGMI: Configurable General Multi-Agent Interaction Framework. (East China Normal University) [[paper](https://arxiv.org/abs/2308.12503)]

37. [2023/08] ProAgent: Building Proactive Cooperative AI with Large Language Models. (The Chinese University of Hong Kong, Shenzhen) [[paper](https://arxiv.org/abs/2308.11339)] [[code](https://pku-proagent.github.io/)]

38. [2023/08] AgentVerse: Facilitating Multi-Agent Collaboration and Exploring Emergent Behaviors in Agents. (Tsinghua University)[[paper](https://arxiv.org/abs/2308.10848)] [[code](https://github.com/OpenBMB/AgentVerse)]

39. [2023/08] AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation Framework. (Pennsylvania State University) [[paper](https://arxiv.org/abs/2308.08155)] [[code](https://microsoft.github.io/FLAML/docs/Use-Cases/Autogen/)]

40. [2023/08] MetaGPT: Meta Programming for Multi-Agent Collaborative Framework. (DeepWisdom) [[paper](https://arxiv.org/abs/2308.00352)] [[code](https://github.com/geekan/MetaGPT)]

41. [2023/08] ChatEval: Towards Better LLM-based Evaluators through Multi-Agent Debate. (Tsinghua University) [[paper](https://arxiv.org/abs/2308.07201)] [[code](https://github.com/thunlp/ChatEval)]

42. [2023/07] Communicative Agents for Software Development. (Tsinghua University) [[paper](https://arxiv.org/abs/2307.07924)] [[code](https://github.com/openbmb/chatdev)]

43. [2023/07] Unleashing Cognitive Synergy in Large Language Models: A Task-Solving Agent through Multi-Persona Self-Collaboration. (University of Illinois Urbana-Champaign) [[paper](https://arxiv.org/abs/2307.05300)] [[code](https://github.com/MikeWangWZHL/Solo-Performance-Prompting)]

44. [2023/07] RoCo: Dialectic Multi-Robot Collaboration with Large Language Models. (Columbia University) [[paper](https://arxiv.org/abs/2307.04738)] [[code](https://project-roco.github.io/)]

45. [2023/06] Multi-Agent Collaboration: Harnessing the Power of Intelligent LLM Agents. (University of Alberta) [[paper](https://arxiv.org/abs/2306.03314)]

46. [2023/05] Training Socially Aligned Language Models in Simulated Human Society. (Dartmouth College) [[paper](https://arxiv.org/abs/2305.16960)] [[code](https://github.com/agi-templar/Stable-Alignment)]

47. [2023/05] SwiftSage: A Generative Agent with Fast and Slow Thinking for Complex Interactive Tasks. (Allen Institute for Artificial Intelligence) [[paper](https://arxiv.org/abs/2305.17390)] [[code](https://yuchenlin.xyz/swiftsage/)]

48. [2023/05] ChatGPT as your Personal Data Scientist. (Auburn University) [[paper](https://arxiv.org/abs/2305.13657)]

49. [2023/05] Agents: An Open-source Framework for Autonomous Language Agents. (AIWaves) [[paper](https://arxiv.org/pdf/2309.07870.pdf)] [[code](https://github.com/aiwaves-cn/agents)]

50. [2023/05] Improving Factuality and Reasoning in Language Models through Multiagent Debate. (MIT CSAIL) [[paper](https://arxiv.org/abs/2305.14325)] [[code](https://composable-models.github.io/llm_debate/)]

51. [2023/05] Improving Language Model Negotiation with Self-Play and In-Context Learning from AI Feedback. (University of Edinburgh) [[paper](https://arxiv.org/abs/2305.10142)] [[code](https://github.com/FranxYao/GPT-Bargaining)]

52. [2023/05] Examining the Inter-Consistency of Large Language Models: An In-depth Analysis via Debate. (Harbin Institute of Technology) [[paper](https://arxiv.org/abs/2305.11595)]

53. [2023/05] Encouraging Divergent Thinking in Large Language Models through Multi-Agent Debate.  (Tsinghua University) [[paper](https://arxiv.org/abs/2305.19118)] [[code](https://github.com/Skytliang/Multi-Agents-Debate)]

54. [2023/04] ChatLLM Network: More brains, More intelligence. (Beijing University of Posts and Telecommunications) [[paper](https://arxiv.org/abs/2304.12998)]

55. [2023/04] Self-collaboration Code Generation via ChatGPT. (Peking University) [[paper](https://arxiv.org/abs/2304.07590)]

56. [2023/03] CAMEL: Communicative Agents for "Mind" Exploration of Large Scale Language Model Society. (King Abdullah University of Science and Technology) [[paper](https://arxiv.org/abs/2303.17760)] [[code](https://github.com/lightaime/camel)]

57. [2023/03] DERA: Enhancing Large Language Model Completions with Dialog-Enabled Resolving Agents. (Curai Health) [[paper](https://arxiv.org/abs/2303.17071)] [[code](https://github.com/curai/curai-research/tree/main/DERA)]

58. [2023/01] Blind Judgement: Agent-Based Supreme Court Modelling With GPT. (McGill University) [[paper](https://arxiv.org/abs/2301.05327)]


## Datasets
We gather information on commonly used datasets for reference. Please be aware that there may be slight difference in the dataset due to different versions.

| Name (link) | Task | Number | Evaluation* | Paper |
|-------------|------|--------|-------------|-------|
|[Hotpot-QA](https://github.com/facebookresearch/KILT)  | open-domain QA   |   train/dev/test:  88k/5.6k/5.6k    |    Exactly Match (EM)    |   [Paper](https://aclanthology.org/D18-1259.pdf)    |
|[mmlu](https://huggingface.co/datasets/cais/mmlu)|multiple-choice questions|train/dev/test:  99.8k/285/1.531k||[paper](https://arxiv.org/pdf/2009.03300.pdf)|
|[math](https://github.com/hendrycks/math/)|reasoning|||[paper](https://github.com/hendrycks/math/)|
|[ALFWorld](https://github.com/alfworld/alfworld)|Embodied AI|||[paper](https://arxiv.org/pdf/2010.03768.pdf)|
|[HOTPOTQA](https://hotpotqa.github.io/)|QA|||[paper](https://arxiv.org/pdf/1809.09600.pdf)|
|[Natural Questions](https://ai.google.com/research/NaturalQuestions)|QA|30.7k//0.78k||[paper](https://aclanthology.org/Q19-1026/)|
|[GSM8K](https://github.com/openai/grade-school-math)         |   reasoning   |        |             |  [paper](https://arxiv.org/abs/2110.14168)     |
|[Humaneval](https://github.com/openai/human-eval)|coding|||[paper](https://arxiv.org/abs/2107.03374)|
|[BigBench](https://huggingface.co/datasets/bigbench)|coding|||[paper](https://doi.org/10.48550/arxiv.2206.04615)|
|[AI2 Reasoning Challenge](https://allenai.org/data/arc)|choice question|||[paper](https://www.semanticscholar.org/paper/Think-you-have-Solved-Question-Answering-Try-ARC%2C-Clark-Cowhey/88bb0a28bb58d847183ec505dda89b63771bb495)|
|[MGSM](https://huggingface.co/datasets/juletxara/mgsm)|Math|8/0.25k||[paper](https://arxiv.org/abs/2110.14168)|
|[FairEval](https://github.com/i-Eval/FairEval)|llm evaluation|||[paper](https://arxiv.org/abs/2305.17926)|
|[MBPP](https://huggingface.co/datasets/mbpp)|coding|0.37k/0.09k/0.5k||[paper](https://arxiv.org/abs/2108.07732)|
|[Topical-Chat](https://github.com/alexa/Topical-Chat)|chat|||[paper](https://arxiv.org/abs/2308.11995)|
|[WinoGrande](https://huggingface.co/datasets/winogrande)|choice|9.25k/1.25k/1.77k||[paper](https://arxiv.org/abs/1907.10641)|
|[CommonsenseQA](https://allenai.org/data/commonsenseqa)|commonsense knowledge QA|||[paper](https://aclanthology.org/N19-1421/)|
|[FinQA](https://github.com/czyssrs/FinQA)|Numerical Reasoning over Financial Data|||[paper](https://arxiv.org/abs/2109.00122)|
|[boolq](https://huggingface.co/datasets/boolq)|yes/no questions|9.23k//3.27k||[paper](https://arxiv.org/abs/1905.10044)|
|[GSMHard](https://huggingface.co/datasets/reasoning-machines/gsm-hard)|math|1.32k//|||
|[SVAMP](https://github.com/arkilpatel/SVAMP)|math|||[paper](https://arxiv.org/abs/2103.07191)|
|[ConvFinQA](https://github.com/czyssrs/ConvFinQA)|Numerical Reasoning in Conversational Finance|3k/0.4k/0.4k||[paper](https://arxiv.org/abs/2210.03849)|
|[TAT-QA](https://github.com/NExTplusplus/TAT-QA)|Finance QA|||[paper](https://arxiv.org/abs/2105.07624)|
|[MultiArith](https://huggingface.co/datasets/ChilleD/MultiArith)|math||||
|[common_gen](https://huggingface.co/datasets/common_gen)| constrained text generation task|67.4k/4.02k/1.5k||[paper](https://arxiv.org/abs/1911.03705)|
||||||

## Evaluation
1. Theory Of Mind For Multi-agent Collaboration Via Large Language Models [[paper]](https://arxiv.org/pdf/2310.10701.pdf)
2. Evaluating Large Language Models at Evaluating Instruction Following [[paper]](https://openreview.net/forum?id=tr0KidwPLc)



## Acknoledgement
Acknowledging all the paper authors for their excellent works. We also extend our thanks to all contributors.

**For Contribution**: There are cases where we miss important works in this field, please contribute to this repo! Thanks for the efforts in advance.


## Contact
For any question, feel free to contact us. We also welcome any form of collaboration.

Email: shizhl@mail.sdu.edu.cn

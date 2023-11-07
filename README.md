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

2. AUTOGEN: ENABLING NEXT-GEN LLM APPLICATIONS VIA MULTI-AGENT CONVERSATION[[ICLR2024](https://openreview.net/pdf?id=tEAF9LBdgu)][[code](https://anonymous.4open.science/r/autogen-iclr2024/README.md)]
- task:Math, QA, Decision, Coding, Chat, Chess
- Dataset: MATH, Natural Questions, ALFWorld

3. CHAIN-OF-EXPERTS: WHEN LLMS MEET COMPLEX OPERATIONS RESEARCH PROBLEMS[[ICLR2024](https://openreview.net/pdf?id=HobyL1B9CZ)][[code](https://github.com/nl4opt/nl4opt-competition)]
- task: Math(LP)
- Dataset: LPWP, ComplexOR

4. OKR-AGENT: AN OBJECT AND KEY RESULTS DRIVEN AGENT SYSTEM WITH HIERARCHICAL SELF-COLLABORATION AND SELF-EVALUATION[[ICLR2024](https://openreview.net/pdf?id=Mngdhgi711)]
- task: storyboard generation, creative writing, trip planning

5. REASON TO BEHAVE: ACHIEVING HUMAN-LEVEL TASK EXECUTION FOR PHYSICS-BASED CHARACTERS[[ICLR2024](https://openreview.net/pdf?id=Y6PVsnkKVV)][[code](https://sites.google.com/view/reasontobehave)]
- task: Path Planning
- Dataset: MoCap

6. GHOST IN THE MINECRAFT: HIERARCHICAL AGENTSFOR MINECRAFT VIA LARGE LANGUAGE MODELS WITH TEXT-BASED KNOWLEDGE AND MEMORY[[ICIR2024](https://openreview.net/pdf?id=cTOL99p5HL)]
- task:Path Planning

7. ADAPTING LLM AGENTS THROUGH COMMUNICATION[[ICIR2024](https://openreview.net/pdf?id=wOelVq8fwL)]
- task:Path Planning, QA,Math reasoning
- Dataset:ALFWorld, HotpotQA, GSM8k

8. AGENTVERSE: FACILITATING MULTI-AGENT COLLABORATION AND EXPLORING EMERGENT BEHAVIORS[[ICIR2024](https://openreview.net/pdf?id=EHg5GDnyq1)][[code](https://github.com/OpenBMB/AgentVerse.)]
- task:Conversation, Mathematical Calculation, Logical Reasoning, Coding
- Dataset:FED, Commongen-Challenge, MGSM, BigBench, Humaneval

9.DEBATEGPT: FINE-TUNING LARGE LANGUAGE MODELS WITH MULTI-AGENT DEBATE SUPERVISION[[ICIR2024](https://openreview.net/pdf?id=ChNy95ovpF)]
- task:Reasoning, Math
- Dataset:AlpacaEval, MMLU, Arithmetic, Winogrande, AI2 Reasoning Challenge

10. Corex: PUSHING THE BOUNDARIES OF COMPLEX REASONING THROUGH MULTI-MODEL COLLABORATION[[ICIR2024](https://openreview.net/pdf?id=GDdxmymrwL)][[code](https://anonymous.4open.science/r/Corex)]
- task:Reasoning
- Dataset:GSM8K, MultiArith, SingleOP/SingleEQ, AddSub, AQuA, SVAMP,GSMHard,StrategyQA, CommonsenseQA, BoolQ ,AI2 Reasoning Challenge (ARC-c),BigBench,FinQA, ConvFinQA, TAT-QA

11. CHATEVAL: TOWARDS BETTER LLM-BASED EVALUATORS THROUGH MULTI-AGENT DEBATE[[ICIR2024](https://openreview.net/pdf?id=FQepisCUWu)]
- task:QA
- Dataset:FairEval, Topical-Chat

 12. LANGUAGE AGENTS WITH REINFORCEMENT LEARNING FOR STRATEGIC PLAY IN THE WEREWOLF GAM[[ICIR2024](https://openreview.net/pdf?id=N1gmpVd4iE)]
- task:Werewolf game

 13.DYNAMIC LLM-AGENT NETWORK:AN LLM-AGENT COLLABORATION FRAMEWORK WITH AGENT TEAM OPTIMIZATION[[ICIR2024](https://openreview.net/pdf?id=i43XCU54Br)]
- task:arithmetic reasoning, general reasoning, code generation.
- Dataset:MATH, MMLU, HumanEval

14. WELFARE DIPLOMACY:BENCHMARKING LANGUAGE MODEL COOPERATION[[ICIR2024](https://openreview.net/pdf?id=AKJLnDgzkm)][[code](https://anonymous.4open.science/r/welfare-diplomacy-72AC)]

15. MINDAGENT: EMERGENT GAMING INTERACTION[[ICIR2024](https://openreview.net/pdf?id=p9pBJv1DTz)]
- task:CuisineWorld

16. BUILDING COOPERATIVE EMBODIED AGENTS MODULARLY WITH LARGE LANGUAGE MODEL[[ICIR2024](https://openreview.net/pdf?id=EnXJfQqy0K)][[code](https://llm-co.github.io/CoELA/.)]
- Dataset:ThreeDWorld Multi-Agent Transport (TDW-MAT)

17. AUTOAGENTS: A FRAMEWORK FOR AUTOMATICAGENT GENERATION [[ICIR2024](https://openreview.net/pdf?id=PhJUd3mbhP)][[code](https://anonymous.4open.science/r/AutoAgents-747C.)]
- task:Open-ended Question Answer task,Trivia Creative Writing

18. METAGPT: META PROGRAMMING FOR A MULTI-AGENT COLLABORATIVE FRAMEWORK[[ICIR2024](https://openreview.net/pdf?id=VtmBAGCN7o)]
- task:Coding
- Dataset:HumanEval, MBPP, SoftwareDev

19. OCEANGPT: A LARGE LANGUAGE MODEL FOR OCEAN SCIENCE TASKS[[ICIR2024](https://openreview.net/pdf?id=pbfy04zvcH)]
- task:ocean-related task

20. EXPLORING COLLABORATION MECHANISMS FOR LLM AGENTS: A SOCIAL PSYCHOLOGY VIEW[[ICIR2024](https://openreview.net/pdf?id=ueqTjOcuLc)]
- Dataset:MMLU, MATH, Chess Move Validity

21. PLAYING REPEATED GAMES WITH LARGE LANGUAGE MODELS[[ICIR2024](https://openreview.net/pdf?id=CSpWgKo0ID)]
- task:cooperation and coordination games.

22.LARGE LANGUAGE MODELS CAN DESIGN GAMETHEORETIC OBJECTIVES FOR MULTI-AGENT PLANNING[[ICIR2024](https://openreview.net/pdf?id=DnkCvB8iXR)]
- task: Embodied Intelligence 
- Dataset:ThreeDWorld Transport Challenge

## Datasets
We gather information on commonly used datasets for reference. Please be aware that there may be slight difference in the dataset due to different versions.

| Name (link) | Task | Number | Evaluation* | Paper |
|-------------|------|--------|-------------|-------|
|   [Hotpot-QA](https://github.com/facebookresearch/KILT)  | open-domain QA   |   train/dev/test:  88k/5.6k/5.6k    |    Exactly Match (EM)    |   [Paper](https://aclanthology.org/D18-1259.pdf)    |
|             |      |        |             |       |



## Acknoledgement
Acknowledging all the paper authors for their excellent works. We also extend our thanks to all contributors.

**For Contribution**: There are cases where we miss important works in this field, please contribute to this repo! Thanks for the efforts in advance.


## Contact
For any question, feel free to contact us. We also welcome any form of collaboration.

Email: shizhl@mail.sdu.edu.cn

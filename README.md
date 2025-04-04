# project_drafter

This repo present and share an initial exploration of the usage of an AI [Multi-Agent System](https://en.wikipedia.org/wiki/Multi-agent_system) to design project proposal, based on recommendations from the IOM (International Organization for Migration) project proposal template and [IOM project handbook](https://publications.iom.int/system/files/pdf/iom_project_handbook_6feb2012.pdf).

The [notebook](http://iom.github.io/project_drafter) will help you understand the basics of [CrewAI](https://www.crewai.com/), an open source framework for building autonomous AI agents that work together to accomplish such complex tasks. The system will consist of multiple agents, each with specific roles and responsibilities, to collaboratively create a __comprehensive project proposal__. 

In the first iteration, the system has one agent writing the report and a second one doing the review. In the second, iteration, the system include a "manager agent" that oversees the collaboration and ensures that the final output is coherent and meets the requirements of the project proposal template. The manager agent will coordinate the efforts of the other agents, ensuring that they work together effectively and that the final output is a well-structured and comprehensive project proposal.

The system shall take an input prompt that outlines the project idea, its location, the targeted donor, an an estimation of budget and duration. The agents will be designed to handle different sections of the proposal, ensuring that all necessary components are covered.

## A first example

For this example, we requested the system to create a project proposal for a fictitious global project "Develop the usage of AI to improve IOM efficiency when drafting project proposals". The project is expected to last 12 months and has an estimated budget of $130,000. The targeted donor is IOM. 

You can review the output in the [output folder of this repository](https://github.com/iom/project_drafter/tree/main/output) as well as the instructions for the agents and tasks within the notebook itself. Do not hesitate to [provide feedback](https://github.com/iom/project_drafter/issues/newhttps://github.com/iom/project_drafter/issues/new).

## Proposal Template Description  

The IOM project proposal template is a comprehensive document that outlines the key components of a project proposal. It includes the following sections:


### 1. Project Summary (350 words max)

Provide a brief overview of the proposed project, including the context and the need, and the objective of the project.
Also, describe how the project's activities will achieve the key outputs, and how outputs are likely to influence the achievement of the project's outcomes.

### 2. Project Rationale (400 words max)

Justify the project being proposed by describing its rationale: 

1. What is the problem, for whom is it a problem and why is it significant? 
 - What is the situation to be addressed? 
 - Why is the situation a problem? 
 - Is the problem ongoing or is it foreseen to be realized within the foreseeable future? 
 - Where, specifically, is it a problem? 
 - For whom is it a problem? How is it affecting certain groups differently, such as men, women, boys, girls and other groups? 

2. Why is the problem the right one to address? 
 - How would solving the problem be of value to the intended beneficiaries? 
 - How might it affect other groups? Consider unintended negative consequences for all groups affected, whether or not they are the focus of the project.

3. How is the project linked to broader national, regional, and/or global initiatives, including IOM internal strategies and results frameworks? 

### 3. Project Description  (600 words max)

Articulate and outline how and why a set of intended results and activities will bring about the changes the project seeks to achieve. More specifically: 

1. What is the intended change brought about by the project? What are the assumptions and hypotheses underlying the casual relationships between activities, outputs and outcomes?
 - Why is the approach being proposed to address the problem(s) the best course of action?
 - What are the assumptions that must hold true in order that results are realized?
 - What are the hypotheses explaining why it is thought that the implementation of activities will lead to the achievement of outputs, why the achievement of outputs will influence the achievement of outcomes, and why the achievement of outcomes will contribute to the project objective?

2. Who are the stakeholders?
- Why is IOM best placed to address the problem?
- What is IOM's added value/comparative advantage in implementing the project? 
- What special skills, knowledge and/or capacities does IOM have to justify its involvement?
- Which other stakeholders would be involved in the project, and why are they required for the project to succeed?
- Consider gender and age when identifying stakeholders and strive for stakeholders who are representative of the target population.

3. How will the project address the following cross-cutting themes of rights-based approach to programming, gender mainstreaming, environmental sensitivity and sustainability, sustainability of project results, principled humanitarian action and mainstreaming protection in crisis response? 

### 4. Partnerships and Coordination Arrangements (350 words max)

Describe the role and/or the key responsibilities of each of the main partners who will be involved in the implementation of the project. Also describe how the project management structure will ensure that the main partners will coordinate their activities. 

### 5. Monitoring Approach (350 words max)

Indicate how the project will monitor the main aspects of the project by providing an overview of the roles and responsibilities of team members. 

Describe how data for the project indicators will be collected, what data collection tools will be used, and how often data will be collected and analysed. 

If working through implementing partners, mention how they will be monitored and their reporting requirements, and in particular if working in a remote management situation with difficult access due to security. 

### 6. Evaluation Approach (350 words max)

Indicate the timing and purpose of the evaluation, its intended use and the evaluation criteria to be used. 
Briefly describe the expected methodology to be employed in realizing the evaluation purpose, and indicate if the evaluation would be conducted internally or externally. 

### 7. Results Matrix

This shall be formatted as a table with the following columns:

1. __Objective__: The most significant, realistic goal to which the project can contribute. It seeks to align to a broader, longer-term strategy, whether internal or external. 

2. __Outcome__: The intended changes in institutional performance, individual or group behaviour or attitudes, or the political, economic, or social position of the beneficiaries.

3. __Output__: The intended changes in the skills or abilities of the beneficiaries, or the availability of new products or services as a result of project activities. 

For each Objective, outcome and output, define Indicators, aka, Quantitative or qualitative factors or variables to measure achievement or to reflect expected changes (this part shall be aligned with the previous parts on Monitoring and Evaluation).

For each indicator, provide the following information:

- Indicate how data is to be disaggregated by key characteristics (age, sex), wherever relevant. 

- Define potential Data source and collection method indicate from where and how information will be gathered for the purposes of measuring the indicator.

- Set up Baseline: Establishes the value of the indicator at the beginning of the project planning period. Disaggregated by key characteristics (age, sex), wherever relevant. 

- Set up Target: Describes the expected value of the indicator upon completion of the result. Disaggregated by key characteristics (age, sex), wherever relevant.

- Mention Assupmtions: The conditions that must be in place for the indicator to be achieved.  


### 8. Workplan

Develop a Workplan, formatted as as table, that includes the following information: 

- When are the main activities expected to begin? 
- How long will they last? 
- When will they be completed? 
- Which partners are responsible for the implementation of each of the main activities? (this part shall be aligned with the previous stakholder mapping)

### 9. Budget

Prepare a budget using an appropriate budget template.
 
### 10. Risk Assessment Plan

The ouput shall be formatted as a table with the following columns:

- __Risk Factors__: List the risk factors identified during risk analysis processes.	

- __Consequence__: For each risk, indicate a rank of the risk consequence, from 1 to 6, based on the analysis done using a modified version of Tool 1.10 as per the context of the project idea.

- __Likelihood and Timeline__: For each risk, insert likelihood and timeline ranking as per the Risk Register, with any necessary revisions or updates.	

- __Risk Treatment Plan__: For each risk, select the treatment option: 
• Avoiding the risk 
• Changing the likelihood of the risk 
• Changing the consequence of the risk 
• Sharing the risk with another party 
• Tolerating the risk without further treatment.

- __Treatment action__: For each risk, describe the action to be taken to implement the treatment option (e.g. build a road, conduct public info campaigns).


















### Working offline - Using Ollama with a local small 7B model

If you can not access any LLM  API, you can install one offline running locally on your computer.

In shell run: 

> winget install Ollama 
> ollama run deepseek-r1

```{python}
#| eval: false
from langchain_ollama import OllamaLLM

#  Initialize Ollama with explicit settings
llm_deepseek = OllamaLLM(
    model="deepseek-r1:latest",
    base_url="http://localhost:11434",
    keep_alive="10m",       # Keep the model loaded for 10 minutes
    num_ctx=4096,           # Increase context length
   # num_gpu=1,              # Use 1 GPU if you have one....
    temperature=0.7,        # Slight randomness in responses
    top_p=0.9,              # Probability sampling
    system="You are an AI expert specialised in Humanitarian Project management.",
    verbose=True,            # Enable debugging logs
    timeout=300  # Important for larger responses
)

# Example usage
response = llm_deepseek.invoke("If you have to create a humanitarian project proposal, what are the key steps you would start and decision point you need before starting writing the document?")
print(response)
```

Check anoter model directly from Hugging Face

> ollama run hf.co/bartowski/OpenThinker-7B-GGUF:IQ4_XS

```{python}
#| eval: false
from langchain_ollama import OllamaLLM

#  Initialize Ollama with explicit settings
llm_OpenThinker = OllamaLLM(
    model="hf.co/bartowski/OpenThinker-7B-GGUF:IQ4_XS",
    base_url="http://localhost:11434",
    keep_alive="10m",       # Keep the model loaded for 10 minutes
    num_ctx=4096,           # Increase context length
   # num_gpu=1,              # Use 1 GPU if you have one....
    temperature=0.7,        # Slight randomness in responses
    top_p=0.9,              # Probability sampling
    system="You are an AI expert specialised in Humanitarian Project management.",
    verbose=True,            # Enable debugging logs
    timeout=300  # Important for larger responses
)

# Example usage
response = llm_OpenThinker.invoke("If you have to create a humanitarian project proposal, what are the key steps you would start and decision point you need before starting writing the document?")
print(response)
 
```
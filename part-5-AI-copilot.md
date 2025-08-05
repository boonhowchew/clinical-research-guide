# Part 5: Supercharging Your Prevalence Study with an AI Co-Pilot

This section provides a structured framework for leveraging Large Language Models (LLMs) like ChatGPT, Gemini, and Claude as a collaborative co-pilot throughout your research process. The key to a successful partnership with an AI is structure. Just as you wouldn't ask a junior research assistant to "do the research" without context, you must properly brief your AI.

Before you begin with the specific prompts for each section, you will use the **"Master Prompt"** below to set the stage for your entire working session. This initial prompt establishes the AI's role, the context of your project, and the rules of your collaboration. Providing this detailed setup at the start will dramatically improve the quality, relevance, and consistency of all subsequent responses.

---

## LLM Master Prompt: Setting Up Your AI Research Co-Pilot

*Instructions: Copy and paste this entire template into your chosen LLM at the very beginning of your session. Fill in the bracketed information with the details of your study.*

### 1. Role, Goal, and Context (The Setup)

**Act as my expert Clinical Research Co-Pilot.** Your persona is a multi-disciplinary expert with deep knowledge in:
*   Clinical Epidemiology
*   Biostatistics
*   Academic Writing for Medical Journals
*   Research Ethics

**Your primary goal** is to collaboratively guide me, as a novice clinician-researcher, through the entire process of planning a methodologically sound clinical prevalence study, from idea to a ready-to-submit proposal, following established best practices.

**The core context of our project is as follows:**
*   **Broad Topic:** `[e.g., Postpartum depression]`
*   **Specific Population:** `[e.g., First-time mothers in a multi-ethnic urban setting in Southeast Asia]`
*   **Primary Setting:** `[e.g., Government maternal and child health clinics]`
*   **Overall Research Aim:** `[e.g., To determine the prevalence of postpartum depression and identify its key psychosocial risk factors in this population to inform early screening strategies.]`

### 2. Rules of Engagement (Our Collaboration Protocol)

Throughout our conversation, you must adhere to the following rules:
*   **Expert Guidance, Not Final Answers:** Your role is to provide expert suggestions, drafts, and explanations. The final decision and responsibility always rest with me.
*   **Ask Clarifying Questions:** If my prompts are vague or missing critical information for a task, you must ask me for the necessary details before proceeding.
*   **No Fabrication:** You must not fabricate data, references, or statistical results. If you do not have information, state that clearly.
*   **Justify Recommendations:** When you recommend a specific method, statistical test, or strategy, briefly explain the rationale behind your choice.
*   **Maintain Your Persona:** All your responses should be from the perspective of the expert Clinical Research Co-Pilot, adopting a formal, educational, and encouraging tone.

### 3. How We Will Work (The Process)

Our workflow will follow the structure of my research guide. I will provide you with prompts corresponding to specific sections of the guide (e.g., "Now, let's work on Section 2.2: Sample Size"). You will provide a detailed response for that specific task, keeping the overall project context in mind.

If you understand this setup, please confirm by stating: **"Clinical Research Co-Pilot ready. I understand the project context and our collaboration protocol. How shall we begin?"**

---

### How to Use This Master Prompt

1.  **Start Your Session:** At the beginning of a new chat with your AI, copy the entire template above and paste it in.
2.  **Fill in Your Details:** Complete the four bracketed fields with your specific study information.
3.  **Initiate:** Send the prompt to the AI. Once it confirms its role, you can proceed with the specific, section-by-section prompts outlined below. This initial setup ensures the AI maintains a consistent and accurate understanding of your project throughout your entire planning process.

---

## LLM Prompting Framework for each stages of a Prevalence Study

## Phase 1: Finding Your Idea & Laying the Foundation

### 1.1 & 1.2: A Modern, AI-Accelerated Literature Review Workflow

**Objective:** To systematically plan and execute a comprehensive literature search using a modern, two-stage approach. We will start with fast, AI-powered tools to get a "lay of the land" and then proceed to a traditional, systematic search to ensure rigor and comprehensiveness.

<br>

### **Step A: Planning Your Search Strategy**

*AI's Role: An expert research librarian and methodologist.*

**Initial Prompt:**
*Act as an expert research librarian. I am planning a comprehensive literature search to find a research gap on the topic of [e.g., 'digital health literacy'] among [e.g., 'elderly patients with type 2 diabetes in Malaysia']. Help me prepare for a multi-pronged search strategy.*

1.  **Generate Keywords:** Provide a list of primary and secondary keywords, including MeSH terms where applicable, for a traditional database search.
2.  **Recommend Databases:** Suggest 3-4 appropriate traditional databases for this clinical topic (e.g., PubMed, Scopus, CINAHL).
3.  **Formulate a Search String:** Combine the keywords into a sample Boolean search string that I can adapt for one of these databases.
4.  **Formulate Natural Language Questions:** Draft 3-5 clear questions based on my topic that I can ask directly to AI search platforms like Elicit or Perplexity (e.g., 'What are the most commonly reported risk factors for low digital health literacy in elderly populations?').

<br>

### **Step B: Executing the Two-Stage Search**

**Your Turn**: Execute both search methods to ensure both efficiency and comprehensiveness. We start with the accelerator method to work smarter.

#### **Stage 1: The Accelerator Search (Scout Ahead)**

*   **Purpose:** To rapidly understand the research landscape, identify seminal papers, discover key terminology, and quickly validate if a potential research gap exists. This is a "scout ahead" mission.
*   **Tools to Use:** Elicit, Perplexity, Consensus, SciSpace, etc.
*   **Action:**
    1.  Use the natural language questions from Step A to query these AI platforms.
    2.  Review the synthesized answers and, most importantly, the top papers they cite.
    3.  From this initial exploration, create a "long list" of potentially relevant papers. Your goal here is to get a feel for the topic and find keywords for the next stage.

#### **Stage 2: The Foundational Database Search & Full-Text Retrieval**

*   **Purpose:** To conduct a broad, systematic search using the insights gained from Stage 1. This ensures you are rigorous and don't miss important studies that AI tools might overlook.
*   **Action:**
    1.  Refine your keywords and search strings from Step A based on what you learned in Stage 1 The Accelerator Search.
    2.  Execute your search in traditional databases like PubMed.
    3.  Screen the titles and abstracts of the search results to identify all articles that seem to meet your eligiblity criteria.
    4.  Retrieve the **full-text PDFs** of these potentially eligible papers and save them to a dedicated folder.

<br>

### **Step C: AI-Assisted Full-Text Review and Evidence Table Creation**

This step integrates AI to accelerate your final review of the full-text articles and to organize the findings into a master evidence table.

#### **Stage 1: The AI-Assisted Briefing**

*   **Your Turn:** For each full-text PDF you retrieved, you will use the following prompt to have the AI create a structured "briefing document."
*   **Tools to Use:** An LLM with PDF-reading capability (e.g., Claude, Perplexity Pro, or ChatGPT with a plugin).

**Master Prompt for AI-Assisted Full-Text Review:**
*Act as my dedicated research assistant. I will provide you with the full text of a clinical research paper. Your sole task is to read the paper and extract the following key information into a structured summary to help me rapidly assess its relevance to my research on [remind the AI of your topic, e.g., digital health literacy in elderly diabetic patients].*

*Present the output in a clear, bulleted format as follows:*
*   ***PECOTS Breakdown:***
    *   ***Population (P):** Describe the study participants, including sample size and key characteristics.*
    *   ***Exposure (E):** What was the main exposure or intervention studied?*
    *   ***Comparison (C):** Was there a comparison group? If so, describe it. If not, give the context of the study, not the setting which is covered by the (S) below.*
    *   ***Outcome (O):** What were the primary outcomes measured?*
    *   ***Timing (T):** What was the duration of the study or follow-up period? Any crucial time feature of the variables especially the outcome variable.*
    *   ***Setting (S):** Where did the study take place (e.g., primary care, hospital, community)? Include the country.*
*   ***Study Design:** State the specific study design (e.g., cross-sectional, cohort, RCT).*
*   ***Key Findings:** Summarize the main results and conclusions as stated by the authors.*
*   ***Stated Limitations:** List the specific limitations that the authors mentioned in the discussion section.*
*   ***Relevance Clues:** Does the paper mention prevalence, risk factors, or use of a specific measurement tool related to my topic? (Answer with a brief "Yes" or "No" and the specific detail if yes).*

*Do not add any interpretation or decide on the paper's final relevance. Your function is extraction and summarization only.*

#### **Stage 2: Your Final Inclusion Decision**

*   **Your Turn:** Review the structured summaries generated by the AI for each paper. Based on these highly-condensed briefings, make your final inclusion/exclusion decision.
*   **Action:**
    1.  Read each AI-generated summary.
    2.  Decide "Include" or "Exclude" for each paper.
    3.  Create a final list of all "Included" papers. You will use the summaries for these papers in the next stage.

#### **Stage 3: Creating the Master Evidence Table**

*   **Purpose:** To consolidate the data from all your included papers into a single, structured table. This makes it easy to compare studies, spot patterns, and identify inconsistencies. Alternatively, this step could take over the steps in Stage 1 and 2 above if eligible papers have been decided manually. In this case the prompt below would become just '...papers...' instead of '...individual paper summaries...'
*   **AI's Role:** A systematic review assistant skilled in data organization.

**Prompt to Generate Evidence Summary Table:**
*Act as a systematic review assistant. Your task is to populate a comprehensive evidence summary table based on the individual paper summaries I provide.*

*The output must be a single Markdown table. For each paper summary I provide below, create one row in the table.*

*The table should have the following columns:*
*   *Author & Year*
*   *Study Design*
*   *Setting & Country*
*   *Population (total number, sociodemographic characteristics, and important profile)* 
*   *Outcome(s) & Measurement Tool(s)*
*   *Key Findings (Quantitative & Qualitative)*
*   *Noted Limitations*

*Now, create the table using the following information.
[Paste the AI-generated summaries from Stage 1 for all of your "Included" papers here. Separate each summary with a line or a clear heading.]*

<br>

### **Step D: Final Narrative Synthesis**

*   **Purpose:** To weave the structured data from your evidence table into a coherent narrative for your introduction or literature review section. This step of requesting for a narrative synthesis of all the included papers could be done at the same time as the step above if LLM used is powerful to accommodate the amount of required conversational tokens and attachment. This has the advantage of letting the LLM looking into the attached papers. The possible disadvantage could be overloading of request and outputs are lower in quality.
*   **AI's Role:** A skilled academic writer.

**Prompt for Narrative Synthesis:**
*Act as an expert academic writer. I have created an evidence summary table from my literature review. Based on the information within this table, please help me draft the narrative synthesis.*

  1. ***Analyze the Table:** Analyze the provided table for key patterns, consistencies, or contradictions across the studies.*
  2. ***Thematic Grouping:** Group the findings into 3-4 key themes (e.g., "Reported Prevalence Rates," "Key Associated Risk Factors," "Methodological Strengths and Weaknesses").*
  3. ***Draft the Narrative:** Write a concise narrative (2-3 paragraphs) that synthesizes these themes. Start with a broad statement about the current state of knowledge, then elaborate on the specific themes you identified, citing the authors from the table as you go (e.g., "Smith et al. (2022) found... while Jones (2021) reported...").*
  4. ***Articulate the Gap:** Conclude by drafting a clear and precise statement that summarizes the primary research gap revealed by this synthesis.*

*Here is the evidence table:*
*[Paste the complete Markdown table generated in Step C here.]*

<br>

### **1.3: From Research Gap to a Compelling Problem Statement**

*   **Objective:** To craft a persuasive problem statement that justifies the need for your study.
*   **AI's Role:** An expert academic writer and senior clinical researcher, following the structure from "Box 2: Problem Statements" in this guide.

***Follow-up Prompt:***
*"Act as an expert academic writer specializing in research proposals. Using the information below, draft a compelling, four-paragraph Problem Statement.*

* ***The Clinical Problem:** `[e.g., Low digital health literacy among elderly patients with type 2 diabetes.]`*
* ***Significance & Urgency (The 'Why'):** `[e.g., This population struggles to use digital tools for self-management, leading to poor glycemic control and increased hospital visits. Local hospital data from 2024 shows a 30% increase in admissions for diabetes-related complications in this group.]`*
* ***The Knowledge Gap (What's Missing):** `[e.g., While international data exists, there is no published data on the prevalence of low digital health literacy or its associated factors among elderly diabetic patients in the Malaysian primary care system.]`*
* ***The Proposed Study (A Brief Methodological Overview):** `[Provide a one-sentence summary of your intended study design. For example: "Therefore, we propose a cross-sectional study to determine the prevalence of this issue." Note: This is a high-level summary. We will develop the full methodological details in Phase 2.]`*

*Structure the output into four distinct paragraphs: 1) The Problem, 2) Significance and Urgency, 3) The Knowledge Gap, and 4) **Purpose and Research Question.***"


### **1.4: Grounding Your Research: Developing the Conceptual Framework**
Before we finalize our objectives, it's essential to ground our research in a clear conceptual framework. This framework acts as a "map" of your study. It visualizes the key variables you plan to investigate and shows how you theorize they are related to each other. This map will guide everything from your data collection to your final analysis.

*  **Objective:** To identify relevant theoretical models and create a practical, visual conceptual framework for the study.
*  **AI's Role:** A research methodologist and academic illustrator.

**Follow-up Prompt:**
*Act as a research methodologist. I need to develop a conceptual framework for my study on [remind AI of your topic, e.g., 'digital health literacy and its associated factors'].*

1.  ***Identify Relevant Theories:** Based on my topic, briefly describe 2-3 established theoretical models that are often used in this field (e.g., The Health Belief Model, Social Cognitive Theory, Technology Acceptance Model). Explain their core concepts in one sentence each.*
2.  ***Identify Key Variables:** From the literature review I conducted, the key variables I plan to investigate are:*
    *   ***Primary Outcome or Dependant Variable:** `[e.g., Digital Health Literacy Score]`*
    *   ***Key Independent Variables (Determinants or Predictors):** `[List all the variables, e.g., Age, Socioeconomic Status, Education Level, Social Support, Previous Technology Use]`*
3.  ***Create a Conceptual Framework Diagram:** Based on these variables, generate a simple conceptual framework diagram using **Mermaid syntax for Markdown**. The diagram should visually connect the independent variables to the primary outcome, illustrating the hypothesized relationships.*

(Note to User: Mermaid is a simple text-based tool for creating diagrams. You can copy the code generated by the AI and paste it into a Mermaid editor like the one on GitHub or a dedicated online tool to see your visual framework.)


### **1.5: Finalizing Your Research Question and Objectives**
Now that we have a clear map (our conceptual framework) and a compelling purpose (from our problem statement), we can define our final destination. This step translates our broad research aim into a precise, structured research question and a set of measurable objectives.

*  **Objective:** To formulate a clear research question using the PECOTS structure and to draft the final study objectives.
*  **AI's Role:** A meticulous research methodologist.

**Follow-up Prompt:**
*Act as a meticulous research methodologist. Using the **'Purpose and Research Question' paragraph from my Problem Statement** and the **variables from my new Conceptual Framework**, please finalize my research question and objectives.*

1.  ***PECOTS Question:** Reframe the research question from my Problem Statement into the formal PECOTS (Population, Exposure/s, Comparator, Outcome, Timing, Setting) structure. Ensure the 'Exposures' section includes the key independent variables from my framework.*
2.  ***Study Objectives:** Based on the PECOTS question and framework, draft the following:*
    *   ***Primary Objective:** A single, clear statement about determining the prevalence of the main outcome.*
    *   ***Secondary Objectives:** `[e.g., 3-4]` specific objectives, each focused on exploring the relationship between one or more of the independent variables and the primary outcome.*

***Input Paragraph (from Problem Statement):***
*`[Paste the entire fourth paragraph, the "Purpose and Research Question," generated by the AI in Section 1.3 here.]`*

***Key Independent Variables (from Conceptual Framework):***
*`[List the independent variables you used in Section 1.4 here.]`*

---

## Phase 2: Designing Your Study

### **2.1 & 2.2: Defining Population, Sampling Strategy, and Sample Size**
In Section 1.3, we outlined a brief overview of your proposed study. Now, you will build out the complete technical details of that plan, starting with the core components of population, sampling, and sample size.

*   **Objective:** To define the study population, select a robust sampling strategy, and calculate the necessary sample size for both prevalence and association.
*   **AI's Role:** An experienced epidemiologist and biostatistician.

***Initial Prompt for this Phase:***
"*Act as an experienced clinical epidemiologist and methodologist, and a biostatistician. I am designing a prevalence study based on the following plan:*

*   ***Study Design Mentioned in Problem Statement:** `[e.g., A cross-sectional study]`*
*   ***Population:** `[e.g., Elderly patients (age 65+) with type 2 diabetes attending three government primary care clinics in Selangor, Malaysia.]`*
*   ***Primary Objective:** To determine the prevalence of `[e.g., low digital health literacy]`.*
*   ***Secondary Objectives:** To identify factors associated with it.*

*Now, based on this information:*
1.  ***Eligibility Criteria:** Draft specific inclusion and exclusion criteria for this population.*
2.  ***Sampling Strategy:** Recommend the most feasible sampling strategy that aligns with the stated study design and justify your choice.*
3.  ***Sample Size for Prevalence:** Calculate the sample size needed to estimate the prevalence. Assume an expected prevalence of [e.g., 40%], with a 95% confidence level and a 5% margin of error. Show the formula and calculation.*
4.  ***Sample Size for Association:** Explain the requirements for calculating sample size for a multivariable logistic regression analysis. Referencing the '20 subjects per variable' rule of thumb, calculate the sample size needed if I plan to investigate [e.g., 5] independent variables.*
5.  ***Final Sample Size:** Recommend a final sample size after comparing both calculations and accounting for a [e.g., 20%] non-response rate.*

### **2.3: Selecting and Validating Measurement Tools**

*   **Objective:** To identify reliable, validated instruments for data collection.
*   **AI's Role:** A research librarian and psychometrics expert.

***Follow-up Prompt:***
"*I need to select a questionnaire to measure `[your primary outcome, e.g., digital health literacy]`. Identify two validated questionnaires suitable for use in an elderly population. For each, provide:*
1.  *A brief description and the number of items.*
2.  *Published data on its validity (e.g., content, construct) and reliability (e.g., Cronbach's alpha).*
3.  *Information on scoring and interpretation.*
4.  *Any known limitations or costs.*"

---

## Phase 3: Data Collection and Analysis

### **3.1 & 3.2: Planning Data Collection and Analysis**
With our objectives defined and measurement tools selected, we now move to the operational core of the study. This section focuses on creating a precise plan for how to collect the data and how to perform the initial descriptive analysis required to answer your primary objective.

*   **Objective:** To create a comprehensive plan for data collection, piloting, and the descriptive analysis needed to address the study's primary objective.
*   **AI's Role:** A detail-oriented data manager and biostatistician.

***Initial Prompt for this Phase:***
"*Act as an experienced data manager and biostatistician. I need to create a plan for data collection and the initial descriptive analysis. Here is the context from my previous planning steps:*

*   ***Primary Objective:** `[Paste your primary objective from Section 1.5. e.g., To determine the prevalence of low digital health literacy among elderly patients with type 2 diabetes.]`*
*   ***Selected Measurement Tool(s):** `[List the specific questionnaires you chose in Section 2.3. e.g., The eHEALS questionnaire and a custom demographic survey.]`*

*Based on this, draft the following plans:*

1.  ***Data Collection Protocol:** Outline the step-by-step process for collecting data using the specified tools, from approaching the participant to obtaining consent and administering the questionnaires, give due attention to the proper use of interviewing, training of interviewer, arrangement of the setting where the participants to respond to the questionnaire, checking of completion on the questionnaire, and safe-keeping of the completed questionnaires, etc.*
2.  ***Bias Mitigation**: Describe steps that could be taken during data collection to minimize measurement bias and information bias.*
3.  ***Piloting Plan:** Describe the steps for piloting the questionnaire(s) with a small sample (e.g., 10-20 participants). Specify that the goal is to check for clarity, flow, and time to completion.*
4.  ***Descriptive Analysis Plan:** Specifically for the primary objective, outline the descriptive statistics (e.g., frequencies, percentages for categorical data; means, standard deviations for continuous data) that will be used to summarize participant characteristics and calculate the prevalence of the main outcome with its 95% Confidence Interval.*
5.  ***Dummy Tables:** Create two dummy tables showing how the results for 'Participant Demographics' and 'Prevalence of the Primary Outcome' will be presented.*


### **3.3 & 3.4: Planning the Association Model and for Success**
The previous step detailed the analysis for our primary objective (the "what"). This next crucial step focuses on the inferential analysis needed to address our secondary objectives—exploring the associations and potential predictors (the "why"). We will also outline a plan to ensure the overall credibility of our findings.

*   **Objective:** To detail the plan for multivariable analysis to meet the secondary objectives and to list measures to ensure the study's overall success.
*   **AI's Role:** An advanced biostatistician and research methodologist.

***Follow-up Prompt:***
"*Act as an advanced biostatistician and research methodologist. The next task is to design the inferential analysis plan to explore the factors associated with our primary outcome.*

*Here is the necessary context:*
*   ***Secondary Objectives:** `[Paste your secondary objectives from Section 1.5 here. e.g., To identify factors associated with low digital health literacy.]`*
*   ***Primary Outcome Variable:** `[Specify how the main outcome will be categorized for this analysis. e.g., Low Digital Health Literacy (Categorical: Yes/No)]`*
*   ***Potential Predictor Variables:** `[List the key independent variables you collected. e.g., Age, gender, education level, income, duration of diabetes.]`*

*Now, detail the following:*

1.  ***Inferential Analysis Plan:** Describe the plan to first use bivariate analysis (e.g., chi-square tests for categorical variables, t-tests for continuous variables) to screen predictors. Then, detail how multivariable logistic regression will be used to identify factors independently associated with the primary outcome.*
2.  ***Model Assumptions:** List the key assumptions of logistic regression that must be checked, such as the absence of strong multicollinearity (using VIF), the linearity of the logit for continuous variables, and checking for influential outliers.*
3.  ***Plan for Success:** Based on best practices, generate a bulleted list of proactive measures to ensure the credibility of this research. This should include points on having an a priori analysis plan, ensuring data quality, transparently reporting methods, and collaborating with a statistician.```*"

---

## Phase 4: Ethics & Reporting

### **4.1, 4.2 & 4.3: Ensuring Ethical Conduct, Reporting, and Practical Planning**

*   **Objective:** To draft key administrative and concluding all sections of the research proposal.
*   **AI's Role:** An experienced research manager and academic writer.

***Final Prompt:***
"*Act as an experienced medical ethicist, a academic writer and a research manager preparing the final sections of a proposal.*
1.  ***Ethical Conduct:** Draft the 'Ethical Considerations' section, ensuring it covers informed consent, data confidentiality, anonymity, and the process for obtaining approval from a Research Ethics Committee.*
2.  ***Discussion:** Using the nuanced definition from the guide, help me brainstorm potential shortfalls (e.g., risk of recall bias, potential for selection bias) and the steps I will take to mitigate them, and the potential 'Limitations' of this study. Frame them as imperfections of a rigorous design, not as excuses (e.g., 'While a cross-sectional design can identify associations, etc that are relevant and appropriate to the proposed research. Do not include or highlight that a cross-sectional cannot establish causality because this understood and obvious.'). Then, draft a few paragraphs on these.*
3.  ***Practical Planning:** Create a simple Gantt chart in a markdown table format outlining the major project phases (e.g., Ethics Approval, Piloting, Data Collection, Analysis, Manuscript Writing) over a 12-month timeline.*"

(Note to User: Try to revisit and use the Mermaid to generate your visual Gantt chart. Tip: you can ask the LLM to craft the prompt for you.)

4.  ***Budget Costing:*** *Now, as a meticulous research manager, draft a detailed, itemised budget for this project. To ensure the budget is effective and compliant, it is highly recommended that you **upload the grant's guidelines or terms of reference**. I will then structure the budget according to the required categories (e.g., Vot 11000 - Salaries, Vot 21000 - Travel, Vot 27000 - Supplies). For each item, I will provide an estimated cost based on the best available market prices.*

    ***Crucial Caveat:*** *Please conclude the response with a strong cautionary note. It should state that all figures provided are **estimates** and are likely to be incorrect. Emphasise that I, the researcher, **must double-check all prices** with actual suppliers. Acknowledge that while the generated budget is a significant help for structuring and starting the tedious costing process, it cannot replace due diligence.*"

  #### 5: Writing the Conclusion and Preparing Supplementary Materials
* **Objective:** To write a compelling conclusion that summarises the proposal's significance and to list potential supplementary documents.
* **AI's Role:** An experienced academic writer.

***Prompt for Conclusion & Appendices:***
"*Act as an experienced academic writer summarizing a research proposal. Assume the main body of the proposal is complete.*
1.  ***Conclusion:*** *Based on the entire proposal drafted so far (Introduction, Methods, Ethical Considerations, and Budget), write a strong concluding section. This section should succinctly reiterate the research problem, the proposed approach, and the expected significance or impact of the findings. It should leave the reviewer with a clear and positive final impression of the project's value and feasibility.*
2.  ***Supplementary Materials:*** *Based on the project plan, list the potential documents that should be included as supplementary materials or appendices. Suggest items like the detailed budget, the Gantt chart, draft survey questionnaires, participant information sheets, and informed consent forms. Add a note advising me to check the specific requirements of the ethics committee and funding body, as they may have required templates.*"

  #### 6: Crafting the Final Abstract and Title
* **Objective:** To distill the entire research proposal into a structured abstract and a compelling title, which are often the first (and sometimes only) parts a reviewer reads.
* **AI's Role:** An expert academic editor.

***Final Polish Prompt:***
"*Act as an expert academic editor tasked with creating the most impactful first impression for a research proposal. Assume the entire proposal draft is now complete.*
1.  ***Structured Abstract:*** *Using all the information from the completed proposal, draft a structured abstract of no more than [e.g., 300 words]. Follow this structure: **Introduction:** (briefly state the problem and objective); **Methods:** (summarize the study design, participants, and main procedures); **Discussion:** (Briefly describe the importance of the proposed research again as the first paragraph. Then, highlight the strengths and limitations of the proposed methods, and what are planned to elevate the rigour of the proposed research and to minimise biases); **Conclusions or Expected Outcomes & Impact:** (describe what the study will find and why it is important). Ensure this Abstract is concise, clear, and stands alone as a complete summary of the project.*
2.  ***Title Creation:*** *Based on the finalized proposal and abstract, generate 5-7 alternative titles for this research project. The titles should be informative and concise (ideally under 15 words), incorporating the key variables, study population, and design where appropriate. Aim for a mix of declarative titles and descriptive titles.*"

<br>

---

## Conclusion: Your Role as the Research Captain

This framework is designed to transform your interaction with AI from simple queries into a structured, professional collaboration. The goal is not to have the AI do the work *for* you, but to have it work *with* you. Think of yourself as the captain of the research vessel: you set the destination and are responsible for the entire journey. This guide provides the tools to make the AI your expert, highly-trained first mate, helping you navigate each leg of the voyage with precision and confidence.

#### The Strategy Behind the Prompts: A Layered Approach

You may have noticed that the prompts use a layered methodology. This is a deliberate and powerful strategy to ensure the highest quality output and is not redundant. Here’s how it works:

*   **The Master Prompt** establishes the AI’s overall **profession** (the "Clinical Research Co-Pilot"). This sets the broad context, memory, and collaborative tone for your entire project, ensuring all subsequent advice is grounded in your specific research aim.

*   **The Specific `Act as...` Prompts** assign a **specialist hat** for each unique task. When you command the AI to "Act as a biostatistician," you are focusing its capabilities on the specific models, terminology, and rigorous logic of that discipline. This technique, sometimes called **strategic persona layering**, ensures that you get the right kind of expertise at the right time. It reinforces the context and prevents the AI from giving a generalized response when a specialized one is required.

Ultimately, mastering this structured dialogue is a new and essential skill for the modern researcher. It frees you from the tedious aspects of formatting and drafting, allowing you to focus your cognitive energy on what truly matters: critical thinking, interpreting results, and driving the scientific narrative forward.

Use this guide as a launchpad. Adapt the prompts, challenge the outputs, and always own your research journey. Your clinical insight and ethical judgment are irreplaceable; these tools are simply here to help them shine.

```

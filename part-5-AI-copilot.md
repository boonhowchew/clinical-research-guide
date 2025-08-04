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

  1. **Analyze the Table:** Analyze the provided table for key patterns, consistencies, or contradictions across the studies.*
  2. **Thematic Grouping:** Group the findings into 3-4 key themes (e.g., "Reported Prevalence Rates," "Key Associated Risk Factors," "Methodological Strengths and Weaknesses").*
  3. **Draft the Narrative:** Write a concise narrative (2-3 paragraphs) that synthesizes these themes. Start with a broad statement about the current state of knowledge, then elaborate on the specific themes you identified, citing the authors from the table as you go (e.g., "Smith et al. (2022) found... while Jones (2021) reported...").*
  4. ***Articulate the Gap:** Conclude by drafting a clear and precise statement that summarizes the primary research gap revealed by this synthesis.*

*Here is the evidence table:*
*[Paste the complete Markdown table generated in Step C here.]*

<br>

### **1.3: From Research Gap to a Compelling Problem Statement**

*   **Objective:** To craft a persuasive problem statement that justifies the need for your study.
*   **AI's Role:** An expert academic writer and senior clinical researcher, following the structure from "Box 2: Problem Statements" in the guide.

***Follow-up Prompt:***
*"Act as an expert academic writer specializing in research proposals. Using the information below, draft a compelling, four-paragraph Problem Statement.*

*   ***The Clinical Problem:** `[e.g., Low digital health literacy among elderly patients with type 2 diabetes.]`*
*   ***Significance & Urgency (The 'Why'):** `[e.g., This population struggles to use digital tools for self-management, leading to poor glycemic control and increased hospital visits. Local hospital data from 2024 shows a 30% increase in admissions for diabetes-related complications in this group.]`*
*   ***The Knowledge Gap (What's Missing):** `[e.g., While international data exists, there is no published data on the prevalence of low digital health literacy or its associated factors among elderly diabetic patients in the Malaysian primary care system.]`*
*   ***The Proposed Study (The Solution):** `[e.g., To conduct a cross-sectional study to determine the prevalence of low digital health literacy and identify its associated factors in this population.]'*

*Structure the output into four distinct paragraphs: 1) The Problem, 2) Significance and Urgency, 3) The Knowledge Gap, and 4) Purpose and Research Question.*"

### **1.4 & 1.5: Establishing a Framework and Finalizing Objectives**

*   **Objective:** To ground your study in a theoretical framework and formulate a clear research question and objectives using the PECOTS structure.
*   **AI's Role:** A meticulous research methodologist.

***Follow-up Prompt:***
"*Now, let's finalize the research question and objectives.*
*1.  **Framework:** Suggest one suitable theoretical framework (e.g., Health Belief Model) that could help explain the factors associated with `[e.g., digital health literacy]` and briefly justify its use.*
*2.  **PECOTS Question:** Reframe the research question `[Insert your research question here]` using the PECOTS (Population, Exposure, Comparator, Outcome, Timing, Setting) framework.*
*3.  **Objectives:** Based on this, draft a primary objective and three specific, measurable secondary objectives for the study.*"

---

## Phase 2: Designing Your Study

### **2.1 & 2.2: Defining Population, Sampling Strategy, and Sample Size**

*   **Objective:** To define the study population, select a robust sampling strategy, and calculate the necessary sample size for both prevalence and association.
*   **AI's Role:** An experienced epidemiologist and biostatistician.

***Initial Prompt for this Phase:***
"*Act as an experienced clinical epidemiologist and methodologist, and a biostatistician. I am designing a prevalence study.*
*   ***Population:** `[e.g., Elderly patients (age 65+) with type 2 diabetes attending three government primary care clinics in Selangor, Malaysia.]*
*   ***Primary Goal:** To determine the prevalence of `[e.g., low digital health literacy].*
*   ***Secondary Goal:** To identify factors associated with it.*

*1.  **Eligibility Criteria:** Draft specific inclusion and exclusion criteria for this population.*
*2.  **Sampling Strategy:** Recommend the most feasible sampling strategy and justify your choice.*
*3.  **Sample Size for Prevalence:** Calculate the sample size needed to estimate the prevalence. Assume an expected prevalence of `[e.g., 40%]`, with a 95% confidence level and a 5% margin of error. Show the formula and calculation.*
*4.  **Sample Size for Association:** Explain the requirements for calculating sample size for a multivariable logistic regression analysis. Referencing the '20 subjects per variable' rule of thumb, calculate the sample size needed if I plan to investigate `[e.g., 5]` independent variables.*
*5.  **Final Sample Size:** Recommend a final sample size after comparing both calculations and accounting for a `[e.g., 20%]` non-response rate.*"

### **2.3: Selecting and Validating Measurement Tools**

*   **Objective:** To identify reliable, validated instruments for data collection.
*   **AI's Role:** A research librarian and psychometrics expert.

***Follow-up Prompt:***
"*I need to select a questionnaire to measure `[your primary outcome, e.g., digital health literacy]`. Identify two validated questionnaires suitable for use in an elderly population. For each, provide:*
*1.  A brief description and the number of items.*
*2.  Published data on its validity (e.g., content, construct) and reliability (e.g., Cronbach's alpha).*
*3.  Information on scoring and interpretation.*
*4.  Any known limitations or costs.*"

---

## Phase 3: Data Collection and Analysis

### **3.1 & 3.2: Planning Data Collection and Analysis**

*   **Objective:** To create a comprehensive plan for data collection, piloting, and analysis.
*   **AI's Role:** A detail-oriented data manager and biostatistician.

***Initial Prompt for this Phase:***
"*Act as an experienced data manager. Draft a data collection and analysis plan.*
*1.  **Data Collection Protocol:** Outline the step-by-step process for collecting data from participants, from approach to consent to questionnaire administration.*
*2.  **Piloting Plan:** Describe the steps for piloting the questionnaire with a small sample (e.g., 10-15 participants) and what feedback to collect.*
*3.  **Data Analysis Plan (Descriptive):** Outline the descriptive statistics (e.g., frequencies, percentages, means, standard deviations) that will be used to summarize participant characteristics and determine prevalence with its 95% CI.*
*4.  **Dummy Tables:** Create two dummy tables showing how the results for 'Participant Demographics' and 'Prevalence of Key Outcomes' will be presented.*"

### **3.3 & 3.4: Planning the Association Model and for Success**

*   **Objective:** To detail the plan for multivariable analysis and list measures to ensure the study's overall success.
*   **AI's Role:** An advanced biostatistician and research methodologist.

***Follow-up Prompt:***
"*Now, let's detail the plan for the association model.*
*1.  **Inferential Analysis Plan:** Describe the plan to use bivariate analysis (e.g., chi-square, t-tests) followed by multivariable logistic regression to identify factors independently associated with `[e.g., low digital health literacy].*
*2.  **Model Assumptions:** List the key assumptions of logistic regression that must be checked, including multicollinearity (VIF), linearity of the logit, and influential outliers (Cook's Distance).*
*3.  **Plan for Success:** Based on Section 3.4 of the guide, generate a bulleted list of proactive measures to ensure the success and credibility of this research, including points on a priori power analysis, data quality, and collaboration with a statistician.*"

---

## Phase 4: Ethics & Reporting

### **4.1, 4.2 & 4.3: Ensuring Ethical Conduct, Reporting, and Practical Planning**

*   **Objective:** To draft key administrative and concluding sections of the research proposal.
*   **AI's Role:** An experienced research manager and academic writer.

***Final Prompt:***
"*Act as an experienced academic writer and a research manager preparing the final sections of a proposal.*
*1.  **Ethical Conduct:** Draft the 'Ethical Considerations' section, ensuring it covers informed consent, data confidentiality, anonymity, and the process for obtaining approval from a Research Ethics Committee.*
*2.  **Interpretation and Discussion:** Using the nuanced definition from the guide, draft a paragraph on the potential 'Limitations' of this study. Frame them as imperfections of a rigorous design, not as excuses (e.g., 'While a cross-sectional design can identify associations, it cannot establish causality...').*
*3.  **Practical Planning:** Create a simple Gantt chart in a markdown table format outlining the major project phases (e.g., Ethics Approval, Piloting, Data Collection, Analysis, Manuscript Writing) over a 12-month timeline.*"

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

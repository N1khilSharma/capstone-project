Template for creating and submitting MAT496 capstone project.

# Overview of MAT496

In this course, we have primarily learned Langgraph. This is helpful tool to build apps which can process unstructured `text`, find information we are looking for, and present the format we choose. Some specific topics we have covered are:

- Prompting
- Structured Output 
- Semantic Search
- Retreaval Augmented Generation (RAG)
- Tool calling LLMs & MCP
- Langgraph: State, Nodes, Graph

We also learned that Langsmith is a nice tool for debugging Langgraph codes.

------

# Capstone Project objective

The first purpose of the capstone project is to give a chance to revise all the major above listed topics. The second purpose of the capstone is to show your creativity. Think about all the problems which you can not have solved earlier, but are not possible to solve with the concepts learned in this course. For example, We can use LLM to analyse all kinds of news: sports news, financial news, political news. Another example, we can use LLMs to build a legal assistant. Pretty much anything which requires lots of reading, can be outsourced to LLMs. Let your imagination run free.


-------------------------

# Project report Template

## Title: Job4Me

## Overview

Job4Me is a system designed to help users discover relevant job opportunities based on the skills listed in their resume. It begins by processing the resume as unstructured text and extracting key technical, tool-based, and soft skills. Using Tavily search, the system then retrieves real job listings from various online sources and compares the required skills in those listings with the user’s extracted skill profile. Based on this comparison, it presents job opportunities that closely align with the user’s current capabilities.
In addition to matching existing skills to available roles, Job4Me also highlights skill gaps and growth opportunities. By examining roles with similar requirements where the user may be missing certain competencies, the system generates practical upskilling suggestions. This includes recommendations for additional skills, learning areas, and potential next steps helping users expand their eligibility for a broader range of job opportunities.

## Reason for picking up this project

I picked this project because it challenged me to bring together everything I learned in MAT496 into one workflow, while also building something practical. Extracting skills from resumes, searching real job listings, comparing requirements, and generating recommendations all require structured reasoning, tool integration, and stateful graph execution exactly are some areas we focused on in the course. This project didn’t just help me revise the concepts, it allowed me to apply them in a way that could be genuinely useful to someone exploring career options.

## Plan

I plan to excecute these steps to complete my project.

- [DONE] Step 1 Set all the required keys and create necessary pdfs for RAG.
- [DONE] Step 2 Parse through the Resume pick up the relevant details.
- [DONE] Step 3 Pass the result to Tavily for a structured query , add Human-in-the-loop to search for specific location for the relevant skill set of the candidate.
- [DONE] Step 4 Get the information from the Tavily search and put it into the LLM to properly format and display the details of the job where the candidate is a good fit.
- [TODO] Step 5 Give advice to the candidate on the topics they can focus on or add to their resume to further increase eligibility and options for jobs.
- [TODO] Step 6 Integrate all the steps together and implement Langchain into the workflow to trace and debug.
- [TODO] Step 7 Polish the formatting for the output and add Documentation for future legibility.
- [TODO] Step 8 Test the full pipeline with multiple resumes and finalize.

## Conclusion:

I had planned to achieve {this this}. I think I have/have-not achieved the conclusion satisfactorily. The reason for your satisfaction/unsatisfaction.

## Future Scope

Looking ahead, there are several improvements I would like to explore as the next steps for this project. One of the biggest directions for expansion is integrating official APIs from major recruitment platforms such as LinkedIn, Indeed, or Glassdoor. Doing that would allow the system to pull a wider variety of opportunities and also give me access to richer data, such as hiring patterns, demand trends, and role-specific requirements. This would make the job matching process even more accurate and meaningful.
Another improvement I’d like to work on is resume optimization. Instead of only telling the user what they are missing, the system could help rewrite or tailor parts of their resume to better match specific positions. This could include suggesting phrasing changes, emphasizing certain projects, or aligning skill terminology with what employers commonly use.

# Added instructions:

- This is a `solo assignment`. Each of you will work alone. You are free to talk, discuss with chatgpt, but you are responsible for what you submit. Some students may be called for viva. You should be able to each and every line of work submitted by you.

- `commit` History maintenance.
  - Fork this respository and build on top of that.
  - For every step in your plan, there has to be a commit.
  - Change [TODO] to [DONE] in the plan, before you commit after that step. 
  - The commit history should show decent amount of work spread into minimum two dates. 
  - **All the commits done in one day will be rejected**. Even if you are capable of doing the whole thing in one day, refine it in two days.  
 
 - Deadline: Nov 30, Sunday 11:59 pm


# Grading: total 25 marks

- Coverage of most of topics in this class: 20
- Creativity: 5
  

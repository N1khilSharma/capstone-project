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
- [DONE] Step 5 Give advice to the candidate on the topics they can focus on or add to their resume to further increase eligibility and options for jobs.
- [DONE] Step 6 Integrate all the steps together and implement Langchain into the workflow to trace and debug.
- [DONE] Step 7 Polish the formatting for the output and add Documentation for future legibility.
- [DONE] Step 8 Test the full pipeline with multiple resumes and finalize.

## Conclusion:
I had planned to achieve "Job4Me," an LLM-powered agent capable of parsing resumes, retrieving real-time job market data via Tavily, and providing structured career guidance.
I think I have achieved the conclusion satisfactorily.
The reason for my satisfaction is that the system evolved from a simple script into a stateful graph application. It successfully implements high-accuracy Chain-of-Thought resume parsing and parallelized job extraction for speed. Furthermore, the addition of the "Career Advisor" node transforms raw search results into a strategic project-based action plan, all while maintaining full observability through LangSmith tracing.

## Future Scope

Looking ahead, there are several improvements I would like to explore as the next steps for this project. One of the biggest directions for expansion is integrating official APIs from major recruitment platforms such as LinkedIn, Indeed, or Glassdoor. Doing that would allow the system to pull a wider variety of opportunities and also give me access to richer data, such as hiring patterns, demand trends, and role-specific requirements. This would make the job matching process even more accurate and meaningful.
Another improvement I’d like to work on is resume optimization. Instead of only telling the user what they are missing, the system could help rewrite or tailor parts of their resume to better match specific positions. This could include suggesting phrasing changes, emphasizing certain projects, or aligning skill terminology with what employers commonly use.

## Video Explanation

https://youtu.be/RO2wWypcSnw

  

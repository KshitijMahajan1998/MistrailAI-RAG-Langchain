# MistrailAI-RAG-Langchain

Exercise Title: "Build a Contextual Q&A Bot using LLM.”

 

Duration: 3-4 days

 

Exercise Description: In this exercise, you will be building a contextual Question-Answer (Q&A) bot using a Language Model. Users can ask questions related to the PDF's content. The Q&A should provide context-based answers and deny questions that are out-of-context. You will be writing a Python program that utilizes the LLM to answer questions from a provided PDF document and enforcing context-based responses. You must ensure the Q&A bot denies answering questions that are out-of-context. You can use langchain to build the system. There is no constraint to context token limit, i.e.: The pdf can be 1000 pages as well which might not fit into the LLM token limit.

 

Summarized task: Create a python code, jupyter notebook/python IDE or any python code that reads pdf file and answers user question only from pdf file. If question is not related to pdf content, LLM denies answering.

 

Tasks:

1. Read the content of a provided PDF document. The pdf will be way above the context limit of LLM.

2. Preprocess the content for efficient question-answering.

3. Develop a Q&A bot using open source LLM to answer questions based on the PDF's content. (Recommended to use Mistral 7b or any variants of mistral as it can easily fit into memory) (a 4/8/16bit precision will help to fit into memory).

4. Implement a mechanism to determine if a question is in or out of context and deny out-of-context questions.

 

Requirements:

- The program should be written in Python.

- Utilize the Open Source LLM for Q&A.

- Provide clear and concise comments to explain the code.

- Ensure error handling for cases like missing or inaccessible PDF files.

- Implement a mechanism for context-aware responses and out-of-context detection.

 

Assessment Criteria:

1. Problem-solving skills and the approach to the problem.

2. Effective utilization of the language model for context-based Q&A.

3. Proper error handling for PDF-related issues and solving for model context limit for longer pdfs.

4. Implementation of the out-of-context question detection.

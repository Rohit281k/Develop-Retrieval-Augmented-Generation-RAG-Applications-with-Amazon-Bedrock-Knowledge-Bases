# Develop-Retrieval-Augmented-Generation-RAG-Applications-with-Amazon-Bedrock-Knowledge-Bases

# Lab overview
In this lab, you build a question-answering application using the AnyCompany knowledge base and Amazon Bedrock’s Retrieve and RetrieveAndGenerate APIs. You leverage the existing knowledge base, which contains comprehensive information about AnyCompany’s products, services, corporate details like history, leadership, financial performance, sustainability efforts, and more. You run through various notebooks that can effectively answer questions related to AnyCompany’s products, services, and corporate information.

# Objectives
By the end of this lab, you should be able to do the following:

Leverage a fully-managed RAG application with Amazon Bedrock RetrieveAndGenerate API.
Build a Q&A application using Amazon Bedrock Knowledge Bases with Retrieve API.
Build and evaluate Q&A Application using Amazon Bedrock Knowledge Bases using RAG Assessment (RAGAS) framework.
Test the guardrail functionality on Amazon Bedrock Knowledge Base using RetrieveAndGenerate API.

# Task 1:

Leverage a fully-managed RAG application with Amazon Bedrock’s RetrieveAndGenerate API
In this task, you leverage a fully-managed Retrieval Augmented Generation (RAG) application with Amazon Bedrock’s RetrieveAndGenerate API. For this task, you run the Task-1.ipynb notebook file.

In the left navigation pane, navigate to en_us folder and open the Task-1.ipynb notebook.

If the Select Kernel pop-up window opens, for Select Kernel for parameter, choose Python 3 (ipykernel).

Choose Select.

Carefully advance through the Task-1.ipynb notebook. Run each code cell and view its output. To run a cell, select within the cell and press Shift+Enter or, at the top of the page, choose the Run button.

 Task complete: You have successfully leveraged a fully-managed Retrieval Augmented Generation (RAG) application with Amazon Bedrock’s RetrieveAndGenerate API.

# Task 2:

Build a Q&A application using Amazon Bedrock Knowledge Bases with Retrieve API
In this task, you build a Q&A application using Amazon Bedrock Knowledge Bases with Retrieve API. Here, you query the knowledge base to get the desired number of document chunks based on similarity search. You then augment the prompt with relevant documents and perform a query which acts as input to Amazon Nova Lite for generating response.

In the left navigation pane, navigate to en_us folder and open the Task-2.ipynb notebook.

If the Select Kernel pop-up window opens, for Select Kernel for parameter, choose Python 3 (ipykernel).

Choose Select.

Carefully advance through the Task-2.ipynb notebook. Run each code cell and view its output. To run a cell, select within the cell and press Shift+Enter or, at the top of the page, choose the Run button.

 Task complete: You have successfully built a Q&A application using Amazon Bedrock Knowledge Bases with Retrieve API.

# Task 3: 

Build and evaluate Q&A Application using Amazon Bedrock Knowledge Bases using RAG Assessment (RAGAS) framework
In this task, you build and evaluate a Q&A application using Retrieve API provided by Amazon Bedrock Knowledge Bases, along with LangChain and RAGAS for evaluating the responses. Here, you query the knowledge base to get the desired number of document chunks based on similarity search, prompt the query using Amazon Nova Lite, and then evaluate the responses effectively using evaluation metrics, such as faithfulness, answer_relevancy, context_recall, context_precision, context_entity_recall, answer_similarity, answer_correctness, harmfulness, maliciousness, coherence, correctness and conciseness.

In the left navigation pane, navigate to en_us folder and open the Task-3.ipynb notebook.

If the Select Kernel pop-up window opens, for Select Kernel for parameter, choose Python 3 (ipykernel).

Choose Select.

Carefully advance through the Task-3.ipynb notebook. Run each code cell and view its output. To run a cell, select within the cell and press Shift+Enter or, at the top of the page, choose the Run button.

 Task complete: You have successfully built and evaluated a Q&A application using Retrieve API provide by Amazon Bedrock Knowledge Bases, along with LangChain and RAGAS for evaluating the responses.

# Task 4 (Optional): 

Test the guardrail functionality on Amazon Bedrock Knowledge Base using RetrieveAndGenerate API
In this task, you test the guardrail functionality on Amazon Bedrock Knowledge Base using the RetrieveAndGenerate API. You utilize an existing knowledge base used with the previous notebooks, which was based on the AnyCompany’s Financial 10K document.

In the left navigation pane, navigate to en_us folder and open the Task-4.ipynb notebook.

If the Select Kernel pop-up window opens, for Select Kernel for parameter, choose Python 3 (ipykernel).

Choose Select.

Carefully advance through the Task-4.ipynb notebook. Run each code cell and view its output. To run a cell, select within the cell and press Shift+Enter or, at the top of the page, choose the Run button.

 Task complete: You have successfully tested the guardrail functionality on Amazon Bedrock Knowledge Base using the RetrieveAndGenerate API. You utilized an existing knowledge base used with the previous notebooks, which was based on the AnyCompany’s Financial 10K document.

Conclusion
Leveraged a fully-managed RAG application with Amazon Bedrock RetrieveAndGenerate API.
Built a Q&A application using Amazon Bedrock Knowledge Bases with Retrieve API.
Built and evaluated Q&A Application using Amazon Bedrock Knowledge Bases using RAG Assessment (RAGAS) framework.
Tested the guardrail functionality on Amazon Bedrock Knowledge Base using RetrieveAndGenerate API.


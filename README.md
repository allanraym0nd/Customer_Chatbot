**Simple Customer Support Chatbot**

This is a beginner-level project implemented in a single Python script (designed for a Jupyter Notebook) to demonstrate basic text classification using keyword matching.

**Objective**

The goal of this script is to simulate a simple customer support system that can:

Accept a user's question.

Classify the question into one of three predefined categories.

Provide an immediate, predefined response based on the classification.

**How It Works**

The script operates using a simple logic:

Input: Takes a question from the user using the input() function.

Normalization: Converts the question to lowercase for case-insensitive matching.

Keyword Count: Iterates through the predefined keyword lists for each category, counting the number of matches in the user's question.

Classification: The question is assigned to the category with the highest number of matching keywords.

Escalation Check: A separate check for "frustration keywords" overrides the keyword count and triggers an escalation response.

Output: Prints the determined category and the corresponding predefined response.

**Prerequisites**

Python 3

Jupyter Notebook (Recommended environment)

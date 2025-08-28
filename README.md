# The-Empathetic-Code-Reviewer

## Aim 
This project, developed for the "Empathetic Code Reviewer" hackathon mission, aims to transform blunt and critical code review feedback into supportive, educational, and constructive guidance. It uses AI principles to act as an ideal senior developer, helping junior developers understand the "why" behind suggestions, not just the "what."

## Key Features

⦁	Empathetic Rephrasing: The program rephrases direct, critical comments into gentle and encouraging statements.

⦁ Contextual Tone: The AI's tone changes based on the severity of the original comment.

⦁	Educational "Why": Each suggestion includes a clear explanation of the underlying software principles.

⦁	Concrete Suggestions: The program provides code examples to demonstrate the recommended fix.

⦁	External Resources: The AI links to relevant external documentation, such as PEP 8 and PEP 257, to support its suggestions.

⦁	Holistic Summary: The report concludes with an encouraging and positive summary of the overall feedback.


## How to Run

⦁	Dependencies: The program uses standard Python libraries (json, sys, re), so no installation is required beyond a basic Python 3 environment.

⦁	Input: Ensure you have a JSON file named sample.json in the same directory as the script. The file should have code_snippet and review_comments keys.

⦁	Execute: Run the Python script from your terminal.
	    
     python your_script_name.py
     
⦁	The program will process the input and print the formatted Markdown report directly to your console.

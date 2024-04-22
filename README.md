# LLM-Collaboration
A Step Towards Collective Intelligence

*ALL CODE RAN USING GOOGLE COLABORATORY

How to run individual agent code (LLM_Test_Taking 1.ipynb):
- pip install Claude 3 Opus, GPT-4, and Gemini 1.0 Pro
- Insert API keys for each agent
- Import Overall answer key and sectional practice question files for each topic
- Execute agent sections for importing test files into each agent and receive excel output
- Download excel output from Google Colab

How to determine an individuals models'strenghts and weaknesses/ LLM Report (LLM_Data_Analyses.ipynb):
- pip install pandas openpyxl
- Ensure your Excel file named "GPT_Results.xlsx" is correctly formatted with the data for each subject and is saved in the same directory as your script, or specify the path correctly in the code.
- Run the script 
- The script will print out the most poorly performed skill for each subject listed (e.g., US History, US Government, Physics, Human Geography, Environmental Science).

How to run collaboration agent code in collaboration folder:
- pip install Claude 3 Opus, GPT-4, and Gemini 1.0 Pro
- Insert API keys for each agent
- Import Overall answer key and all individual practice questions for each topic
- Execute round 1 section (first agent then the next agent)
- (Optional) run output section to ensure each agent received the questions properly
- Download round 1 excel results for graded only
- Execute round 2 section (first agent then the next agent)
- (Optional) run output section to ensure each agent received the questions properly
- Download round 2 excel results for graded only
- Execute round 3 section (arbiter agent)
- Download round 3 excel results

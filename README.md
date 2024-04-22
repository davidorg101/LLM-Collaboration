# LLM-Collaboration
## A Step Towards Collective Intelligence

*All code ran using Jupyter Notebooks (VS Code/Google Collaboratory)*

### Test Preparatory (Test_Prep.ipynb):
#### Image Captioning with GPT-4 Vision (for image questions/answers)
- Import necessary libraries (os, openai, base64).
- Use OpenAI's API to submit the encoded images and receive descriptions.
- Print the descriptions provided by the AI for analysis.
- Copy and paste descriptions into individual corresponding test questions/answers.

#### Question Combining (to have all test questions into 1 txt file)
- Loop through each section folder and question where you have your test questions, read the contents, and combine them into a single file.

#### Run Answer Combiner (from individual answer txt files)

#### Run Skill and Answer Combiner (makes master answer key)

#### Unbiased Answer Skill Assessment (GPT-4)
- Open and read the content of the test file.
- Send the content to OpenAI's API to determine which skill each question assesses.
- Print the AI's assessment and copy and paste it into the answer key.

### How to run individual agent code (LLM_Test_Taking 1.ipynb):
- pip install Claude 3 Opus, GPT-4, and Gemini 1.0 Pro
- Insert API keys for each agent
- Import Overall answer key and sectional practice question files for each topic
- Execute agent sections for importing test files into each agent and receive excel output
- Download Excel output from Google Colab

### How to determine an individual model's strengths and weaknesses/ LLM Report (LLM_Data_Analyses.ipynb):
- pip install pandas openpyxl
- Ensure your Excel file named "GPT_Results.xlsx" is correctly formatted with the data for each subject and is saved in the same directory as your script, or specify the path correctly in the code.
- Run the script 
- The script will print out the most poorly performed skill for each subject listed (e.g., US History, US Government, Physics, Human Geography, Environmental Science).

### How to run collaboration agent code in the collaboration folder:
- pip install Claude 3 Opus, GPT-4, and Gemini 1.0 Pro
- Insert API keys for each agent
- Import Overall answer key and all individual practice questions for each topic
- Execute round 1 section (first agent then the next agent)
- (Optional) Run the output section to ensure each agent received the questions properly
- Download round 1 Excel results for graded only
- Execute round 2 section (first agent then the next agent)
- (Optional) Run the output section to ensure each agent received the questions properly
- Download round 2 Excel results for graded only
- Execute round 3 section (arbiter agent)
- Download round 3 Excel results

### Data Visualization ( LLM_Visualizations.Rmd):
- Read your data into R using read_csv or similar functions.
- Manipulate and transform your data as needed using dplyr functions like mutate, summarise, and pivot_longer.
- Use ggplot2 to build visualizations like bar plots. Customize these plots using geom_bar, scale_fill_manual, and other ggplot2 functions to adjust aesthetics.
- Employ theme functions to improve readability and presentation quality.


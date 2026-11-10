# AI Tool Use Disclosure

* **Tool Used:** Gemini 3.1 Pro
* **Purpose:** Conceptual understanding, code generation, troubleshooting, and report drafting.

**How I used the tool:**
1. **Sections 1 to 8 (Data Preprocessing, EDA, and Model Training):** We proceeded mostly in a question-and-answer format. I wrote the majority of the code myself. However, in some specific parts where I needed help (like setting up the exact training loops or applying StandardScaler correctly), Gemini generated the code blocks for me.
2. **Sections 8 to 10 & Section 12 (Data Export and Final Analysis):** I continued using the AI for code generation in the later steps. Specifically, I used Gemini to generate the exact `pandas` code for Section 12 to correctly concatenate my dataframes from two separate notebooks and export the 6 required CSV files without creating unnecessary files.

**Verification:** 
I did not copy-paste blindly. I executed all AI-generated code in my own Jupyter Notebook environment, checked the dataframe shapes, reviewed the charts, and manually verified that the confusion matrix calculations matched the computer's results. I made sure to understand the code before including it in my final project.
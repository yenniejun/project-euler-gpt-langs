# GPT-4 can solve math problems — but not in all languages
_A few experiments making GPT-4 solve math problems in 16 different languages
_

![screenshot of Project Euler website](project-euler-screenshot.png)


This repository includes the code used in the related article. 

![diagram showing the translation of Project Euler question into Burmese and back into English](translate-to-burmese-diagram.png)

Data included:
- `solutions.txt` from https://www.kaggle.com/datasets/dheerajmpai/projecteuler?select=Solutions.md.txt
- `problems.csv` from https://www.kaggle.com/datasets/patrickgendotti/project-euler-full-problem-set?resource=download
- `problems_df_cleaned.csv`: My cleaned version merging the solutions and problems into a single dataframe
- `project_euler_gpt4_responses.csv`: CSV containing all of GPT-4's generated responses to Project Euler questions in the different languages
- `back_trans_df.csv`': CSV containing GPT-4's responses translated back into English

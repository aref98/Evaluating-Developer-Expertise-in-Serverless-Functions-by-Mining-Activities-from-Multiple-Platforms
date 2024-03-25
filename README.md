# Evaluating Developer Expertise in Serverless Functions by Mining Activities from Multiple Platforms

This repository contains six public datasets related to our research on predicting developer expertise within the realm of serverless functions. **You can find the article at the following URL: https://cke.um.ac.ir/article_45050.html.** These datasets were created using features extracted from GitHub and Stack Overflow, and they represent our target languages.


## Research Overview

Our research ventured into the domain of predicting developer expertise specifically within the realm of serverless functions. We found that integrating data from multiple platforms like GitHub and Stack Overflow provides an in-depth understanding of developer expertise. One of the tangible outputs of our research is the creation and public release of these six language-specific datasets. By making these datasets publicly available, we aim to contribute to the academic community and foster further research in this area.

## Dataset Structure

Each dataset is provided in CSV format with the following columns:

- `number_of_commits`
- `commits_client_files`
- `commits_import_library`
- `code_churn`
- `code_churn_client_files`
- `imports`
- `days_since_first_import`
- `days_since_last_import`
- `days_between_imports`
- `avg_days_commits_client_files`
- `avg_days_commits_import_library`
- `projects`
- `projects_import`
- `Num_Answers`
- `Num_Accepted_Answers`
- `Num_Upvotes`
- `Avg_Score_Per_Answer`
- `Num_Questions`
- `Num_First_Answers`
- `Tag_Score`
- `time_of_activity`
- `rating`: This is our label which came from a survey (sent by email) that asked developers to rate themselves.

We hope these datasets will be useful for your research. If you use them, please consider citing our paper.

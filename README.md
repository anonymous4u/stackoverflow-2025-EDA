# Stack Overflow 2025 Developer Survey — Exploratory Data Analysis

An exploratory data analysis of the Stack Overflow 2025 Developer Survey, covering developer demographics, salary trends, country comparisons, role and skill breakdowns, and AI adoption/sentiment across the developer community.

## Overview

This project analyzes nearly 49,000 developer responses from the Stack Overflow 2025 Developer Survey using Python. The analysis covers demographic patterns, salary trends by age, experience, role, and country, technology usage, and how developers are adopting and feeling about AI tools.

## Dataset

This project uses the official Stack Overflow 2025 Developer Survey results. The raw survey file is not included in this repository due to its size — download it directly from the [Stack Overflow Developer Survey page](https://survey.stackoverflow.co/) and place it in the project folder before running the notebook.

## Key Findings

**Demographics & Salary**
- Salary generally increases with age, peaking in the 55–64 bracket before dipping slightly, likely reflecting late-career transitions.
- Salary rises sharply with experience up to roughly 25 years, then plateaus, peaking around 40–45 years before a slight decline.
- Years of coding and years of work experience are strongly correlated (0.84), as expected, but neither correlates strongly with salary or job satisfaction, suggesting experience alone doesn't guarantee higher pay or happiness at work.

**Geography**
- The United States, Germany, and India have the highest number of survey respondents.
- Countries with the highest average salaries (e.g. Iran, Oman) are likely skewed by small sample sizes, while the US ranks more reliably given its much larger respondent base.

**Roles & Skills**
- Senior executives and engineering managers earn the highest median salaries, while students unsurprisingly earn the least.
- JavaScript, Python, and SQL remain the dominant languages across most top countries.

**AI Adoption**
- OpenAI's GPT models are by far the most used AI models among developers.
- The majority of developers do not see AI as a threat to their jobs, though a meaningful portion remain unsure, suggesting cautious optimism rather than alarm.

## Final Thoughts

This analysis highlights that experience and skills matter, but factors like role, company size, and geography play just as large a role in shaping a developer's compensation and career satisfaction. AI adoption is clearly mainstream at this point, with sentiment leaning more curious than fearful.

## Tools Used

- Python
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook

## Author

[anonymous4u](https://github.com/anonymous4u)
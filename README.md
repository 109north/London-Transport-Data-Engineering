[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/ihYmGsb-)
# LSE ME204 - Final Project

⏲️ **Due Date**:

- Monday, **31 July 2023** at 23:59:59, UK Time. (but hopefully, you will be able to complete it during the week by 28 July)

This assignment is worth **75%** of your final grade.

## 📝 **Structure of the assignment**:

1. Go to our Slack workspace's `#general` channel to find a GitHub Classroom link. Do not share this link with anyone else, as it is a private assignment for those taking this course.
2. Click on the link, sign in to GitHub if needed and then click on the green button `Accept this assignment`.
3. You will be redirected to a new repository created for you. The repository will be named something like `LSE-DSI/me204-2023-final-project-<your-username>`, where `<yourusername>` is your GitHub username. The repository will be private and will contain the following:
    - a `README.md` file with a copy of these instructions
    - a `project.qmd` file that is a template you can use for your project report. Feel free to edit it as long as you meet the requirements in the Instructions below.
    - an `R/` folder with a template of script files you can use for your project. Feel free to edit it as you prefer.
    - a `data/` folder where you can store your data
4. Don't edit the README file. Just follow the instructions and complete the assignment.

**"How do I submit?"**

You don't need to submit anything. Your assignment will be automatically submitted when you `commit` **AND** `push` your changes to GitHub. You can push your changes as many times as you want before the deadline. We will only grade the last version of your assignment.

## 📋 Instructions

Here's your roadmap for this project:

1. **Find a Data Source**: Seek out a data source with ample volume to showcase your data manipulation skills. Choose either an API or perform web scraping from an open website (avoid collecting personal/sensitive data). If you have no idea which data sources to use, consider using **Wikimedia**—it offers a treasure trove of data from various sources (Wikipedia, Wikidata, Wiktionary, etc.). Pick a theme, like "hurricane records over history," and begin your exploration.

2. **Collect and Store Data**: Collect the data and store it in your repository's `data/raw` folder.

3. **Preprocess and Tidy**: Ensure your data is clean and tidy. Store the processed data in your repository's `data/tidy` folder.

4. **Setup Guide**: Concisely explain your data collection and preprocessing steps in the `# ⚙️ Setup` section of your `report.qmd` (or `report.Rmd`). Use code chunks to demonstrate the code used for data collection and preprocessing.

5. **Summarise the Data**: In the `# 💾 The Data` section of your `report.qmd` (or `report.Rmd`), briefly overview your data source and why it's interesting to you.

6. **Paint the Big Picture**: In the `# 🚁 Big Picture` section of your `report.qmd` (or `report.Rmd`), create a minimum of 3 plots/tables that vividly showcase the content of your data.

7. **Further Exploration**: In the `# 📈 Further Exploratory Analysis` section of your `report.qmd` (or `report.Rmd`), produce at least two additional plots/tables that delve deeper into your data. Provide explanations, highlight insights, and draw conclusions from each visual.

8. **Future Endeavors**: Conclude your report with a `# ⏭️ Future` section in your `report.qmd` (or `report.Rmd`). Share what you would explore next if you had more time for this project.

9. **Run and Generate**: Run your markdown file to produce an HTML file.

10. **Commit and Push**: Upload all changes to GitHub, including the original `.qmd`/`.Rmd` file **and the HTML file**.

Good luck, and have a blast working on your project!

## ✔️ How we will assess your submission: 

1. **Scoring**: This assignment has a maximum score of 100 points. The points for each task are specified next to the task names.
2. **Weightage**: This assessment contributes to **75%** of your final grade.
3. **Assessment Criteria**:
   - **Correctness**: We will evaluate if you followed the instructions precisely.
   - **Creativity**: We'll assess the ingenuity and originality of your ideas for data sources, data manipulation, and data visualisation.
   - **Organisation, Style, and Efficiency**: We will evaluate your code and markdown on clarity, organisation, high-quality comments, and adherence to the best use of the R packages and software development practices discussed in the course.
4. **Weighting**: Initially, we plan to use the following weighting: 15% for correctness, 15% for creativity, and 70% for organisation, style, and efficiency. If this weighting leads to too many high scores, we might need to apply small changes to these weights based on the submissions received to match the Marking Scheme Expectations below.
5. **Expected Score**: A pristine job would likely score around **70%**. This means flawless code, high efficiency, and impeccable markdown formatting with well-documented comments that make it a delightful read. Scoring beyond that indicates exceptional performance, showcasing genius-level work (or potential leniency in our assessment).

Remember, the main goal is for you to learn and grow throughout this process. So, give it your best shot, and we look forward to seeing your remarkable work!

**More on 'Organisation, Style, and Efficiency'**

To achieve a good score in this which is the most valuable criterion, it's imperative that you showcase your data wrangling skills. We will be looking for the following:

- Good use of `dplyr`, including pipes, to efficiently manipulate data.
- Skillful application and use of custom functions, especially when dealing with long or repetitive code sections. If you choose not to create a custom function in certain cases, explain why.
- Preferential use of `lapply` and `sapply` over `for` or `while` loops. We want to see that you avoided the 'growing objects' bad pattern (Check Chapter 2 of the R Inferno book).
- Effective use of `ggplot` with appropriate choice of geoms, aesthetics, and scales to create meaningful visualizations.
- Well-organized and clean code, along with a structured file organization.
- Good use of markdown formatting to create a clear and concise report.
- Appropriate usage of data types, going the extra mile to make your tidy data concise and well-organized.
- A coherent data storytelling approach that effectively communicates the insights from your data analysis.
- Skillful data summarization using `group_by`, `mutate`, and `summarise` functions.
- Proficiency in data reshaping, demonstrated through the use of `pivot_longer` and `pivot_wider`.
- (Optional): Consider creating a database to store your data and explore interactive visualizations.

Remember, your data wrangling skills will be a significant determinant of your success in this assignment. So, focus on showcasing your mastery of these techniques to create a compelling and insightful project. Good luck!

**Marking scheme expectations**

| Percentage Mark | Letter Grade Equivalent |
|:----------------|:------------------------|
| 80+             | A+                      |
| 70-79           | A                       |
| 65-69           | A-                      |
| 60-64           | B+                      |
| 50-59           | B                       |
| 48-49           | B-                      |
| 42-47           | C+                      |
| 40-41           | C                       |
| 39 or less      | F                       |


You should expect to earn around **B+** or **A-** points (good and excellent scores!) if you have followed all instructions correctly, although you might have made some inefficient choices in your code or your files need better formatting. For instance, if you did not create custom R functions when it could have made your code more efficient, you didn't use suitable data types, the structure of files and directories is sub-par, or the layout and aesthetics of your markdown file were not particularly clear and easy to follow. 

You should expect closer to an **A** if, on top of following all instructions to the letter, your code looks _really_ neat and organised, to a point where we felt impressed. The HTML produced by your code is well-formatted and easy to read.

You should expect more **>70/100**  (the upper band of **A** and beyond) only if, on top of being correct and well-formatted and efficient, your submission contained some advanced `tidyverse` operations and functions that were really impressing, refined, well documented and well reasoned!

You should expect less than **55/100** if you did not follow the instructions, did not produce the suitable output files, or did not use any functions or any of the `dplr`/`tidyverse` functions we have been exploring in class.

# Homework 1 Report

**Name:** Robert M. Martin Jr  
**Course:** CS 625 Data Visualization  
**Due Date:** September 7, 2025  

---

## Git and GitHub

**Q1.** What is the URL of the new GitHub repo that you created in your personal account?  

**Answer:** [https://github.com/rmmartin1207/CS_625_HW1](https://github.com/rmmartin1207/CS_625_HW1)

**Q2.** In which direction does the 'pull' command work?  

**Answer:** The `git pull` command downloads changes from the **remote repository (GitHub.com)** to the **local repository**.

**Q3.** If you committed a change on your local machine, but do not see the update on GitHub.com, what step might you have forgotten?  

**Answer:** You likely forgot to run the `git push` command, which sends your local commits to GitHub.

---

## Markdown

**Q1.** Create a bulleted list with at least 3 items. How is this different from a numbered list?  

- Item one  
- Item two  
- Item three  

Numbered lists (1., 2., 3.) imply sequence or ranking, while bulleted lists simply group related items without order.  

**Q2.** Write a single paragraph that demonstrates the use of *italics*, **bold**, ***bold italics***, `code`, and includes a [link](https://openai.com).  

This is a paragraph with *italics*, **bold**, ***bold italics***, and `inline code`. Here is also a [link to OpenAI](https://openai.com).  

**Q3.** Find an image of an animal, upload it to your repo, and insert it below.  

![Christy the animal](Christy.png)

Or resized with HTML:  
<img src="Christy.png" height="200" alt="Christy the animal">  

---

## Tableau

**Q1.** After you have created the final bar chart displaying the data from the South region, pick one of the other regions, save the chart as an image, and include it below.  

![Tableau chart for East Region](tableau_east.png)  

**Answer:** This bar chart shows the sales distribution for the **East region**. It is similar in style to the South region chart, but the values differ by category. Saving and embedding the chart as an image demonstrates exporting visualizations from Tableau and inserting them into Markdown.  

---

## Google Colab

**Q1.** Provide the shareable link to your edited Colab notebook.  

**Answer:** [My Colab Notebook](https://colab.research.google.com/drive/example_link)  

*(Replace `example_link` with your actual Colab shareable link.)*  

---

## Python / Seaborn

**Q1.** Insert the first scatterplot figure and describe what it shows.  

![Seaborn scatterplot](scatter.png)  

**Answer:** The scatterplot maps **bill_length_mm** (x) vs **bill_depth_mm** (y) for penguins. Points tend to form **distinct clusters** corresponding to species and show a general **trade‑off pattern** (longer bills often accompany shallower depths and vice‑versa). Outliers are sparse and most observations lie in a few dense clouds.

**Q2.** Insert the bar chart figure and describe what it shows.  

![Seaborn bar chart](bar.png)  

**Answer:** This bar chart aggregates **body_mass_g** by **species** (the `.Agg()` layer computes an average for each category). Bars show that species differ in mean body mass—one species has the **largest average mass**, another the **smallest**, with a clear separation across categories.

**Q3.** Remove the outer parenthesis from the second figure code. What happened?  

**Answer:** Without the outer parentheses, Python no longer allows the line break before the chained method call (the leading `.add(...)`). The result is a **syntax/indentation error** because implicit line continuation was provided by the parentheses. Keeping the outer parentheses (or putting the expression on one line) is required for multi‑line method chaining.

---

## Observable / Vega-Lite

**Q1.** Replace `markCircle()` with `markSquare()`. What happened?  

**Answer:** …

**Q2.** Replace `markCircle()` with `markPoint()`. What happened?  

**Answer:** …

**Q3.** What change is needed to swap the x and y axes?  

**Answer:** …

**Q4.** Comment out `vl.y().fieldN("Origin"),` in the horizontal bar chart. Insert PNG below and explain.  

![Vega-Lite modified chart](vegalite.png)  

**Answer:** …

---

## References

List all websites, tutorials, Q&A posts, or AI tools you consulted. Include full URLs, not just domain names.

---

# Computational Biology Starter Kit

Welcome to the **Computational Biology Starter Kit**! This repository aims to help scientists, especially those new
to computational biology, get started with the essential tools, skills, and best practices in the field. Whether
you're a biologist interested in coding or a computational enthusiast diving into biology, this guide provides
a structured path to help you begin your journey.

## Recommended (Probably Required) Reading

Start with this selection of articles that provide an overview of computational biology and getting started.

These articles were very helpful in shaping my own path in computational biology,
and I hope they will be useful to you as well.

1. **[So you want to be a computational biologist?](http://www.nature.com/nbt/journal/v31/n11/full/nbt.2740.html)**
2. **[Best Practices for Scientific Computing](http://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1001745)**
3. **[Good Enough Practices in Scientific Computing](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005510)**
4. **[Ten simple rules for biologists learning to program](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005871)**
5. **[Ten Simple Rules for Reproducible Computational Research](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003285)**
6. **[A Quick Guide to Organizing Computational Biology Projects](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1000424)**
    - This article is a bit old, but the principles are still relevant.
    - I recommend reading this [MIT article on file structure](https://mitcommlab.mit.edu/be/commkit/file-structure/) and using a
    directory structure similar to [this](https://github.com/mitcommlab/Coding-Documentation/blob/master/File-Structure-Case-Studies.md#case-study-2-a-simple-hierarchy)

Overall, these articles help you learn some best practices before diving into a project or learning git, Unix,
Python, or R.

## What You’ll Learn

- Basics of version control with Git and GitHub
- Navigating the Unix command line
- Introduction to scripting with Python and R
- Best practices for reproducibility in computational biology
- Workflow management and automation tips

## A Suggested Learning Path

There are multiple paths a person can take to learn computational biology. Here is a suggested path I am providing
that would have been helpful to me when I was starting out.

In general, you should have a project in mind before jumping into these tutorials. This will help you apply what you
learn and make the learning process more engaging.

### 1. **Navigating the Unix Command Line**

- **Why Learn This?** The command line is the backbone of many computational biology workflows, allowing you to
automate tasks, manage files, and run bioinformatics software.
- **Topics to Cover:**
    - Basic commands (`ls`, `cd`, `mv`, `cp`, `rm`, `grep`, `find`)
    - File permissions and environment variables
    - Writing and executing simple bash scripts
    - Data manipulation with `awk`, `sed`, and `cut`
- **Best Practices:**
    - Always back up your data before running destructive commands.
    - Use comments in scripts to document your code.

### 2. **Getting Started with Git and GitHub**

- **Why Learn This?** Version control is crucial for managing your code, collaborating with others, and maintaining
reproducibility in your research.
- **Topics to Cover:**
    - Basic Git commands (`init`, `clone`, `commit`, `push`, `pull`)
    - Creating and managing repositories on GitHub
    - Branching, merging, and resolving conflicts
    - Writing good commit messages and maintaining a clean commit history
- **Best Practices:**
    - Commit often with descriptive messages.
    - Use branches for new features or experiments.
    - Regularly sync with the main branch and keep it stable.

### 3a. **Introduction to Python**

- **Why Learn This?** Python is a versatile language widely used in data analysis, machine learning, and bioinformatics.
- **Topics to Cover:**
    - Basic syntax, data types, and control structures
    - Libraries for data analysis (`pandas`, `numpy`, `matplotlib`)
    - Bioinformatics libraries (`Biopython`, `scikit-bio`)
    - Writing functions and organizing code into modules
- **Best Practices:**
    - Write clean, readable code with meaningful variable names.
    - Use virtual environments to manage dependencies (`venv`, `conda`).

### 3b. **Introduction to R**

- **Why Learn This?** R is especially powerful for statistical analysis and data visualization, often used in genomics
 and other biology-related data analysis.
- **Topics to Cover:**
    - Basic syntax and data structures
    - Data visualization with `ggplot2`
    - Data manipulation with `dplyr` and `tidyverse`
    - Writing reproducible reports with R Markdown
- **Best Practices:**
    - Keep scripts organized and well-commented.
    - Use R projects for organizing related scripts and data.

## Best Practices for Computational Biology

- **Reproducibility:** Document your workflows and use version control for code and data. Consider using Jupyter
notebooks, R Markdown, or similar tools to create reproducible research documents.
- **Data Management:** Keep raw data unchanged and well-documented. Use clear naming conventions for files.
- **Coding Standards:** Follow PEP 8 (Python) or Tidyverse style guide (R) for code readability.
- **Collaboration:** Use GitHub issues, pull requests, and project boards to manage work and collaborate effectively.

## Additional Resources

- [GitHub Learning Lab](https://lab.github.com/)
- [Software Carpentry](https://software-carpentry.org/lessons/)
- [Python for Biologists](https://pythonforbiologists.com/)
- [R for Data Science](https://r4ds.had.co.nz/)

## Contributing

We welcome contributions! Please read our [CONTRIBUTING.md](CONTRIBUTING.md) guide for more details.

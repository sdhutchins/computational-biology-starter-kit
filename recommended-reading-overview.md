# Best Practices for Scientific Programming

## Code Readability and Clarity

- **Write code for people, not just computers.**
  - Prioritize human readability and maintainability in your code structure and style (Wilson et al., 2014).
  - Break programs into small, focused functions to reduce cognitive load.
  - Use meaningful, distinctive names for variables and functions.
  - Apply consistent coding style and formatting throughout the project (Wilson et al., 2014).
  - Let the innovation lie in your scientific logic, not in confusing variable names or tangled code structure (MIT Comm Lab).
  - Well-written code should self-document its purpose, minimizing the need for excessive comments (MIT Comm Lab).

## Automate Repetitive Tasks

- **Let the computer do the work.**
  - Automate repetitive steps and analyses instead of performing them manually (Wilson et al., 2014).
  - Script commands or use workflow tools to execute and repeat operations automatically.
  - Save command histories or use shell scripts, Makefiles, or similar tools to capture operations (Wilson et al., 2014).
  - Avoid manual data manipulation—it is error-prone and irreproducible (Sandve et al., 2013).
  - Convert all repeatable or reproducible tasks into scripts or pipelines.

## Develop Incrementally and Use Version Control

- **Make incremental changes.**
  - Work in small, manageable steps with frequent feedback (Wilson et al., 2014).
  - Catch errors early and identify sources when issues arise.
  - Break problems into smaller parts to make programming more approachable (Carey & Papin, 2017).

- **Use version control for everything.**
  - Adopt a version control system (e.g., Git) from the start (Wilson et al., 2014; Wilson et al., 2017).
  - Track changes in code and all manually created files.
  - Commit often in small chunks with informative messages.
  - Regularly push changes to remote repositories for backup (Wilson et al., 2017).
  - Some teams use checklists to ensure changes are saved and shared.
  - Version control also helps your future self understand and reuse your work later.

## Avoid Duplication and Embrace Reuse

- **Don’t repeat yourself (DRY).**
  - Ensure each piece of information or functionality appears in only one place (Wilson et al., 2014).
  - Refactor common operations into functions or modules.
  - Avoid code duplication by modularizing logic.
  - Reuse existing libraries or tools instead of building from scratch (& Papin, 2017).
  - Search for well-maintained solutions before writing new functionality (Wilson et al., 2017).
  - Test libraries on small examples to confirm reliability.

## Test and Validate Rigorously

- **Plan for mistakes and test your code.**
  - Use assertions to confirm that program state is as expected (Wilson et al., 2014).
  - Turn bugs into test cases to prevent reoccurrence.
  - Write unit tests using established frameworks (Wilson et al., 2014).
  - Test critical logic and edge cases.
  - Use debuggers to inspect complicated code (Wilson et al., 2014).
  - Record intermediate results in readable, standardized formats (Sandve et al., 2013).
  - Track what was run and why—like a computational lab notebook (Carey & Papin, 2017).

## Optimize Only After Correctness

- **Get it right before you make it fast.**
  - Premature optimization increases complexity and hides bugs (Wilson et al., 2014).
  - First, ensure the code is correct and results are valid.
  - Optimize only after correctness is verified.
  - Use profiling tools to identify real performance issues.
  - Write code in the highest-level language reasonable for the task (Wilson et al., 2014).
  - Use lower-level languages only if profiling confirms a need.

## Document Code and Workflows

- **Document design and purpose, not just mechanics.**
  - Focus comments on why code exists, not what it does line-by-line (Wilson et al., 2014).
  - Top-of-file comments should describe purpose, inputs, outputs, and usage (Wilson et al., 2017).
  - Document function arguments, return values, and assumptions.
  - Avoid repeating information that is obvious from clear code.
  - Refactor complex code instead of adding excessive commentary.
  - Embed docstrings and inline comments with code (Wilson et al., 2014).
  - Provide runnable examples or small test data for illustration (Wilson et al., 2017).

- **Maintain project-level documentation.**
  - Write an overview or README with:
    - Project goals
    - Code organization
    - Reproduction instructions (Wilson et al., 2017)
  - Aim to help your future self or collaborators get up to speed quickly (MIT Comm Lab).

## Organize Projects and Data Logically

- **Establish a coherent file structure.**
  - Use a consistent directory layout (Wilson et al., 2017).

```bash
project/
├── data/       # raw data and metadata
├── results/    # processed data or outputs
├── src/        # source code
├── doc/        # documentation and manuscripts
├── bin/        # external executables
```

- **Best practices:**
  - Do not modify raw data—store processed copies separately.
  - Use relative paths in code, not absolute ones (MIT Comm Lab).
  - Name files descriptively with meaningful terms or timestamps (Wilson et al., 2017).
  - Avoid ambiguous labels like `final_version2.csv`.
  - File structures communicate project logic and organization (MIT Comm Lab).

## Collaborate and Share Effectively

- **Use code reviews and issue trackers.**
  - Conduct peer reviews before merging changes (Wilson et al., 2014).
  - Try pair programming to solve difficult problems.
  - Track bugs and tasks using an issue tracker (Wilson et al., 2014; Wilson et al., 2017).

- **Make projects accessible and citable.**
  - Agree on coding and communication standards (Wilson et al., 2017).
  - Include a license early in the project.
  - Archive in public repositories with DOIs for citation (Wilson et al., 2017).
  - Share early and frequently—don’t wait for perfection.
  - Ask for help on forums like Stack Overflow or BioStars (Carey & Papin, 2017).
  - Scientific programming is collaborative and benefits from openness.

## Ensure Reproducibility of Results

- **Track every step of your analysis.**
  - Record exactly how each result or figure was produced (Sandve et al., 2013).
  - Make workflows executable—don’t rely on prose descriptions alone.

- **Avoid manual manipulation.**
  - Replace hand-edits with scripts (Sandve et al., 2013).
  - If manual edits are needed, document them and save all intermediates.

- **Archive software environments.**
  - Record tool versions and library dependencies.
  - Use containers, virtual environments, or export environment lists (Sandve et al., 2013).

- **Record provenance.**
  - Link results to specific scripts and commit hashes (Sandve et al., 2013).

- **Account for randomness.**
  - Set and save random seeds in stochastic analyses (Sandve et al., 2013).

- **Save data at all stages.**
  - Preserve raw, cleaned, and intermediate data files (Wilson et al., 2017).
  - Store the data behind each figure (Sandve et al., 2013).

- **Share openly.**
  - Publish code, data, and documentation (Sandve et al., 2013; Wilson et al., 2017).
  - Use public archives for long-term access.
  - Transparency improves your work and benefits the community.

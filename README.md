# My Assessment Repository  

![cloud](img/cloud_infrastructure.jpg)

**By Hugo Camacho Romero at [ATU](https://www.atu.ie/)** Lecturer Mr. Ian McLoughlin.

This repository contains my assessment submission for the computer infrastructure module.

## Overview

***

This project leverages the Linux command line environment to configure, script, manipulate, and move data, offering a comprehensive introduction to command-line operations as an alternative to graphical user interfaces (GUIs). Key technologies include GitHub, GitHub Codespaces, Python (Anaconda), Visual Studio Code, and Jupyter Notebooks.

The project focuses on developing essential skills in data handling and automation. Tasks range from creating structured directory hierarchies, working with timestamps for

file creation, and downloading structured weather data from Met Éireann's API, to automating processes using bash scripts and GitHub Actions workflows.

### Tasks Summary

***
1. Create Directory Structure

Set up a structured hierarchy of folders using the command line. The root directory includes data, with subfolders timestamps and weather for organized data management.

2. Timestamps

Learn how to create and log timestamps in a file for event tracking. This task introduces the use of the date command with append operators (>>) and highlights best practices for avoiding data overwrites.

3. Formatting Timestamps

Format timestamps to ensure unique, sortable filenames (e.g., YYYYmmdd_HHMMSS). These are critical for preventing duplication in processes that rapidly generate files.

4. Create Timestamped Files

Generate files with dynamic, timestamped names using the touch command combined with formatted date outputs. This approach ensures an orderly and chronological file structure.

5. Download Weather Data

Use the wget command to programmatically retrieve weather data for the Athenry station from Met Éireann's API. This step eliminates manual data scraping and integrates directly with the structured API endpoint.

6. Timestamp the Data

Enhance the data download process by appending a timestamp to filenames (e.g., YYYYmmdd_HHMMSS.json) for efficient storage and retrieval. This builds on earlier tasks by adding automation to the workflow.

7. Write the Script

Automate the weather data retrieval process by creating a bash script (weather.sh) that downloads and saves timestamped data files directly into the designated directory.

8. Automate Weather Script Execution

Configure a GitHub Actions workflow to run the weather.sh script daily at 10:00 AM. Key steps include:

- Cloning the repository.
- Executing the script.
- Committing and pushing the new data to the repository.

Logs from GitHub Actions confirm the workflow's functionality and success

9. Analyze Weather Data with Pandas

In the weather.ipynb notebook:

- Use the pandas function read_json() to load and analyze one of the weather data files.
- Summarize the data and provide context using metadata from data.gov.ie.

10. Cowsay Fortune Automation

A similar process was implemented for an additional task:

- A folder named .github/workflows was created to define an automation workflow for generating and saving cowsay fortunes daily at 3:00 AM.
- This process uses GitHub Actions to generate a random fortune, timestamp it, and push the results back to the repository.


### Project Overview
***

This project ties together scripting, data handling, and automation concepts. By utilizing GitHub Codespaces in a Linux bash environment, it builds practical skills for

managing structured data efficiently. The tasks demonstrate how to create automated workflows that integrate directly with version control systems like GitHub.

By the project's completion, the system is fully automated for both weather data retrieval and fortune generation, with scheduled GitHub Actions workflows handling 



### Context installer

Source: [Ian McLoughlin](https://github.com/ianmcloughlin/2425_computer_infrastructure/tree/main)

Within the context we will navigate through the environment to create and develope programs using Linux command
line. The following information will lead us to the steps  from singing up to GitHub, GitHub Pro to use
codespaces, Git, Visual Studio Code and Anaconda.

### GitHub

1. [Sign Up for GitHub.](https://github.com/signup)
2. [Get a free GitHub Pro Account.](https://github.com/education/students)
3. [Download Git.](https://git-scm.com/downloads)

### Visual Studio Code

1. [Download Visual Studio Code.](https://code.visualstudio.com/Download)
2. [Watch VSCode Introductory Videos.](https://code.visualstudio.com/docs/getstarted/introvideos)
3. [Read Python in Visual Studio Code.](https://code.visualstudio.com/docs/languages/python)
4. [Read Using Git source control in VS Code.](https://code.visualstudio.com/docs/sourcecontrol/overview)

### Python

1. [Download the Anaconda Python Distribution.](https://www.anaconda.com/download/success)
2. Update Anaconda: `conda update --all` (as in command line).

# ADA Final Exam

This repository contains the final exam for Applied Data Analysis (CS-401).

The questions and the data will be made available to you at 15:15 on January 17th, 2023 via the Jupyter Notebook named "exam.ipynb" and the folder named `data`, respectively.

All the logistical details, rules, and guidelines pertaining to the exam are stated below.

Additionally, to iron-out critical logistical aspects, such as execution environment setup, sharing of high-level rules, and submission process of your solved exam, we would like each of you to participate in a dry-run of the exam. Please see the [dry-run instructions](#Dry-run-Instructions) section at the bottom of this document for details.

## Conda Environment
We have prepared a conda environment, named `adaexam`, with all the Python packages that you might need for the exam. You can install it with the following command:   
`conda env create -f adaexam_crossplatform.yml`

Once installed, to activate the environment, please use `conda activate adaexam`. To use it in Jupyter, please initiate Jupyter from a terminal with adaexam as the active conda environment. Alternatively, you can add the conda environment as a custom kernel by using the following command:   
`python -m ipykernel install --user --name=adaexam`

*Note-1: You are of course welcome to install any additional package to the aforementioned conda environment.*   
*Note-2: The aforementioned setup has already been tested by the ADA teaching staff on Mac OS Ventura 13.0.1, Ubuntu 22.04, and Windows 10.*

## Timeline
**Exam date:** Tuesday, January 17th, 2023   
**Exam start:** 15:15 (CET/UTC+1h)   
**Exam end:** 18:15 (CET/UTC+1h)   
We allow a grace period of 15 minutes for you to submit your solved IPython notebooks. The strict deadline is at 18:30. **Later submissions will not be accepted!**

## High-level Guidelines and Rules

1. You cannot leave the room in the first and last 15 minutes.
2. You should be connected to the EPFL network for the duration of the exam and are not allowed to use VPNs or Hotspots.
3. You can use all the online resources you want, except for communication tools (emails, web chats, forums, phone, etc.) and AI-powered tools (e.g. ChatGPT, GitHub Copilot, LLMs, etc.) that have the potential to directly give you a solution. We will be monitoring the network for any unusual activity between 15:00 and 18:30.
4. Announcements during the exam, if any, will be made under the *"Announcements"* section of [this Google document](https://docs.google.com/document/d/e/2PACX-1vT4WC_5U4aLwlm0xiCyhBudlw1JmL8H24DIXoEb2F9fDCo_VtFAa9h3M_ZdYfnm0eb0TTzB6K8quQJ6/pub).   
   *Note: For sharing documents with more than 100 viewers, Google recommends publishing them to the web (details [here](https://support.google.com/a/users/answer/9308870?hl=en)). As a consequence, the document may no longer be updated in real time by your Web browser. Thus, in order to view an up-to-date version of the document you might need to periodically refresh the page.*   
5. You have to open "exam.ipynb" in Jupyter, edit it, and submit it with your solutions.
6. You have *3 hours* (15:15 -- 18:15) to solve the exam and upload your solved iPython (.ipynb) notebook.
7. We have prepared a conda environment with all the necessary Python packages. If not done already, you can install it with the following command:   
`conda env create -f adaexam_crossplatform.yml`
8. You are allowed to use any built-in Python library that comes with Anaconda.
9. You are allowed to use [Google Colab](https://colab.research.google.com/) or [EPFL Noto](https://noto.epfl.ch), however, it's your responsibility to ensure that the required Python packages (see the section [Conda environment](#Conda-environment) for details) are accessible in the execution environment and platform of choice.
10. There are **three tasks:** 1, 2, and 3, which are further split into several subtasks.
11. Tasks 2 and 3 are independent of each other (although conceptually related).
12. For questions containing the **/Discuss:/** prefix, answer not with code, but with a textual explanation (in markdown).
13. Don't forget to add a textual description of your thought process, the assumptions you made, and your results!
14. Please write all your comments in English, and use meaningful variable names in your code.
15. We suggest that you not obsess over small details in the beginning, and try to complete as many tasks as possible during the first 2 hours. Then, go back to the obtained results, write meaningful comments, and debug your code if you have found any glaring mistake.
16. Fully read the instructions for each question before starting to solve it to avoid misunderstandings, and remember to save your notebook often!
17. We will **not run your notebook for you**! Rather, we will grade it as is, which means that only the results contained in your evaluated code cells will be considered, and we will not see the results in unevaluated code cells. Thus, be sure to hand in a **fully-run and evaluated notebook**.
18. In continuation to the previous point, interactive plots, such as those generated using `plotly`, should be **strictly avoided**!
19. Remember, this is not a homework assignment -- no teamwork allowed!

## Submission
* You will have until 18:30 (strict deadline) to turn in your submission. **Late submissions will not be accepted.**
* For students **with** an EPFL email address:
   * Your file has to be named as "YourSCIPERNumber.ipynb". For example, if your SCIPER number is '123456', please name your file as '123456.ipynb'.   
   **Note-1: We won't grade your exam if the file is not properly named, thus, be extra careful in this regard.**   
   *Note-2: The Google form upload utility might automatically append the name on your EPFL account to the filename provided by you, thus, don't be alarmed if this happens; it’s fine. For instance, if your name on the EPFL account is 'Abc Xyz' and you upload the file '123456.ipynb', it might be renamed to '123456 - Abc Xyz.ipynb'*
   * Upload your Jupyter Notebook (1 file) to [this Google form](https://forms.gle/pkXJqL5oRqtjfCsv5) at the end of the exam, with all the cells already evaluated. You need to **sign in to Google** using your **EPFL credentials** in order to access the form. Please see [this EPFL Wiki](https://wiki.epfl.ch/help-gdrive-en) (accessible only from the EPFL network or via VPN if not physically on campus) for more details on how to use Google services via your EPFL credentials.   
   *Note-1: If you get a *'You need permission'* message, then it means you are trying to access the Google form via a non-EPFL account. This can be fixed by opening the submission link in a private/incognito window and signing in using your EPFL credentials.   
   *Note-2: You can correct 'typos' in your name using the "edit response" option, however, the uploaded 'ipynb' file cannot be modified. If you need to modify the ‘ipynb’ file, please create a new submission.*   
   *Note-3: Multiple submissions are allowed. We will only consider the **latest** submission before the deadline and ignore all other previous submissions.*
   * On successful submission, you should receive an acknowledgement email from forms-receipts-noreply@google.com. If you don't receive an acknowledgement email (check your ‘spam’ and ‘junk’ folders as well) by 19:30, please notify us by sending an email to ada-core-assistants-2022@groupes.epfl.ch.
   * In case of problems with the form, send your Jupyter Notebook via email to ada-core-assistants-2022@groupes.epfl.ch. This is reserved only for those who encounter problems with the submission - you need to have a **reasonable justification** for using this backup.
* For students either **without** an EPFL email address or participating in the **extramural exam**:
   * Your file has to be named (in *titlecase*) as "YourFirstName_YourLastName.ipynb". For example, if your first name is 'Abc', and last name is 'Xyz', please name your file as 'Abc_Xyz.ipynb'.   
   **Note: We won't grade your exam if the file is not properly named, thus, be extra careful in this regard.**   
   * Send your Jupyter Notebook (1 file) via email to ada-core-assistants-2022@groupes.epfl.ch.

## Dry-run Instructions

Complete the following steps for a smooth exam experience on the day of the exam:
1. Carefully read and familiarize yourself with all the aforementioned rules and instructions.
2. Set up the `adaexam` [conda environment](#Conda-Environment).
3. Execute all the cells of `exam_dryrun.ipynb` in Jupyter with `adaexam` as the active conda environment. On successful execution, it should print **'Package import test successful!'** without throwing any errors.
4. Make sure you can access the [Google document](https://docs.google.com/document/d/e/2PACX-1vT4WC_5U4aLwlm0xiCyhBudlw1JmL8H24DIXoEb2F9fDCo_VtFAa9h3M_ZdYfnm0eb0TTzB6K8quQJ6/pub) containing the *"Announcements"* section. This document would be used for sharing the announcements during the exam.
5. **[Only for students with an EPFL email address]** Test the [submission](#Submission) utility by submitting any 'ipynb' file using [the Google form](https://forms.gle/pkXJqL5oRqtjfCsv5). On successful submission, you should receive an acknowledgement email from forms-receipts-noreply@google.com.

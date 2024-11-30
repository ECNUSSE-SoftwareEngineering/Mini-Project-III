# Course Mini Project III

## Task Selection
You can choose **one task** between Task 1 and Task 2.

## Task 1: Property-Based Testing and the Kea Tool

### Assignment Requirements
1. **Understand the basic concepts of random testing (fuzz testing) and GUI testing**.
2. **Research the theories and methods of property-based testing**.
3. **Investigate the property-based GUI testing tool Kea to know its technical principles**:
   - Visit the Kea GitHub repository: [Kea GitHub](https://github.com/ecnusse/Kea)
   - Read the relevant research paper: [Property-Based Testing for Android Apps](https://xyiheng.github.io//files/Property_Based_Testing_for_Android_Apps.pdf)

### Assignment Content
1. **Run the Kea Tool**:
   - Successfully run the Kea tool based on the [tutorial](https://kea-doc.readthedocs.io/en/latest/).
   - Execute the tool on some of the application properties included in the Kea repository and **provide screenshots as evidence that you have run the tool and discovered some application bugs**.

2. **Understanding the Technical Principles and Suggestions for Improvement**:
   - Summarize your understanding of the technical principles behind the Kea tool, such as:
     - Where is random testing used in the kea tool.
     - Your new understanding of testing techniques.
   - Provide suggestions for improving the Kea tool to enhance its testing effectiveness, such as:
     - How to increase code coverage.
     - How to enhance bug detection capabilities.
     - How to improve usability.
   - Write 1-2 pages of content. We mainly based on the content of the writing itself, such as whether the technical understanding is correct, whether the improvement suggestions provided are meaningful and reasonable, etc

### Reference Links
- Regarding the principles of the AFL tool:
  - [AFL Documentation](https://afl-1.readthedocs.io/en/latest/index.html)
  - [More About AFL](https://afl-1.readthedocs.io/en/latest/about_afl.html#more-about-afl)

### Submission
- Submit a `.docx` file containing the following:
  - Screenshots of running the tool.
  - Your understanding and suggestions regarding the technical principles behind the Kea tool.

---

## Task 2: Implementing a Fuzz Testing Tool

### Assignment Requirements
1. **Understand the basic concepts of random testing (fuzz testing)**.
2. Use lab3 from the course **"Software Analysis, Testing and Verification"** to deeply understand the theory and method of fuzzing testing, particularly AFL (American Fuzzy Lop).
   - Visit the course GitHub repository: [Software Analysis and Verification Course GitHub](https://github.com/ecnu-sa-labs/ecnu-sa-labs/)
   - Read the Lab 3 manual: [Lab 3 Manual](https://github.com/ecnu-sa-labs/ecnu-sa-labs/blob/master/lab_manual/lab3.md)

### Assignment Content
1. **Setup the experiment environment according to [lab instructions](https://github.com/ecnu-sa-labs/ecnu-sa-labs/blob/master/lab_manual/course-vm.md )**
2. **Follow the Lab 3 manual to implement the fuzzing test tool**:
   - Complete the implementation of the missing code (marked as TODO) in the simplified fuzz testing tool code framework provided in Lab 3.
   - Test using some of the programs provided in Lab 3.
   - Submit the complete code for Lab 3.

### Submission
- Package your Lab 3 project files into a compressed file (e.g., `.zip` / `.rar`) and submit it to the repository.

---

### Note
If you selected task 1, you should have a.docx file in your repository; If you chose Task 2, you should have a .zip/.rar/ etc zip file in your repository.

Please give these two projects stars by the way, thank you ~ 
1. [Kea GitHub](https://github.com/ecnusse/Kea)
2. [Software Analysis and Verification Course GitHub](https://github.com/ecnu-sa-labs/ecnu-sa-labs/)

java c
Module code/name 
MSIN0023 Computational Thinking
Academic year 
2024/25 
Term 
1 
Assessment title 
Assignment 3: Code, discuss and analyse an algorithm applied to a management problem
Individual/group assessment 
Individual 
Submission deadlines: Students should submit all work by the published deadline date and time. Students experiencing sudden or unexpected events beyond your control which impact your ability to complete assessed work by the set deadlines may request mitigation via the extenuating circumstances procedure. Students with disabilities or ongoing, long-term conditions should explore a Summary of Reasonable Adjustments. Students may use the delayed assessment scheme for pre-determined mitigation on a limited number of assessments in a year. Check the Delayed Assessment Scheme area on Portico to see if this assessment is eligible.
Return and status of marked assessments: Students should expect to receive feedback within 20 working days of the submission deadline, as per UCL guidelines. The module team will update you if there are delays through unforeseen circumstances (e.g. ill health). All results when first published are provisional until confirmed by the Examination Board.
Copyright Note to students: Copyright of this assessment brief is with UCL and the   module leader(s) named above. If this brief draws upon work by third parties (e.g. Case Study publishers) such third parties also hold copyright. It must not be copied, reproduced, transferred, distributed, leased, licensed or shared with any other individual(s) and/or organisations, including web-based organisations, without permission of the copyright holder(s) at any point in time.
Academic Misconduct: Academic Misconduct is defined as any action or attempted action that may result in a student obtaining an unfair academic advantage. Academic misconduct includes plagiarism, self-plagiarism, obtaining help from/sharing work with others be they individuals and/or organisations or any other form. of cheating that may result in a student obtaining an unfair academic advantage. Refer to Academic Manual Chapter 6, Section 9: Student Academic Misconduct Procedure - 9.2 Definitions.
Referencing: You must reference and provide full citation for ALL sources used, including AI sources, articles, text books, lecture slides and module materials.    This includes any direct quotes and paraphrased text.    If in doubt, reference it.    If you need further guidance on referencing please see UCL’s referencing tutorial for students. Failure to cite references correctly may result in your work being referred to the Academic Misconduct Panel.
Use of Artificial Intelligence (AI) Tools in your Assessment: Your module leader will explain to you if and how AI tools can be used to support your assessment. In some assessments, the use of generative AI is not permitted at all. In others, AI may be used in an assistive role which means students are permitted to use AI tools to support the development of specific skills required for the assessment as specified by the module leader. In others, the use of AI tools may be an integral component of the assessment; in these cases the assessment will provide an opportunity to demonstrate effective and responsible use of AI. See page 3 of this brief to check which category use of AI falls into for this assessment. Students should refer to the UCL guidance on acknowledging use of AI and referencing AI. Failure to correctly reference use of AI in assessments may result in students being reported via the Academic Misconduct procedure. Refer to the section of the UCL Assessment success guide on Engaging with AI in your education and assessment.
Content of this assessment brief Section 
Content A 
Core information B 
Coursework brief and requirements C 
Module learning outcomes covered in this assessment  D 
Groupwork instructions (if applicable) E 
How your work is assessed  F 
Additional information 
Section B: Assessment Brief and Requirements 
Code, discuss and analyse an algorithm applied to a management problem 
Introduction: 

Consider a problem we have covered from this module or from any other module (e.g. from Data Analytics I or Mathematics II) involving non-trivial algorithms. You are also free to consider any other algorithmic topics we may not have covered e.g. image-processing. The problem should relate to a management problem or business-idea that requires the use of algorithms.
A non-trivial algorithm   uses loops and will be of at least linear complexity. The more complex your algorithm the more opportunity you will have to demonstrate increased understanding and more sophisticated analysis, providing enhanced potential of a good grade.
You may wish to continue with the same algorithm/problem you presented in your Assignment 2 essay or choose a different algorithm or problem.
Example algorithms: 
Here are some examples of non-trivial algorithms you could consider:·   Data Analytical Classification algorithms including Decision Tree Induction and Nearest Neighbour·   Data Analytical Clustering algorithms including Hierarchical Clustering and K-Means Clustering·   Matrix Row Reduction algorithm to solve systems of simultaneous equations or to find inverse matrices·   Simplex Linear Programming algorithm·   Search and Graph Analysis algorithms, including shortest-path algorithms·   Exhaustive Enumeration and Greedy/Heuristic Algorithms for any NP-Complete problem (eg travelling salesman, knapsack packing problem, wedding banquet seating …)
Report Format and Structure: 
The main body of your report has a word count limit of 2000 words, consisting of a number of sections, as detailed below. In addition, you should include as appendices: all your code appropriately commented; your test run outputs; and extracts from your test data. There is no word limit on the appendices, which will be assessed alongside the main body of your report.
You are required to submit two files, with a third optional data file:1.   A single PDF document containing your full report, including all the appendices.2.   A single supplemental code file, which can either be in the form. of a standard python code file (.py) or a Jupyter notebook file (.ipynb). This code will not be marked, but may be required to validate that the code you have provided as an appendix can be executed, as claimed.3.   An op代 写MSIN0023 Computational Thinking Assignment 3 2024/25Python
代做程序编程语言tional data file   (.csv), if this is required to run your supplemental code file.
The requirements of the code and code appendix are provided first in these instructions as this forms the primary focus of this assignment. This is followed by instructions for each of the sections of main body of the report.
CODE APPENDIX: Provide working python code that solves your problem (30%) 
Provide, as an appendix   to your report, your completed coded.
Embed in your code comments that describe each function in terms of its purpose, inputs and outputs. Additional comments should also be included to help explain key steps in your algorithms, and examples of particular techniques you have used.
You are not required to have written all the code yourself.
There are plenty of examples of python code on the Internet that provide solutions to any problem you are likely to consider. Please feel free to use such code, providing suitable references to these sources. Any code you do re-use should fully implement your chosen algorithms, so that you can identify and comment on how the code implements these algorithms.
You are not allowed to use python modules that directly implement your algorithm in such a way that you cannot see exactly how the code implements the algorithm. 
You can though use standard python modules to provide appropriate data representations for your algorithm (eg numpy for matrix data or networkx for graph data) or provide other functions that do not form. part of the core implementation of your focus algorithm (eg math, statistics, csv, random modules).
You are required to demonstrate you have fully understood the code and have been able to apply it to your particular problem, using suitable test data. This is likely to require, at a minimum, that you write some additional code to run and test your algorithm code on your particular problem; maybe to load data from a csv file, enter some initial input values, and to print or plot outputs.
You should add additional print statements within your code to illustrate key aspects of how the algorithm works.
You should also add appropriate additional code (such as loop counters) and print statements within your code to help assess the complexity your algorithm and prepare Big(O) plots.
You are required to provide code that it understandable and well designed. Code copied from the Internet is often not well designed! Don’t necessarily use the first version you find. You are likely to need to edit and potentially change any code you re-use from the Internet so that it uses clear and consistent names.
You will need to demonstrate decomposition in your code (ie it should contain multiple functions, rather than one large single function). You may therefore need to decompose a large unstructured program from the Internet into smaller functions that are easier to understand.
Main Report Sections: 
1. System Requirements and Your Algorithm (10%) 
Describe your management problem or business-idea and outline the purpose of the software system/application that addresses this problem/idea in the form. of a brief set of system requirements, listing: ·   The functional requirements, identifying the key functions with their data inputs and outputs.·   Any non-functional requirements you believe may be important for this problem.
(Note: The topic of Functional and Non-functional Requirements is covered in Week 8.)
Briefly introduce your algorithm, identifying:·   How your algorithm works.·   How your algorithm helps solve your problem.·   Which functional requirements are associated with your algorithm.
2. Explain how the code works (30%)
Explain the design of your code, particularly commenting on:·   The overall structure of the code in terms of the key functions it contains and how the code decomposes into a hierarchy of functions.·   The flow of the overall code as it progresses from loading/inputting/generating some input data to providing the final solution to your problem.·   In what ways the code is generalised, i.e. in what ways can the code you are using be used to solve more other, more generalised, problems to the specific scenario problem you have applied it to?·   How data is represented in your code and why it is represented in this way.·   The use of any particularly noteworthy or advanced coding features such as: recursive functions, use of list comprehensions, use of dictionaries and sets, passing functions as input parameters.
You must also identify and comment on which parts of the code are re-used (you must reference the source of all re-used code), any re-used code you have improved or changed (how and why), and which parts you have coded fully yourself.
3. Analyse the complexity of your code (10%) 
Explain how the key inputs to your problem can vary in size and nature.    Assess the expected running time complexity of your code in terms of an order of magnitude of the size of your input value(s). Justify your results.
Record the run time performance of your code using a range of different input size values and produce a run time Big(O) plot based on these timings.
Provide additional loop-counter-based and/or theoretical Big(O) plots to support your findings.
Explain you results and compare any theoretical or loop-counter-based analysis with your experimental timing results.
Explain any realistic limits of your code, in regard to runtime performance.
4. Describe the data used in your code (10%) 
Describe the data you used to illustrate how your algorithm could solve your particular management problem or business-idea software. Did you use an open data source for this or did you create/generate the data yourself?    Explain the choices you made in this regard.
Explain how you selected or generated different ‘sizes’ of data to analyse the running time complexity of your code.
5. Conclusions (10%) 
Briefly conclude by discussing the benefits and limitations of your code. Things you may like to consider are:·   Explain in what ways you believe your code follows good design principles.·   Discuss any alternative approaches to solving this problem.·   Suggest how your code could be improved.·   Discuss whether and how you think this code can be generalised for use on different problems.·   Discuss any limitations in your data and the implications for your findings









         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com

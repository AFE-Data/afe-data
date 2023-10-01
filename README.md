### Introduction
In this repository, the available data consists of (1) AFE-101, (2) AgeingDroid, and (3) all evaluation data. 
AFE-101 contains all AFE issues confirmed by ageing users and the whole study results; 
AgeingDroid includes an executable .jar file AgeingDroid and the source code of UITraverser and IssueDetector. 
Our evaluation data is composed of the information of experimental subjects and detailed experimental results (including newly confirmed AFE issues).

### Dataset AFE-101
Here, we list all the collected AFE issues that are confirmed by ageing users.

### AgeingDroid
### How to run AgeingDroid?
Use the following command to execute AFEDroid:

<code> java -jar path-to-AgeingDroid.jar packageName path-to-output-folder runtime-limit </code>

Below is an example of running AgeingDroid for a time litmit of 3600s:

<code> java -jar AgeingDroid.jar com.netease.newsreader.activity C:\Users\strug\Desktop\output 3600 </code>

### The output of AgeingDroid

In the output folder, the screenshots and the associated GUI trees for all traversed ageing-fit GUI pages are in the path <code> path-to-output-folder\layouts </code>, and AFE issue detection results are in the path <code> path-to-output-folder\layouts_results </code>.

### Evaluation data
Here, we list all the experimental subjects and results.




### Introduction
In this repository, the available data consists of (1) AFE-101, (2) AgeingDroid, and (3) all evaluation data. 
AFE-101 contains all AFE issues confirmed by ageing users and the whole study results; 
AgeingDroid includes an executable .jar file AgeingDroid and the source code of UITraverser and IssueDetector;
Our evaluation data is composed of the information of experimental subjects and detailed experimental results (including newly confirmed AFE issues).

### Dataset AFE-101
Here, we list the examples of AFE issues in mobile app Himalayan, and you can obtain the complete data at the following website:
https://terabox.com/s/1xkT3lJBwoWPVSUDNqpHSSg

For each AFE issue, we will provide it's related  GUI trees and GUI screenshots. Specifically, take the issue 1 of Himalayan as an example (in path: AFE-101/Himalayan-Issue-set/1),  there exists four files: layout_1.xml, layout_2.xml, screenshot_1.png, and screenshot_2.png.
Among these files, layout_1.xml and layout_2.xml are the associated GUI trees of screenshot_1.png and screenshot_2.png. During the execution of the app, screenshot_2.png is executed after screenshot_1.png. That is, screenshot_1.png -> screenshot_2.png is the execution trace of the app. The AFE issue lies in the last screenshot (i.e., screenshot_2.png) of the execution trace and we use a green solid line box to indicate the widget where the AFE issue is located.

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

You can obtain the experimental subjects of ageing-fit mobile apps' .apk files at: https://terabox.com/s/1OWl6tAe3gwaKfsiramWAdQ

You can obtain the examples of newly detected AFE issues in mobile app CaiNiao.
For the whole newly detected AFE issues, you can obtain them at: https://terabox.com/s/1Btfh6EElweSLX29kZNRRKw



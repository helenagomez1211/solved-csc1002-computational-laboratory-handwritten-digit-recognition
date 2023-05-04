Download Link: https://assignmentchef.com/product/solved-csc1002-computational-laboratory-handwritten-digit-recognition
<br>
<h1>OVERVIEW</h1>

In this assignment, you will apply Machine Learning skills.  You are asked to design and develop one of its popular classification algorithm called kNN (k-Nearest Neighbors) to programmatically predict handwritten digits in its digitized format.  kNN is supervised based algorithm by majority vote of its neighbors.  It is supervised in a sense that a sufficient large sample dataset of known target values is carefully selected.  This sample dataset will be split into 2 groups.  One group will be used to formula a kNN model to be used for prediction.  It’s called Training.  The other group is used to verify the accuracy of the established model, called Testing. The Training-Testing cycle might result in several iterations of tuning and adjustment until a satisfactory model is achieved with high accuracy of positive predictions, higher better.  Once such a model has been implemented, it’s ready to make prediction.  To make a prediction, simply feed an unknown value of same format to the program and then perform the required computation in accordance to the established kNN model.




<h1>SCOPE</h1>




Note: refer to the sample output for references.

<ol>

 <li>Construct a kNN models based on 2 files called digit-training.txt &amp; digit-testing.txt for training &amp; testing respectively (cross-validation is not required), files are text based.</li>

 <li>Refer to the lab materials for more information on kNN implementation, file format and ideas.</li>

 <li>Use ONLY vector-based function developed from previous lab class to determine nearest neighbors

  <ol>

   <li>Download the latest version of vector.py from moodle</li>

  </ol></li>

 <li>Implement majority vote algorithms to do the best guess prediction; you need to experiment with different values of “k” (3,5,7 or 9) and apply your majority rule to make the prediction. By comparing the results (accuracy) of each outcome, pick the one with the highest accuracy rate.</li>

 <li>IN THE DESIGN DOC: explain (a) how the closest neighbors are chosen and (b) the rule(s) used in making the prediction</li>

 <li>Based on your “FINAL” kNN model implemented (value of k and rule(s)):

  <ol>

   <li>show training and testing info (see Output sections)</li>

   <li>show prediction outcome using file digit-predict.txt (see Output sections).</li>

  </ol></li>

 <li>Files to download from moodle:

  <ol>

   <li>digit-training.txt, digit-testing.txt, digit-predict.txt &amp; vector.py</li>

  </ol></li>

</ol>

<h1>SKILLS</h1>




In this assignment, you will be trained on the use of the followings:




<ul>

 <li>Machine Learning life cycle – dataset, data mining, kNN construction, training &amp; testing</li>

 <li>Python objects &amp; modules (file IO, string, string formatting, sorting, dictionary, list, list comprehensions)</li>

 <li>Controls – if, while, for to control program flow</li>

 <li>Variable Scope</li>

 <li>Functions to breakdown the logic</li>

</ul>




<h1>DELIVERABLES</h1>




<ol>

 <li>Design documentation (A3_School_StudentID_Design.doc/pdf)</li>

 <li>Program source code (A3_School_StudentID_Source.py)</li>

 <li>Output (A3_School_StudentID_Output.doc/pdf)</li>

</ol>




Zip all files above in a single file (A3_School_StudentID.zip) and submit the zip file by due date to the corresponding assignment folder under “Assignment (submission)”

For instances, a SME student with student ID “119010001”:

    A3_SME_119010001.zip:

o A3_SME_119010001_Design.doc/pdf o A3_SME_119010001_Source.py o A3_SME_119010001_Output.doc/pdf

5% will be deducted if any files are incorrectly named!!!




<h1>OUTPUT</h1>




<ol>

 <li>Training Info (see sample output)</li>

 <li>Testing Info (see sample output)</li>

 <li>Prediction Outcome (see sample output)</li>

</ol>




<strong>              </strong>

<h1>DESIGN DOCUMENTATION</h1>




For the design document provide write-up for the following information:

<ol>

 <li>Design:

  <ol>

   <li>Describe the general structure of the program (functions, variables and program flow).</li>

   <li>Describe kNN model you implemented:

    <ol>

     <li>your choice of k value</li>

     <li>how the closest neighbors are determined</li>

    </ol></li>

  </ol></li>

</ol>

<ul>

 <li>the rule(s) used in making the prediction</li>

</ul>

<ol>

 <li>Propose one strategy in reducing the kNN computation time (finding the neighbors) specific to this assignment; “random” is already suggested in class.</li>

</ol>




<ol start="2">

 <li>Test Plan: (Not Required)</li>

</ol>




<h1>TIPS &amp; HINTS</h1>




<ul>

 <li>Use Dictionary to keep list of digit-vectors (during training) and to track accuracy rate (during testing)</li>

 <li>Use Counter() and most_common() from module “collections” to return the closest neighbors</li>

 <li>Use zip + list comprehension for vector sum, subtract, sum, or, average, sum and so on</li>

 <li>Use String Formatting for training and testing info</li>

 <li>Use reduce() from module “functools” to combine multiple vectors into a single OR-vector or AND-vector, if needed</li>

</ul>




<strong>              </strong>

<h1>SAMPLE OUTPUT – TRAINING</h1>







<h1>SAMPLE OUTPUT – TESTING</h1>










<h1>SAMPLE ODUTPUT  – PREDICTION</h1>




Simply output the predicted value, one number per line, such as:

9

8

6

6

8

9

6




<strong>              </strong>

<h1>MARKING CRETERIA</h1>




<ul>

 <li>Coding Styles – layout, comments, white spaces, naming convention, variables, indentation.</li>

 <li>Documentation – Design + Test Plan</li>

 <li>Program Correctness – logic, program structure, functions with appropriate parameters</li>

 <li>User Interaction – how informative and accurate information is exchanged between game player and host.</li>

 <li>Readability counts – programs that are well structured and easy-to-follow using functions to breakdown complex problems into smaller cleaner generalized functions are preferred over a function embracing a complex logic with nested conditions and sub-functions! In other words, a design with clean architecture with high readability is the predilection for the course objectives over efficiency.</li>

 <li>KISS approach – Keep It Simple and Straightforward.</li>

 <li>Balance approach – you are not required to come up a very optimized solution. However, take a balance between readability and efficiency with good use of program constructs.</li>

</ul>







<u>C</u><u>HALLENGES</u>




Determine other means of reducing kNN computation time yet keeping accuracy rate relatively high.



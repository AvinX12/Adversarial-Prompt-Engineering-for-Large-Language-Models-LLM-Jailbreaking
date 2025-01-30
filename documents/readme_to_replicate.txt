ECE-GY 9163 Machine Learning for Cyber Security Lab 2

--- OUR TEAM ---
1. Durga Avinash Kodavalla | dk4852
2. Ark Pandey | ap8652
3. Giorgi Merabishvili | gm3386

--- How to replicate running experiments? ---
1. Upload all the below mentioned files into a Google Colab instance
|
|_ All files inside KOV-main folder (don't upload folder, upload all files in it)
|_ Lab2_Notebook_MLCS.ipynb

2. To run Task 1: I have provided all the training files generated with baseline parameters in the folder...
'task1-vicuna7b-baseline-training-json'. If you want to use it, please upload these too...
Also, the prompts are in file 'testing_subset.csv' inside KOV-main folder (already uploaded)

3. To run Task 2: Please follow guidelines/code as in Lab2_Notebook_MLCS
Change all the hyperparameters as needed, even in files like 'WhiteBox.py'...
As, changing default parameters per experiment will be used in training

4. Similarly, to run Task 3: Please follow the same guidelines as task 2
For the best model, named 'task3-0', I have provided training files too!

--- Extra Notes ---
1. Please use A100 GPU on Google Colab for faster runtimes
2. Please use you own OpenAI API key 
3. All the experiments run and analyzed were as per given guidelines and announcements.
|
|_ For task 1, we used the baseline with given 5 prompts (no parameters changed to improve run-time, we ran it completely)
|_ For task 2, we ran all the 6 experiments (n_tokens: 3, 16 | topk: 25, 50, 100 | max_steps:5) completely
|_ For tasl 3, we ran all first 20 prompts and analysis is given in report.

4. For this announcement given below on NYU Brightspace:
'For those still struggling to run the lab on colab, please go into the WhiteBox.py file and change the "n_iterations" and "depth" parameters for the solver (Lines 89 - 99). By decreasing these parameters, you should have more reasonable runtimes. In addition, the "num_steps" parameter for WhiteBoxParams (Lines 335-343 of KOV.py) also has a large impact on runtime. Feel free to reduce all of these parameters to allow for complete runs so you have jailbreaking data to analyze in your report. If you have any other issues/questions, please email me or come to office hours (Tues/Weds, 1PM EST). '
We haven't modified any additional hyperparameters other than given in assignment pdf.

5. 'requirements.txt' file is provided if you want to replicate all library installatios with exact versions we used.

--- RESULTS ---
All the result csv files are provided in results-csv folder
For task 3, the best score producing file is: "jailbreak_task3-0_BEST.csv"

--- REPORT ---
Please find the report submitted named "Lab_2_Report.pdf" to understand the experiment run.

--- EXTRA CREDIT ---
We have ran all 100 prompts given with surrogate model as 'gpt2-xl', n_tokens=4, topk=100, and max_steps=5
The results are available in "jailbreak_task3-3_gpt2-xl_Extra_Credit.csv"
The average of all prompts moderation (avg) scores recorded: 0.012671017
Percentage better than baseline: +2891.96%
The runtime: 2.5 hrs x 100 = 250 hrs (if run sequentially on A100 GPU)
[This data is not included in the original report submitted, so, included here!]
So, this will be the BEST SCORE producing file of all the files.

--- Special Thanks ---
Thanks to our TA Patrick and Prof. Siddharth Garg to help us get through this lab work by clarifying all our doubts.
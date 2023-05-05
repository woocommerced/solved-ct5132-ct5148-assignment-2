Download Link: https://assignmentchef.com/product/solved-ct5132-ct5148-assignment-2
<br>
Programming and Tools for AI  – ICHEC for Random Walk Experiments




<ul>

 <li><strong>Weighting</strong>: 15% of the module</li>

 <li><strong>Deadline</strong>: Midnight Sunday 22 November</li>

 <li><strong>Groups</strong>: Students may work solo or in groups of two, but may not work together with a student they have already worked with in any assignment in any module on this programme. If working in a group, only one student need submit, but both may submit identical submissions if desired (to silence Blackboard reminders).</li>

</ul>

<h1>Tasks</h1>

Download from Blackboard the file rw.py which runs a random walk experiment. Read it to understand how to run it and the data it will output. You don’t need to understand any theory or applications of random walks.

Write submit.sh and taskfarm.sh files suitable for running rw.py 20 times with taskfarming on ICHEC as studied in lectures and labs. The 20 runs should use random seeds 0-19 inclusive.

(NB: if the resulting .out file contains text such as CommandNotFoundError: Your shell has not been properly configured to use ‘conda activate’., try editing submit.sh to replace conda activate myenv with new lines conda init and source activate myenv, and re-running.)

When the run is successful, you will have 20 new .dat files on kay. Copy the resulting .out and .dat output files from kay to your own machine. Write a program called rw_plot.py which uses Python libraries to combine the data from the .dat files and produce a scatter-plot named rw_results.png showing norm against d. Hint: np.concatenate may be useful for combining data. The plot should look similar to below.

1

Take a screenshot of the email you receive from the SLURM workload manager when your job completes successfully (if you have multiple emails, choose the one whose job ID matches your successful run and .out file). It should be a screenshot from a mail client on a computer, not a phone, so that it clearly shows the

From: and To: and Subject: fields, the job ID, total runtime, and other data, and the email timestamp. It should be named screenshot.png.

Submit a zip including:

<ul>

 <li>sh</li>

 <li>sh • rw.py (do not alter it)</li>

 <li>py</li>

 <li>all .dat files</li>

 <li>the .out file</li>

 <li>png • screenshot.png.</li>

</ul>

<strong>Plagiarism </strong>Students are reminded of the University’s policy on plagiarism. Students may discuss the assignment with other students/groups but must not look at other students’/groups’ work, or allow others to look at theirs. Any online sources used must be cited with URL and date of access in a comment. Materials from CT5132/CT5148 need not be cited. By making a submission, you declare that you have abided by these conditions. Students may be called to interview to discuss their submissions. Suspected infringements will be investigated, and may be referred to NUI Galway authorities.



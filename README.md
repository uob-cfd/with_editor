# Instruction for the "with editor" exercise

The file `oliner_table.py` is a Python code file that implements in the
analysis in the [noble
politics](https://matthew-brett.github.io/cfd2019/chapters/07/noble_politics).
You will recognize the code in `oliner_table.py` from the notebook.

The `.py` file, like the notebook, analyzes the data in `oliner_tab6_8a_1.csv`.

If you run the `.py` code file, for example in Spyder, you will see the
analysis output.  In particular you will see a printout of the proportion of
samples from the ideal (null hypothesis) model that were less than or equal to
the observed number of Bystanders who were also members of a political party.

Your job, should you chose to accept it, is to adapt this file to analyze the
data file `oliner_tab6_8a_2.csv`.

This file contains a series of classifications of the political parties of
which the rescuers and bystanders were members.  These only refer to the
rescuers and bystanders who said, in the data for table `oliner_tab6_8a_1.csv`,
that they were members of a political party before the war.

In particular, your job is to analyze the numbers of rescuers / bystanders who
were members of a "Democratic" political party, as compared to a non-democratic
party.

For the original analysis, we selected a two-by-two table of counts. The two
rows were Yes / No (for Yes was a member of a political party; No not
a member).  The two columns were Rescuer and Bystander.  The values in the
table were the respective counts, so the Bystander column of the Yes row gave
the count of Bystanders who were members of a political party.

For this task, you need to adapt `oliner_table.py` to form a similar two-by-two
table from the data in `oliner_tab6_8a_2.csv`.  The two rows should be
"Democratic", "Other" (for members of Democratic parties; members of
non-Democratic parties).  The two columns should be Rescuer and Bystander. Then
check and adapt the subsequent code to analyze this table.  You should print
out the proportion of samples from the ideal (null-hypothesis) world that the
same number, or fewer than the observed count for Bystander / Democratic,
meaning, the count for Bystanders who were also members of a democratic
political party.

The output should be something of form:

```
Proportion of ideal <= actual X
```

where X is the proportion you calculated.  I think you'll find that proportion
will be small.

When working in Spyder, you can run the whole `.py` file, and inspect the
contents of variables, plots in "IPython" console window, on the bottom right.

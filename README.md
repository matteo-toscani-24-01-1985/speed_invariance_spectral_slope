# speed_invariance_spectral_slope

There are three files per subject - 4 subjects in total.
for instance, for subject 1:
S1.mat - table with trials, speed conditions and material samples
S1_acc.mat - acceleration data per trial
S1_speed_new.mat 

The table file  consists of one line per trial.
In each line the sample is indicated, as well as the speed condition, and the ratings for each adjective. The headings should be self-standing.

The acc data is a matrix with one line per time sample
The fist column represents the time stamp (secs), the second, third and fourth represent acceleration (g units) on the x,y, z axes, respectively , the sixth column is the trial (starting from 0).

The speed data is also a matrix with one line per time sample
The fist column represents the time stamp (secs), the second, third and fourth represent speed (mm/sec) on the x,y, z axes, respectively, the sixth column is the trial (starting from 0).


Sampling was at 3200 Hz

Our samples corresponded to 7 material categories
stone: materials from 1 to 7
plastic: materials from 8 to 18
fabric: materials from 19 to 34
paper: materials from 35 to 46
wood: materials  47 and 48, materials from 63 to 74
metal: materials from 49 to 55
animal (fur or leather): materials from 56 to 62


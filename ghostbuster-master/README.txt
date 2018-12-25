Adaptive  Sampling  Technique  using  KullbackLeibler  distance

Arun Vignesh Malarkkan(1215098183)
Gowtham Sekkilar(1215181396)
Raghavendran Ramakrishnan(1215325696)
Faisal Alatawi(1215360666)

Arizona State University
Dec 3, 2018

There are two modules present in this project:

1. tracking - this is the code base for Project 4 which was required to be integrated with the Adaptive sampling
2. ghostbuster - this was a older version of Project 5 from University of Berkeley,
we altered the dynamic ghost buster game to use the Adaptive sampling . This provides a visual representation of sample size.
We have also added a feature to view the sample size dynamically in the GUI.

* To run the tracking code:

Switch to the tracking project

    -To test the code:
    python KLD_run.py

    -To run q4 (from project 4) :
    python KLD_run.py  -q q4

        - note add (--no-graphics) to turn off the graphics : python KLD_run.py  -q q4 --no-graphics

    -To run q5 (from project 4):
    python KLD_run.py  -q q5

        - note add (--no-graphics) to turn off the graphics : python KLD_run.py  -q q5 --no-graphics

*To run the ghostbuster app:

     -To run the ghostbuster game:

      python ghostbusters.py -w -m center -i approximate -k 1 --fixrandomseed -n 0.3 -l medium -n 0.8



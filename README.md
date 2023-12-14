Step1: Separate the 1MILSED excel sheet into 5 decades in txt files. Decade 5 is only 1 year. Only Articles from journals that appear in 2020 will be included in the decades
Decade 1: 1980-1989
Decade 2: 1990-1999
Decade 3: 2000-2009
Decade 4: 2010-2019
Decade 5: 2020

Step2: Load each decade into VosViewer using these parameters
	Parameters: full counting, thesaurus, min occurrence 10, 100% relevancy, Linlog(2-1).
This creates a map and network txt file for each decade. Rotate each map so that child is rotated to 45 degrees in the first quadrant 


Step3: Load each map txt file into the programme filter_d3_and_d4.ipynb
This filters the keyterms in all decades so that only global keyterms appear in each decade. All decades should contain the same number of terms (304 terms)

Step4: Load each map into VosViewer and rotate each map so that child is rotated to 45 degrees in the first quadrant 

Step5: Load files into top50totaldecades.ipynb.
This scales the <link>weights of nodes with the cubic function so that each node size corresponds with its <link>weights. The cubic function allows the <link>weights to be scaled non linearly.

To use other non-linear functions to scale the weights:
Create another column for the new function in the decade map txt file
Allocate size to this new column

Step5: top50totaldecades.ipynb also creates Edges between nodes which reach a threshold of minimum co-occurence between nodes. The minimum co-occurence can be customised.

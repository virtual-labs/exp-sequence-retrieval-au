Follow ( https://vlab.amrita.edu/index.php?sub=3&brch=311&sim=1835&cnt=2) to install R in personal computer.

Install the SeqinR package.

To load “SeqinR” R package follow the commands

            > library("seqinr")
            > leprae <- read.fasta(file = "Q9CD83.fasta")
            > ulcerans <- read.fasta(file = "A0PQ23.fasta")
            > lepraeseq <- leprae[[1]]
            > ulceransseq <- ulcerans[[1]]
            > lepraeseq # Display the contents of the vector "lepraeseq" 


**Procedure to work simulator**

Follow the code in the command window: 

                library("seqinr")   # Load seqinr package in R
                choosebank("swissprot") # Chossingswissprot for the sequence
                test_query<- query("leprae", "AC=Q9CD83")
                lepraeseq<- getSequence(test_query$req[[1]])
                lepraeseq
	            Click Execute Button for output.    
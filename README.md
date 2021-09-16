# Same-Time-Next-Year-crunching-PubMed-data

The details of the codeset and plots are included in the attached Adobe Acrobat reader (.pdf) file in this repository. 
You need to download the same to view the contents. There are referrals to other contents in BLUE colour also to follow.

A brief Introduction
=====================

The question is: how long does it take for a paper get published?

The R script below loads all of these files in, extracts the data we need and saves them out so that they can be loaded again as a large data frame for analysis. This approach was necessary because the full dataset is 24 GB and difficult to work with.

Some quick figures:

    1.1,060,195 papers in 4,673 journals
    2.3,847 journals had >9 papers)
    3.Median received-to-published time is 146 days (IQR = 94 – 216)
    4.Median time per journal is 165 days (IQR = 125 – 219)
![image](https://user-images.githubusercontent.com/26252963/133556798-d26122bd-3ecb-404e-903a-47cfe23b41cb.png)


    Lag times for all papers
    
According to PubMed the time taken for a paper to be received by a journal and then published is just under six months. The usual caveats apply:
Journals may “reset the clock” on submissions by rejecting the paper and allowing resubmission
This analysis only shows the time that each paper spent at the journal that published it. Manuscripts can go through multiple submissions at other journals, which is not shown here.

Same time next year?

Previous Analysis on PubMed can be found that the time was a lot longer, 239 days. What is responsible for the speed up?

More data: in the previous analysis, around 400,000 lag times could be calculated from 1.5 million records. This time over 1 million lag times could be calculated.
Processes have got faster: the lag from acceptance to published was previously 122 days. This is likely to have fallen (I haven’t calculated this figure this time). A lot of journals now run a continuous publication model which decreases the time to actual publication.


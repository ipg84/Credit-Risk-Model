OBJECTIVE: The purpose of this study is to estimate the Expected Loss (EL), associated with provisions, and the Unexpected Loss (EL), associated with provisions, and the Unexpected Loss (UL), associated with provisions. Unexpected Loss (UL), associated with regulatory capital, of a portfolio of unsecured retail consumer portfolio of unsecured retail loans using advanced Machine Learning and Artificial Intelligence techniques.

Dataset: Detailed information on more than 400,000 consumer loans granted between 2007 and 2015 by Lending Club, one of the leading peer-to-peer financing platforms in the United States.

Files used: Two datasets were used: loan_data_2007_2014.csv (466,285 records) as the construction set, and loan_data_2015.csv (421,094 records) as the validation set, with approximately 75 variables each.

Processing infrastructure: The data processing was performed using notebooks (Python) in virtual environments deployed on EC2 instances of Amazon Web Services (AWS), with storage in S3. We used r5.large (2 vCPUs and 16 GiB of RAM) and r6i.4xlarge (16 vCPUs and 128 GiB of RAM) instances.

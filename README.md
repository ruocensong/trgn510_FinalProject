# trgn510_FinalProject

## Title
**Analyzing RNA-seq of white patients dead of brain cancer between Age 10-40 and Age 60-90**

## Author
* Ruocen Song
* <ruocenso@usc.edu>

## Overview of project
**1. Overview**
* One of the reasons why brain cancer is so terrible is that it is difficult for doctors to remove all the cancer cells clinically, and surviving cancer could turn normal brain cells into cancer cells again.
* In this project, I focus on patients with brain cancer by their AGE.

**2. Objectives**
* I analyze different gene expressions in different samples using Bioconductor.

**3. References/Links to Vignettes**
* https://www.bioconductor.org/packages/devel/workflows/vignettes/RNAseq123/inst/doc/limmaWorkflow.html

## Data
1. I find the data in the HTSeq counts file format from https://portal.gdc.cancer.gov/. The website shows me 20 cases, which are about Age 10-40, and 40 cases, which are about Age 60-90, white people dead of brain cancer. However, I choose 20 cases for each part.
* Age 10-40 cases:  
21badc40-5fb8-496d-a3e6-4f0704500a5d.htseq.counts  
2fafd7bb-e8ce-4b03-8607-cf6cb2a2119a.htseq.counts  
349eaa81-0d2c-4c2b-a762-31555fd1ca50.htseq.counts  
820e3299-bd67-4ba8-a637-32d31205e120.htseq.counts  
7824eae3-957c-4515-b128-45453a11624d.htseq.counts  
960fa206-af01-4f92-b066-4e899fe356fb.htseq.counts  
98cf4f9b-aa89-4c14-b84b-2b8f32439ea0.htseq.counts  
d6706bff-1f56-43a5-a180-1223034cfc09.htseq.counts  
fc8d7362-7eb6-42bb-b3eb-dba3053aa381.htseq.counts  
646f0e58-d861-4761-9fd5-2e48cd28753e.htseq.counts  
39701843-3dae-4114-b04c-b3387e402e4f.htseq.counts  
63a70793-af6d-4248-9085-5d69276a3fff.htseq.counts  
709ff388-3764-4251-90b4-88728468e9f1.htseq.counts  
71e3ff84-ab49-4906-99de-3b873ea04c68.htseq.counts  
7376f374-1439-405e-87d3-c45cfac92ed5.htseq.counts  
88956de1-e6a5-425d-b7dc-2e095c7effee.htseq.counts  
c42fa4ad-4f31-4dfd-b499-599896a57517.htseq.counts  
c5be9ea4-315d-4675-ad8e-269e44b7b77c.htseq.counts  
cd5f0be9-9011-4826-99bc-2850f878ee4e.htseq.counts  
f8e7cbd2-b54a-4f30-8fc1-a5c80bfad8b6.htseq.counts  

* Age 60-90 cases:  
0e30bd18-8e8b-4c52-aace-b5587c6df51a.htseq.counts  
12fbb8e2-457e-48c2-8afe-92c032020580.htseq.counts  
2556ce90-db5f-4beb-897a-db3cf556e054.htseq.counts  
2c15cc20-2347-4bfc-826d-a062f6d74b46.htseq.counts  
2eb90caf-5d1f-48c0-b0c6-8d13c6ef7a4c.htseq.counts  
2f7160fe-5f34-49bc-95fd-029ce83d8c42.htseq.counts  
35d0022b-f677-4340-a3db-c6558782b9d7.htseq.counts  
5d57e2e2-a409-4392-8ea8-900a08a25a6f.htseq.counts  
62727106-91c2-4f63-8ce5-d207569b38e4.htseq.counts  
681955cd-356d-4e64-924b-b0381e3c12bc.htseq.counts  
12b9d0de-401d-4656-8df0-1834dce82751.htseq.counts  
29e74bed-6e84-497e-b78c-1133771203f3.htseq.counts  
337e33d8-d151-4509-8b16-62b288489c4c.htseq.counts  
37355f52-90e5-43e8-a473-0d3bad45a394.htseq.counts  
3af76286-821a-4552-b4f2-b048342abb6e.htseq.counts  
40714706-62ad-4e65-856e-1f40ca0a0fe7.htseq.counts  
982e2940-10b0-4383-bde8-f7ccb9920fc4.htseq.counts  
9c10ea63-f990-4c9b-9149-df9583e59610.htseq.counts  
aee96226-464f-4ab1-ad5f-a9295b9b6a0e.htseq.counts  
e9a0fc7b-94ea-477d-918a-1ef80fefefcd.htseq.counts  


## Milestone 1
I download 40 HTSeq counts format files from the website and handle them in Rstudio. After load the files, I package the data by organising sample inforamtion and gene annotations. Then I pre-process the data by transforming raw counts onto the scale format, removing low-expressed genes, normalising gene expression distributions and analyze the data in an unsupervised manner.
* Update: This milestone 1 has been accomplished.(11/3/2020)

## Milestone 2
Using previous data, I could analyze different gene expression to compare them better. Also,  the coding present heatmaps, MDS plots and boxplots to understand analyze results better.
* Update: This milestone 2 has been accomplished.(11/12/2020)
* However, some information are changed in Readme, for example, datasets. 
* Note: the log-fold-change was changed from 1 to 0.1 for getting more up and down expression. 

## Deliverable
*R Markdown*

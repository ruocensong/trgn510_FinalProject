# trgn510_FinalProject

## Title
**Analyzing RNA-seq of patient dead of brain cancer between white male and white female age 10-60**

## Author
* Ruocen Song
* <ruocenso@usc.edu>

## Overview of project
**1. Overview**
* One of the reasons why brain cancer is so terrible is that it is difficult for doctors to remove all the cancer cells clinically, and surviving cancer could turn normal brain cells into cancer cells again.
* In this project, I focus on patients with brain cancer by vital status, gender, race and age.

**2. Objectives**
* I analyze different gene expressions in different samples using Bioconductor.

**3. References/Links to Vignettes**
* https://www.bioconductor.org/packages/devel/workflows/vignettes/RNAseq123/inst/doc/limmaWorkflow.html

## Data
I find the data in the HTSeq counts file format from https://portal.gdc.cancer.gov/. The website shows me 95 cases, which are about white males, and 60 cases, which are about white females, dead of brain cancer from 10 to 60 years old.
* 20 cases male:  
b4919075-90a9-4c8a-82a0-a0b5f9944ad3.htseq.counts.gz  
a59a3ab2-2bc8-4745-b68c-15339de26484.htseq.counts.gz  
075f1275-3514-47af-a311-477f901e7c4b.htseq.counts.gz  
ce6a9f34-cfd5-44f5-a1be-7362aab92a81.htseq.counts.gz  
d2613681-9368-4ce1-a43d-7d51d5c59098.htseq.counts.gz  
adce8dd4-e2df-43ed-9821-3781ddb7a82f.htseq.counts.gz  
44ed61ae-e74e-40d7-98ce-7803e040567f.htseq.counts.gz  
709ff388-3764-4251-90b4-88728468e9f1.htseq.counts.gz  
90767683-f174-4f81-af32-80430d92f1d7.htseq.counts.gz  
d7851974-f928-428c-a2f6-e9fa4886860e.htseq.counts.gz   
7376f374-1439-405e-87d3-c45cfac92ed5.htseq.counts.gz  
eb24e6f8-dc16-4a6d-b584-9046829cc2ef.htseq.counts.gz  
a3e5cda5-f468-48f3-92fa-864b8bbbecdc.htseq.counts.gz  
31ca8045-265b-4b3d-9065-0e2b14174179.htseq.counts.gz  
ef177d2e-0778-400c-b668-ce23f5237768.htseq.counts.gz  
5cee6ae7-ec80-473f-ad14-864229265985.htseq.counts.gz  
c1fdf09e-3960-4aaa-8c49-fe64c6c5bcea.htseq.counts.gz  
7c03de7a-fafa-4f25-96bd-dc283674a273.htseq.counts.gz  
2fcb9b43-8a11-4730-b57e-4e9fe9013f1c.htseq.counts.gz  
02654be6-2049-4000-a0ac-c26f7ba6f0c9.htseq.counts.gz  

* 20 cases female:  
84762203-320a-4ef6-b080-4c2b04b6a619.htseq.counts.gz  
21badc40-5fb8-496d-a3e6-4f0704500a5d.htseq.counts.gz  
2fafd7bb-e8ce-4b03-8607-cf6cb2a2119a.htseq.counts.gz  
d4eed6a4-986c-409a-8f6c-1ddb00069894.htseq.counts.gz  
349eaa81-0d2c-4c2b-a762-31555fd1ca50.htseq.counts.gz  
284d5f4a-5b44-42f7-90e6-14a5250183aa.htseq.counts.gz  
f5bb4817-1727-41f9-b7f6-3a4e1818c2df.htseq.counts.gz  
820e3299-bd67-4ba8-a637-32d31205e120.htseq.counts.gz  
f6a99d72-7ef2-4c9c-880c-a26bd5fef9c7.htseq.counts.gz  
d1be9c82-7450-4f59-b20b-5f3032aa89a9.htseq.counts.gz  
7824eae3-957c-4515-b128-45453a11624d.htseq.counts.gz  
25f5c640-600a-4874-af11-1ff647b0b26d.htseq.counts.gz  
844bbccc-8e4e-4c0a-ad29-0aa196f14c26.htseq.counts.gz  
960fa206-af01-4f92-b066-4e899fe356fb.htseq.counts.gz  
f8fbe8b1-7831-4853-8dfd-be977f3a5da0.htseq.counts.gz  
98cf4f9b-aa89-4c14-b84b-2b8f32439ea0.htseq.counts.gz  
8223f42b-434d-4966-a123-3b8a947884bc.htseq.counts.gz  
d44d370d-d86e-4006-9530-ab3442cb2848.htseq.counts.gz  
37889f67-62a8-483b-97af-d8391806ede9.htseq.counts.gz  
34c48a6e-1714-4871-aa8f-7d39dd8fe78e.htseq.counts.gz  

## Milestone 1
I download raw data about brain cancer and handle them in Rstudio. After data processing, it could be saved as CSV file. When I load it into Vignette, it could be successful to run. In this part, I will complete section 4 and 5 in Vignette.

## Milestone 2
Using previous data, I could analyze different gene expression. In this way, I will finish Vignette's section 6.

## Deliverable
*R Markdown*

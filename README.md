# trgn510_FinalProject

## Title
**Analyzing RNA-seq of white female dead of brain cancer between Age 10-40 and Age 41-60**

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
I find the data in the HTSeq counts file format from https://portal.gdc.cancer.gov/. The website shows me 20 cases, which are about Age 10-40, and 40 cases, which are about Age 41-60, white female dead of brain cancer.
* Age 10-40 cases:  
21badc40-5fb8-496d-a3e6-4f0704500a5d.htseq.counts.gz  
2fafd7bb-e8ce-4b03-8607-cf6cb2a2119a.htseq.counts.gz  
349eaa81-0d2c-4c2b-a762-31555fd1ca50.htseq.counts.gz  
820e3299-bd67-4ba8-a637-32d31205e120.htseq.counts.gz  
7824eae3-957c-4515-b128-45453a11624d.htseq.counts.gz  
960fa206-af01-4f92-b066-4e899fe356fb.htseq.counts.gz  
98cf4f9b-aa89-4c14-b84b-2b8f32439ea0.htseq.counts.gz  
d6706bff-1f56-43a5-a180-1223034cfc09.htseq.counts.gz  
fc8d7362-7eb6-42bb-b3eb-dba3053aa381.htseq.counts.gz  
646f0e58-d861-4761-9fd5-2e48cd28753e.htseq.counts.gz  
722becbc-9e08-4d7e-8dd6-415761cd84f3.htseq.counts.gz  
522efe0e-2785-4e16-85a0-898ea586ddcd.htseq.counts.gz  
6508275a-e712-424e-bdaf-b9e1b07b0f95.htseq.counts.gz  
5a092f95-7774-41ed-b70c-58ed1daa0cf1.htseq.counts.gz  
d6478e3f-149e-4b99-82c2-182405f1040b.htseq.counts.gz  
6578ea58-0e5d-43aa-927a-7ac53e1df985.htseq.counts.gz  
900e6a24-1504-4c2d-85dd-b1c6088339b2.htseq.counts.gz  
3d3245f2-a2c9-4742-bfec-cd17f5aaca23.htseq.counts.gz  
bd118e30-6764-4adb-8a5e-0a80bd6c6d74.htseq.counts.gz  
9b09de85-1cd6-472f-bac8-de05c101f4cb.htseq.counts.gz  

* Age 41-60 cases:  
84762203-320a-4ef6-b080-4c2b04b6a619.htseq.counts.gz  
d4eed6a4-986c-409a-8f6c-1ddb00069894.htseq.counts.gz  
284d5f4a-5b44-42f7-90e6-14a5250183aa.htseq.counts.gz  
f5bb4817-1727-41f9-b7f6-3a4e1818c2df.htseq.counts.gz  
f6a99d72-7ef2-4c9c-880c-a26bd5fef9c7.htseq.counts.gz  
d1be9c82-7450-4f59-b20b-5f3032aa89a9.htseq.counts.gz  
25f5c640-600a-4874-af11-1ff647b0b26d.htseq.counts.gz  
844bbccc-8e4e-4c0a-ad29-0aa196f14c26.htseq.counts.gz  
f8fbe8b1-7831-4853-8dfd-be977f3a5da0.htseq.counts.gz  
8223f42b-434d-4966-a123-3b8a947884bc.htseq.counts.gz  
d44d370d-d86e-4006-9530-ab3442cb2848.htseq.counts.gz  
37889f67-62a8-483b-97af-d8391806ede9.htseq.counts.gz  
34c48a6e-1714-4871-aa8f-7d39dd8fe78e.htseq.counts.gz  
31944ca5-2685-4b3f-8f61-d1e41eea44f9.htseq.counts.gz  
35d0022b-f677-4340-a3db-c6558782b9d7.htseq.counts.gz  
e87cfbaa-791e-4a6b-8ec8-28df636e7cdc.htseq.counts.gz  
6a7c7af6-b3b4-44a1-93bb-79a143db53d0.htseq.counts.gz  
60fd76fd-8522-497d-b631-e550988a1064.htseq.counts.gz  
e934722f-3571-4348-a518-1ad262b86b94.htseq.counts.gz  
ceb8fbdf-dd36-4273-b17c-0ee2eca493c5.htseq.counts.gz  

## Milestone 1
I download raw data about brain cancer and handle them in Rstudio. After data processing, it could be saved as CSV file. When I load it into Vignette, it could be successful to run. In this part, I will complete section 4 and 5 in Vignette.

## Milestone 2
Using previous data, I could analyze different gene expression. In this way, I will finish Vignette's section 6.

## Deliverable
*R Markdown*

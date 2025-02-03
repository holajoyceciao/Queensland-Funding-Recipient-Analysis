# Queensland-Funding-Recipient-Analysis
An analysis focuses on the Advance Queensland funding program distribution and the alignment with program objectives.

#### Source 
- [Data](https://www.data.qld.gov.au/dataset/advance-queensland-funding-recipients)
- [Analysis - Source Code](https://github.com/holajoyceciao/Queensland-Funding-Recipient-Analysis/blob/main/Queensland_Funding_Recipient_Analysis.ipynb)

# Goal
Analysing the publicly available data on the funding distribution over time and identifying the insight which may be a good insight or a cause of concern. The following focuses are:
- The balance between South-East Queensland and the remainder of the state (regional Queensland).
- Alignment with the program objectives which may include supporting specified groups of people.

#### Business Problems
1. Unequal Funding Allocation Across Areas and Specified Groups of People
  - Does South-East Queensland and the remainder of the state (regional Queensland) influence the programs and their funding distribution?
  - Are there differences in funding allocation that disadvantage certain communities?
  - How is the program funding distributed to each community?
2. Misalignment Between Funded Projects and Community Objectives
  - Are funded projects effectively aligning with program objectives?
  - What projects do each community have and how do distributions align with the objectives?

# Highlights
- The data was initially categorized into **SEQ (South-East Queensland)** and **Non-SEQ** regions. Under these two categories, the programs were categorized into 5 communities including **Startups and Industry**, **Education and Researchers**, **Technology and Innovation**, **Female**, and **Indigenous** to gain further insight into funding distribution and their objectives' alignment.
- Utilized [Advance Queensland Program and Grants](https://advance.qld.gov.au/) and Google Search to gain more knowledge of programs and their main community.

# Overview
The funding distribution between the SEQ and Non-SEQ regions is unbalanced and the funding in the female and indigenous communities is significantly less than in other communities. In addition, the female community is only located in the SEQ region. This refers to these two communities not only having fewer programs but also having unbalanced funding distribution by area. 

![image](https://github.com/user-attachments/assets/92140e6b-469a-4769-ba58-0799a3a69f4e)

#### Key Findings
1. **Unusual cases**: While preparing data, 20 NonQueensland values are in the RAP Region category which is unusual. This is because the dataset is about Queensland programs, it does not make sense if the programs' recipients were located outside of Queensland.
2. **Total Funding for each program**: The Ignite Ideas Fund program has the highest funding than other programs followed by Industry Research Fellowships and Innovation Partnerships Grants programs. 
3. **The Funding Distribution between the RAP Region**: The funding distribution is seriously unbalanced between the SEQ and the Non-SEQ regions. However, to clarify whether it is unbalanced, the population density data will be needed as a consideration.  
4. **Categorize Programs with Communities**: Programs are categorized into "Startups and Industry", "Education and Researchers", "Technology and Innovation", "Female", and "Indigenous". The last two communities are considered as specified groups of people which means Advance Queensland programs include some specific communities.
5. **The Funding Distribution Between Communities (marked with separate SEQ & Non-SEQ regions)**: The differences in funding between communities are significant, the funding of "Female", and "Indigenous" communities is extremely lower than other communities. Moreover, the majority of the funding was located in the SEQ region.  
6. **The Reasonability of Each Community's Funding Distribution**: One of the projects in the female community with the highest funding does not relate directly to the community.   

#### Recommendations
1. Build a standard to evaluate the distribution to ensure fairness and equity to solve the issue of the funding of the program being distributed unbalanced.
2. Improve the publicity of the funding distribution process to decrease the potential for bias and difference.
3. Collect more relative data such as the population density to ensure the balance of the fundings


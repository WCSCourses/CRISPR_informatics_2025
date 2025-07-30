# <img src="https://coursesandconferences.wellcomeconnectingscience.org/wp-content/themes/wcc_courses_and_conferences/dist/assets/svg/logo.svg" width="300" height="50">
# CRISPR Screening and Analysis - Genome Informatics and Computational Design and Analysis Informatics Guide 2025

### Important Notes 
- You will require **admin access** to install Docker and SnapGene Viewer. Please get this arranged **in advance through your institution or workplace IT admin**.  
- You will need adequate storage on your **computer (15 GB+)** and **Google Drive (5 GB+)**.  
- We recommend you attend this course in a location with **strong, reliable internet**, as this is a **computation-heavy, cloud-based training**.


## Software/Tools used during the course

| Prep Day              | For Day               | What Needs to Be Done                                                                                                                                                                                                                       | Notes & Course Modules                                                                                                           |
|-----------------------|-----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------|
| Sunday 27 July        | Monday 28 July        | No preparation needed                                                                                                                                                                                                                       | –                                                                                                                                |
| Monday 28 July        | Tuesday 29 July       | - Download [CRISPResso_data](https://github.com/WCSCourses/CRISPR_informatics_2025/tree/main/course_data_2025/CRISPResso_data).<br>- Install [Docker](https://www.docker.com/products/docker-desktop).                                      | **Module:** [CRISPResso_data](https://github.com/WCSCourses/CRISPR_informatics_2025/tree/main/course_data_2025/CRISPResso_data)<br>**Slides:** [Tuesday](https://github.com/WCSCourses/CRISPR_informatics_2025/tree/main/course_modules_2025/Tuesday)<br>**Setup:** Will be working on the [CRISPResso2](https://crispresso2.pinellolab.org/submission) web tool and using Docker for local analysis. Admin access required. |
| Tuesday 29 July       | Wednesday 30 July     | - Download dataset from [Figshare](https://figshare.com/ndownloader/articles/29581727/versions/1) and upload to Google Drive.<br>- Access Colab notebook: [CRISPR_BEstimate_Practical.ipynb](https://colab.research.google.com/github.com/WCSCourses/CRISPR_informatics_2025/blob/main/course_data_2025/base_editor_data/CRISPR_BEstimate_Practical.ipynb)<br><br>- Install [SnapGene Viewer](https://www.snapgene.com/snapgene-viewer)<br>- Download <br>- [Knock_in_checks](https://github.com/WCSCourses/CRISPR_informatics_2025/tree/main/course_data_2025/Knock_in_checks)<br>- [SNP_checks](https://github.com/WCSCourses/CRISPR_informatics_2025/tree/main/course_data_2025/SNP_checks)<br>- [TIDE_analysis](https://github.com/WCSCourses/CRISPR_informatics_2025/tree/main/course_data_2025/TIDE_analysis)<br>  | **Modules:**<br>- [base_editor_data](https://github.com/WCSCourses/CRISPR_informatics_2025/tree/main/course_data_2025/base_editor_data)<br>- [Knock_in_checks](https://github.com/WCSCourses/CRISPR_informatics_2025/tree/main/course_data_2025/Knock_in_checks)<br>- [SNP_checks](https://github.com/WCSCourses/CRISPR_informatics_2025/tree/main/course_data_2025/SNP_checks)<br>- [TIDE_analysis](https://github.com/WCSCourses/CRISPR_informatics_2025/tree/main/course_data_2025/TIDE_analysis)<br>**Slides:** [Wednesday](https://github.com/WCSCourses/CRISPR_informatics_2025/tree/main/course_modules_2025/Wednesday)<br>**Setup:**<br>- Base editor session requires Google account and ≥5 GB Drive storage.<br>- SnapGene session requires local install with admin access. |
| Wednesday 30 July     | Thursday 31 July      | - Access Colab notebook: [crispr_counts_analysis.ipynb](https://colab.research.google.com/github/WCSCourses/CRISPR_informatics_2025/blob/main/course_data_2025/CRISPR_Screening_data/crispr_counts_analysis.ipynb)<br>- Access Colab notebook: [supplementary_generate_crispr_counts.ipynb](https://colab.research.google.com/github/WCSCourses/CRISPR_informatics_2025/blob/main/course_data_2025/CRISPR_Screening_data/supplementary_generate_crispr_counts.ipynb) | **Module:** [CRISPR_Screening_data](https://github.com/WCSCourses/CRISPR_informatics_2025/tree/main/course_data_2025/CRISPR_Screening_data)<br>**Slides:** [Thursday](https://github.com/WCSCourses/CRISPR_informatics_2025/tree/main/course_modules_2025/Thursday)<br>**Setup:** Google account required. Data is handled in Colab; upload not required. At least 5 GB of Drive space recommended. |
| Thursday 31 July      | Friday 1 August       | No new preparation required                                                                                                                                                                                                                 | Group presentations using previously downloaded software and data.                                                              |

## Download & Installation Checklist

Below is a consolidated list of all tools and datasets you need to download or install for the course:

### Required Software & Tools
- **Docker**  
  [Download Docker Desktop](https://www.docker.com/products/docker-desktop)  
  *Used for local execution of CRISPResso2 (admin access required).*

- **SnapGene Viewer**  
  [Download SnapGene Viewer](https://www.snapgene.com/snapgene-viewer)  
  *Required to visualize `.dna` files in the TIDE dataset (admin access required).*

- **Google Account with Drive Access**  
  *Required for opening Colab notebooks and uploading data (ensure at least 5 GB of free space).*

### Required Datasets
- [CRISPResso_data (10 FASTA files)](https://github.com/WCSCourses/CRISPR_informatics_2025/tree/main/course_data_2025/CRISPResso_data)  
- [Figshare Base Editor Data](https://figshare.com/ndownloader/articles/29581727/versions/1) *(must be uploaded to Google colab)*  
- [TIDE_knock_in_checks_data](https://github.com/WCSCourses/CRISPR_informatics_2025/tree/main/course_data_2025/TIDE_knock_in_checks_data)

### Google Colab Notebooks (no download required)
- [CRISPR_BEstimate_Practical.ipynb](https://colab.research.google.com/github.com/WCSCourses/CRISPR_informatics_2025/blob/main/course_data_2025/base_editor_data/CRISPR_BEstimate_Practical.ipynb)
- [crispr_counts_analysis.ipynb](https://github.com/WCSCourses/CRISPR_informatics_2025/blob/main/course_data_2025/CRISPR_Screening_data/crispr_counts_analysis.ipynb)
- [supplementary_generate_crispr_counts.ipynb](https://github.com/WCSCourses/CRISPR_informatics_2025/blob/main/course_data_2025/CRISPR_Screening_data/supplementary_generate_crispr_counts.ipynb)

---

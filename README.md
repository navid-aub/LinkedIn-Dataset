# LinkedIn-Dataset

## Overview:

This dataset has been collected for research purposes and is intended to assist researchers in exploring LinkedIn profiles, with a particular focus on identifying fake profiles. If you decide to use this dataset for your research, please make sure to cite [our paper](https://dl.acm.org/doi/abs/10.1145/3603163.3609064). 

## Dataset Description:

This dataset comprises a total of 3600 LinkedIn profiles, categorized into three main groups:
- Legitimate LinkedIn Profiles (LLPs): 1800 profiles
- Fake LinkedIn Profiles (FLPs): 600 profiles
- ChatGPT-generated LinkedIn Profiles (CLPs): 1200 profiles
  
## Data Fields:

The dataset provides various section for each profile, all of which are accessible to any LinkedIn user before initiating a connection. The list of sections includes:
- Intro section
  - Workplace
  - Location
  - Number of Connections
  - Number of Followers
  - Status of Profile Picture
- About section
- Experiences section
- Educations section
- Licenses section
- Volunteers section
- Skills section
- Recommendations section
- Projects section
- Publications section
- Courses section
- Honors and Awards section
- Scores section
- Languages section
- Organizations section
- Interests section
- Activities section
  
In addition to the above sections, numerical columns have been added to the dataset, representing the number of components in each section (e.g. Number of Experiences).

## Labels:
- Label 0: Legitimate LinkedIn Profiles (LLPs)
- Label 1: Fake LinkedIn Profiles (FLPs)
- Label 10: ChatGPT-generated LinkedIn Profiles (CLPs) created based on legitimate profiles' statistics
- Label 11: ChatGPT-generated LinkedIn Profiles (CLPs) created based on fake profiles' statistics

## Usage Guidelines:
- ***This dataset is exclusively intended for research purposes***.
- If you utilize this dataset in your research, please ensure that you provide proper citation to [our paper](https://dl.acm.org/doi/abs/10.1145/3603163.3609064).
- Respect LinkedIn's terms of service and user privacy when using this dataset for analysis or research.

## Citation:
```
@inproceedings{ayoobi2023looming,
  title={The Looming Threat of Fake and LLM-generated LinkedIn Profiles: Challenges and Opportunities for Detection and Prevention},
  author={Ayoobi, Navid and Shahriar, Sadat and Mukherjee, Arjun},
  booktitle={Proceedings of the 34th ACM Conference on Hypertext and Social Media},
  pages={1--10},
  year={2023}
}
```
## Contact:
If you have any questions or need further assistance regarding this dataset, please feel free to contact us at nayoobi@cougarnet.uh.edu.

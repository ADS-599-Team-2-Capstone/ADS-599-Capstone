# Dataset Description
This dataset contains approximately 18K job descriptions out of which about 800 are fake. 
The data consists of both textual information and meta-information about the jobs. 

Origin: Kaggle https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction 
* File Type: CSV
* File Size: 47.7 MB
* Modeling Problem: Classification
* Missing Values: Yes
* Duplicated Values: Yes
* Unbalanced Dataset: Yes

# Feature Descriptions
* Categorical Features:
   * title: The title of the job ad entry. (text)
   * location: Geographical location of the job ad. (categorical: e.g. US, NY, New York)
   * department: Corporate department (categorical: e.g. sales).
   * salary_range: Indicative salary range (categorical: e.g. 50,000-60,000)
   * company_profile: A brief company description. (text)
   * description: The details description of the job ad. (text)
   * requirements: Enlisted requirements for the job opening. (text)
   * benefits: Enlisted offered benefits by the employer. (text)
   * employment_type: Full-type, Part-time, Contract, etc. (categorical: e.g. Full-type)
   * required_experience: Executive, Entry level, Intern, etc. (categorical: e.g. Executive)
   * required_education: Doctorate, Master’s Degree, Bachelor, etc. (categorical: e.g. Bachelor)
   * industry: Automotive, IT, Health care, Real estate, etc. (categorical: e.g. Automotive)
   * function: Consulting, Engineering, Research, Sales etc. (categorical: e.g. Engineering)
* Numerical Features:
   * job_id: Unique Job ID (numeric)
   * telecommuting: True for telecommuting positions. (Binary: 1="True",0="False")
   * has_company_logo: True if company logo is present. (Binary: 1="True",0="False")
   * has_questions: True if screening questions are present. (Binary: 1="True",0="False")
* Target Feature:
   * fraudulent: Target - Classification attribute. Is the job posting fraudulent? (Binary: 1="True",0="False")

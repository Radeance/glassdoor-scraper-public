
#  Glassdoor Scraper

[Try it out now for free on Apify!](https://apify.com/radeance/glassdoor-jobs-scraper)

## ⌲ Job & Company Data Scraper

![Glassdoor Job Search Plattform](https://i.imgur.com/5VzbtTB.png)

### What does Glassdoor Scraper do?

Our premium Glassdoor Jobs Scraper enables you to extract millions of job offerings and company data from [Glassdoor](https://www.glassdoor.com), one of the largest job and career plattforms worldwide. This robust tool enables you to extract valuable information at scale, perfect for your data projects, business reports, and developing new applications. The Glassdoor Scraper allows you to scrape:

 - All job listings including key details: job id, posted date, title, category, job type, experience, description, location, salary range, and skills.
- Detailed company profiles including: company ID, name, headquarters, year founded, size, industry, sector, overall rating, CEO rating, employee reviews, and revenue.

| Try our other scrapers ► | [Wellfound Premium Job Scraper](https://apify.com/radeance/wellfound-job-listings-scraper) | [Similarweb Scraper](https://apify.com/radeance/similarweb-scraper)| [Tesco UK Scraper](https://apify.com/radeance/tesco-scraper)
|----------------------------|-----------------------------|-----------------------------|-----------------------------|


### How you could use this job and company data
- **Job Market Analysis**: Efficiently scrape and analyze large volumes of job postings to understand market trends, popular job categories, and in-demand skills.
- **Salary Benchmarking**: Extract and compare salary ranges across different job positions and locations to determine competitive compensation packages.
- **Company Insights**: Gather detailed company information, including ratings, CEO ratings, employee recommendations, and benefits, to evaluate potential employers.
- **Recruitment Optimization**: Identify and track job postings to optimize recruitment strategies and improve the visibility of job listings.
- **Skills Demand Analysis**: Collect and analyze the required skills for various job positions to understand current and emerging skill demands in the job market.
- **Job Description Parsing**: Extract comprehensive job details such as job ID, title, category, job type, experience, and detailed descriptions to automate job posting analysis.
- **Location-Based Job Search**: Monitor job availability and salary information by location to assist job seekers in finding opportunities in their preferred regions.
- **Employer Branding**: Analyze company ratings and reviews to help employers understand their brand perception and improve their workplace culture.
- **Application Tracking**: Track the status of job listings, including whether they are expired, sponsored, or have easy apply options, to streamline job application processes.
- **Promotion and Benefits Analysis**: Examine the benefits and promotional opportunities offered by different companies to attract and retain talent.

These use cases demonstrate the versatility and value of the scraper in providing detailed job market insights, optimizing recruitment efforts, and enhancing employer branding strategies.

### How easy it is to get started
**1.** Create an Apify Account & get your **3 day free trial**

**2.** Go to the **Inputs Tab** on this Scraper

**3.** Enter **Job Search / Listings** or **Job Page URLs** from [Glassdoor](https://www.glassdoor.com)

**4.** Press **Start**

**5.** Get your **results in seconds**!


### Input ⬇

If you are using this actor on the Apify platform, the UI Input interface is fairly self-explanatory. You can find detailed documentation on the scraper page on Apify.



### Output ⬆


#### Detailed Output Fields
- **Job Details:**
  - **Job ID:** Unique identifier for the job.
  - **Posted Date:** The date and time when the job was posted.
  - **Days Ago:** Number of days since the job was posted.
  - **Title:** Title of the job position.
  - **Category:** Job category or field.
  - **Job Type:** Type of employment (e.g., Full-time, Part-time).
  - **Education Level:** Required education level for the job.
  - **Experience:** Required years of experience for the job.
  - **Short Description:** Brief summary of the job.
  - **Description:** Detailed description of the job responsibilities and requirements.

- **Company Details:**
  - **Company ID:** Unique identifier for the company.
  - **Company Name:** Name of the company.
  - **Company Rating:** Overall rating of the company.
  - **Location:** Location of the job.
  - **State:** State where the job is located.
  - **Country:** Country where the job is located.
  - **Latitude:** Latitude coordinate of the job location.
  - **Longitude:** Longitude coordinate of the job location.

- **Salary Information:**
  - **Salary Range:** Salary range offered for the job.
  - **Salary Min:** Minimum salary offered.
  - **Salary Avg:** Average salary offered.
  - **Salary Max:** Maximum salary offered.
  - **Currency:** Currency in which the salary is listed.
  - **Salary Period:** Salary period (e.g., Annual).
  - **Salary Source:** Source of the salary information.

- **Skills and Keywords:**
  - **Skills:** List of skills required for the job.
  - **Keywords:** Relevant keywords associated with the job.

- **Job Attributes:**
  - **Organic:** Indicates if the job is an organic listing.
  - **Sponsored Job:** Indicates if the job is a sponsored listing.
  - **Sponsored Company:** Indicates if the company is a sponsored employer.
  - **Easy Apply:** Indicates if the job has an easy apply option.
  - **Expired:** Indicates if the job listing has expired.
  - **Job URL:** Direct link to the job listing.

- **Company Information:**
  - **Company ID:** Unique identifier for the company.
  - **Name:** Name of the company.
  - **Headquarters:** Headquarters location of the company.
  - **Year Founded:** Year the company was founded.
  - **Size:** Size of the company.
  - **Stage:** Development stage of the company.
  - **Industry:** Industry in which the company operates.
  - **Sector:** Sector of the company.
  - **Overall Rating:** Overall rating of the company.
  - **CEO Rating:** Rating of the company's CEO.
  - **CEO Ratings Count:** Number of ratings for the company's CEO.
  - **Recommend to Friend:** Percentage of employees who would recommend the company to a friend.
  - **Compensation and Benefits Rating:** Rating of the company's compensation and benefits.
  - **Culture and Values Rating:** Rating of the company's culture and values.
  - **Career Opportunities Rating:** Rating of the company's career opportunities.
  - **Senior Management Rating:** Rating of the company's senior management.
  - **Work Life Balance Rating:** Rating of the company's work-life balance.
  - **Logo URL:** Direct link to the company's logo image.
  - **URL:** Direct link to the company's website.
  - **Benefits:** Information about the company's benefits.
  - **Revenue:** Company's revenue.
  - **Company Logo:** Direct link to the company's logo image.


#### Data Sample

**Full JSON Data Sample**
```json
{
  "job_id": 1009320992555,
  "posted_date": "2024-06-13 19:39:02.188643",
  "days_ago": 3,
  "title": "Medical Analytics Data Engineer",
  "category": "Data Engineer",
  "job_type": "Full-time",
  "education_level": null,
  "experience": "1 years",
  "description": "ROLE SUMMARY Develop data infrastructure for data scientists and ensure appropriate and efficient development of care gap and HCP prioritization models ROLE RESPONSIBILITIES Develop and maintain data infrastructure Design, develop, optimize, and maintain data architecture and pipelines (e.g., feeding medical data sources into data lake for ongoing projects) Partner with product manager and data lead to develop technical architectures for analytical models Identify data inputs needed to conduct analytics (e.g., claims data for unmet need analysis) Gather, prepares, and maintains datasets required to perform analytics Oversee data systems holding in close collaboration with data mgmt. lead and ensure accurate collection, storage, and processing of data within team Enhance data infrastructure for greater scalability and optimize data delivery (e.g., automating manual processes to retrieve medical data) Support analytics development Solve complex data problems to deliver insights that helps the team produce the required analytics Create data products for analytics and data scientist team members to improve their productivity and facilitate team collaboration Ensure adherence to data practices and standards Advise, consult, mentor and coach other data and analytic colleagues on data standards and practices Foster a culture of sharing, re-use, design for scale stability, and operational efficiency of data and analytical solutions Lead the evaluation, implementation and deployment of emerging tools and analytic data engineering process in order to improve team productivity BASIC QUALIFICATIONS Candidate demonstrates a breadth of diverse leadership experiences and capabilities including: the ability to influence and collaborate with peers, develop and coach others, oversee and guide the work of other colleagues to achieve meaningful outcomes and create business impact. Degree in Computer Sciences, Statistics, Clinical Informatics or similar Relevant certification &/or work experience in data engineering Experience (7+ years) in data engineering, notably in the healthcare sector Demonstrated effectiveness working in cross-functional business environment. Proven influencing skills Strong interpersonal skills to quickly build rapport and credibility with Pfizer leaders and key external stakeholders. Ability to partner cross culturally/regionally. Effective English verbal and written communication with flexibility to be clear, consistent, compliant, and appropriate for a variety of settings including scientific/technical, promotional, patient/consumer, regulatory, and media. In depth understanding of the business of pharmaceutical medicine including clinical trial design, GCP and data interpretation, drug development, regulatory and promotional rules/guidance, legal and compliance, issue management and business development opportunity evaluations. Infrastructure as code, data warehousing, Apache Airflow, Kafka or similar streaming data engineering tools. Databricks, DSS Data Science Studio (Dataiku) experience Understanding of taxonomy structures and hierarchy Plan and implement methods including Tag Management Solutions like Tealium iQ(primarily), GTM, Adobe Launch, Dynamic Tag Manager, Ensighten Understand and use multitude of tag managers and writing JavaScript code Marketing Performance analysis i.e. data aggregation (leveraging marketing & click-stream API’s, data cleaning & transformation) Understanding of digital analytics specially Clickstream Data, Adobe and/or Google Analytics, Drupal platforms Knowledge on Adobe Analytics, Google Analytics, /Omniture SiteCatalyst, Matomo/Piwik Tag Managers – Tealium IQ, Adobe Launch/DTM, Google Tag Manager, Piwik Pro, Signal/Bright Tag. tags and tag debugging tools like Charles Proxy Programming Languages - JavaScript, jQuery 1+ years in a client facing role for solutioning and / or evangelizing technology approaches. Markup Languages - HTML, CS Preferred Qualifications: Optimization Platform – Adobe Target, Google Optimize, Optimizely Experienced building web apps and interactive visualizations that focus on data explanation and exploration. You have experience with front-end JavaScript and Node.js. You have experience working with visualization libraries, plus a component framework like React or Vue. Experience with Data Studio and Adobe Report Builder Technical: Anticipates Customer and Market Needs – Knows the industry; knowledgeable in current and possible future trends, knows the competition; is aware of how strategies and tactics work in the marketplace. Is dedicated to meeting the expectations and requirements of internal and external customer's; always focused on patient safety first, establishes and maintains effective relationships with customers and gains their trust and respect. Acts Decisively – Makes timely and effective decisions by applying business and financial acumen. Acts with urgency and removes barriers that hinder productivity. Can be counted on to exceed goals successfully; is very bottom-line oriented; steadfastly pushes self and others for results. Builds Change-Agile Organizations – Develops teams that are facile at initiating and responding to change. Aligns teams and processes to support sustainable change. Designs and leads teams that are flexible and adaptive. Strategic and Innovating Thinking – Demonstrates insightful thinking by developing creative approaches to business models and strategies and creates an environment to encourage others to do the same. Grows Leaders – Actively coaches and develops talent. Builds leadership bench strength for Pfizer. Provides opportunities and experiences to develop skills, competencies, and business knowledge. Is a role model of Pfizer’s values and behaviors. NON-STANDARD WORK SCHEDULE, TRAVEL OR ENVIRONMENT REQUIREMENTS Travel as required, up to 40% of role Other Job Details: Additional Location Information: New York, NY; Collegeville, PA; Cambridge, MA; Groton, CT; Bothell, WA, Lake Forest, IL; La Jolla, CA; Boulder, CO; US - remote; Montreal, Canada Eligible for Relocation Package: No #LI-PFE Last Date to Apply: June 19, 2024 The annual base salary for this position ranges from $117,300.00 to $195,500.00. In addition, this position is eligible for participation in Pfizer’s Global Performance Plan with a bonus target of 17.5% of the base salary and eligibility to participate in our share based long term incentive program. We offer comprehensive and generous benefits and programs to help our colleagues lead healthy lives and to support each of life’s moments. Benefits offered include a 401(k) plan with Pfizer Matching Contributions and an additional Pfizer Retirement Savings Contribution, paid vacation, holiday and personal days, paid caregiver/parental and medical leave, and health benefits to include medical, prescription drug, dental and vision coverage. Learn more at Pfizer Candidate Site – U.S. Benefits | (uscandidates.mypfizerbenefits.com). Pfizer compensation structures and benefit packages are aligned based on the location of hire. The United States salary range provided does not apply to Tampa, FL or any location outside of the United States. Relocation assistance may be available based on business needs and/or eligibility. Sunshine Act Pfizer reports payments and other transfers of value to health care providers as required by federal and state transparency laws and implementing regulations. These laws and regulations require Pfizer to provide government agencies with information such as a health care provider’s name, address and the type of payments or other value received, generally for public disclosure. Subject to further legal review and statutory or regulatory clarification, which Pfizer intends to pursue, reimbursement of recruiting expenses for licensed physicians may constitute a reportable transfer of value under the federal transparency law commonly known as the Sunshine Act. Therefore, if you are a licensed physician who incurs recruiting expenses as a result of interviewing with Pfizer that we pay or reimburse, your name, address and the amount of payments made currently will be reported to the government. If you have questions regarding this matter, please do not hesitate to contact your Talent Acquisition representative. EEO & Employment Eligibility Pfizer is committed to equal opportunity in the terms and conditions of employment for all employees and job applicants without regard to race, color, religion, sex, sexual orientation, age, gender identity or gender expression, national origin, disability or veteran status. Pfizer also complies with all applicable national, state and local laws governing nondiscrimination in employment as well as work authorization and employment eligibility verification requirements of the Immigration and Nationality Act and IRCA. Pfizer is an E-Verify employer. This position requires permanent work authorization in the United States. Marketing and Market Research #LI-PFE",
  "company_id": 525,
  "company_name": "Pfizer",
  "company_rating": 3.9,
  "location": "New York, NY",
  "state": "New York State",
  "country": "United States",
  "latitude": 40.71417,
  "longitude": -74.00639,
  "salary_range": "117300.0 - 195500.0",
  "salary_min": 117300.0,
  "salary_avg": 156400.0,
  "salary_max": 195500.0,
  "currency": "USD",
  "salary_period": "ANNUAL",
  "salary_source": "EMPLOYER_PROVIDED",
  "skills": [
    "Drupal",
    "Node.js",
    "React",
    "Google Tag Manager",
    "Omniture",
    "English",
    "Google Cloud Platform",
    "Taxonomy",
    "JavaScript",
    "Clinical trials",
    "APIs",
    "Apache",
    "Kafka",
    "Data science",
    "Google Analytics",
    "Financial acumen",
    "Communication skills",
    "Adobe Analytics",
    "jQuery",
    "HTML5",
    "Adobe Target",
    "Analytics",
    "Performance marketing"
  ],
  "keywords": null,
  "organic": true,
  "sponsored_job": false,
  "sponsored_company": true,
  "easy_apply": false,
  "expired": false,
  "job_url": "https://www.glassdoor.com/job-listing/medical-analytics-data-engineer-pfizer-JV_IC1132348_KO0,31_KE32,38.htm?jl=1009320992555",
  "company": {
    "id": 525,
    "name": "Pfizer Inc.",
    "headquarters": "New York, NY",
    "year_founded": 1849,
    "size": "Unknown",
    "stage": "UNKNOWN",
    "industry": "Biotech & Pharmaceuticals",
    "sector": "Pharmaceutical & Biotechnology",
    "overall_rating": 3.9,
    "ceo_rating": 0.57,
    "ceo_ratings_count": 2322,
    "recommend_to_friend": 0.72,
    "compensation_and_benefits_rating": 3.9,
    "culture_and_values_rating": 3.7,
    "career_opportunities_rating": 3.6,
    "senior_management_rating": 3.3,
    "work_life_balance_rating": 3.7,
    "logo_url": "https://media.glassdoor.com/sql/525/pfizer-squareLogo-1611768873226.png",
    "url": "https://www.pfizer.com",
    "revenue": "$10+ billion (USD)"
  },
  "company_logo": "https://media.glassdoor.com/sql/525/pfizer-squareLogo-1611768873226.png"
}
```

## Feedback and Support 💬

**Your satisfaction** is **important** to us! Therefore we are constantly striving to enhance the performance of our Actors.

If you have any technical feedback or encounter any bugs with the Glassdoor Scraper, please create an issue [here](https://github.com/radeance/glassdoor-scraper-public/issues).

You can also contact us directly for custom integrations or project use cases at business@radeance.com

Thank you and happy scraping!

<br>

[Try it out now for free on Apify!](https://apify.com/radeance/glassdoor-jobs-scraper)
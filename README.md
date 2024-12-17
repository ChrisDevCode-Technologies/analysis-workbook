# Data

This workbook generates realistic data for people, but making it "dummy" so as to not work with real people data.

## People Data

For people data, these are the fields to be generated:

- Youth ID (Abbreviations of first and last name, current year(year of data input) and random 4 alphanumerics: CA-2024-S89C)
- date_added
- date_updated

### PII


- first name
- middle name
- last name
- year of birth
- month of birth (not required)
- day of birth (not required)
- gender (male, female, not specified)
- is person with disability (boolean: true/false)
- disability details (select type of disability)
- marital status (Single, Married, Divorced, Widowed)
- identification document (passport, national id, military id)
- identification document number
- primary language (choose from list of languages)
- secondary language (choose from list of languages)
- religion (choose from a list of religions)


### Contact Information

- phone number (starting with country codec e.g Kenya - +254)
- email address (not required)
- preferred socila media
- modes of communication

### Address

- county
- sub county (based on county selected)
- ward (based on ward selected)
- street (not required)


### Employment/Occupation Information

- Employment Status (Options: Employed, Self-Employed, Unemployed, Student, Retired)
- Occupation (Free text or dropdown for common occupations)
- Industry/Field of Work
- Employer Name (If employed)
- Work Address (Optional)
- Monthly Income Bracket (Ranges, e.g., <$100, $100-$500, etc.)
- Years of Experience in Current Field

### Education Information

- Highest Education Level (Options: None, Primary, Secondary, Diploma, Bachelor's, Master's, PhD, Other)
- Skills/Certifications


### Household Information

- Household Size
- Number of Dependents
- Is Head of Household (Boolean: True/False)
- Housing Status (Options: Owned, Rented, Mortgaged, Other)
- Housing Type (Options: Apartment, Detached House, Semi-Detached, Other)
- Access to Utilities (Boolean: True/False for Electricity, Water, Internet, etc.)


### Health Information

- Health Insurance Provider (Optional)
- Health Conditions (Optional, free text for chronic or other conditions)
- Allergies (Optional)
- Blood Group (Optional)


### Demographic Information

- Income Bracket (Ranges, e.g., <$100, $100-$500, etc.)
- Ownership of Assets (Boolean: True/False for House, Car, Livestock, Land, etc.)
- Access to Technology (Boolean: True/False for Smartphone, Computer, Internet)


### Miscellaneous

- Emergency Contact Name
- Emergency Contact Relationship
- Emergency Contact Phone Number
- Membership in Groups (E.g., Community Groups, Religious Organizations)
- Volunteer/Community Work Participation (Boolean: True/False)
- Voting Status (Boolean: Registered/Not Registered)
- Preferred Mode of Engagement (E.g., Online, Physical Meetings)

## Company Data


### Basic Information

- Company Name
- Trade Name/DBA (Doing Business As) (If different from the official name)
- Registration Number (Business or Tax ID)
- Year of Establishment
- Industry/Field (Dropdown or free text, e.g., Agriculture, Technology, Healthcare)
- Company Size (Options: 1-10 employees, 11-50, 51-200, 201-500, 500+)
- Public/Private/NGO (Type of Organization)

### Contact Information

- Headquarters Address
    - Country
    - Sub County
    - Ward
    - Postal Address
    - Latitude (Optional, for mapping)
    - Longitude (Optional, for mapping)
- Branch Locations (Optional, list format or nested structure for multiple branches)
    - Branch Name
    - Sub County
    - Ward
    - Postal Address
    - Latitude (Optional, for mapping)
    - Longitude (Optional, for mapping)

- Phone Number (Include country code)
- Alternate Phone Number
- Email Address
- Website URL
- Social Media Handles (Optional, for platforms like LinkedIn, Twitter, Facebook)

### Business Activities

- Primary Line of Business (E.g., Manufacturing, Retail, Software Development)
- Secondary Activities (If applicable)
- Products/Services Offered (List or free text)
- Target Market (E.g., Local, Regional, Global)
- Key Clients or Partners (Optional, list format)
- Operating Hours (Optional, include time zones)

### Employment Information

- Number of Employees
- Employee Demographics (Optional: Gender ratio, Age groups, Diversity metrics)
- Recruitment Policy (E.g., Remote, On-site, Hybrid)
- Skills/Qualifications Typically Required
- Training/Development Opportunities Offered
- Employee Benefits (E.g., Health Insurance, Paid Leave, Pension)

### Legal and Financial Information

- Business Registration Date
- Tax Identification Number (TIN)
- License Number (If applicable)
- Annual Revenue Bracket (Optional: <$1M, $1M-$10M, etc.)
- Funding Sources (E.g., Self-Funded, Investors, Grants)

### Miscellaneous

- Company Mission/Vision Statement
- Corporate Social Responsibility (CSR) Initiatives (Optional)
- Awards/Certifications (Optional)
- Compliance with Labor Laws (Boolean: Yes/No, with details if No)
- Preferred Communication Channel (E.g., Email, Phone, Meetings)


## Activities by Employers/Companies

### Activity Details

- Company Name(Linked with generated data for companies)
- Activity Name (E.g., "Environmental Cleanup Drive", "Hackathon 2024")
- Activity Type (Options: Social Responsibility, Networking, Recruitment, Product Launch, Community Outreach, Employee Engagement, etc.)
- Description (Free text)
- Target Audience (E.g., Employees, Public, Partners, Students)
- Start Date
- End Date
- Location (Include virtual option if applicable)
- Number of Participants Expected
- Key Partners/Sponsors (Optional)
- Activity Goals/Outcomes
- RSVP'd - (from generated people data - link with Youth ID)
- Attended people: from RSVP'd list - (from generated people data - link with Youth ID)

### Logistics

- Is Recurring? (Boolean: Yes/No)
- Frequency of Recurrence (Options: Daily, Weekly, Monthly, Annually, Ad Hoc)
- Budget (Optional)
- Resources Needed/Provided (E.g., Training materials, equipment)

### Impact Measurement
- Success Metrics (E.g., Number of participants, Engagement levels)
- Feedback Mechanism (Optional: Survey, Feedback Form, etc.)


## Trainings Offered by Employers/Companies

### Training Details

- Training Name (E.g., "Leadership Development Program", "Python for Data Science")
- Training Type (Options: Technical Skills, Soft Skills, Leadership, Compliance, Onboarding, etc.)
- Description (Free text)
- Target Audience (E.g., New Hires, Mid-Level Managers, Public)
- Prerequisites (Optional)
- Duration (E.g., 3 hours, 2 days, 1 month)
- Mode of Delivery (Options: Online, In-Person, Hybrid)
- Trainer Name/Organization
- Training Materials Provided (Boolean: Yes/No, with details)

### Schedule and Location

- Training Start Date
- Training End Date
- Location (Include virtual link if applicable)
- Training Time Zone (For virtual or cross-region trainings)

### Outcomes
- Certification Provided? (Boolean: Yes/No)
- Skills Gained
- Assessment/Evaluation Method (Optional)

## Jobs by Employers/Companies

### Job Details

- Job Title
- Job ID (Unique identifier)
- Job Type (Options: Full-Time, Part-Time, Internship, Contract, Freelance)
- Department/Team (E.g., Engineering, Marketing, HR)
- Job Level (Options: Entry-Level, Mid-Level, Senior-Level, C-Suite, Internship)
- Job Description (Free text)
- Key Responsibilities (List format)
- Required Skills and Qualifications
- Preferred Skills and Qualifications (Optional)

### Location and Timing

- Job Location (Include city, state, and remote options)
- Remote/Hybrid Options (Boolean: Yes/No)
- Work Hours (E.g., 9:00 AM - 5:00 PM, Flexible)

### Compensation and Benefits

- Salary/Pay Range (Optional or mandatory based on company policy)
- Other Benefits (E.g., Health Insurance, Bonuses, Retirement Plans)
- Travel Requirements (Boolean: Yes/No, with details if Yes)

### Application Process

- Application Start Date
- Application End Date
- How to Apply (E.g., Upload resume, Fill form, Email application)
- Contact Person for Job
- Interview Rounds (Optional: e.g., Screening, Technical, HR)
- Expected Start Date

## Metrics and Reporting for Jobs, Activities, and Trainings

- Number of Applications/Participants
- Feedback Collected (Boolean: Yes/No)
- Post-Event/Job Impact Assessment (Optional)
- Retention Rate (For Hired Roles)
- Training Completion Rate
- Activity/Training Effectiveness Score (Optional)
---

> ## Challenge Advisor: Update & Finalize Your Project Overview
>
> > 💡 **These grey text instructions are just for you, the team's Challenge Advisor; please delete them once you have completed the steps below.**
>
> We've pre-populated this Challenge Project Overview page — which is what will be shared with your Break Through Tech student team in August — using the details from your submission form. You should have received an email inviting you to join this repo as a Collaborator, enabling you to add files and make edits.
> 
> In order for your project to be finalized and assigned to a team, please:
> 1. **Review all sections below** and update or expand any content as needed, making sure to address the SME Feedback in the section immediately below. Look for square brackets to find the places below that require additional inputs from you (e.g., "About [Company / Org Name]").
> 2. **Add your dataset** to the [data folder](data) in this repo.
> 3. **Close the Issue assigned to you in this repo** to let us know that you have made your edits and the overview page is ready for final review. You can do this by going to the _Issues_ tab in the top left section of the menu above, add a comment that says "CA review complete", and click the button to Close the Issue. 
>
> If you're unfamiliar with how to edit a page like this in GitHub, check out [this tutorial](https://ubc-lib-geo.github.io/gis-workshop-waml-template/content/handson/edit-readme.html) for a quick overview (start with step 2 and only edit this page), and [this guide](https://ubc-lib-geo.github.io/gis-workshop-waml-template/content/markdown.html) on how to use Markdown to compose text.
>
>
> ❌ Remember that this is a public repo. Do NOT include: Proprietary data, PII, API keys, credentials, or anything confidential.

---

## 📋 BTT Internal Evaluation Notes

| Check | Status | Notes |
|-------|--------|-------|
| Python Compatibility | 🟢 | The project utilizes a Python-centric tech stack, including scikit-learn for machine learning and Google Colab for execution, which aligns well with academic needs. |
| Data Readiness | 🟡 | The dataset is publicly available but requires some cleaning and preprocessing. Students may spend considerable time preparing the data, impacting the overall project timeline. |
| Resource Check | 🟢 | No specialized hardware requirements; the project can be executed using Google Colab's free tier, which is readily accessible to students. |

**Student Fit Score:** 7/10  
**Technical Depth Score:** 8/10  
**Overall Recommendation:** REVISE

**Advisor Feedback Draft:**
This project addresses relevant and timely industry challenges. However, consider providing additional resources on uplift modeling and interpretation techniques to ensure students can navigate the complexities effectively. Moreover, streamline the data-cleaning process to minimize hurdles in the project's initial phases. Encourage students to focus on the implications of their findings for privacy measures, enhancing the educational value.

---

# Incrementality Modeling for Privacy-Conscious Retail Media and Data Cleaning

**Company / Org:** Other  
**Challenge Advisor:** Annamalai Annamalai, annamalai1.a@gmail.com  
**Program:** Break Through Tech AI Studio - Fall 2026

---

## 🏢 About Other

Other is focused on privacy-conscious digital advertising solutions, helping retail media practitioners utilize data responsibly while respecting consumer privacy.

---

## 🎯 The Challenge

### Project Summary
In this project, you will use anonymized treatment and control digital advertising experiment data, along with supervised classification and uplift modeling techniques, to build and evaluate an educational prototype that ranks audience records by estimated incremental visit response after ad exposure. This will help retail media and advertising practitioners explore more trustworthy, privacy-conscious measurement methods that focus on causal lift rather than correlation. The project reflects a common measurement challenge in retail media and data clean room environments: estimating whether advertising exposure drove incremental outcomes without relying on raw, identifiable customer data.

### Success Criteria
Delivering a reproducible end-to-end Python workflow that demonstrates whether the model can rank audiences by incremental visit response better than random targeting. Primary metrics include uplift by audience decile, cumulative uplift curve, incremental visits captured, and runtime/memory performance in a free-tier notebook.

### Project Milestones

Use these milestones to guide your work. Your team will create a **GitHub Projects board** to track tasks within each milestone.

| Month      | Milestone                  | Key Activities                                           |
|------------|----------------------------|---------------------------------------------------------|
| **September** | Data Understanding       | Explore dataset, handle missing values, document findings |
| **October**   | Model Development        | Train baseline model, experiment with approaches, iterate |
| **November**  | Evaluation & Presentation | Finalize model, prepare presentation, document results   |

> **Note for the team:** Please create a GitHub Projects board in this repository to break these milestones into weekly tasks. Go to the **Projects** tab → **New project** → Choose **Board** → Add columns for each month.

---

## 📊 Dataset

**Name and Source:** Criteo dataset (criteo-uplift)  
**Format:** CSV/TSV  
**Size:** under 1gb  
**Location:** [Link to dataset or instructions for accessing it]

### Key Details
- Publicly available Criteo dataset (criteo-uplift) containing numerical/quantitative and categorical data in CSV/TSV format. Documentation is available but it requires some cleaning/preprocessing.
- Data requires cleaning and preprocessing.
- [Link to data dictionary or documentation, if available]

---

## 🛠️ Suggested Approach

**ML Problem Type:** Uplift Modeling

**Recommended Libraries:**
- Python
- scikit-learn
- Google Colab
- Causal inference / uplift modeling / heterogeneous treatment effect estimation

**Evaluation Metrics:**
- Uplift by audience decile
- Cumulative uplift curve
- Incremental visits captured
- Runtime/memory performance

---

## 📚 Resources to Get Started

The following resources will help your team understand the problem space and potential technical approaches for this project:

**Background Reading:**
- [Link to an article or blog post about uplift modeling]
- [Link to an industry report or case study related to retail media]

**Technical Tutorials:**
- [Link to a tutorial on uplift modeling techniques]
- [Link to documentation for scikit-learn]

**Code Examples:**
- [Link to a relevant GitHub repo with uplift modeling examples]
- [Link to a sample implementation of a classification model]

**Other:**
- [Link to papers or additional resources related to data cleanliness and privacy in advertising]

*Feel free to explore beyond these, and share anything interesting you find with me!*

---

## 🤝 How We'll Work Together

**Check-ins:** During our biweekly 60-min AI Studio Lab Section meeting block (2nd and 4th week of every month)  
**Communication:** Slack (Break Through Tech workspace)  
**Response time:** Within 48 hours on weekdays  

**Recommended Tools:**
- **Coding:** Google Colab
- **Collaboration:** GitHub, Notion
- **Virtual Meetings:** Zoom, Google Meet

---

## 🚀 Getting Started

1. **Review this overview document** and note any questions for our first meeting
2. **Begin reviewing the dataset** using the link above
3. **Read the GitHub Projects documentation** [here](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects)

I'm excited to work with you!

---

## ❓ Questions?

Please bring any questions to our first meeting during the week of August 24th (Break Through Tech's Bridge to Studio - Session B).

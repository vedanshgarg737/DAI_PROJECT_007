# Team 007: An Analysis of India's Civilian and Military Honours: Trends, Geography, and Demographics

## 1. The Main Hypothesis/Question

This project examines how the Indian state has recognised service and sacrifice since independence, using records of civilian honours (Bharat Ratna and the Padma awards) and gallantry awards (Ashoka Chakra and Param Vir Chakra). We ask three questions. First, how has the demographic makeup of civilian awardees changed over time, and do particular groups dominate particular fields such as Arts or Public Affairs? Second, how do the demographics of gallantry awardees compare with those of civilian awardees? Third, has the mix of civilian award categories shifted across decades, for example towards grassroots social work and away from traditional fields such as civil service and literature?

We hypothesise that civilian awards cluster strongly within a few demographic groups and regions in the early decades and diversify gradually as the nomination and tracking of grassroots work improved. For military honours, we expect spikes in award counts around known conflicts (1965, 1971, Kargil) and a much higher share of posthumous awards for wartime gallantry than for peacetime operations. Comparing the two spheres should show how recognition maps onto the socio-political timeline of the country.

Our approach is descriptive and exploratory. We will clean and standardise the three datasets, harmonise state names and award categories, and derive variables such as decade, state of origin, gender and posthumous status wherever the data allow. We will then use time-series plots, grouped bar charts and choropleth maps to compare distributions across decades, domains and states. Where the data support it, we will test whether observed differences, such as the posthumous share in wartime versus peacetime, are larger than chance would produce. We expect missing fields in older records and inconsistent spellings of names and states, and we will restrict the analysis to attributes that are actually recorded in the data.

### 1.1 Source Papers, Blogs, Podcasts

- [Padma Awards 1954–2021](https://www.kaggle.com/code/mohandeep20/padma-awards-1954-2021/input?select=padmaawards.csv) (Kaggle notebook)
- [Ashoka Chakra: Indian Gallantry Awards](https://www.kaggle.com/code/mpwolke/ashokachakra-indian-gallantry-awards/notebook) (Kaggle notebook)
- [Gallantry Awards portal](https://www.gallantryawards.gov.in/), Government of India

### 1.2 Programming Languages or Tools/Software Intended

- **Data cleaning and exploration:** Python (Pandas, NumPy) in Jupyter Notebooks.
- **Visualisation:** Matplotlib and Seaborn for exploratory analysis and plots.
- **Version control and collaboration:** Git and GitHub.

### 1.3 Datasets

| File | Contents |
| --- | --- |
| `nationalawards.xls` | Civilian awards, including Bharat Ratna and the Padma awards. |
| `ashokachakra.xls` | Recipients of the Ashoka Chakra, India's highest peacetime gallantry award. |
| `param_vir_chakra_recipients.csv` | Recipients of the Param Vir Chakra, India's highest wartime gallantry award. |

Dataset spreadsheet: [Google Sheets](https://docs.google.com/spreadsheets/d/1gQLGac7pDK6iEWy3bS8SCupirn4jv8mCdcFrBGwfOgQ/edit?usp=sharing).

### 1.4 Links to LLMs Used

- Gemini (brainstorming and outline generation): [chat link]([https://gemini.google.com/app/4b79a99777ec2335](https://share.gemini.google/wDSPNs8JMhfm))
- Claude (LaTeX formatting): [chat link]([https://claude.ai/chat/27a579e4-47c7-40c3-8e0e-89dcdc41236b](https://claude.ai/share/5dfc40cd-7429-4f5a-b609-8dd7ba3c48e5))

## 2. Logistics

### 2.1 Updated Spreadsheet

Link to the updated logistics spreadsheet: [Google Sheets](https://docs.google.com/spreadsheets/d/1nl8ZXkT0riqtaikWkRYjA4ZqpnblbEIMVS0L9JiT9Bc/edit?usp=sharing). We added rows for our chosen datasets, the GitHub repository link, and the primary tool stack.

### 2.2 Proposed Breakup of Work and Working Plan

| Member | Roll no. | Responsibility |
| --- | --- | --- |
| Vedansh Garg | 25B0950 | Cleaning and standardisation of `nationalawards.xls`, including missing data and state-name formatting. |
| Akshita Jain | 25B0999 | Cleaning of the military datasets and exploratory analysis of historical timelines. |
| Maulik | 25B1002 | Geographical mapping and visualisation (choropleth maps, area charts). |
| Arush Anand | 25B1012 | Compilation of the report, repository management, and the presentation video script. |

We will sync code asynchronously through GitHub. We have scheduled bi-weekly meetups on weekends and will use the Dept. Library (CC503) for co-working sessions.

## 3. Specific Help Needed from the Teaching Team

None at this stage.


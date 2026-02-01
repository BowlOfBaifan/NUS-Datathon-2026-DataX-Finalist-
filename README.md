# NUS Datathon 2026 Submission

This repository contains the code and resources for our submission for the NUS Datathon 2026.

## Project Structure

Please ensure you maintain the following folder structure for the code to run correctly, as `SUBMISSION.ipynb` relies on relative paths to access the dataset.

```text
.
├── SUBMISSION.ipynb                                      # Main analysis notebook
├── requirements.txt                                      # Python dependencies
├── sds_datathon_gradsingapore.xlsx                       # Dataset file
└── gemini_prompt_rewrite_insight_pack_user_friendly.md   # Insight pack/Documentation
```

## Setup and Installation

### 1. Prerequisites

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab

### 2. Environment Setup

It is recommended to use a virtual environment to manage dependencies.

**Windows:**

```bash
python -m venv .venv
.venv\Scripts\activate
```

**macOS/Linux:**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install Dependencies

Install the required packages using `requirements.txt`:

```bash
pip install -r requirements.txt
```

## Usage

1. Activate your virtual environment (if used).
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open `SUBMISSION.ipynb` and run the cells.

## Key Insights 

### How the Notebook Produces Results for Requirements 1–4

When the Jupyter notebook is executed end-to-end, it performs the full analysis pipeline and prints the final results directly in the notebook output sequentially from Requirements 1-4.

## Key Results & Insights (Requirements 1–4)

### Requirement 1: Survey Structure & Redundancy

* Several survey questions exhibit high semantic overlap, indicating redundancy.
* Questions naturally cluster into clear thematic groups (demographics, perception, motivation, learning).
* Consolidation and reordering can improve survey clarity and respondent experience.

### Requirement 2: Partial Response Behaviour

* Overall completion among eligible respondents is high (~86%).
* Most drop-off occurs early in the survey, particularly at the demographics stage.
* Mobile users and late-day respondents are more likely to partially complete.
* Early-question simplification and mobile optimisation are key improvements.

## Requirement 3: Respondent Segmentation

- Respondents segment cleanly by awareness and attractiveness levels, aligning with recruitment funnel stages.
- Segments enable targeted communication strategies.

### Requirement 4: Employer Attractiveness Drivers

- Employer attractiveness is moderately positive (≈6.3 / 10).
- Key motivation drivers centre on meaningful work impac
- The strongest information gaps relate to career development and growth opportunities.
- Motivation and learning needs are broadly consistent across demographics.
- However, ratings differ by group, with Business & Economics and local AU respondents rating higher, and Year 3 students rating lower.

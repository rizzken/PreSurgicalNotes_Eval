# PreVisitPatientSummary-Eval

Quality evaluation of patient demographic summarization before primary care visit

## Project Overview

This project evaluates the quality of synthetic patient demographic data and tests the ability of generative AI models to create concise, structured summaries for physicians before a first-time patient visit.

**Goal**  
- Identify data quality issues in demographic records (missing values, invalid dates, duplicates, inconsistencies)  
- Assess how well open-source LLMs summarize key patient information for quick physician review  
- Highlight common failures: omissions, hallucinations, formatting issues, bias in presentation

The project is motivated by a real-world need in primary care: doctors need fast, accurate overviews of a new patient’s basic profile before the consultation begins.

## Skills & Tools Demonstrated

- Manual & exploratory testing  
- Data quality validation (missing values, duplicates, range/date checks, consistency)  
- Python + pandas for data analysis  
- Hugging Face Transformers (summarization models)  
- Text generation evaluation (ROUGE, manual coverage & hallucination checks)  
- GitHub + Google Colab for development & version control

## Phase 1: Data Quality Assessment

Tested on synthetic patient records.

**Key Findings** (to be updated with real results):
- Dataset size: X rows, Y columns
- Missing values: highest in [column names]
- Invalid birthdates: X records (future dates or illogical)
- Duplicate patient IDs: X cases
- Gender inconsistencies: multiple spellings detected
- Unrealistic income/expenses: negative or zero values

**Conclusion**: Even synthetic demographic data requires thorough validation before feeding into AI summarization pipelines.

## Next Steps (Planned)

- Generate structured patient summaries using open-source LLMs  
- Evaluate summaries for coverage of key fields: age, gender, marital status, location, income, insurance  
- Test for hallucinations, omissions, and formatting consistency  
- Compare zero-shot vs prompted summarization

## How to Run

1. Open notebooks in Google Colab  
2. Load data from the `data/` folder  
3. Run cells sequentially

## Author

Katerina  Kasparova
QA Engineer transitioning to AI/ML QA  
[LinkedIn] (linkedin.com/in/katerina-kasparova)

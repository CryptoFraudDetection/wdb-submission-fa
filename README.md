# WDB Submission
Mini-Challenge by Florian Baumgartner & Aaron Brülisauer

## Report
The report can be found in the file `report.pdf`.

## Code
The code can be found in the folder `main`. The folder `main` is a submodule that points to the correct commit on our challenge repository. You might need to run `git submodule update --init --recursive` to get the code.

## How to use this Repository
1. Clone the repository.
2. Run `git submodule update --init --recursive` to get the code.
3. Navigate to the `main` folder and read its README file for further instructions on how to use the code.

## Relevant Files
- `README.md`       This file.
- `report.pdf`      Report of our submission.
- `.gitignore`      Gitignore file.
- `main/`           Submodule pointing to the correct commit on our challenge repository.
- `main/README.md`  Challenge Repository Readme with instructions on how to use the code.
- `main/pyproject.toml`  Challenge Repository pyproject file with dependencies (instead of `requirements.txt`).
- `main/Makefile`   Challenge Repository Makefile with commands to install the package.
- `main/.gitignore` Challenge Repository Gitignore file.
- `main/.env-template`       Challenge Repository environment template file (copy to `.env` and fill in the values).
- `main/tests/`      Challenge Repository tests folder.
- `main/tests/test_scraper_reddit.py` Test for the Reddit Scraper.
- `main/tests/test_sentiment.py`      Test for the Sentiment Analysis.
- `main/notebooks/`  Challenge Repository notebooks folder.
- `main/notebooks/90-wdb-scrape-reddit.qmd` Notebook for scraping Reddit.
- `main/src/CryptoFraudDetection/scraper/reddit.py` Reddit Scraper.
- `main/src/CryptoFraudDetection/utils/sentiment.py` Sentiment Analysis.
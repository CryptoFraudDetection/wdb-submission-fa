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

## Branching Strategy
Features were developed in feature branches on the challenge repository. The feature branches were reviewed by a second person, optionally improved and finally merged into the `main` branch. The `main` branch was then used as a submodule in this repository.

## Issue Tracking
We used the issue tracker on the challenge repository to keep track of tasks and bugs. The issues were assigned to one or multiple team members. The [Taskboard](https://github.com/orgs/CryptoFraudDetection/projects/1) shows the overview of the project sprints. Discussions where documented in the [Discussions](https://github.com/orgs/CryptoFraudDetection/discussions) section of the challenge organization.

## Logging
Logging was implemented and can be enabled to a specific verbosity level. See also: `main/src/CryptoFraudDetection/utils/logger.py` which was used to log messages in the code.

# Historical Cricket Performance Data Cleaning 

## Overview
This project focuses on the end-to-end Data Cleaning and Transformation of a historical cricket dataset scraped from ESPN Cricinfo, featuring the highest career batting averages in the sport's history. Raw sports data is notoriously messy—often containing embedded symbols, composite strings (e.g., "1994-2006"), and mixed data types—which prevents accurate statistical modeling. This repository demonstrates a robust Python pipeline designed to resolve these complexities and prepare the data for high-level performance benchmarking.

By leveraging Pandas, the project transforms a raw "object-heavy" dataset into a refined numerical format. The workflow emphasizes the "Data Janitor" phase of analytics: handling special characters, engineering new temporal features, and ensuring data integrity across multiple decades of athletic records.

Table: [ESPN cricinfo's Highest Career Batting Averages](https://www.espncricinfo.com/records/highest-career-batting-average-282910)

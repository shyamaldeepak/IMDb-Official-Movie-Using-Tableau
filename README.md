# IMDb-Official-Movie-Using-Tableau

# IMDb Official Movie Analysis Using Tableau

This repository contains a Tableau-based Business Intelligence project that analyzes IMDb movie data to understand rating trends and audience popularity across genres and release years.

## Project Overview

The goal of this project is to explore:

- How IMDb average ratings vary by movie genre
- How audience engagement (number of votes) changes across genres
- How ratings and popularity evolve over release years
- Which genres receive stronger audience attention

## Repository Structure

- **IMDb_Movies_Team_Hunter X Hunter.twbx**  
  Tableau Packaged Workbook containing:
  - Tableau workbook definition (`.twb`)
  - Embedded data source (`imdb_movies_final.xlsx`)

- **Business_Intelligence_Team_Hunter X Hunter.docx**  
  Project report/documentation with theme and data dictionary.

- **LICENSE**  
  Project license information.

## Dataset

Source: [IMDb Datasets](https://datasets.imdbws.com)

Key fields used in analysis:

- `tconst` — Unique movie identifier
- `Movie_Title` — Movie name
- `Release_Year` — Year of release
- `Genre` — Movie genre
- `Average_Rating` — IMDb user rating
- `Number_of_Votes` — Total user votes

## Tableau Workbook Details

The workbook contains **9 worksheets** (`Chart1` to `Chart9`) built to analyze ratings, vote distribution, and genre/year patterns.

### Calculated Fields

- **Vote share %**  
  `SUM([Number_of_Votes]) / TOTAL(SUM([Number_of_Votes]))`

- **% of Total Votes**  
  `[Number_of_Votes] / { FIXED : SUM([Number_of_Votes]) }`

## Technologies Used

- **Tableau** (Workbook format version 18.1)
- **Microsoft Excel** (embedded data source in `.twbx`)

## How to Use

1. Open `IMDb_Movies_Team_Hunter X Hunter.twbx` in Tableau Desktop.
2. Navigate through worksheets (`Chart1` to `Chart9`).
3. Interact with filters/fields to explore trends by genre and year.

## Team

Hunter X Hunter

- Shyamal Deepak VEMPADAPU
- Sarvan CHATTU
- Venkatesh LANKALAPALLI
- Trinath GURRAPUSALA
- Suraj Reddy JAGIRAPU

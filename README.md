# Global Fast Food Brands Dataset Extractor

A simple Python project that collects Wikipedia text for famous food brands and saves each brand as a separate text file.

This repository is suitable for:
- NLP lab assignments
- Text preprocessing practice
- Building small brand-related corpora
- Sharing on GitHub and Kaggle

## Project Summary

Topic: Global Fast Food Brands  
Target output: 15 text files (one per brand)

The script uses the Wikipedia API to fetch page content and stores it in a local folder.

## Default Brand List (15)

1. McDonald's
2. KFC
3. Burger King
4. Subway (restaurant)
5. Pizza Hut
6. Domino's Pizza
7. Starbucks
8. Dunkin'
9. Taco Bell
10. Wendy's
11. Popeyes
12. Chipotle Mexican Grill
13. Papa John's
14. Little Caesars
15. Tim Hortons

## Project Structure

- Famous_Food_Brands_Extractor.py
- TOPIC_DESCRIPTION.txt
- famous_food_brands_data/
  - Generated .txt files for each brand

## Requirements

- Python 3.8+
- wikipedia-api package

Install dependency:

    pip install wikipedia-api

## How To Run

From the project folder:

    python Famous_Food_Brands_Extractor.py

You will see 2 options:

- Option 1: Extract the default 15 brands
- Option 2: Search and save a custom topic interactively

## Output

All extracted files are saved in:

- famous_food_brands_data/

Each file contains full Wikipedia page text for one brand.

## Kaggle Upload Notes

If you upload this project as a Kaggle Dataset or Notebook resource:

- Include this README.md and all extracted text files in famous_food_brands_data/
- If internet is disabled in a Kaggle Notebook, extraction from Wikipedia will not run live
- In that case, use already generated text files for analysis

Suggested Kaggle dataset title:

- Global Fast Food Brands Wikipedia Text Dataset

Suggested Kaggle dataset subtitle:

- 15 brand text files extracted from Wikipedia for NLP tasks

## GitHub Upload Notes

Recommended repository name:

- global-fast-food-brands-extractor

Recommended tags/topics:

- nlp
- wikipedia
- text-mining
- dataset
- python
- food-brands

## License and Source

Wikipedia content is community-created and available under Creative Commons licensing terms.
Please review Wikipedia licensing and attribution requirements before redistribution.

## Author

Muhammad Jawad

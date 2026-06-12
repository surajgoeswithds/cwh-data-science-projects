# CWH Data Science Projects

Python data wrangling projects from the CodeWithHarry Data Science course.

## Project 1 - Coders of Delhi
Data cleaning pipeline built in pure Python:
- Input: data2.json
- Output: cleaned_data.json
- Remove users with blank names
- Remove duplicate friends
- Remove inactive users
- Remove duplicate pages

---

### People You May Know
Friend recommendation algorithm built in pure Python:
- Input: massive_data.json (separate dataset from the cleaning project)
- Built a lookup dictionary mapping each user to their friend set
- Implemented friend-of-friend traversal logic
- Filtered out the user themselves and existing direct friends
- Counted mutual friend connections to rank suggestions
- Sorted suggestions by mutual friend count (highest first)

---


### Pages You Might Like
Page recommendation algorithm built in pure Python:
- Input: massive_data2.json
- Built a lookup dictionary mapping each user to their liked pages
- Found shared interests between target user and every other user
- Filtered out users with zero shared interests (relevance check)
- Suggested pages liked by similar users that target user doesn't already follow
- Weighted suggestions by degree of shared interest
- Sorted suggestions by relevance score (highest first)

---


## Project 2 - Coders of Bangalore
Instagram profile data parsing and analysis built in pure Python:
- Code: parsing_data.ipynb
- Input: initialdata.txt
- Built parse_chunk() to convert raw text profiles into structured dictionaries
- Handled variable-length bio fields using list slicing and string joining
- Built convert_followers() to handle K-suffix notation and comma-separated numbers
- Found profile with maximum posts
- Found profile with maximum followers


---


## Tech Stack
- Python
- JSON


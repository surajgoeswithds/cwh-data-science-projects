# CWH Data Science Projects

Python data wrangling projects from the CodeWithHarry Data Science course.

## Project 1 - Coders of Delhi
Data cleaning pipeline built in pure Python:
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

## Tech Stack
- Python
- JSON


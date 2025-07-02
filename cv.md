# Alina M
#### DEVELOPER

### DETAILS
* email: email@gmail.com
* github: https://github.com/crlinm
* telegram: t.me/telegram
* phone: +7 700 000 0000

### PROFILE
Python developer and data analyst with experience in developing APIs and web applications using Python, PostgreSQL, Bash, Docker, and FastAPI, as well as building analytical systems and reports with SQL (CTE, window functions, query optimization). Familiar with Linux (Ubuntu) and version control systems (Git/GitLab) and experienced with project management tools (Jira, Trello). Proficient in using Python libraries for data analysis and visualization. Skilled in Google Analytics for tracking metrics and analyzing user behavior.

Eager to learn new technologies and methodologies in development and data analytics and to apply them in practice.

### WORK EXPERIENCE
+ Ecommerce: analyst (Python, SQL, Linux, Docker, GA, YM)

### SKILLS
+ Python, Flask, Sanic, FastApi, Django
+ SQL (PostgreSQL, MySQL)
+ Linux, Docker, Bash
+ Base algorithms
+ Git, Github, GitLab, GitHub Actions

### CODE EXAMPLES
Leetcode Solution

[3. Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/)

```
class Solution:
    def lengthOfLongestSubstring(self, s: str) -> int:
        mem, left, res = set(), 0, 0

        for right, symbol in enumerate(s):
            while symbol in mem:
                mem.remove(s[left])
                left += 1
            mem.add(symbol)

            res = max(res, right - left + 1)
        return res
```

### COURSES
+ Stepik: Python, Docker, Statistics
+ Napoleon IT School: Junior Backend Dev.Python, Project & Product Management Course
+ Redrover: QA Automation Testing (Python)
+ The Rolling Scopes School: JS/FE Pre-School 2024Q2 (Javascript)

### EDUCATION
+ SUSU, specialist

### LANGUAGES
+ English - Intermediate (B1)
+ Russian - Native
+ French - Beginner (A1)

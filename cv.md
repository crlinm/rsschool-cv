# Alina M
#### JUNIOR DEVELOPER

### DETAILS
* email: email@gmail.com
* github: https://github.com/crlinm
* telegram: t.me/telegram
* phone: 8 700 000 0000

### PROFILE
I'm interested in ...

### WORK EXPERIENCE
+ Ecommerce: analyst (Python, SQL, Linux, Docker, GA, YM)

### SKILLS
+ Python, base Flask, Sanic, FastApi, Django
+ SQL (PostgreSQL, MySQL)
+ Linux, Docker, Bash
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

### EDUCATION
+ SUSU, specialist

### LANGUAGES
+ English - Intermediate (B1)
+ Russian - Native
+ French - Beginner (A1)



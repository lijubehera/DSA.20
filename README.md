#Day20 of My LeetCode Journey – Problem 387: First Unique Character in a String
This one was all about character frequency and smart indexing.

📘 Problem Summary:
🧾 Given a string s, find the first non-repeating character and return its index.
 If none exist, return -1.

💡 My Approach:
Used a dictionary to store character frequencies. Then, looped through the string again to find the first character with frequency 1.

🧪 Example:
Input: "leetcode"
 Output: 0 (→ 'l' is the first non-repeating character)
Input: "loveleetcode"
 Output: 2 (→ 'v' is the first unique one)

🧠 What I Learned:
Use dictionaries to count frequencies efficiently
Lookups in dictionaries are fast and great for string-related problems
Always check edge cases like: "", "aabb", or long strings
Another small win on this learning path 🚀
 On to the next problem tomorrow!

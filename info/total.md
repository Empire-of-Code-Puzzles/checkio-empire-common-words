For communication in in combat we often use false commands to distract the enemy.
Our troops need to have an algorithm to determine which are the real commands which should be followed.
For this they have been given the secret method to tell the real from the fake.

You are given two string with words separated by commas.
Try to find what is common between these strings. The words are not repeated in the same string.

Your function should find all of the words that appear in both strings.
The result must be represented as a string of words separated by commas in **alphabetical order**.

**Input:** Two arguments as strings. 

**Output:** The common words as a string.

**Example:**

```python
common_words("hello,world", "hello,earth") == "hello"
common_words("one,two,three", "four,five,six") == ""
common_words("one,two,three", "four,five,one,two,six,three") == "one,three,two"
```
**How it is used:**

This mission simply teaches you how to work with strings and sets, knowledge which can be useful in linguistical analysis.

**Precondition:**

Each string contains no more than 10 words.
All words separated by commas.
All words consist of lowercase latin letters.


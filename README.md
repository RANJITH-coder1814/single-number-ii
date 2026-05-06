🚀 Single Number II
📌 Problem

Given an integer array nums where every element appears three times except for one, which appears exactly once, return that single element.

🔒 Constraints:

Must run in O(n) time
Must use O(1) extra space

🧠 Approach

We use a bit manipulation trick with two variables:

ones → tracks numbers appearing once
twos → tracks numbers appearing twice

🔑 Logic:
First occurrence → stored in ones
Second occurrence → moved to twos
Third occurrence → removed from both

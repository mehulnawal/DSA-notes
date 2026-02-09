# 🧠 DSA Question Notes

## 📌 Question Details
- **Question Name:** Missing Number 
- **Platform:** LeetCode
- **Link:**  https://leetcode.com/problems/missing-number/description/
- **Topic:** Array
- **Difficulty:** Easy  
- **Date Solved:**  09-02-2026

---

## 🎯 Problem Summary (In My Words)
> You are given a array, which contains distinct numbers from O to n and there is only one missing number in that range.
> We have to return that missing nunmber
---

## 🔍 Key Observations
- 
- 
- 
- 

---

## 🚫 Brute Force Approach
**Idea:** Sorting & Comparison 
**Time Complexity:** O(n log n)
**Space Complexity:** O(log n) 
**Why Not Optimal:**  Because we are using the TC of n log n 

---

## ✅ Optimized Approach - 1
**Core Idea:**  Using Maths Formula (Total - Sum = Missing Number)
**Why It Works:**  because here we are using only one loop to find total and sum , and then using the formula to find missing number
**Data Structures Used:**  

### 🪜 Step-by-Step Logic
1. Initialize total = 0, sum = 0
2. Loop from i = 0 to n - 1
   total += i;
   sum += nums[i
3. return (total + n) - sum 

---

## ⏱ Complexity Analysis
- **Time Complexity:** O(n)
- **Space Complexity:** O(1)

---

## ✅ Optimized Approach - 2
**Core Idea:**  Using Xor Method
**Why It Works:**  we can take xor all the number from o to n and also xor the values present 
**Data Structures Used:**  

### 🪜 Step-by-Step Logic
1. Initialize xor = 0
2. Loop from i = 0 to n - 1
    xor ^= i
    xor ^= nums[i]
3. After loop, do xor ^= n
4. Return xor
---

## ⏱ Complexity Analysis
- **Time Complexity:** O(n)
- **Space Complexity:** O(1)

---

## ⚠️ Mistakes I Made
- The sort function only takes SC of O(log n) in Cpp 
- Cannot think of both Optimal solution 

---

## 🧪 Edge Cases
- In Brtue force approach - we will check that the first element is 0 or not if not then we can return 0
- 
- 

---

## 🧩 Pattern Tag
`#Math` `#Array` `#SumFormula`

---

## 🔁 Revision Log

### Day 3
- Could solve without help?  
- Time Taken:  
- Confidence (1–5):  

### Day 7
-  

### Day 15
-  

### Day 30
-  

---

## 🗣 Interview Explanation (Optional)
> So we are given a array which has distinct values from 0 to n , and we have to find missing number from that range
> And we can assume that one missing number exists 

---

## 💡 Extra Notes / Follow-ups
- 
- 

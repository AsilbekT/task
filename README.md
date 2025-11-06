# Example Queries and Expected Outputs

Below are some example queries and the expected top matching documents.  
These help verify that your **Mini Vector Search Engine** is working correctly.

---

### Query 1
**Input:**
> How do we process raw data before analysis?

**Expected Output:**
```
Top 3 Similar Documents:
1. data_pipeline.txt        (similarity ≈ 0.35)
2. product_roadmap.txt      (similarity ≈ 0.25)
3. customer_support.txt     (similarity ≈ 0.18)
```
**Explanation:**  
`data_pipeline.txt` discusses ETL, cleaning, and data warehousing — perfect match.

---

### Query 2
**Input:**
> What are the company’s hiring goals?

**Expected Output:**
```
Top 3 Similar Documents:
1. hiring_plan.txt          (similarity ≈ 0.57)
2. product_roadmap.txt      (similarity ≈ 0.34)
3. marketing_strategy.txt   (similarity ≈ 0.21)
```
**Explanation:**  
`hiring_plan.txt` directly describes recruiting plans and hiring targets.

---

### Query 3
**Input:**
> How are we improving customer engagement?

**Expected Output:**
```
Top 3 Similar Documents:
1. marketing_strategy.txt   (similarity ≈ 0.47)
2. customer_support.txt     (similarity ≈ 0.46)
3. product_roadmap.txt      (similarity ≈ 0.37)
```
**Explanation:**  
Marketing focuses on awareness and campaigns; support mentions chatbots and satisfaction — both relevant to engagement.

---

### Query 4
**Input:**
> Which tools manage our data processing?

**Expected Output:**
```
Top 3 Similar Documents:
1. data_pipeline.txt        (similarity ≈ 0.56)
2. product_roadmap.txt      (similarity ≈ 0.33)
3. hiring_plan.txt          (similarity ≈ 0.22)
```
**Explanation:**  
`data_pipeline.txt` mentions Apache Airflow and AWS S3 — exactly the tools for data processing.

---

### Query 5
**Input:**
> What’s planned in the next product release?

**Expected Output:**
```
Top 3 Similar Documents:
1. product_roadmap.txt      (similarity ≈ 0.54)
2. data_pipeline.txt        (similarity ≈ 0.29)
3. marketing_strategy.txt   (similarity ≈ 0.24)
```
**Explanation:**  
`product_roadmap.txt` explicitly lists features and milestones for the next release.

# 👨‍🎓Hankuk Univeristy of Foreign Studies

## 🧑‍💻Department of Information Communications Engineering



### Graduation Thesis Topic 
### "Improving Network Intrusion Detection Speed based on Auto Encoder"

### 0. Experiment environment
****
![image](https://github.com/0su1327/Graduation_Thesis/assets/81498362/a2c15605-c99f-48a7-b42f-c3da025a57b6)


### 1. Difference from existing research
   ****
![image](https://github.com/0su1327/Graduation_Thesis/assets/81498362/47ef6a0f-9bbf-4a2a-b6b9-9c97ce8dec53)


### 2. Total flow
****
![image](https://github.com/0su1327/Graduation_Thesis/assets/81498362/190d9c20-4feb-42bd-a0cb-ba2a907220cb)


### 3. DATASET
****
   USING NSL-KDD DATASET 

   ref : <a href = https://discuss.pytorch.org/t/pre-processing-on-nsl-kdd-dataset/80995>NSL-KDD pre-processing</a>


### 4. Feature Selection Algorithm
****
   Drop- column Algorithm, Permutation Importance Algorithm 


### 5. Result of Preprocessing
****
   ![image](https://github.com/0su1327/Graduation_Thesis/assets/81498362/fd548e5e-9345-48fd-a339-610643ec54a3)


### 6. AutoEncoder Model
****
   - <bord>Stacked Autoencoder</bord>
     ![image](https://github.com/0su1327/Graduation_Thesis/assets/81498362/ae081200-4deb-4ecc-8bf0-f55c94626e1b)

****
   - Stacked Denosing Autoencoder
     ![image](https://github.com/0su1327/Graduation_Thesis/assets/81498362/0ff99527-7990-4621-a3fb-a09c09247b95)

****
   - Stacked Sparse Autoencoder
     ![image](https://github.com/0su1327/Graduation_Thesis/assets/81498362/b507bcec-e910-4d40-8fe8-26b7557b98a0)


### 7. Result
****
   <h2>All the left side of graph is result about using all feature and the right side of graph is result about using feature selection algorithm</h2>
   ****
   
  - CPU usage
    ![image](https://github.com/0su1327/Graduation_Thesis/assets/81498362/ba7973f6-81cc-449c-b778-d2e84e2f0e45)

 ****
 
 - Training Time
   ![image](https://github.com/0su1327/Graduation_Thesis/assets/81498362/bdf4bd3c-5655-4d70-9404-ec20d1942d65)

****

 - Memory usage
   ![image](https://github.com/0su1327/Graduation_Thesis/assets/81498362/0febe8cb-698c-4590-aff8-acda7552b3f3)

****

This experiences show us that decreasing overhead when we use feature selection algorithm.

And The following results show that if the overhead is reduced using the feature selection algorithm, the model's performance is not significantly harmed.

****

<h2>Confusion Matrix</h2>

- using all feature
![image](https://github.com/0su1327/Graduation_Thesis/assets/81498362/ffa147d9-3908-4dfd-97d3-b9182c92feb0)

*****
- using feature selection algorithm
![image](https://github.com/0su1327/Graduation_Thesis/assets/81498362/bffd815b-a7b8-440c-b84c-f047a6b3e76e)



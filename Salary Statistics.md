Salary Statistics:
count       612.000000
mean     158767.901961
std       40140.941353
min       82361.000000
25%      131400.000000
50%      161800.000000
75%      179100.000000
max      323640.000000


Min Salary: ₹82,361.00
Max Salary: ₹323,640.00
Mean Salary: ₹158,767.90
Median Salary: ₹161,800.00


 Created 8 features:
   1. PHD_INSTITUTION
   2. CURRENT_INSTITUTION
   3. PHD_IS_PRESTIGIOUS
   4. CURRENT_IS_PRESTIGIOUS
   5. PHD_FROM_IIT
   6. CURRENT_IS_IIT
   7. IS_INBRED
   8. PHD_INTERNATIONAL


Training set: 489 samples
✓ Test set: 123 samples

Training Models...

   Training Linear Regression...
   ✓ Train R²: 0.1855
   ✓ Test R²: -0.0621
   ✓ MAE: ₹26,450.17
   ✓ RMSE: ₹32,573.57

   Training Ridge Regression...
   ✓ Train R²: 0.1739
   ✓ Test R²: -0.0222
   ✓ MAE: ₹25,786.94
   ✓ RMSE: ₹31,955.85

   Training Random Forest...
   ✓ Train R²: 0.7081
   ✓ Test R²: 0.3138
   ✓ MAE: ₹20,419.31
   ✓ RMSE: ₹26,182.17

   Training Gradient Boosting...
   ✓ Train R²: 0.7823
   ✓ Test R²: 0.1783
   ✓ MAE: ₹19,726.14
   ✓ RMSE: ₹28,650.38



MODEL COMPARISON
======================================================================
            Model  R² (Test)  R² (Train)          MAE         RMSE
Linear Regression  -0.062086    0.185531 26450.173311 32573.567696
 Ridge Regression  -0.022185    0.173887 25786.936672 31955.848781
    Random Forest   0.313817    0.708063 20419.309651 26182.168304
Gradient Boosting   0.178345    0.782348 19726.135105 28650.379739




BEST MODEL: Random Forest
   Test R² Score: 0.3138
   Train R² Score: 0.7081
   MAE: ₹20,419.31
   RMSE: ₹26,182.17



Feature  Importance
       PHD_INSTITUTION    0.776534
   CURRENT_INSTITUTION    0.093718
     PHD_INTERNATIONAL    0.042895
CURRENT_IS_PRESTIGIOUS    0.026243
        CURRENT_IS_IIT    0.022735
    PHD_IS_PRESTIGIOUS    0.020899
          PHD_FROM_IIT    0.016977
             IS_INBRED    0.000000

Available Current Institutions:
   1. IISER KOLKATA
   2. IISER MOHALI
   3. IISER THIRUVANANTHAPURAM
   4. IIT DELHI (DMS)
   5. IIT HYDERABAD
   6. NISER


https://elyse-unintimate-sparklingly.ngrok-free.dev/
# UPI-FRAUD-DETECTION-USING-ML-IN-PYTHON

With the growing reliance on digital payment systems, especially through platforms like 
the Unified Payments Interface (UPI), ensuring transaction security has become a pressing 
concern. While UPI offers speed and convenience, it has also become a target for 
increasingly sophisticated fraudulent activities. This project aims to address this issue by 
developing a UPI fraud detection model that not only identifies irregular transaction 
behavior but also adapts to the evolving patterns of fraud. To achieve this, we propose a 
two-tiered approach: first, we use a Hidden Markov Model (HMM) to analyze the sequence 
and timing of a user’s past transactions, identifying hidden behavioral trends that may 
indicate suspicious activity. Second, we incorporate a Random Forest classifier to further 
evaluate multiple transaction features—such as amount, time, location, and device usage—
 to improve the system’s accuracy and reliability. By combining the strengths of HMM in 
behavior modeling and Random Forest in classification, our goal is to create a robust, 
intelligent fraud detection system tailored for UPI-based payment 

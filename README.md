# Relapse Risk Detection Using Wearable Physiological Signals in AUD

## Overview
In this project, I have mainly focused on detecting stress using wearable physiological signals. 
Because Stress is considered as one of the major factor for alcohol relapse, so identifying it early can help in understanding relapse risk.

## Dataset
i have used the WESAD dataset, which contains physiological data collected from wearable devices.

Signals used :
- EDA (Electrodermal Activity)
- BVP (Blood Volume Pulse)
- Temperature

Data collected from 15 participants was used for the final model.

## Methodology
The raw signals were first divided into smaller segments using a window size of 200 samples (around 50 seconds).

From each segment, simple features like mean and standard deviation were extracted.  
These features help in converting the signals into a structured format.

A Random Forest model was then used to classify the data into:
- Baseline
- Stress

## Model
Random Forest was used because it works well with structured data and can handle complex patterns.

## Results
The model achieved an accuracy of around 87% on the test data.

- Correct predictions: 97  
- Incorrect predictions: 14  

The model performed well in detecting stress cases.

## Key Findings
- Physiological signals show noticeable changes during stress  
- The model can distinguish between stress and baseline  
- Wearable data can be useful for monitoring  

## Limitations
- No direct relapse data (only stress used as indicator)  
- Limited features used  
- Some overlap between stress and baseline signals  

## Future Work
- Use more advanced features  
- Apply deep learning models  
- Use larger datasets  
- Build a real-time monitoring system  

## Conclusion
This project shows that stress detection using wearable signals is possible using machine learning, and it has potential for real-world applications.

## Author
Adarsh konderu
Adarshkonderu51@gmail.com 

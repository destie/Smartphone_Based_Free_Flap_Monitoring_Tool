# Smartphone_Based_Free_Flap_Monitoring_Tool
Code and information overview for "Free Flap" monitoring tool created using video data and machine learning. 

A "Free flap" is a medical term for a procedure that involves transporting tissue and a corresponding blood supply from one part of the body to the next. An important component of monitoring the success of a free-flap (both during the procedure and immediately after), is to ensure vascular sufficiency. This means that it's important to ensure blood flow is still occuring in the transplanted tissue.

Postoperative flap failure can lead to multiple complications including need for further salvage surgery and increased hospitilization. Early detection of vascular insufficiency is strongly correlated with a decrease in these symptoms. 

Traditional means of monitoring are invasive, expensive, and often non-continuous. The standard of care for most hospitals is often the "doppler," where an ultrasonography probe is used to identify blood flow. Creech and Miller identified criteria for monitoring systems for plastic surgery to be “Continuous, Non-Invasive, Direct, Easy to Interpret, Quantitative, and Not Expensive.” Unfortunately systems like the doppler probe do not meet this criteria and no system available on the current market provides means to meet all of these. 

Our group sought to create a non-invasive free-flap monitoring tool that involved video data, a smart phone, and machine learning. Our group collected patient data for a  series of patients of varying skin tones on the Fitzpatrick spectrum with [1] normal, [2] arterial occluded and [3] venous occluded skin video data samples, and generated a custom script in python to process and analyze the video data. Video data was converted to evaluate changes in pixels for the region of skin compared to external image, and then evaluated for patterns of change between regions of occlusion and normal blood flow. It can be inferred that a patient with vascular insufficiency would see either venous or arterial occlusion, and thus the identified pattern created an adequate model and monitoring method that could be run on a smart phone. 

Method was validated and verified using normal samples of skin with heart rate to confirm video data assessed blood flow/ pulse/ heart rate.

For further information please see:
https://meeting.aaps1921.org/abstracts/2019/25.cgi

https://journals.lww.com/prsgo/fulltext/2019/04001/abstract_qs14__novel_smartphone_based_free_flap.161.aspx

If you'd like to use this data or replicate this study, please cite:
-	Provenzano D, Chandawarker A, Caterson E. Novel Smartphone-based Free Flap Monitoring Tool Using Machine Learning. Plastic and Reconstructive Surgery – Global Open. 2019 Apr; Vol 7, Issue 42, p111-112.

Provenzano D, Chandawarker A, Caterson E. Novel Smartphone-based Free Flap Monitoring Tool Using Machine Learning. Short Oral Presentation at: The Plastic Surgery Research Council (PSRC) Annual Meeting, Presented by: Destie Provenzano. 2019 May 2 - 5; Baltimore, MD 

Chandawarker A, Provenzano D, Caterson E. Blood Perfusion Monitoring Using Machine Learning and a Phone Camera. Short Oral Presentation at: American Association of Plastic Surgeons (AAPS) Annual Meeting, Presented by: Akash Chandawarker. 2019 Apr 6 - 9; Baltimore, MD 

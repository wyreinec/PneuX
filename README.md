# PneuX
First prediction of pneumonia based on rontgen picture

Pneumonia is a disease caused by bacteria, viruses, or fungi, which makes it difficult for children to breathe because their lungs fill with pus and fluid. Various medical methods can be used to diagnose the onset of this disease, one of which is to perform a chest X-ray accompanied and analyzed visually directly by an expert in the lungs field. The number of doctors in Indonesia is very low compared to the world. The ratio of doctors in Indonesia is the second-lowest in Asia resulting in 2018. About 19,000 children/year or 71 children/hour die from pneumonia in Indonesia. Our research questions are how to enhance the effectiveness of Pneumonia identification using a Machine Learning Algorithm? How do optimize the resources needed to diagnose such disease? What are the similarities and differences between expert-based diagnosing and machine-based diagnosing methods of Pneumonia detection? The reason we make this application is to cut time to be more effective and help health workers in Indonesia. 

<h2>Backgrounder</h2>
1. <b>Machine Learning:</b> building models with TensorFlow lite, using transfer learning (inceptionV3) to predict the rontgen picture normal or pneumonia with 0.93 accuracy and 70% test is correct with data that has not been seen. 
2. <b>Android:</b> Implementing tensorFlow into android studio which will allow users to scan their X-rays. The application uses firebase's real-time database to store results and user data when logged in.
3. <b>Cloud:</b> Configuring firebase like authentication for login method, realtime database for store data user and result, deploy ML model, and app distribution for deploy app. Also configuring Google Cloud Platform like enabling API key, making roles for members, creating buckets, and creating a simple dashboard for monitoring the service's availability


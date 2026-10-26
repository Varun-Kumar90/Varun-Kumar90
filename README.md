<img src="assets/banner.svg" alt="hello, I'm Varun Kumar — AI/ML, computer vision, data science" width="100%"> <p align="center"> <a href="https://github.com/Varun-Kumar90"><b>GitHub</b></a> <sub>@Varun-Kumar90</sub> &nbsp;·&nbsp; <a href="https://www.linkedin.com/in/varun-kumara35301315"><b>LinkedIn</b></a> <sub>Varun Kumar</sub> &nbsp;·&nbsp; <a href="mailto:varun.chaudhary0025@gmail.com"><b>Gmail</b></a> <sub>varun.chaudhary0025</sub> &nbsp;·&nbsp; <a href="https://t.me/ivarunk_90"><b>Telegram</b></a> <sub>@ivarunk_90</sub> </p> <img src="assets/sec-about.svg" alt="01 / about" width="100%"> <table> <tr> <td width="210" align="center" valign="middle"> <img src="assets/avatar.png" alt="Varun" width="170"> </td> <td valign="middle"> Hi, I'm <b>Varun</b>, a Computer Science student who likes turning data into working systems. I build things around <b>machine learning</b>, <b>computer vision</b> and <b>data analytics</b>, and I learn best by shipping real projects and improving the fundamentals along the way. <br><br> <code>B.Tech CSE</code> &nbsp; <code>CGC Landran</code> &nbsp; <code>Final year</code> <br><br> <sub><b>focus</b> &nbsp;AI &amp; machine learning &nbsp;·&nbsp; <b>interests</b> &nbsp;computer vision, data science, applied AI</sub> </td> </tr> </table> <img src="assets/sec-stack.svg" alt="02 / stack" width="100%"> <img src="assets/stack.svg" alt="Tech stack" width="100%"> <img src="assets/sec-projects.svg" alt="03 / projects" width="100%">
DFU Detection & Wagner Grading

Deep Learning Computer Vision Final-year team project

A two-stage AI tool that checks a foot image for a diabetic foot ulcer and, if one is found, grades its severity on the clinical Wagner scale. Early detection matters because these ulcers are a leading cause of amputation in diabetic patients, so the goal was to make analysis faster and easier to access.

image ─▶ [ stage 1 · detect  · TensorFlow EfficientNet ] ─▶ ulcer?
                                                              │ yes
         [ stage 2 · grade   · PyTorch EfficientNet    ] ◀────┘
                     └─▶ Wagner grade 0–4 + confidence + short clinical summary
Runs as a Streamlit web app: upload an image, get the result with no ML knowledge needed
Two frameworks in one pipeline: a Keras model for detection and a timm model in PyTorch for grading
Built with OpenCV, Pillow and albumentations for image handling
Next up: Flask REST API, batch processing, cloud deployment and PDF report export

View project →

<br>
Online Retail Sales Analysis

Power BI DAX Power Query Business Intelligence

An interactive dashboard that turns raw transaction data into answers to four executive questions:

Question	Visual
How did revenue trend through 2011, and is it seasonal?	Line chart
Which countries bring in the most revenue outside the UK?	Clustered bar
Who are the top revenue-generating customers?	Column chart
Where is demand strongest for future expansion?	Map
Cleaned the data by removing returns and invalid rows (quantity or price ≤ 0)
Built a Revenue = Quantity × Unit Price measure used across the report
Ended with concrete recommendations: plan around seasonality, retain top customers, expand where demand is high

View project →

<br>
Smart Seat Belt Safety System

Arduino C++ Embedded Systems

An Arduino circuit that gives a visual (LED) and audio (buzzer) warning based on seat belt status, designed and simulated in Tinkercad, and documented as a full academic project report.

View project →

<br>

<sub><b>also built</b>  ·  <a href="https://github.com/Varun-Kumar90/Heart_Disease_predictor">Heart Disease Predictor</a> (classification models on patient health data, Jupyter)  ·  <a href="https://github.com/Varun-Kumar90/java_Consumer_Producer_Problem">Producer–Consumer in Java</a> (multithreading with <code>synchronized</code>, <code>wait()</code> and <code>notify()</code>)</sub>

<img src="assets/sec-journey.svg" alt="04 / journey" width="100%"> <img src="assets/timeline.svg" alt="Education timeline from 2021 to final year" width="100%"> <img src="assets/sec-goals.svg" alt="05 / goals" width="100%"> <table> <tr> <td valign="middle"> <b>Exploring now</b><br> Deep-learning pipelines, computer vision, data storytelling and embedded systems. <br><br> <b>Where I'm headed</b><br> Finish my final year with a portfolio of ML and CV projects that run outside a notebook, starting with taking the DFU tool from a local app to a deployed one. <br><br> <i>"Make it work, make it right, make it fast."</i> &nbsp;— Kent Beck </td> <td width="300" align="center" valign="middle"> <img src="assets/network.svg" alt="animated neural network" width="280"> </td> </tr> </table> <br> <img src="assets/footer.svg" alt="less noise. more signal." width="100%">

🧠 AWS Image Classifier — Full-Stack AI on the Cloud ☁️
New Skill Unlocked: Full-Stack AI on AWS 🚀

Built from scratch — a fully working, real-time image classification platform using React + FastAPI + AWS (S3, SageMaker, DynamoDB, SNS).
Upload an image → Get predictions → See results → Receive an email. Zero servers, 100% cloud.

🌐 Live Demo Flow

Upload an image (JPEG/PNG)
Inference via SageMaker (pretrained model)
SageMaker gives you top-3 predictions (currently raw class labels like 281, 285)
Image stored in S3
Result saved to DynamoDB
Email sent via SNS with prediction

🧩 Tech Stack

Layer	Tech Used
Frontend	React, TypeScript, Tailwind
Backend	FastAPI, Python
Cloud	AWS S3, SageMaker, SNS, DynamoDB
Dev Tools	GitHub, VS Code, Postman, Uvicorn
Features

Real-time image upload to S3 SageMaker model prediction 
Email notifications via SNS 
History tracking with DynamoDB UI feedback, loading states, and 
clean progress bar animations

##Screenshots
HomeScreen
<img width="1675" alt="1" src="https://github.com/user-attachments/assets/71fbb524-7b2b-48b9-88dc-a754d9b31868" />

Architecture 
<img width="1680" alt="2" src="https://github.com/user-attachments/assets/a2be99f7-4417-4307-979b-d00304b113b5" />

Image 
<img width="1680" alt="3" src="https://github.com/user-attachments/assets/4d3239d0-d551-46df-8989-6f4f337b6f6a" />

predictions
<img width="1680" alt="4" src="https://github.com/user-attachments/assets/96c2641e-9d74-4548-98db-5a2bc93bf082" />

✉️ Sample Email Notification
![IMG_B785CC642085-1](https://github.com/user-attachments/assets/914f0810-d9df-4359-8ac2-f4ef88a66b82)

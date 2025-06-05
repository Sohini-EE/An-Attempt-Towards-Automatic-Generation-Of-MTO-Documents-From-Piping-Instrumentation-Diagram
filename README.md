## Project Title: An Attempt Towards Automatic Generation Of MTO Documents From Piping And Instrumentation Diagram

### Project Description:
Piping and Instrumentation Diagrams (P&IDs) are diagrams visualizing engineering projects and their components.
P&IDs can be used to create Material-Take-Off documents (MTOs), which record the components of the P&IDs. 
Automating this process is an important concern in the process plant industry because presently MTO document creation from the image of a P&ID document is done manually. 
This project focuses on text detection, recognition and symbol detection from a P&ID document image.
OpenCV and Easy-OCR were used to detect and extract textual information from the diagrams.
Additionally, YOLOv11-L, a state-of-the-art object detection model, was employed for automatic identification of any one of the twelve standard symbols appearing in an input 
P&ID document image.
The work demonstrates the potential of combining OCR and symbol detection for industrial automation tasks. 
This effort serves as a foundational step toward generating a comprehensive MTO document. 
The extracted text and symbol data can help identify components like valves, pipelines, and instruments.
Automation of this process is not intended to replace engineers. 
Instead, the purpose of the model is to assist them and save time for them so they can focus on other more challenging tasks. 

### Results:

The Result for Symbol Detection has been determined based on :- 
• The number of symbols of each class present in an image 
• Accurate symbol identification (with confidence score above a particular 
threshold) 
• Number of symbols of each class detected by the model. 
• Percentage of symbols identified, of a definite class.

Result of Text Recognition & Extraction consists of – 
i) Annotated Image Output: The processed image retains its original resolution and includes clearly marked 
bounding boxes around each detected text region. Each bounding box is labeled 
with a unique identifier corresponding to the recognized text. Detected 
horizontal texts are shown in green rectangular box and vertical texts shown 
in red rectangular box.The output image is made available for download. 
ii) CSV Output:  A CSV file is generated containing the detected text data. It is made 
available for download. Each row in the CSV file includes:- The unique label identifier named as Serial No , The corresponding recognized text named as Text.
To enhance the usability and visualization of the text recognition results, a web based Text Annotation Viewer was developed using Streamlit. 

### Dataset Link : https://www.kaggle.com/datasets/hristohristov21/pid-symbols

### Contributors :
This project was developed by the following team members-

-Sohini Das (Githib: [@Sohini-EE] (https://github.com/Sohini-EE))

-Anubhav Bakshi

-Saptarsi Roy

-Riwk Mandal

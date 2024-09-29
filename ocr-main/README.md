IITR_OCR: A Web-Based OCR Application for Hindi and English Text Extraction
IITR_OCR is a comprehensive Streamlit-based web application designed to perform Optical Character Recognition (OCR) on uploaded images, supporting both Hindi and English text extraction. This web prototype provides a simple and intuitive interface, allowing users to upload images, extract text, and perform keyword searches within the extracted content. Built using the powerful EasyOCR library, the application ensures efficient and accurate text extraction, with features that support a multilingual environment.

Key Features:
Multi-Format Image Support: Users can upload images in popular formats such as PNG, JPG, or JPEG for text extraction.
OCR for Hindi and English: The application can handle images containing both Hindi and English text, leveraging robust OCR models designed for multi-language capabilities.
Powered by EasyOCR: Utilizes EasyOCR for accurate text recognition, providing confidence scores for each detected text element.
Keyword Search: Users can input keywords to search within the extracted text, with the application highlighting the relevant sections.
Visual Annotations: The application displays the uploaded image with bounding boxes around detected text, allowing users to visually confirm the OCR output.
User-Friendly Interface: The application is built on Streamlit, offering a clean, intuitive UI for uploading images, viewing extracted text, and performing keyword searches.
Real-Time Results: After uploading the image, the extracted text and corresponding confidence scores are displayed in tabular format, offering transparency and accuracy in OCR results.
Deployed Online: The application is deployed on a public platform and accessible via a live URL, ensuring easy access for users.
Scope of the Application:
The main focus of IITR_OCR is to develop and deploy a fully functional web-based prototype that demonstrates the ability to:

Upload and process images containing both Hindi and English text using OCR.
Extract the text in a structured format (either JSON or plain text).
Implement a basic keyword search feature that allows users to search within the extracted text and highlights matching sections.
Ensure the prototype is accessible online through a live URL.
Tasks Overview:
Task 1: Setup and OCR Implementation
Environment Setup:

Set up a Python environment with the necessary dependencies, including Huggingface Transformers, PyTorch, and EasyOCR.
Install additional libraries like OpenCV, NumPy, Pandas, Pillow, and Streamlit.
Commands to install dependencies:
bash
Copy code
pip install torch transformers easyocr opencv-python-headless pillow numpy pandas streamlit
OCR Model Exploration:

Explore and choose one of the following OCR models:
ColPali implementation of Byaldi library using Huggingface Transformers' Qwen2-VL, optimized for multi-language OCR.
General OCR Theory (GOT), a 580M end-to-end model, designed for OCR 2.0 with advanced text extraction capabilities.
Implement the selected OCR model to extract text from an uploaded image containing Hindi and English.
Return the extracted text in a structured format, either in JSON or plain text.
Task 2: Web Application Development
Web Application Design:
Develop a simple yet functional web application using Streamlit.
The app will allow users to:
Upload a single image in PNG, JPG, or JPEG format.
Display the extracted text in a structured format, with confidence scores.
Search for specific keywords within the extracted text.
Highlight the matching sections of text based on keyword input.
Streamlit Features:
Image Upload: Users can upload an image directly through the interface.
Text Display: The extracted text is shown alongside its prediction confidence.
Search Functionality: A keyword search input field allows users to search within the text. The results will be highlighted dynamically on the same page.
Annotated Image: The uploaded image will be annotated with bounding boxes around the detected text for visual verification.
Task 3: Deployment
Deploying the Web Application:
Deploy the application on platforms like Streamlit Sharing, Hugging Face Spaces, or any other suitable cloud-based deployment service.
Ensure the application is publicly accessible via a live URL.
Verify that the deployment is stable, ensuring that the application handles real-time user interactions, including OCR processing and search functionalities.
Deliverables:
Code Submission:
Submit all Python scripts required for the web application, including the OCR integration and search functionality.
Ensure the
code is well-documented and follows clean coding practices, making it easy for others to understand and maintain.

README File:

Provide a clear and detailed README file that includes:
Instructions on how to set up the environment and install dependencies.
Steps to run the web application locally.
An overview of how the application works, including its key features.
Detailed deployment instructions, including how the application was deployed online and the live URL where it can be accessed.
Live Web Application:

The application should be deployed online and accessible via a public URL. This allows evaluators and users to test the OCR functionality and keyword search feature in real-time.
Extracted Text and Search Output:

Provide a sample of the extracted text from a test image containing both Hindi and English text.
The output should be available in either JSON or plain text format.
Demonstrate the keyword search functionality with examples of keyword searches, showcasing how the matching sections of text are highlighted within the results.
Evaluation Criteria:
Accuracy:

The effectiveness of the OCR model in extracting text from both Hindi and English sections of the image.
The extracted text should be accurate, and the prediction confidence scores should reflect the model's reliability.
Functionality:

The web application should handle image uploads smoothly, process the image for OCR, and display the extracted text.
The keyword search feature should function properly, highlighting the relevant parts of the extracted text.
User Interface:

The UI should be simple, intuitive, and easy to use, ensuring that users can upload images, view the extracted text, and search keywords without difficulty.
Visual annotations on the image should provide clarity on the detected text regions.
Deployment:

The application must be reliably deployed and accessible online via a public URL.
The deployment should ensure real-time functionality for OCR processing and keyword search features.
Clarity:

The documentation should be concise and clear, providing users with all necessary information to run and test the application locally or through the deployed URL.
Completeness:

All features described in the assignment scope should be implemented and demonstrated, ensuring the full functionality of OCR, keyword search, and deployment.

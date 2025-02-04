# Cheque Parser
<h3> Overview </h3>
This Cheque Parser is a project developed during a hackathon conducted by Standard Chartered Company. The goal of this project is to leverage Vision Transformer (ViT) technology to accurately and efficiently parse information from cheques.

<h3> Features </h3>


1. Information Extraction: The Cheque Parser utilizes advanced computer vision techniques powered by Vision Transformer to extract essential information from cheques, such as payer name, payer account number, amount, date, and cheque number.

2. Accuracy: The parser is designed to achieve high accuracy in recognizing and extracting information from various cheque formats and handwriting styles.


3. Speed: With optimized algorithms and leveraging the capabilities of Vision Transformer, the parsing process is swift, enabling quick processing of cheque information.


4. Data Validation: The parser includes mechanisms to validate the extracted data, ensuring accuracy and reliability.


5. Signature Verification : We also included a module solely dedicated for authenticating user signatures from the cheques.


6. User Interface: The parser includes a user-friendly interface for ease of use.


<h3> Datasets </h3>

1. Visual Transformer training: We used a Kaggle cheque dataset to train our model [Kaggle dataset](https://www.kaggle.com/datasets/medali1992/cheque-images).

2. Signature fraudulent dataset: We create our signature dataset by modifying the above mentioned kaggle dataset. 
<h3> Requirements </h3>


1. Python 3


2. TensorFlow


3. OpenCV


4. Transformers library (Hugging Face)
<h3> Usage </h3>


1. Provide the scanned image of the cheque as input to the parser.


2. Run the parser script.


3. Retrieve the parsed information from the output.

 

<h3> Acknowledgements </h3>
We thank Standard Chartered Company for organizing the hackathon that inspired this project. Additionally, we acknowledge the contributions of the open-source community and the developers of libraries and tools used in this project.

<h3> Credits </h3>
The Cheque Parser project was developed by Caffeine Overflow during the hackathon conducted by Standard Chartered Company.

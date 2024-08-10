# **GenAI-Driven Email Processing for Fashion Retail**

## **Overview**

This project demonstrates the application of Generative AI (GenAI) to automate and enhance email processing for a fashion retail business. By integrating OpenAI's GPT model with Google Sheets, the project streamlines the management of customer inquiries and order requests, improving operational efficiency and customer service responsiveness.

## **Project Structure**

- **Jupyter Notebook**: Contains the core implementation of the AI-driven email processing system. [Link to the notebook](https://colab.research.google.com/drive/1qD_ZgUHlm2xFzEeVax2_O5MRDM57LTZP?usp=sharing).
- **Google Sheets**: Serves as the data source for incoming emails and the destination for processed outputs. [Link to the Google Sheets](https://docs.google.com/spreadsheets/d/1lt6hxv96azZcIBAYkPDYmtkR4o-w1EthzFM0nN3v_B4/edit?usp=drive_link).

## **Technologies Used**

- **Python**: The primary language for developing the solution.
- **OpenAI GPT API**: Employed for natural language processing tasks, including email classification and response generation.
- **Google Sheets API**: Used for seamless data handling and updates within Google Sheets.
- **Pandas**: Utilized for data manipulation and transformation.
- **gspread**: Facilitates interaction between Python and Google Sheets.
- **Google Colab**: Cloud-based environment for executing the notebook.

## **Project Details**

### **Email Classification**

- **Objective**: Automate the categorization of emails into "product inquiry" or "order request".
- **Approach**: Leveraged OpenAI's GPT model to analyze and classify the content of incoming emails.
- **Outcome**: Categorized emails are written back to the Google Sheets, providing an organized dataset for further processing.

### **Order Request Management**

- **Objective**: Automate order processing by verifying stock levels, updating inventory, and generating customer notifications.
- **Approach**: Implemented threading to handle stock updates safely and used GPT to generate personalized order confirmations or stock shortage notifications.
- **Outcome**: Order statuses and responses are automatically recorded in Google Sheets, ensuring accurate and timely communication with customers.

### **Product Inquiry Handling**

- **Objective**: Provide quick and accurate responses to customer inquiries about products.
- **Approach**: Used natural language processing to identify the type of inquiry (e.g., stock availability, pricing) and generate a relevant response using GPT.
- **Outcome**: Customer responses are dynamically generated and stored in the Google Sheets, enhancing customer engagement and satisfaction.

## **Installation and Setup**

### **Prerequisites**

Ensure that the following tools are installed:
- Python 3.x
- pip (Python package installer)

### **Clone the Repository**

```bash
git clone https://github.com/yourusername/GenAI_Email_Processing_for_Fashion_Retail.git
cd GenAI_Email_Processing_for_Fashion_Retail


To run this project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/GenAI_Business_Problem_Assessment.git
   cd GenAI_Business_Problem_Assessment

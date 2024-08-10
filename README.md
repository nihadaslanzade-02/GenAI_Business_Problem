# **GenAI-Driven Email Processing for Fashion Retail**

## **Overview**

This project leverages Generative AI (GenAI) to automate and enhance email processing for a fashion retail business. By integrating OpenAI's GPT model with Google Sheets, the project efficiently manages customer inquiries and order requests, ensuring operational efficiency and improved customer service responsiveness.

## **Project Structure**

- **Jupyter Notebook**: Contains the core implementation of the AI-driven email processing system. [Link to the notebook](https://colab.research.google.com/drive/1qD_ZgUHlm2xFzEeVax2_O5MRDM57LTZP?usp=sharing).
- **Google Sheets**: Serves as the data source for incoming emails and the destination for processed outputs. [Link to the Google Sheets](https://docs.google.com/spreadsheets/d/1lt6hxv96azZcIBAYkPDYmtkR4o-w1EthzFM0nN3v_B4/edit?usp=drive_link).

## **Technologies Used**

- **Python**: The primary language for developing the solution.
- **OpenAI GPT API**: Employed for natural language processing tasks, including email classification and response generation.
- **Pandas**: Utilized for data manipulation and transformation.
- **Google Sheets**: Interacted with Google Sheets data via direct URL construction and processing it as CSV using Pandas.
- **Google Colab**: Cloud-based environment for executing the notebook.

## **Project Details**

### **Email Classification**

- **Objective**: Automate the categorization of emails into "product inquiry" or "order request".
- **Approach**: OpenAI's GPT model is used to analyze and classify the content of incoming emails.
- **Outcome**: The results, including the classification of each email, are stored in a CSV file.

### **Order Request Management**

- **Objective**: Automate order processing by verifying stock levels, updating inventory, and generating customer notifications.
- **Approach**: The solution iterates over each order, checks product availability, updates stock levels, and generates appropriate responses using the GPT model.
- **Outcome**: Order statuses and responses are saved in CSV files for future reference.

### **Product Inquiry Handling**

- **Objective**: Provide quick and accurate responses to customer inquiries about products.
- **Approach**: The email content is analyzed to determine the type of inquiry (e.g., stock availability, pricing), and a relevant response is generated using the GPT model.
- **Outcome**: The generated responses are saved to a new Excel file.

## **Installation and Setup**

### **Prerequisites**

Ensure that the following tools are installed:
- Python 3.x
- pip (Python package installer)

### **Clone the Repository**

```bash
git clone https://github.com/yourusername/GenAI_Email_Processing_for_Fashion_Retail.git
cd GenAI_Email_Processing_for_Fashion_Retail
```

## Usage
___-Email Classification: Automatically classify incoming emails into predefined categories and save the results as a CSV file.___
<br>
___-Order Processing: Manage orders by checking stock levels and notifying customers, with results saved in CSV files.___
<br>
___-Inquiry Response: Generate and store AI-driven responses to customer inquiries in a new Excel file.___


## Contribution
Contributions to this project are welcome. If you have any suggestions or improvements, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For further inquiries, suggestions, or collaboration opportunities, feel free to reach out via email at nihadaslanzade02@icloud.com

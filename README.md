
## ShopAssist 2.0

### Background:
In today's digital age, many prefer online shopping and interacting with online websites or mobile apps to purchase items from shops or supermarkets. Sometimes, we seek guidance or more information about products to help us filter based on our needs. In this technological landscape, we are often overwhelmed by the multitude of options and struggle to find the products that suit us best.

To address this challenge, we are developing a chatbot that will guide users in selecting the best laptop according to their individual needs and provide personalized assistance. This chatbot utilizes a large language model, GPT-4o-mini, along with rule-based functions to ensure accurate and reliable information delivery.

### Problem statements:

Create a chatbot that can analyze a dataset containing information about laptops, including product names, specifications, descriptions, and more. This chatbot should offer precise laptop recommendations based on user requirements. Make use of the newly introduced 'function calling' feature to enhance the chatbot experience, making it smoother and more efficient.

### Prerequisites
- Python 3.11
- OpenAI API Key
- create a file named OpenAI_API_Key.txt and pass your OpenAI API key inside it.
- csv data file (laptop_data.csv)

### Installation & Setup
- Clone the Repository
> git clone https://github.com/jayshah-07/shopAssit_2.git
>
> cd shopAssit_2
- Install Dependencies
> pip install -r requirements.txt
- Run the Flask Application
> python app.py
- Access the Web Interface
> Open a browser and go to http://127.0.0.1:5001/

### Technology: 
The chatbot is built using the following technologies.
> Python 3.11
>
> Flask
>
> openai 

### Improvements done:
- Improved shop assist UI to indicate processing.
- Disabled the submit button when the input is empty.
- Removed submit button with loader icon while prompts are under processing.
- Beautified submit and add button
- Handled cases of empty value of GPU, processing, budget, etc
- Implemented function calling.

### Conclusion:
Shop Assistant Chatbot effectively utilizes OpenAI’s Function Calling API, transforming the way users interact with AI-powered shopping assistants.
- Improved interaction consistency over traditional bots
- Better user experience
- Reliable and accurate recommendations 



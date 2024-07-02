
Tourism Guide Project

Welcome to the Tourism Guide Project! This guide is designed to help you explore various tourist destinations with ease and convenience, offering a range of features to enhance your travel planning experience.
One of the key features of our project is budget selectivity through database integration. You can choose your travel destinations based on your budget preferences, ensuring you find the best options within your desired price range. Our database includes various packages, allowing you to view detailed pricing for adults and children, helping you make informed decisions.
For instant assistance, our chatbot, powered by a Flask application, is at your service. The chatbox feature provides immediate help and answers to your travel-related queries, ensuring you have support whenever you need it.
To enhance your travel experience, we've integrated various APIs. The YouTube API allows you to watch travel videos directly from YouTube, giving you a visual glimpse of your destinations. Additionally, the Weather API provides real-time weather forecasts for your selected destinations, helping you plan your trips accordingly.
The Tourism Guide Project is designed to be your ultimate travel companion, making it easier for you to plan, explore, and enjoy your trips. We hope you find it helpful and enjoy using our platform as much as we enjoyed creating it for you.

Getting Started:-
Prerequisites:-
Node.js
Mongoose
Body-Parser
Express
MongoDB
Flask

Installation:-

Clone the repository:-
git clonehttps://github.com/janhavi-naik14/travel_jp.git

Navigate to the project directory:-
cd travel_jp

Install dependencies for Node.js application:-
npm install
npm i mongoose express body-parser

Start the Node.js server:-
node index.js

Navigate to the Flask application directory and open virtual environment:-
cd chatbox
python -m venv venv
venv\Scripts\activate

Install Flask dependencies:
pip install "numpy<2.0" Flask==2.1.2 torch==2.0.0 torchvision==0.15.0 nltk==3.8.1
pip install werkzeug==2.0.3

Train the chatbox:-
python
import nltk
nltk.download('punkt')
python train.py

Run the app:-
python app.py

Usage
Web Interface: Open your web browser and navigate to http://localhost:3000 to explore the tourism guide.
Chatbot: Interact with the chatbot for any travel-related queries.
Review and Contact: Use the respective sections to leave reviews or contact us.
Contributing
We welcome contributions to improve the Tourism Guide Project. Feel free to fork the repository and submit pull requests.

License
This project is licensed under the MIT License.








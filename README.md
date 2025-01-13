# Mental Health Chatbot 💬🧠

## Your Personal Mental Health Assistant 🌟  
**Mental Health Chatbot** is an AI-powered chatbot designed to provide empathetic and informed responses to user queries. Built on a Transformer model, it offers features like real-time interaction, intent recognition, and profanity filtering to ensure a positive user experience.

### Key Features:  
1. **Transformer Model Architecture**: Advanced encoder-decoder framework for natural language processing.  
2. **Profanity Filtering**: Maintains a supportive environment by filtering inappropriate language.  
3. **Intent Recognition**: Detects and processes user intent for better context understanding.  
4. **Interactive Chat**: Provides meaningful and accurate responses in real-time.  
5. **Custom Training Pipeline**: Includes preprocessing and optimization techniques for superior performance.  

### Technology Used:  
- **TensorFlow** for deep learning model implementation 🤖  
- **Pandas** for efficient dataset handling 📊  
- **Better Profanity** for filtering offensive language 🌟  
- **SubwordTextEncoder** for effective tokenization 🧩  

### How to Run:  
1. Clone the repository to your local machine:  
   ```bash
   git clone <repository_url>
   cd <repository_name>
   ```
2. Install the necessary dependencies:  
   ```bash
   pip install tensorflow pandas better_profanity
   ```
3. Download the dataset:  
   ```bash
   wget https://raw.githubusercontent.com/nbertagnolli/counsel-chat/master/data/20200325_counsel_chat.csv
   ```
4. Preprocess the dataset for training:
   - Perform text cleaning, profanity filtering, tokenization, and padding.

5. Train the model:
   ```python
   python train.py
   ```
6. Test and interact with the chatbot:
   ```python
   python chatbot.py
   ```

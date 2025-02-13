# 📚 Flash Cards  

## ✨ Description  

**Flash Cards** is a simple, interactive application designed to help with learning and reviewing words from different languages. The idea is to load a CSV file with words and their meanings, then review them efficiently using flashcards that automatically flip to show the translation or meaning of the word.  

Each time you indicate whether you know a word or not, the app organizes the words so you can focus more on the ones you still need to learn.  

## 🚀 Features  

- **Word Display:** The app displays a word in the target language, and after 3 seconds, it flips to show the meaning in your native language.  
- **Mark Known Words:** You can mark a word as "known," and it will no longer appear until you restart the review process.  
- **Continuous Review:** If you click "don’t know," the word will be shown again later to ensure you have enough time to learn it.  

## ⚙️ How It Works  

1. The app loads a CSV file containing words in a target language and their translations.  
2. For each round, it shows a word (e.g., in French), and after 3 seconds, it flips the card to reveal the translation.  
3. If you know the word, click the "Know" button to remove it from future reviews.  
4. If you don’t know the word, click the "Don’t Know" button, and it will be shown again later.  

## 🛠️ How to Use  

### 📥 Prerequisites  

- **Python 3.6+**  
- **Python Libraries:** Tkinter, Pandas  

### 📋 Steps to Run  

1. **Download the Project:**  

   Download the project to your computer.  

2. **Prepare the CSV File:**  

   Create or download a CSV file with two columns: one containing the words in the target language (e.g., French) and the other with the translation or meaning in your native language.  

   Example CSV:  
   ```  
   bonjour, hello  
   merci, thank you  
   chat, cat  
   ```  

3. **Install Dependencies:**  

   In the terminal, install the required dependencies using the following command:  

   ```bash  
   pip install pandas tk  
   ```  

4. **Run the Application:**  

   Execute the main file to start the application:  

   ```bash  
   python main.py  
   ```  

   Now you can start reviewing the words!

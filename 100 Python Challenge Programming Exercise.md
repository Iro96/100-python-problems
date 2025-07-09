# 🐍 100 Python Challenge Projects

Welcome to the **100 Python Challenge Projects**! These exercises are designed to test and improve your Python skills across a wide range of topics — from beginner to advanced. Each challenge includes a brief description, suggested libraries, and hints to help you get started.

---

## 🔰 Beginner (1–20)

### 1. **Hello World Web App**
- **Description**: A simple Flask web server that displays "Hello, World!" in the browser.
- **Libraries**: `flask`
- **Hint**: Use Flask's route decorators and `app.run()`.

### 2. **Basic Calculator**
- **Description**: Perform basic arithmetic operations from user input.
- **Libraries**: None
- **Hint**: Use `input()`, `eval()` or define functions for each operation.

### 3. **To-Do List (CLI)**
- **Description**: Command-line to-do manager with add/remove/show options.
- **Libraries**: `argparse`, `os`
- **Hint**: Store tasks in a list or text file.

### 4. **Simple Guessing Game**
- **Description**: User guesses a number between 1–100.
- **Libraries**: `random`
- **Hint**: Use a loop until guess is correct.

### 5. **Fibonacci Generator**
- **Description**: Generate a list of Fibonacci numbers.
- **Libraries**: None
- **Hint**: Use recursion or iteration.

### 6. **Palindrome Checker**
- **Description**: Check if a string is a palindrome.
- **Libraries**: None
- **Hint**: Compare string to its reverse.

### 7. **BMI Calculator**
- **Description**: Calculate BMI from weight and height.
- **Libraries**: None
- **Hint**: BMI = weight / (height^2)

### 8. **Multiplication Table Generator**
- **Description**: Generate a table for any number.
- **Libraries**: None
- **Hint**: Use a `for` loop.

### 9. **Password Generator**
- **Description**: Generate strong random passwords.
- **Libraries**: `random`, `string`
- **Hint**: Combine uppercase, lowercase, digits, and symbols.

### 10. **Countdown Timer**
- **Description**: Countdown from a set time in seconds.
- **Libraries**: `time`
- **Hint**: Use `time.sleep()` in a loop.

### 11. **Unit Converter**
- **Description**: Convert distances, weights, etc.
- **Libraries**: None
- **Hint**: Use fixed conversion rates.

### 12. **Mad Libs Generator**
- **Description**: Fill in blanks in a story with user input.
- **Libraries**: None
- **Hint**: Use string templates.

### 13. **Rock, Paper, Scissors**
- **Description**: CLI game against the computer.
- **Libraries**: `random`
- **Hint**: Use conditionals to compare choices.

### 14. **Currency Converter (Static)**
- **Description**: Convert currency using static rates.
- **Libraries**: None
- **Hint**: Hardcode some exchange rates.

### 15. **Dice Roller Simulator**
- **Description**: Simulate a dice roll.
- **Libraries**: `random`
- **Hint**: Use `randint(1, 6)`.

### 16. **Email Slicer**
- **Description**: Extract username and domain from email.
- **Libraries**: None
- **Hint**: Use string `split()` method.

### 17. **Alarm Clock**
- **Description**: Set an alarm at a specific time.
- **Libraries**: `datetime`, `time`
- **Hint**: Compare current time to alarm time.

### 18. **Number to Words**
- **Description**: Convert digits into English words.
- **Libraries**: `inflect`
- **Hint**: Use `engine.number_to_words()`.

### 19. **Login System**
- **Description**: Simple CLI login and password system.
- **Libraries**: `getpass`
- **Hint**: Use a dictionary for storing credentials.

### 20. **QR Code Generator**
- **Description**: Generate QR code from user input.
- **Libraries**: `qrcode`
- **Hint**: Save as image with `.make()` and `.save()`.

---

## 🧪 Intermediate (21–60)

### 21. **Weather App (CLI)**
- **Description**: Get live weather using an API.
- **Libraries**: `requests`
- **Hint**: Use OpenWeatherMap API.

### 22. **To-Do List (GUI)**
- **Description**: Add/remove/display tasks with a GUI.
- **Libraries**: `tkinter`
- **Hint**: Use `Listbox` and `Button`.

### 23. **Markdown to HTML Converter**
- **Description**: Convert `.md` files to `.html`.
- **Libraries**: `markdown`
- **Hint**: Read file and use `markdown.markdown()`.

### 24. **Web Scraper**
- **Description**: Scrape titles from a website.
- **Libraries**: `requests`, `BeautifulSoup`
- **Hint**: Parse HTML with `soup.find_all()`.

### 25. **Pomodoro Timer**
- **Description**: Time your focus and break sessions.
- **Libraries**: `tkinter`, `time`
- **Hint**: 25 min focus, 5 min break cycle.

### 26. **YouTube Video Downloader**
- **Description**: Download video from a URL.
- **Libraries**: `pytube`
- **Hint**: Use `YouTube.streams.first().download()`.

### 27. **File Organizer**
- **Description**: Sort files by extension into folders.
- **Libraries**: `os`, `shutil`
- **Hint**: Loop through files and move them.

### 28. **Expense Tracker**
- **Description**: Track and total daily expenses.
- **Libraries**: `csv`, `datetime`
- **Hint**: Store and read entries in CSV.

### 29. **Chatbot (Rule-Based)**
- **Description**: Respond to simple user inputs.
- **Libraries**: None
- **Hint**: Use `if-elif` conditions.

### 30. **PDF Merger**
- **Description**: Merge multiple PDFs into one.
- **Libraries**: `PyPDF2`
- **Hint**: Use `PdfMerger.append()`.

### 31. **Typing Speed Test**
- **Description**: Measure user typing speed.
- **Libraries**: `time`
- **Hint**: Compare time before and after typing.

### 32. **Image Resizer**
- **Description**: Resize images to new dimensions.
- **Libraries**: `Pillow`
- **Hint**: Use `.resize()` and `.save()`.

### 33. **Tic Tac Toe (CLI)**
- **Description**: Two-player game on the terminal.
- **Libraries**: None
- **Hint**: Use a 2D list or flat list for board.

### 34. **Random Quote Generator**
- **Description**: Fetch a random quote from an API.
- **Libraries**: `requests`
- **Hint**: Use `quotable.io` or similar API.

### 35. **Digital Clock**
- **Description**: Live digital clock with GUI.
- **Libraries**: `tkinter`, `time`
- **Hint**: Update time every second.

### 36. **Barcode Generator**
- **Description**: Create a barcode image.
- **Libraries**: `python-barcode`
- **Hint**: Use `EAN13` or similar class.

### 37. **Face Detector**
- **Description**: Detect faces in images.
- **Libraries**: `opencv-python`
- **Hint**: Use Haar Cascades.

### 38. **MP3 to WAV Converter**
- **Description**: Convert audio files from MP3 to WAV.
- **Libraries**: `pydub`
- **Hint**: Use `AudioSegment.from_mp3()`.

### 39. **GIF Creator**
- **Description**: Create GIF from images.
- **Libraries**: `Pillow`
- **Hint**: Use `.save(..., save_all=True)`.

### 40. **Flashcard CLI App**
- **Description**: Display flashcards to learn new terms.
- **Libraries**: `json`
- **Hint**: Load terms from a JSON file.

### 41. **Markdown Blog Generator**
- **Description**: Generate static blog HTML pages from markdown.
- **Libraries**: `markdown`, `jinja2`
- **Hint**: Use HTML template rendering.

### 42. **Stopwatch App**
- **Description**: A stopwatch with start/stop/reset.
- **Libraries**: `time`
- **Hint**: Track elapsed time.

### 43. **Quiz Game**
- **Description**: Load and display MCQs from file.
- **Libraries**: `json`
- **Hint**: Include score tracking.

### 44. **Desktop Notifier**
- **Description**: Show desktop popup notifications.
- **Libraries**: `plyer`
- **Hint**: Use `notification.notify()`.

### 45. **Reddit Scraper**
- **Description**: Scrape top posts from subreddit.
- **Libraries**: `praw`
- **Hint**: Authenticate with Reddit API.

### 46. **CSV to JSON Converter**
- **Description**: Convert CSV data to JSON.
- **Libraries**: `csv`, `json`
- **Hint**: Use `csv.DictReader`.

### 47. **Markdown Table Formatter**
- **Description**: Convert CSV rows to Markdown table format.
- **Libraries**: None
- **Hint**: Format strings with `|`.

### 48. **Screenshot Taker**
- **Description**: Take a full-screen capture.
- **Libraries**: `pyautogui`
- **Hint**: Use `pyautogui.screenshot()`.

### 49. **Audio Recorder**
- **Description**: Record audio from mic.
- **Libraries**: `pyaudio`
- **Hint**: Stream to WAV.

### 50. **Currency Converter (Live)**
- **Description**: Convert currency using API data.
- **Libraries**: `requests`
- **Hint**: Use exchangerate.host or similar.

### 51. **Chat Logger**
- **Description**: Save all user input into a log file.
- **Libraries**: `datetime`
- **Hint**: Append each message with timestamp to a `.txt` file.

### 52. **Instagram Hashtag Generator**
- **Description**: Generate hashtags for a given topic or keyword.
- **Libraries**: `random`, `json`
- **Hint**: Use a local file of hashtags and random sampling.

### 53. **Memory Puzzle Game**
- **Description**: Match pairs of cards by memory.
- **Libraries**: `pygame`
- **Hint**: Flip two cards, then hide if no match.

### 54. **Command Line Dictionary**
- **Description**: Define words via dictionary API.
- **Libraries**: `requests`
- **Hint**: Use `api.dictionaryapi.dev`.

### 55. **Invoice Generator**
- **Description**: Generate printable PDF invoices.
- **Libraries**: `reportlab`, `datetime`
- **Hint**: Generate PDF with tables, totals, and date.

### 56. **Calendar App**
- **Description**: Create and view calendar events.
- **Libraries**: `tkinter`, `calendar`, `datetime`
- **Hint**: Let users click dates and add tasks.

### 57. **Site Availability Checker**
- **Description**: Check if a list of websites is online.
- **Libraries**: `requests`
- **Hint**: Use `requests.get()` and check `status_code`.

### 58. **Chat Interface (GUI)**
- **Description**: Simulate chat between two users.
- **Libraries**: `tkinter`
- **Hint**: Use input boxes and chat window for display.

### 59. **Directory Tree Generator**
- **Description**: Display a folder structure like `tree` command.
- **Libraries**: `os`
- **Hint**: Use recursion with indentation.

### 60. **System Monitor**
- **Description**: Monitor CPU, RAM, and disk usage live.
- **Libraries**: `psutil`
- **Hint**: Display usage as percentages in terminal.

## 🧠 Advanced (61–100)

### 61. **Chatbot with NLP**
- **Description**: Build a smart chatbot using natural language processing.
- **Libraries**: `nltk`, `re`
- **Hint**: Tokenize and match user intents.

### 62. **Stock Market Dashboard**
- **Description**: Show live stock prices and charts.
- **Libraries**: `yfinance`, `plotly`, `dash`
- **Hint**: Use Dash callbacks for dynamic updates.

### 63. **Twitter Bot**
- **Description**: Automatically tweet from your account.
- **Libraries**: `tweepy`
- **Hint**: Authenticate via Twitter API.

### 64. **Portfolio Website (Flask)**
- **Description**: Create a personal portfolio to showcase your projects.
- **Libraries**: `flask`, `jinja2`
- **Hint**: Use templates and routes for dynamic pages.

### 65. **Face Recognition App**
- **Description**: Identify people in images using face encoding.
- **Libraries**: `face_recognition`, `opencv-python`
- **Hint**: Load known faces and compare encodings.

### 66. **Instagram Image Downloader**
- **Description**: Download photos from Instagram.
- **Libraries**: `instaloader`
- **Hint**: Login with credentials to access private posts.

### 67. **Crypto Tracker App**
- **Description**: Track live prices of cryptocurrencies.
- **Libraries**: `requests`, `matplotlib`, `tkinter`
- **Hint**: Use CoinGecko or similar API.

### 68. **FastAPI REST API**
- **Description**: Build an async REST API for a microservice.
- **Libraries**: `fastapi`, `uvicorn`, `pydantic`
- **Hint**: Use data models and decorators.

### 69. **Movie Recommendation System**
- **Description**: Suggest similar movies based on user input.
- **Libraries**: `pandas`, `scikit-learn`
- **Hint**: Use cosine similarity on TF-IDF matrix.

### 70. **Language Translator**
- **Description**: Translate text between languages.
- **Libraries**: `googletrans`, `deep_translator`
- **Hint**: Detect language and translate using API.

### 71. **News Aggregator**
- **Description**: Display latest headlines from multiple sources.
- **Libraries**: `newsapi-python`
- **Hint**: Loop through top headlines by category.

### 72. **Voice Assistant**
- **Description**: Respond to voice commands like “what’s the time?”
- **Libraries**: `speechrecognition`, `pyttsx3`
- **Hint**: Use speech-to-text and conditionals.

### 73. **Virtual Whiteboard**
- **Description**: Draw using webcam and color tracking.
- **Libraries**: `opencv-python`, `numpy`
- **Hint**: Use color masking and contour tracking.

### 74. **AI Sudoku Solver**
- **Description**: Solve any Sudoku puzzle using backtracking.
- **Libraries**: `numpy`
- **Hint**: Use recursion to fill empty cells.

### 75. **Chat Application (Socket)**
- **Description**: Build a basic LAN chat server and client.
- **Libraries**: `socket`, `threading`
- **Hint**: Use separate threads for sending/receiving.

### 76. **Resume Parser**
- **Description**: Extract info from PDF resumes.
- **Libraries**: `pdfminer.six`, `re`
- **Hint**: Parse name, email, and skills.

### 77. **AI Snake Game**
- **Description**: Snake game controlled by AI.
- **Libraries**: `pygame`, `numpy`
- **Hint**: Use a neural network or rule-based AI.

### 78. **Email Automation**
- **Description**: Automatically send bulk emails to a contact list.
- **Libraries**: `smtplib`, `email`, `csv`
- **Hint**: Use CSV for contact list and `MIMEText` for email body.

### 79. **AI Flappy Bird**
- **Description**: Create Flappy Bird and train an AI to play it.
- **Libraries**: `pygame`, `neat-python`
- **Hint**: Use NEAT algorithm to evolve the agent.

### 80. **Image Caption Generator**
- **Description**: Generate text captions for images.
- **Libraries**: `tensorflow`, `keras`, `PIL`
- **Hint**: Use CNN + LSTM-based architecture.

### 81. **Object Detection App**
- **Description**: Detect multiple objects in real-time using webcam.
- **Libraries**: `opencv-python`, `YOLO`, `cvlib`
- **Hint**: Load pre-trained object detection model.

### 82. **Handwritten Digit Recognizer**
- **Description**: Classify digits from images using a trained model.
- **Libraries**: `tensorflow`, `keras`, `sklearn`
- **Hint**: Use the MNIST dataset.

### 83. **PDF Text Extractor**
- **Description**: Extract text content from PDF documents.
- **Libraries**: `PyPDF2`, `pdfplumber`
- **Hint**: Loop through all pages and extract text.

### 84. **AI ChatGPT Clone (Local)**
- **Description**: Build a mini conversational model using transformers.
- **Libraries**: `transformers`, `torch`
- **Hint**: Use pre-trained models like `DialoGPT`.

### 85. **Blog CMS (with Flask or Django)**
- **Description**: Web-based blog manager with posts and admin panel.
- **Libraries**: `flask` or `django`, `sqlite3`
- **Hint**: Use a relational DB and login system.

### 86. **Video to GIF Converter**
- **Description**: Convert short videos into animated GIFs.
- **Libraries**: `moviepy`
- **Hint**: Use `.subclip()` and `.write_gif()`.

### 87. **Keylogger**
- **Description**: Record every keystroke typed on the keyboard.
- **Libraries**: `pynput`
- **Hint**: Log output to a file — for educational purposes only.

### 88. **OCR App**
- **Description**: Extract text from images using OCR.
- **Libraries**: `pytesseract`, `Pillow`
- **Hint**: Preprocess image before feeding to OCR engine.

### 89. **Traffic Sign Classifier**
- **Description**: Identify traffic signs from images.
- **Libraries**: `tensorflow`, `opencv`, `sklearn`
- **Hint**: Use GTSRB dataset.

### 90. **Virtual Mouse (with Hand Gestures)**
- **Description**: Control your mouse using webcam and hand gestures.
- **Libraries**: `opencv`, `mediapipe`, `pyautogui`
- **Hint**: Track hand landmarks with Mediapipe.

### 91. **AI Voice Cloning**
- **Description**: Clone a voice from a sample and synthesize speech.
- **Libraries**: `coqui-ai`, `torchaudio`, `resemblyzer`
- **Hint**: Use pretrained TTS + speaker encoder.

### 92. **Excel Report Generator**
- **Description**: Generate styled Excel reports.
- **Libraries**: `openpyxl`, `xlsxwriter`
- **Hint**: Format tables, fonts, and charts.

### 93. **Realtime Chat (WebSockets)**
- **Description**: Live browser-to-browser chat app.
- **Libraries**: `Flask-SocketIO`, `eventlet`
- **Hint**: Use rooms and emit messages in real time.

### 94. **Fitness Tracker App**
- **Description**: Track workout logs and progress.
- **Libraries**: `tkinter`, `sqlite3`, `matplotlib`
- **Hint**: Store exercises with timestamps.

### 95. **AI Text Summarizer**
- **Description**: Summarize long articles into short bullet points.
- **Libraries**: `transformers`, `sumy`, `nltk`
- **Hint**: Use pretrained BART or T5 model.

### 96. **E-commerce Backend API**
- **Description**: Backend for a shopping app with products, users, and carts.
- **Libraries**: `fastapi`, `sqlalchemy`
- **Hint**: Include authentication and CRUD routes.

### 97. **Currency Forecasting (ML)**
- **Description**: Predict future currency prices.
- **Libraries**: `pandas`, `scikit-learn`, `xgboost`
- **Hint**: Time-series forecasting with regression.

### 98. **PDF Filler**
- **Description**: Automatically fill out PDF forms.
- **Libraries**: `pdfrw`, `reportlab`
- **Hint**: Replace placeholder fields with text.

### 99. **Virtual Keyboard**
- **Description**: Type without a physical keyboard using webcam.
- **Libraries**: `opencv`, `mediapipe`, `pyautogui`
- **Hint**: Detect hand tap motion on screen.

### 100. **AI-Powered Resume Builder**
- **Description**: Generate resume content based on user input and templates.
- **Libraries**: `jinja2`, `pdfkit`, `openai`
- **Hint**: Collect info, auto-fill HTML templates, convert to PDF.


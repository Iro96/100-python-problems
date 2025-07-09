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

... *(Continue through project 100 with similar structure)* ...


# 💬 Java GUI ChatBot using Swing

This is a simple **Graphical ChatBot application** built with **Java Swing**. The bot replies to basic user inputs with pre-defined responses using a graphical user interface.

---

## 🧠 Features

* Interactive GUI with text input and chat history display
* Basic pattern-matching chatbot logic using `HashMap`
* Instant response to common phrases (like "hi", "bye", "help")
* Easy to expand with more keywords and answers

---

## 📂 File Structure

```
ChatBot.java
```

Includes:

* GUI setup using `JFrame`, `JTextArea`, `JTextField`, and `JButton`
* `HashMap<String, String>` for storing response patterns
* Event listeners for user interaction

---

## 🛠️ How to Run

### ✅ Requirements

* Java JDK installed (version 8 or above)
* Any Java IDE (e.g., IntelliJ, Eclipse, NetBeans) or a terminal

### ▶️ Run via Command Line

1. Save the file as `ChatBot.java`.

2. Open terminal and compile:

   ```bash
   javac ChatBot.java
   ```

3. Run the application:

   ```bash
   java ChatBot
   ```

### ▶️ Run via IDE

1. Open the file in your Java IDE.
2. Run the `main()` method in `ChatBot` class.

---

## 🧾 Sample Interaction

```
You: hi
Bot: Hello! How can I help you?

You: what is your name?
Bot: I am a Java-based AI chatbot.

You: bye
Bot: Goodbye! Have a nice day.
```

---

## 💡 Customization Tips

You can add more responses inside the `loadResponses()` method like:

```java
responses.put("who are you", "I'm your friendly chatbot!");
responses.put("thanks", "You're welcome!");
```

Or improve logic using NLP libraries or regex matching for smarter interaction.

---

## 👨‍💻 Author

**Gourab Tikadar**
A basic project to learn GUI programming and chatbot logic in Java.


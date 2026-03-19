<h1>🤖 Basic Rule-Based Chatbot</h1>

<h2>📌 Project Overview</h2>
<p>
This project is a <b>simple rule-based chatbot</b> built using Python. It interacts with users by taking text input and responding with predefined replies based on specific keywords or phrases.
</p>

<h2>🎯 Goal</h2>
<ul>
  <li>Take user input like "hello", "how are you", "bye"</li>
  <li>Respond with predefined messages</li>
  <li>Continue conversation until the user exits</li>
</ul>

<h2>🧠 Key Concepts Used</h2>
<ul>
  <li>if-elif-else conditions</li>
  <li>Functions</li>
  <li>Loops (while)</li>
  <li>User input/output</li>
</ul>

<h2>⚙️ How It Works</h2>
<ol>
  <li>The chatbot continuously asks for user input.</li>
  <li>It checks the input against predefined conditions.</li>
  <li>Based on the input, it returns a response.</li>
  <li>The loop continues until the user types "bye" or "exit".</li>
</ol>

<h2>💬 Example Interaction</h2>
<pre>
You: hello
Bot: Hi!

You: how are you
Bot: I'm fine, thanks!

You: bye
Bot: Goodbye!
</pre>

<h2>📂 Project Structure</h2>
<pre>
basic-chatbot/
│
├── chatbot.py
└── README.md
</pre>

<h2>▶️ How to Run</h2>
<ol>
  <li>Make sure Python is installed</li>
  <li>Download or clone the project</li>
  <li>Open terminal in the project folder</li>
  <li>Run the command:</li>
</ol>

<pre>
python chatbot.py
</pre>

<h2>🧩 Sample Code</h2>
<pre><code>
def chatbot():
    while True:
        user = input("You: ").lower()

        if user == "hello":
            print("Bot: Hi!")
        elif user == "how are you":
            print("Bot: I'm fine, thanks!")
        elif user == "bye":
            print("Bot: Goodbye!")
            break
        else:
            print("Bot: Sorry, I don't understand.")

chatbot()
</code></pre>

<h2>🚀 Future Improvements</h2>
<ul>
  <li>Add more responses and keywords</li>
  <li>Use dictionaries instead of if-elif</li>
  <li>Implement basic NLP</li>
  <li>Add GUI using Tkinter</li>
</ul>

<h2>📚 Learning Outcome</h2>
<ul>
  <li>Understanding chatbot logic</li>
  <li>Using conditional statements</li>
  <li>Loop control</li>
  <li>Handling user interaction</li>
</ul>

<h2>👨‍💻 Author</h2>
<p>Sushil Singraul</p>

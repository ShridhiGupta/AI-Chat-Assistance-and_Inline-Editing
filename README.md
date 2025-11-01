# 💬 AI Chat Assistance and Inline Editing

You don’t need to write code manually anymore — **Really!** 😄  

## 🚀 How is it possible?
By adding an extension named **Continue** — an open-source AI code agent for VS Code.

🔗 **Find it here:** [https://www.continue.dev/](https://www.continue.dev/)

---

## 🧩 Installation Steps

1. **Download the Continue Extension**
   - Open VS Code and search for **"Continue - open-source AI code agent"** in the Extensions tab.
   - Install it.

2. **Sign In**
   - After installation, you’ll see the Continue icon in your VS Code sidebar.
   - Click it and sign in to activate the chat window.

3. **Add AI Models**
   - Open the chat window.
   - At the bottom-left corner, click to manage models.
   - Select **Groq** as your provider.

4. **Get Groq API Key**
   - Visit [https://console.groq.com/keys](https://console.groq.com/keys)
   - Sign in and generate an API key.
   - Add this key to Continue.

5. **Select and Configure Models**
   - From the Groq Playground, select the **versatile** model.
   - Copy the model string:
     ```
     llama-3.3-70b-versatile
     ```
   - Paste it into your `config.yaml` file and remove all other models.
   - Your configuration file will look like this:
     **config1.yaml**

6. **Try a Prompt**
   Example:
Write the code for Two Sum in Java

You can then create a new file and paste the generated code directly.

---

## ⚙️ Adding Another Model
You can also add the **instant** model in your config file.

Model string:
```
llama-3.1-8b-instant
```

Your updated configuration will look like:
**config2.yaml**

---

## ✏️ Inline Editing Feature
Once everything is set up, you can even **edit your code inline**!  
Just select the lines of code you want to modify and use Continue’s editing prompt.

---

## 🙏 Thank You!

# 🧠 long-horizon-cpu-llm - Run Long-Context AI Models on Your PC

[![Download Now](https://img.shields.io/badge/Download%20Software-Visit%20Link-4CAF50?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Juniperusnutrientartery2964/long-horizon-cpu-llm)

---

## 👋 Welcome

This software lets you run powerful language models (the same kind of AI that powers chatbots) directly on your own computer—no fancy graphics card needed. It works with regular processors (CPUs) and helps you test how well these models handle very long conversations or documents.

Think of it as a toolbox for curious users who want to explore AI without buying expensive hardware.

---

## 🌟 Key Features

- **Works on Your CPU** – No need for a dedicated GPU. If your computer turns on, you can try this.
- **Smarter Memory Reuse** – The software remembers previous parts of a conversation to save time and power.
- **Multiple Model Formats** – Supports popular AI model types like GGUF and Hugging Face Transformers.
- **Honest Performance Checks** – Built-in tools measure how fast and accurate the AI is, so you know what to expect.
- **Friendly Interface** – A simple dashboard (using Streamlit) shows results in plain charts and tables.

---

## 📋 What You Need

| Requirement | Minimum Spec |
|-------------|--------------|
| Operating System | Windows 10 or 11 (64-bit) |
| Processor | Any x64 CPU (Intel or AMD) |
| RAM | 8 GB (16 GB recommended for larger models) |
| Storage | 2 GB free space |
| Internet | Needed for first-time setup |

---

## 🔽 Download and Installation

### Step 1: Get the Software

Visit this link to download the application:

[**https://github.com/Juniperusnutrientartery2964/long-horizon-cpu-llm**](https://github.com/Juniperusnutrientartery2964/long-horizon-cpu-llm)

### Step 2: Install

You will be taken to a page with download options. Click the download button and follow any on-screen prompts. The file will likely be a ZIP archive or an installer. If you see a `.zip` file, right-click and choose "Extract All" to unpack it.

### Step 3: First Launch

1. After extraction, open the folder you just created.
2. Double-click the file named `run_app.bat` (or `start_windows.bat`).
3. A command window will open briefly—this is normal. Wait a moment.
4. Your web browser will open automatically showing the software interface.

---

## 🖥️ How to Use

### Loading a Model

1. In the left sidebar, you'll see a dropdown menu labeled "Model Source."
2. Choose either "Local GGUF" or "Hugging Face."
3. If you have your own model file, click "Browse" and select it. If not, the software will download a small test model for you automatically.
4. Click the **Start Model** button.

### Having a Conversation

- Type your question in the text box at the bottom.
- Press Enter or click **Send**.
- The AI will respond, and previous messages stay visible for context.

### Running a Benchmark

- Click the "Benchmark" tab at the top.
- Press the **Run Test** button.
- Wait 1–3 minutes while the software measures speed and memory.
- View the results as graphs and numbers on the same page.

### Checking Long-Context Quality

- Go to the "Quality" tab.
- Load a sample long document (or paste your own).
- The tool will ask the model questions about the beginning, middle, and end of the text.
- You'll see a score showing how well the model remembered everything.

---

## 🛠️ Troubleshooting

### "No Python Found" Error

1. Download Python from [python.org](https://python.org) (version 3.10 or newer).
2. During installation, check the box "Add Python to PATH."
3. Restart your computer, then run `run_app.bat` again.

### App Opens but No Model Shows

- Some models take longer to download. Look at the command window for progress like "Downloading 45%."
- If the download fails, try a different model from the dropdown list.

### Slow Performance

- Close other heavy programs (especially browsers with many tabs).
- Reduce the "Context Length" slider in the sidebar to a smaller number like 2048.

### App Stops Early

- If the command window closes with an error, your computer likely ran out of memory. Try a smaller model file.

---

## 📊 Understanding Results

### Speed (Tokens per Second)
How fast the model writes. Higher is better. On a typical CPU, you might see 5–20 tokens per second.

### Memory Usage (MB)
How much RAM the model consumes. Larger models use more memory.

### Quality Score (0–100%)
How accurately the model answers questions about a long document. Above 80% is considered good.

---

## ❓ Frequently Asked Questions

**Q: Is this safe to download?**
A: Yes. The software is open source, meaning anyone can inspect the code for security issues.

**Q: Do I need a powerful computer?**
A: No. A standard laptop with 8 GB RAM will work, though larger models may run slower.

**Q: Can I use this with my existing chat applications?**
A: Yes. The software includes an "OpenAI-Compatible" mode, which lets other apps connect to it like they would to a cloud service.

**Q: Will this damage my computer?**
A: No. It only uses CPU and memory while running. No system changes are made.

---

## 🔧 Advanced Tips

- **Use Smaller Models for Speed** – Models ending in "Q4_K_M" or "Q5" are compressed and run much faster.
- **Batch Testing** – You can queue up multiple benchmark tests by pressing Run Test several times; results will appear side by side.
- **Command Line Mode** – If you're comfortable with typing commands, open the `cli` folder and run `python cli_chat.py` for a text-only interface.

---

## 📁 Project Structure

| Folder/File | Purpose |
|-------------|---------|
| `/benchmarks` | Raw performance test results |
| `/models` | Place downloaded model files here |
| `/scripts` | Automation tools for testing |
| `app.py` | The main interface (Streamlit) |
| `requirements.txt` | List of required software components |

---

## 📜 License

This project is free to use, modify, and share. Full terms are in the LICENSE file included with your download.

---

## 🤝 Support and Community

- **Issues**: Found a bug? Visit the GitHub page and click "Issues" to report it.
- **Discussions**: Ask questions or share results in the "Discussions" tab on GitHub.
- **Updates**: Check the same link regularly for new versions.

---

## ✅ Final Checklist

Before starting, confirm you have:

- [ ] Downloaded the software from the link above
- [ ] Windows 10 or 11 (64-bit)
- [ ] At least 8 GB of RAM
- [ ] A stable internet connection for first run
- [ ] Closed other heavy programs for best performance

---

**Keywords:** ai-agents, benchmarking, cpu-inference, gguf, kv-cache, llama-cpp, llm-inference, long-context, openai-compatible, prefill, python, rag, streamlit, transformers
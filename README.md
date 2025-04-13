
---

## 📘 Getting Started with Python Notes

Welcome to this repository! It contains well-structured Python notes in `.ipynb` (Jupyter Notebook) format, designed to help you start learning Python effectively and interactively.

---

### ▶️ Quick Start via Google Colab

If you'd like to **start learning Python immediately without setting up anything locally**, you can do so via **Google Colab**:

1. Navigate to the `.ipynb` file you're interested in (for example, `getting_started.ipynb`).
2. Copy the **raw GitHub URL** of the notebook.
3. Paste it into [Google Colab](https://colab.research.google.com/) using the `File > Open Notebook > GitHub` option.

> ⚠️ **Note**: Some code blocks may require external files or datasets. If a cell references an external file, make sure to upload or import that data manually within Colab before running the cell.

---

### 💡 Why `.ipynb` Format?

I chose the **Jupyter Notebook (`.ipynb`) format** because:

- It's **ideal for combining code and explanations** in one place.
- You can write, document, and run Python code **in cells**, making the learning process seamless and interactive.
- It supports **rich formatting** (like headings, bullet points, LaTeX, images) which is great for note-taking and teaching concepts.

Whether you're a beginner or someone revisiting Python, notebooks make the experience fluid and engaging.

---

### 🖥️ Running the Code Locally

If you'd rather **run everything on your local machine**, follow these steps:

#### 1. Clone the Repository

```bash
git clone https://github.com/AmmarAamir786/Intro_To_Python .
```

#### 2. Initialize the Project (using [`uv`](https://github.com/astral-sh/uv))

This project uses [`uv`](https://github.com/astral-sh/uv) — a modern Python package manager that's fast and environment-friendly.

Run the following commands in your terminal one by one:

```bash
uv init .
uv venv
source .venv/bin/activate  # On Windows, use: .venv\Scripts\activate
uv sync
```

> This will automatically create and activate a virtual environment and install all the required dependencies listed for the project.

---

### 🛠️ Troubleshooting Environment Issues

If you're using **VS Code** and running into environment or kernel issues:

1. Press `Ctrl + Shift + P`
2. Search for and select **"Python: Select Interpreter"**
3. Choose the interpreter that shows: `.venv: venv` (our local environment)

Still not working?

- Press `Ctrl + Shift + P` again
- Search and select **"Reload Window"**

---

### 🚀 Start Coding

1. Open `getting_started.ipynb` (or any notebook).
2. At the top right, click **"Select Kernel"**.
3. Choose the `.venv` environment.
4. Run the first block to confirm everything is working.

---

### 🎉 Good Luck Learning!

You're all set! Have fun diving into Python, one block at a time 🧠🐍. If you encounter any issues or have suggestions, feel free to reach out to me.

---

# 🧠 CYBERNOX-CODE

**An Advanced AI-Powered Code Generation and Rehabilitation Platform**

CYBERNOX-CODE is a standalone, browser-based tool that leverages a multi-stage AI pipeline to generate new code from requirements and rehabilitate existing broken code. It's designed with a strong emphasis on security, quality, and a seamless user experience, featuring a live preview, a mini IDE, and full session management.



---

## ## Key Features ✨

* **Dual AI Modes**:
    * ⚡ **Code Generator**: Describe your project in plain English, and the AI will write the complete, functional code for you.
    * 🚑 **Code Rehabilitation**: Paste in your broken or buggy code, describe the problem, and the AI will analyze, fix, and enhance it.
* **Multi-Stage AI Pipeline**: Each request goes through a transparent, five-stage process (Generation, Security Audit, Optimization, Validation, and Fulfillment) to ensure the highest quality and security standards.
* **Integrated Live Preview**: Instantly see and interact with your generated front-end code in a securely sandboxed `iframe` right on the page.
* **Built-in Mini IDE**: Launch a full-screen code editor to modify the generated code in real-time with a side-by-side preview, offering a complete development loop within the browser.
* **AI Assistant Chat**: Plan your project and flesh out requirements through a conversational AI chat that maintains context and can populate the generator fields for you.
* **Full Session Management**: Never lose your work. Save and load entire sessions—including your inputs, results, and chat history—using your browser's local storage.
* **Security-First Design**: Built by CYBERNOX LLC with security in mind, from the AI pipeline's validation stage to the robust sandboxing of the live preview.

---

## ## How It Works

CYBERNOX-CODE operates entirely within a single `index.html` file. It uses vanilla JavaScript to manage the user interface, state, and logic.

The core AI functionality is powered by API calls to a public AI service (`text.pollinations.ai`). The application intelligently crafts a series of chained prompts for its multi-stage pipeline to progressively build, secure, and refine the code based on the user's initial request. All session and chat data is securely stored locally in your browser using `localStorage` and `IndexedDB`, ensuring your work is private and persistent.

---

## ## Getting Started

This tool is designed for maximum portability and ease of use. No installation is required.

1.  Download the `index.html` file from this repository.
2.  Open the file in any modern web browser (like Chrome, Firefox, or Edge).
3.  That's it! You can start generating or rehabilitating code immediately.

---

## ## Usage Guide

### ### ⚡ Code Generation
1.  Make sure you're in **Code Generator** mode (the default).
2.  In the **Project Requirements** text area, describe the application or component you want to build. Be as detailed as possible.
3.  Select the target **Programming Language** from the dropdown.
4.  Click **🚀 Generate Secure Code**.
5.  Watch the AI pipeline process your request. The results, setup guide, and a live preview will appear below.

### ### 🚑 Code Rehabilitation
1.  Click the mode toggle button to switch to **Code Rehab** mode.
2.  Paste your non-functional or buggy code into the **Paste Your Broken Code** text area.
3.  In the **Describe the Problems** box, explain what's wrong with the code.
4.  Select the code's language.
5.  Click **🚑 Rehabilitate Code**.

### ### 📂 Session Management
1.  Click the **Manage Sessions** button in the header to open the session manager.
2.  To save your current work (all inputs, chat history, and the generated result), give it a name and click **💾 Save Session**.
3.  To load a previous session, find it in the list and click the **📂 Load** button.

---

## ## License

This project is licensed under the MIT License. You are free to use, modify, and distribute this code as you see fit.

**Copyright (c) 2025 CYBERNOX LLC**

See the `LICENSE` file for more details.

## ## Attribution

Powered by **🛡️ CYBERNOX LLC**.

If you use this code, a "Powered by CYBERNOX LLC" mention or a link back to this repository would be greatly appreciated.

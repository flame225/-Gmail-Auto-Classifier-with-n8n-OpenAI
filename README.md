# 📧 Gmail Auto Classifier with n8n + OpenAI

This project is an **automated email classification system** built using **n8n** and **OpenAI**. It connects to Gmail, analyzes incoming messages, and classifies them into categories such as **Services Requests, Consultation Requests, Payments, and Others**. Based on classification, the workflow automatically organizes and replies to emails.

---

## 🚀 Features

* **Gmail Trigger**: Listens for new incoming emails.
* **Data Extraction**: Extracts subject and body for processing.
* **OpenAI Integration**: Uses AI to classify the email intent.
* **Text Classifier**: Routes emails into categories:

  * 📌 Services Request
  * 📌 Consultation Request
  * 📌 Payments
  * 📌 Others
* **Automated Replies**: Sends pre-configured responses to each category.
* **Smart Workflow**: Cleans and merges data before classification for accuracy.

---

## ⚙️ Workflow Overview

1. **Trigger** – Gmail detects a new incoming email.
2. **Extractor + OpenAI** – Extract text and classify with AI.
3. **Edit & Merge Fields** – Prepare email data for processing.
4. **Text Classifier** – Directs emails to the right category.
5. **Automated Replies** – Sends back a tailored response depending on the email type.



### Classified Gmail Inbox

![Inbox Screenshot](./Screenshot%202025-10-03%20at%2019-14-49%20Inbox%20-%20ndubuisiagughara533@gmail.com%20-%20Gmail.png)

---

## 🔧 Tech Stack

* [n8n](https://n8n.io/) – Workflow automation tool
* [OpenAI](https://platform.openai.com/) – Natural Language Processing & classification
* Gmail API – For email fetching and replies

---

## 📌 Use Cases

* Customer support automation
* Auto-labeling emails for productivity
* Smart replies to frequently asked questions
* Payment / invoice tracking

---

## 💡 Next Improvements

* Add support for multi-language classification.
* Integrate with Google Sheets or a database for logging.
* Train custom AI model for domain-specific emails.

---

#🧑‍💻 Author

**Ndubuisi Agughara**

* 🌐 Portfolio: [ndubuisidev.com](http://ndubuisidev.com)




Do you want me to make this post **as a full README.md file** (with the correct GitHub markdown formatting and linked screenshots), so you can directly upload it to your repo?

# 🇨🇦 MyTax Companion – AI-Powered Canadian Tax Summary App (No-Code)


A simple Glide App that helps Canadians understand their tax situation before filing. Users input basic financial info, and Glide AI instantly generates a clear, personalized summary of their tax situation.

📱 **Live App**: [mytax-companion-2zua.glide.page](https://mytax-companion-2zua.glide.page)  
🎥 **Demo Video**: [Watch Demo](https://drive.google.com/file/d/1JPQfpnfOVCJ--HhWosdQPGb-5ZOIvFF5/view)

---

## ✨ Features

- 🤖 AI-generated tax summaries based on Glide AI
- 📋 Pre-built input form for income, dependents, deductions, province, etc.
- 🧠 Uses joined-list prompt engineering to feed data into AI summary
- 📧 “Email this to me” action sends the summary to the user
- 🧾 Homepage shows tax checklist and welcome message

---

## 🔍 How It Works

1. User fills in tax info form
2. Glide combines inputs using a Joined List (`Tax_Inputs`)
3. This is fed into a Prompt Template column
4. A “Generate Text” column (Glide AI) creates a professional, friendly tax summary
5. The summary can be emailed with one click

---

## 🧠 AI Prompt Logic

See [`glide-design/prompt-template.md`](glide-design/prompt-template.md)

---

## 📊 Tables + Columns

See [`glide-design/table-structure.md`](glide-design/table-structure.md)

---

## 📁 Sample Input

Check [`data/sample-tax-inputs.csv`](data/sample-tax-inputs.csv)

---

## 📸 Screenshots

📷 Add homepage, form, and summary screenshots inside `screenshots/`.

---

## 📝 Built With

- **Glide Apps**
- **Glide AI**
- **Google Sheets**
- No external APIs or Make.com integrations

---

## 💡 Why This Matters

This app empowers non-technical users and immigrant communities to understand tax basics in Canada using simple AI-powered automation — all without coding.

---

## 📫 Contact

Made by Beni Mahmud 
📧 mahmudbeni@gmail.com 
🔗 [LinkedIn](#) | [GitHub](#)

---

## 📜 License

MIT License – See [`LICENSE`](LICENSE)

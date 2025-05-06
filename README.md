# 🧩 MuleSoft Unused YAML Key Scanner Plugin (Anypoint Studio)

A productivity-boosting Eclipse plugin designed to help **MuleSoft developers** keep their projects clean and efficient by identifying **unused YAML keys** in the `src/main/resources` folder. Built specifically for Anypoint Studio (Eclipse-based), this plugin scans your project and gives you a neat, searchable report with just one click.

---

## 📌 Key Features

### ✅ Deep Project Scan
Scans all YAML files in `src/main/resources` and detects usage in:
- XML files inside `src/main/mule`
- DWL (DataWeave) files inside `src/main/resources`

### 🔎 Smart Unused Key Detection
Only reports keys **not used** in:
- `${}` expressions in XML
- `p('key')` syntax in DWL

### 🧾 Instant Results in UI
Displays a **scrollable popup** with:
- 🔍 **Search and filter**
- 📋 **Copy to clipboard**
- 💾 **Download as file** (for record-keeping or code reviews)

### 🧠 YAML-Aware
Understands **dot notation keys** (`app.name`, `db.connection.url`) and maps them correctly to ensure **accurate usage tracking**.

### 🛡️ Safe and Non-Intrusive
- Doesn't modify your files.
- Simply scans and reports.

---
---
## 🎯 Why Use This?

- 💡 **Catch unused configs** before they become technical debt.
- 🧹 **Keep YAML files clean and relevant.**
- 🛠️ **Improve project maintainability** with better configuration hygiene.
- 🔄 Great for **code refactors**, **review cycles**, or pre-deployment sanity checks.

---
---



## 📸 Quick View (screenshots)

Menu Bar
---

![image](https://github.com/user-attachments/assets/ca2b06a6-50e1-4583-aa1b-789428ebcce7)

---
---


Tool Bar
---

![image](https://github.com/user-attachments/assets/aa8ec7da-c47b-4444-a960-54d1ed48c88d)

---
---

Popup
---

![image](https://github.com/user-attachments/assets/6f779b13-936a-4866-b926-309140171b64)

---
---

## 📦 Download

- Latest Release: [📥 Download JAR](./com.gaurav.keyscanner_1.0.0.jar)

---

## 🛠 Installation

1. Download the latest `.jar` from the [repository](./com.gaurav.keyscanner_1.0.0.jar)
2. Copy it into:
   - `plugins/` folder inside your Eclipse or Anypoint Studio
3. Restart the IDE

---

## 🎥 Demo

Watch: [YouTube Demo](Comming soon...)

---

## 🙌 Credits

Created with ❤️ by [Gaurav Oberoi](https://in.linkedin.com/in/gauravoberoi09)

---

## 📣 Spread the Word!

- ⭐ Feel free to rate this repo and share it with fellow MuleSoft devs!
- 💌 Feel free to raise issues or feature ideas via GitLab Issues.
- 📬 Connect on [LinkedIn](https://in.linkedin.com/in/gauravoberoi09) or [YouTube](https://www.youtube.com/@MuleSoftTechBites) for plugin demos and updates.


## License

This plugin is licensed under the **Creative Commons Attribution-NoDerivatives 4.0 International License (CC BY-ND 4.0)**.

You are free to:

- **Use** this plugin for personal, professional, or commercial purposes.
- **Share** or redistribute the plugin **as-is**.

You are **not permitted to**:

- Modify, transform, or create derivative works based on this plugin.
- Repackage or redistribute any modified version of this plugin.

**Full license details**: [http://creativecommons.org/licenses/by-nd/4.0/](http://creativecommons.org/licenses/by-nd/4.0/)

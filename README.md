![GitHub stars](https://img.shields.io/github/stars/rohitcodilya/fixzi-developer-workspace)
![License](https://img.shields.io/badge/license-MIT-blue)
![Made with Laravel](https://img.shields.io/badge/backend-Laravel-red)
![Frontend Vue](https://img.shields.io/badge/frontend-Vue%203-green)

# Fixzi Developer Workspace

🚀 Free JSON & XML Developer Tools — Validate, Fix & Monitor Data

👉 **Try it now:** [https://fixzi.ai](https://fixzi.ai)

---

## 💡 Why Fixzi Exists

If you’ve worked with APIs long enough, you’ve seen this happen:

* **JSON breaks** because of one missing comma  
* **XML responses** don’t match the expected structure  
* **APIs silently change** in production  
* You jump between multiple tools just to debug a single issue  

The frustrating part? These aren’t hard problems—just repetitive and time-consuming. **Fixzi** was built to eliminate that friction.

---

## ⚡ What Fixzi Does

### 🧩 JSON Tools
* **[JSON Validator](https://fixzi.ai/json-validator):** Fast, highly accurate linting.
* **[Smart Fix](https://fixzi.ai/json-validator):** Repair invalid JSON structures instantly.
* **[Formatter & Prettifier](https://fixzi.ai/json-validator):** Clean up minified, unreadable payloads.
* **[JSON Validator](https://fixzi.ai/json-diff):** Visually compare two distinct JSON files side-by-side.
* **[Schema Tools](https://fixzi.ai/json-schema-generator):** Generate and validate against strict JSON Schemas.

### 🧩 XML Tools
* **[XML Validator](https://fixzi.ai/xml-validator):** Verify structural layout correctness.
* **[Formatter & Minifier](https://fixzi.ai/xml-validator):** Toggle layouts cleanly.
* **[XML Diff](https://fixzi.ai/xml-validator):** Detect line-by-line differences in structural trees.
* **[Data Conversion](https://fixzi.ai/xml-diff):** Effortless XML to JSON / CSV parsing.

### 🔄 Data Converters
* JSON ⇄ XML
* JSON ⇄ CSV
* JSON ⇄ YAML / TOML

### 🔍 Smart Features
* **Path Search:** Locate deep nesting coordinates inside large JSON/XML objects.
* **Drag & Drop:** Quick upload handling for heavy structural payloads.
* **Zero Overhead:** A distraction-free UI completely free of ads.

### 📡 [API Contract Monitoring](https://fixzi.ai/api-contracts) (Core Feature)
* **Blueprint Snapshots:** Save your expected API payload patterns.
* **Live Inspection:** Continuously monitor live endpoints in production.
* **Drift Detection:** Instantly identify structural or response change drifts.
* **Real-time Webhooks:** Receive quick alerts via Email, Slack, or custom Webhooks.

---

## 🧠 Diagnostic Example

Imagine your application relies on an explicit payload key structure.

**Expected response profile:**
```json
{ 
  "status": "success", 
  "data": { "id": 1 } 
}

```

**Actual shifted response profile:**

```json
{ 
  "status": "success", 
  "payload": { "id": 1 } 
}

```

Even though the server responds with a `200 OK` status code, **your frontend application will break** because the keys shifted. Fixzi monitors catch this structural drift automatically and alert your team instantly before it impacts production users.

---

## 🚧 Why Not Just Use Existing Tools?

Most tools solve only one tiny fragment of the modern API workflow:

* **Validators** only identify basic structural syntax errors.
* **Formatters** only adjust line spacing.
* **API clients** are often bloated and too heavy for rapid diagnostic debugging.

Fixzi synthesizes these utilities into a singular, cohesive development workspace.

---

## 🛠️ Tech Stack & Ecosystem

* **Backend Framework:** Laravel
* **Frontend Architecture:** Vue 3 + Inertia.js
* **Styling Engine:** Tailwind CSS

---

## 📈 Target Audience

* **Backend Developers:** Rapidly debug nested relational payloads.
* **API Integrators:** Standardize third-party data layer payloads cleanly.
* **QA Automation Engineers:** Build deterministic contract validation profiles.
* **DevOps Teams:** Monitor operational endpoint contract health.

---

## 🌐 Official Resource Indexes

* **Main Application Portal:** [https://fixzi.ai](https://fixzi.ai)
* **Direct JSON Toolkit:** [https://fixzi.ai/json-validator](https://fixzi.ai/json-validator)
* **Direct XML Toolkit:** [https://fixzi.ai/xml-validator](https://fixzi.ai/xml-validator)


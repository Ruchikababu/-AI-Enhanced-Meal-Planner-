# 🍽️ AI-Enhanced Meal Planner

This project is an **n8n workflow** that generates custom meal recipes using **Gemini AI**, stores results in **Google Sheets**, and can send the recipe to the user by **email**. It supports testing with a **Webhook** using **Postman**.

---

## 🚀 **Project Summary**

✨ **What it does:**
- ✅ Collects user meal preferences (ingredients, dietary constraints, etc.)
- ✅ Uses **Gemini AI** to generate a custom recipe
- ✅ Saves the generated recipe to a **Google Sheet**
- ✅ Sends the recipe to the user by **email**
- ✅ Supports sending meal preferences directly via **Webhook** (tested with Postman)

---

## 🗒️ **My Learning Journey**

> 💡 *“As a beginner, I first built this workflow using only Google Sheets and AI:  
> I collected data with Google Sheets nodes, generated recipes using Gemini AI, saved them to another Google Sheet, and sent them by email.  
> After learning and working hard, I improved it by adding a Webhook and testing it with Postman. Now, my workflow is more flexible and real-world ready!”*

---

## 🗂️ **Files included**

| File | Description |
|------|--------------|
| `My workflow 3.json` | The main n8n workflow |
| `Recipe-Generator-Webhook.postman_collection.json` | Postman collection for testing the Webhook |
| `test-request.http` | Example HTTP request for VS Code REST Client (optional) |
| `README.md` | This documentation file |

---

## ⚙️ **How to use**

### ✅ **1. Clone this repository**

```bash
git clone https://github.com/Ruchikababu/AI-Enhanced-Meal-Planner.git
cd AI-Enhanced-Meal-Planner

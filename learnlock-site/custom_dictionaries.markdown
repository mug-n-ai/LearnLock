---
layout: default
title: Custom Dictionaries
---

# 📝 How to Create a Custom Dictionary for LearnLock  

## 📌 Step 1: Understand the JSONL Format  

A custom dictionary in LearnLock is a **JSONL file** where each flashcard follows a **specific structure**. Here’s the required format:

```json
{
  "title": "Newton’s Laws",
  "category": "Physics",
  "content": "Newton's first law states that an object in motion stays in motion unless acted upon by an external force.",
  "extra": "F = ma"
}
```

### 💡 Explanation of Each Field  

<div class="table-container">
  <table>
    <thead>
      <tr>
        <th>Field</th>
        <th>Description</th>
        <th>Example</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><code>title</code></td>
        <td>The main topic or term of the flashcard</td>
        <td><code>"Newton’s Laws"</code></td>
      </tr>
      <tr>
        <td><code>category</code></td>
        <td>The general topic area (Optional)</td>
        <td><code>"Physics"</code>, <code>"History"</code>, <code>"Vocabulary"</code></td>
      </tr>
      <tr>
        <td><code>content</code></td>
        <td>The main learning material (definition, explanation, or key information)</td>
        <td><code>"An object in motion stays in motion unless acted upon."</code></td>
      </tr>
      <tr>
        <td><code>extra</code></td>
        <td>Additional optional information like <strong>formulas, dates, pronunciations</strong></td>
        <td><code>"F = ma"</code></td>
      </tr>
    </tbody>
  </table>
</div>

📌 **Note:** Each card must follow this structure to be recognized by LearnLock.

---

## 📌 Step 2: Create Your JSONL File  

You can use any **text editor** to create your custom dictionary.

### 💡 Example for Vocabulary Learning  

```json
[
  {
    "title": "Swop",
    "category": "Dance",
    "content": "A fusion of swing and hip-hop dance styles.",
    "extra": "/swɑp/"
  },
  {
    "title": "Abacist",
    "category": "Mathematics",
    "content": "One who uses an abacus in casting accounts; a calculator.",
    "extra": "/ˈæb.ə.sɪst/"
  }
]
```

### 💡 Example for Science Concepts  

```json
[
  {
    "title": "Newton’s Laws",
    "category": "Physics",
    "content": "Newton's first law states that an object in motion stays in motion unless acted upon by an external force.",
    "extra": "F = ma"
  },
  {
    "title": "DNA Replication",
    "category": "Biology",
    "content": "The process of producing two identical replicas from one original DNA molecule.",
    "extra": "Occurs in the S-phase of the cell cycle."
  }
]
```

---

## 📌 Step 3: Save and Import Your Custom Dictionary  

1. **Save the file as `.jsonl`**  
   - Example: `my_dictionary.jsonl`  

2. **Transfer the file to your phone**  
   - You can use **Google Drive, Dropbox, or a direct USB connection**.  

3. **Open LearnLock and Import the Dictionary**  
   - Navigate to **Sources** → **Import Dictionary**  
   - Select your **JSONL file**  

4. **Start Learning!**  
   - Your new flashcards will now appear **every time you unlock your phone**. 🚀

---

## 📌 Troubleshooting & Common Issues  

**🟢 LearnLock isn’t detecting my file**  
✅ Ensure your file **uses valid JSON syntax** and follows the correct **structure**.  
✅ Check that the file **ends in `.jsonl`**.  

---

## 📝 Get Started with Your Custom Dictionary Today!  

🚀 **Try creating your own dictionary now and personalize your learning experience with LearnLock!**  

📩 **Need help? Contact us at:** [mug.n.ai.dev@gmail.com](mailto:mug.n.ai.dev@gmail.com)


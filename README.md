# Certificate of Appearance Generator (Excel VBA)

![Excel Interface](Restricted%20Files/resources/excel.png)
Automate the generation of **Certificate of Appearance** documents directly from Microsoft Excel.

This project eliminates repetitive copy-and-paste work in Microsoft Word by allowing users to enter certificate information in an Excel worksheet and generate professionally formatted Word documents with a single click.

---

## ✨ Features

### Generate All

https://github.com/user-attachments/assets/85811e8d-7d1f-4c0f-a274-1bbff99e4376

Generates Certificate of Appearance documents for **all records** available in the Excel worksheet.

**Best for:**

- Bulk certificate generation
- Preparing certificates for an entire event
- Saving time on large datasets

---

### Generate Selected

https://github.com/user-attachments/assets/b08217e1-796e-4f4c-a623-23243a0f939f

Generates certificates **only for the selected rows**.

Users simply highlight one or multiple rows and click the **Generate Selected** button.

**Best for:**

- Reprinting certificates
- Generating certificates for late attendees
- Printing only specific records

---

# ⚠️ Before You Start

## Enable Macros

This workbook uses **Visual Basic for Applications (VBA)** macros. Macros must be enabled before using any of the features.

### If you downloaded the file from GitHub

Windows may block downloaded Office files.

1. Close the Excel workbook.
2. Right-click the downloaded `.xlsm` file.
3. Select **Properties**.
4. Under the **General** tab, check **Unblock** (if available).
5. Click **Apply**.
6. Click **OK**.
7. Open the workbook again.

---

### Enable Editing

When opening the workbook, click:

> **Enable Editing**

if the yellow security banner appears.

---

### Enable Content (Macros)

After enabling editing, click:

> **Enable Content**

This allows the VBA macros to run.

> **Important:** If macros remain disabled, the Generate buttons will not work.

---

# 🚀 How to Use

1. Open the Excel workbook.
2. Enable Editing and Enable Content.
3. Fill in the required participant information.
4. Choose one of the following:

### Option 1 – Generate All

Click the **Generate All** button.

Result:

- Generates certificates for every row with data.
- Saves the generated Word document inside the output folder.

---

### Option 2 – Generate Selected

1. Highlight the desired row(s).
2. Click **Generate Selected**.

Result:

- Generates certificates only for the selected records.
- Skips all other rows.

---

# 📁 Output

Generated certificates are automatically saved inside the:

```
Generated Certificate/
```

folder.

---

# 📋 Requirements

- Microsoft Windows
- Microsoft Excel (Macro-enabled)
- Microsoft Word
- Macros enabled

---

# 📝 Notes

- Do not modify the worksheet structure unless you also update the VBA code.
- Ensure Microsoft Word is installed before generating certificates.
- Blank rows are ignored during generation.
- Save your workbook before generating certificates.

---

# 💡 Purpose

This project was created to simplify repetitive certificate preparation by replacing manual copy-and-paste work in Microsoft Word with a fast and automated Excel VBA solution.

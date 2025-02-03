# 📖 Write Documentation Guide

Welcome to the **Docusaurus Documentation Project**! This guide will walk you through **how to create, edit, and manage content** for this project using **GitHub's web interface**.

By following this guide, you will learn how to:\
✅ **Set up a public repository** for documentation.\
✅ **Create and organize** Markdown (.md) and MDX (.mdx) files.\
✅ **Understand and use Markdown & MDX formatting** for better documentation.\
✅ **Add images, GIFs, and videos** to enhance the documentation.

Resource:
Write MD basic syntax: [Basic MD Syntax](https://www.markdownguide.org/basic-syntax/)
Write MD extended syntax: [Extended MD Syntax](https://www.markdownguide.org/extended-syntax/)
MDX Component Guide: [MDX for additional UI/UX Function Guide](https://mdxjs.com/guides/)

---

## 🛠 1. Setting Up a Public Repository

To contribute to this project, you **must create a public repository** on GitHub. Follow these steps:

1. Go to **[GitHub](https://github.com/)** and log in.
2. Click the **"+"** button in the top-right and select **New Repository**.
3. Enter a name for the repository (e.g., `MyDocumentation`).
4. Select **Public** so it can be accessed remotely.
5. Click **Create Repository**.

Once your repository is created, you are ready to start adding documentation files.

---

## 📂 2. Creating and Organizing Markdown & MDX Files

### ✅ Creating a Markdown (.md) or MDX (.mdx) File

1. Navigate to your **GitHub repository**.
2. Click the **"Add file"** button and select **"Create new file"**.
3. Enter a file name ending with `.md` or `.mdx`, for example:
   - `introduction.md`
   - `getting-started.mdx`
4. Type your content directly into the editor.
5. Scroll down and click **"Commit changes"** to save the file.

---

### 📁 Organizing Documentation with Folders

To **organize your content**, you can create folders inside your repository:

1. Click **"Add file" > "Create new file"**.
2. In the file name field, type the folder name followed by `/` and then the file name.
   - Example:
     - `guides/setup.md`
     - `tutorials/basics.mdx`
3. Click **"Commit changes"** to save.

🔹 **Note:** The folders and files you create will be fetched automatically into the **Docusaurus site**.

---

## 📝 3. Basic Markdown & MDX Formatting

Markdown (.md) and MDX (.mdx) are simple ways to format text for documentation. Below are some basic and advanced formatting tips.

### 🔤 **Text Formatting**

| Format            | Syntax     | Example                     | Output                    |
| ----------------- | ---------- | --------------------------- | ------------------------- |
| **Bold**          | `**Bold**` | `**This is bold**`          | **This is bold**          |
| *Italic*          | `*Italic*` | `*This is italic*`          | *This is italic*          |
| ~~Strikethrough~~ | `~~Text~~` | `~~This is strikethrough~~` | ~~This is strikethrough~~ |

---

### 📑 **Headings**

Use `#` for headings.

```md
# Heading 1  
## Heading 2  
### Heading 3  
#### Heading 4  
##### Heading 5  
###### Heading 6  
```

---

### 🔗 **Links**

```md
[Google](https://www.google.com)
```

**Output:** [Google](https://www.google.com)

---

### 📌 **Lists**

#### **Bullet Points (Unordered List)**

```md
- Item 1  
- Item 2  
  - Sub-item 2.1  
  - Sub-item 2.2  
```

**Output:**

- Item 1
- Item 2
  - Sub-item 2.1
  - Sub-item 2.2

#### **Numbered List (Ordered List)**

```md
1. First item  
2. Second item  
   1. Sub-item  
   2. Sub-item  
```

**Output:**

1. First item
2. Second item
   1. Sub-item
   2. Sub-item

---

### 📤 **Blockquotes & Alerts**

#### **Blockquote**

```md
> This is a blockquote.
```

**Output:**

> This is a blockquote.

#### **Alerts (Docusaurus Feature)**

Docusaurus supports **custom alerts**:

```md
:::info  
This is an information alert.  
:::  

:::warning  
This is a warning alert!  
:::  
```

**Output:**

---

## 🖼️ 4. Adding Media (Images, GIFs, and Videos)

### 📸 **Adding an Image**

1. Go to your **GitHub repository**.
2. Click **"Add file" > "Upload files"**.
3. Select an image from your device and upload it.
4. Copy the **file URL** after uploading.
5. In your Markdown or MDX file, add the image using this format:

```md
![Image Description](https://your-repo-url.com/image.png)
```

🔹 **Example:**

```md
![Docusaurus Logo](https://docusaurus.io/img/docusaurus.png)
```

**Output:**\


---

## 🎯 Next Steps

Now that you know how to **create and organize content**, you can start contributing to the documentation! 🚀

If you need further assistance, check the **Docusaurus Documentation**:\
🔗 [Docusaurus Guide](https://docusaurus.io/docs)

Happy writing! 😊


## 🚀 Chrome Extension Installation Guide

Follow the steps below to install the Chrome extension built using TypeScript and React with Vite.

---

### 📝 Prerequisites
Make sure you have these installed on your system:
- 🟢 **Node.js** (version 14 or higher)  
- 📦 **npm** (Node Package Manager)  

---

### 🔧 Installation Steps

1️⃣ **Clone the Repository** 📥  
```bash
git clone https://github.com/saifalikhan9/Extention
```
> Replace the URL with your repository’s clone link.

2️⃣ **Navigate to the Root Folder** 📂  
```bash
cd <repository-folder>
```
> Swap `<repository-folder>` with the name of your cloned directory.

3️⃣ **Install Dependencies** 💾  
```bash
npm install
```
> This pulls in all the packages your extension needs.

4️⃣ **Build the Extension** 🛠️  
```bash
npm run dev
```
> This creates a `dist` folder containing your production-ready files.

5️⃣ **Load the Extension in Chrome** 🚀  
- Open Chrome and go to `chrome://extensions/`.  
- Toggle **Developer mode** on (top-right).  
- Click **Load unpacked**.  
- Select the newly generated `dist` folder.  

6️⃣ **Verify Installation** ✅  
- Your extension should now appear in the list.  
- Pin it to the toolbar for quick access (click the puzzle‑piece icon).

---

### 🗒️ Notes
- After any code changes, rebuild with `npm run dev` to update the `dist` folder. 🔄  
- For troubleshooting or extra docs, check your project’s README or contact the developer. 📚  

---

🎉 **Enjoy using your Chrome extension!** 🎊

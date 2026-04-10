# 🎨 Background Color Changer

A simple and interactive **Background Color Changer** built using **HTML, CSS, and JavaScript**.  
Click on any button to change the background color instantly.

---
## 🌐 Live Demo

https://backgroud-color-changer.netlify.app/

---

## 🚀 Features

- 🎨 Change background color with one click  
- ⚡ Fast and lightweight  
- 🖱️ Event delegation used (optimized JS)  
- 📱 Responsive layout  
- 💡 Clean and beginner-friendly code  

---

## 🛠️ Tech Stack

- HTML  
- CSS  
- JavaScript  

---

## 📂 Project Structure

```
Background-Color-Changer/
├── index.html
├── style.css
├── script.js
```

---

## ⚙️ How It Works

- Buttons are inside a parent div  
- Event listener is applied to the parent (event delegation)  
- When a button is clicked:
  - The button `id` is taken
  - Background color of body changes dynamically  

```javascript
parent.addEventListener('click', (e) => {
    const child = e.target;
    document.body.style.backgroundColor = child.id;
});
```

---

## 🧑‍💻 Run Locally

```bash
git clone https://github.com/Mahtab-123/backgroud-color-changer
cd background-color-changer
```

Open `index.html` in your browser

---

## 🚀 Deployment

Go to **Settings → Pages → Select main branch → Save**

Live URL:
```
https://github.com/Mahtab-123/backgroud-color-changer/
```

---

## ✨ Future Improvements

- Add more colors  
- Add color picker  
- Add gradient backgrounds  
- Add animations  

---

## 👨‍💻 Author

**Mahtab Alam**  

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
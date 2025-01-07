# FiveM GTA HUD  

A clean and modern **Heads-Up Display (HUD)** interface for FiveM GTA servers, offering seamless tracking of player stats, money, and location information.  

![Preview](assest/img/logo.png)  

---

## ✨ Features  

### 🎮 **Player Information**  
- Real-time **clock** and **date** display  
- Player **ID tracking**  
- Server branding with a **custom logo**  

### 💰 **Money Management**  
- **Cash balance** and **bank account** display  
- Animated **money icons**  
- Proper **currency formatting** with `$` symbol  

### ❤️ **Status Indicators**  
- Health status (percentage display)  
- Armor shield level  
- Thirst/Water level  
- Hunger/Food status  
- Mental state/Brain activity  

### 🌍 **Location Services**  
- Current **location name** display  
- **Safe zone indicators**  
- Interactive **map integration**  

---

## 🖼️ Project Screenshots  

Here are some screenshots showcasing the HUD in action:  

### Main Interface:  
![HUD Preview](assest/img/screenshot1.png)

---

## 🚀 Installation  

1. Clone this repository into your server resources folder:  
   ```bash
   git clone https://github.com/Code1616/fivem-gta-hud.git
   ```  

2. Add the resource to your `server.cfg`:  
   ```lua
   ensure fivem-gta-hud
   ```  

3. Copy the `assest` folder to your server resources directory.  

---

## 🕹️ Usage  

Once installed, the HUD will automatically display when players join the server.  

- **Top Right**: Player ID, Time, and Date  
- **Top Left**: Location Information (toggleable)  
- **Right Side**: Money Statistics  
- **Left Side**: Player Status Bars  
- **Bottom**: Map Location  

---

## 🎨 Customization  

### 🖍️ Changing Colors  

Update the colors in `style.css`:  
```css
.pol-kif-text {
    color: #093200;
}

.pol-bank-text {
    color: white;
}
```  

### 🖼️ Modifying Icons  

Replace the icons in the `img` directory with your own **SVG files**, ensuring to keep the same filenames.  

---

## 📋 Dependencies  

- FiveM server  
- Modern web browser support  
- Font: **'Unbounded'** (included via Google Fonts)  

---

## 🤝 Contributing  

1. **Fork** the repository.  
2. Create your feature branch:  
   ```bash
   git checkout -b feature/AmazingFeature
   ```  
3. Commit your changes:  
   ```bash
   git commit -m "Add some AmazingFeature"
   ```  
4. Push to the branch:  
   ```bash
   git push origin feature/AmazingFeature
   ```  
5. Open a **Pull Request**!  

---

## 📜 License  

This project is licensed under the **Unlicense**. See the [LICENSE](LICENSE) file for details.  

---

## 🙌 Credits  

- Icons: [SVG Repo](https://www.svgrepo.com/)  
- Background Image: Hindustan Times  
- Font: [Google Fonts](https://fonts.google.com/)  

---

## 🛠️ Support  

For support, please:  
- Open an **issue** in this repository.  
- Join our **Discord server** for direct assistance.  

---

### ❤️ Made with love for the FiveM community  

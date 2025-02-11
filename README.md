# 3D Cube Animation

A **3D Rotating Cube** created using **HTML, CSS**, and **CSS animations**. The cube rotates automatically and reacts to hover events, with full responsiveness for different screen sizes, including desktops, tablets, and mobile devices.

## 🌟 Features

✅ **3D Cube Effect** with smooth CSS animations  
✅ **Hover Interactions** to dynamically change cube positions  
✅ **Responsive Design** – Adapts to different screen sizes  
✅ **Modern UI** with a glassmorphism effect  
✅ **Lightweight & Fast** – Pure HTML & CSS, no JavaScript needed  

## 📂 Installation

1. Clone the repository or download the files:
   ```sh
   git clone https://github.com/your-username/3d-cube-animation.git
   ```
2. Open the project folder and launch `index.html` in your browser.

## 🚀 Usage

- Open the `index.html` file in any modern web browser.
- The cube will **rotate automatically**.
- **Hover over the cube** to see an interactive effect.
- Resize the browser window to see the **responsive design in action**.

## 🎨 Customization

You can modify the cube's size, colors, and animation speed by editing the `style.css` file:

- **Change Cube Size:**
  ```css
  .cube {
      width: 250px;
      height: 250px;
  }
  .box {
      width: 250px;
      height: 250px;
  }
  ```
- **Modify Animation Speed:**
  ```css
  @keyframes Cube {
      0% { transform: rotateX(45deg) rotateY(45deg); }
      100% { transform: rotateX(405deg) rotateY(405deg); }
  }
  ```

## 📱 Responsive Design

The cube adapts to different devices with **media queries**:

- **Desktops (1200px+)**: Standard size (200px x 200px)
- **Tablets (768px - 1199px)**: Reduced to 150px
- **Mobiles (480px - 767px)**: Reduced to 120px
- **Small Phones (below 360px)**: Reduced to 100px

## 🛠️ Technologies Used

- **HTML** – Structure
- **CSS** – Styling & Animations

## 📜 License

This project is open-source and available under the **MIT License**.

---

Enjoy coding! 🚀 If you like this project, feel free to contribute or improve it! 😊


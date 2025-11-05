# 🕒 Digital Clock with Random Background – Tkinter Project

This project is a **Python-based Digital Clock GUI** built using **Tkinter** and **Pillow (PIL)**.
It displays the **current time and date** on a stylish digital interface with a **random background image** every time you run the app.

---

## 🌟 Features

* 🖼️ **Dynamic Backgrounds** — Randomly selects one of multiple background images on startup.
* ⏰ **Real-Time Clock** — Updates every second using the system’s time.
* 📅 **Live Date Display** — Shows current day, date, month, and year.
* 🎨 **Stylish Digital Look** — Uses a “ds-digital” font style for a modern clock feel.
* 🪟 **Fixed Window Size** — Prevents resizing for consistent layout.

---

## 🧰 Technologies Used

* **Python 3.x**
* **Tkinter** — for GUI creation
* **Pillow (PIL)** — for handling and displaying images
* **time (strftime)** — for fetching live date and time
* **random** — for random image selection

---

## 🗂️ Project Structure

```
digital_clock/
│
├── main.py              # Main program file (your script)
├── as.jpg               # Background image 1
├── asd.jpg              # Background image 2
├── ass.jpg              # Background image 3
├── sss.jpg              # Background image 4
└── README.md            # Project documentation
```

---

## ⚙️ Installation & Setup

1. **Clone or Download** this repository.
2. Make sure you have **Python 3** installed.
3. Install the required library:

   ```bash
   pip install pillow
   ```
4. Place your **background images** (`as.jpg`, `asd.jpg`, etc.) in the same folder as the script.
5. Run the program:

   ```bash
   python main.py
   ```

---

## 🧠 How It Works

* When the program starts:

  * One of the given background images is selected **randomly**.
  * A digital-style label shows the **current time**, updated every second using `after()`.
  * Another label shows the **current date**, updated every minute.

---

## 🖼️ Preview (Example)

```
--------------------------------------------
|                                          |
|      10:45:32 PM                         |
|                                          |
|          Tuesday, 05 November 2025       |
|                                          |
--------------------------------------------
```

Each launch gives a different background behind the digital clock.

---

## 💡 Customization

* Add more background images to the `backgrounds` list.
* Change font color, size, or style in:

  ```python
  label = Label(root, font=("ds-digital", 60, "bold"), bg="black", fg="cyan")
  ```
* Modify window size:

  ```python
  root.geometry("600x350")
  ```

---

## 👨‍💻 Author

**Created by:** *[vijay selvan]*
📧 Contact: [[vijayvs2341@gmail.com]]

---

## 🪄 License

This project is open-source. You’re free to modify and use it for learning or personal projects.

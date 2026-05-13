Here is the professional **README.md** tailored for your repository. Since you are building a portfolio to showcase your skills as a **Software Developer** and **Data Engineer**, this version focuses on clean architecture and technical implementation.

---

# Compose Topic Grid - Courses App

A modern Android application built with **Jetpack Compose** that displays a categorized list of learning topics. This project demonstrates the implementation of efficient grid layouts and data-driven UI components using **Material 3**.

## 📱 Final Preview

<img width="480" height="852" alt="Screenshot from 2026-04-20 15-15-45" src="https://github.com/user-attachments/assets/5f277fe5-dc3d-4700-af4b-266b21c90038" />


---

## ✨ Features

* 
**Adaptive Grid Layout:** Implements a `LazyVerticalGrid` with a fixed 2-column configuration for optimal data visualization.


* 
**Material 3 Components:** Utilizes modern `Card`, `Row`, and `Column` structures to create a clean, responsive interface.


* 
**Dynamic Data Binding:** Maps a structured `DataSource` to the UI, reflecting real-world software engineering practices.


* 
**Visual Precision:** Features consistent spacing, `aspectRatio` control, and `ContentScale.Crop` for professional image rendering.



---

## 🛠️ Tech Stack

* 
**Language:** Kotlin 


* 
**UI Framework:** Jetpack Compose 


* 
**Design System:** Material Design 3 


* **Environment:** Developed on **Ubuntu Linux**.

---

## 🏗️ Technical Highlights

The heart of this application is the `TopicCard` composable. It handles the alignment of category images alongside titles and course counts, using a `Row` to balance the visual elements and a `Column` for text hierarchy.

```kotlin
// Snippet of the Grid implementation
LazyVerticalGrid(
    columns = GridCells.Fixed(2),
    verticalArrangement = Arrangement.spacedBy(8.dp),
    horizontalArrangement = Arrangement.spacedBy(8.dp),
    modifier = modifier.padding(8.dp)
) {
    items(DataSource.topics) { topic ->
        TopicCard(topic = topic)
    }
}

```

---

## 🚀 How to Run

1. Clone the repository: `git clone https://github.com/ClassMadikoa/Compose-Topic-Grid`
2. Open the project in **Android Studio**.
3. Sync the **Gradle** files and run the app on an emulator or physical device.

---

### **How to add this to your project:**

1. In your terminal (inside the project folder), run: `nano README.md`
2. **Paste** the content above.
3. **Save and Push:**
```bash
git add README.md
git commit -m "docs: create professional README for portfolio"
git push origin main

```



This documentation highlights your "detective work" in scanning and fixing datasets to create a functional UI, a skill you've noted as a personal favorite.

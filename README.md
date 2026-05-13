Compose Topic Grid - Courses App
A modern Android application built with Jetpack Compose that displays a categorized list of learning topics. This project demonstrates the implementation of efficient grid layouts and data-driven UI components using Material 3.

📱 Final Preview

<img width="480" height="852" alt="Screenshot from 2026-04-20 15-14-18" src="https://github.com/user-attachments/assets/f92c5e73-9ce7-4907-98e5-01a01c318b51" />
<img width="480" height="852" alt="Screenshot from 2026-04-20 15-15-45" src="https://github.com/user-attachments/assets/8f51381f-24c5-4f8a-93a5-f165c58376cb" />
✨ FeaturesAdaptive Grid Layout: Implements a LazyVerticalGrid with a fixed 2-column configuration for optimal data visualization.  Material 3 Components: Utilizes modern Card, Row, and Column structures to create a clean, responsive interface.  Dynamic Data Binding: Maps a structured DataSource to the UI, reflecting real-world software engineering practices.  Visual Precision: Features consistent spacing, aspectRatio control, and ContentScale.Crop for professional image rendering.  🛠️ Tech StackLanguage: Kotlin   UI Framework: Jetpack Compose   Design System: Material Design 3   Environment: Developed on Ubuntu Linux.🏗️ Technical HighlightsThe heart of this application is the TopicCard composable. It handles the alignment of category images alongside titles and course counts, using a Row to balance the visual elements and a Column for text hierarchy.  Kotlin// Snippet of the Grid implementation
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
🚀 How to RunClone the repository: git clone https://github.com/ClassMadikoa/Compose-Topic-GridOpen the project in Android Studio.Sync the Gradle files and run the app on an emulator or physical device.How to add this to your project:In your terminal (inside the project folder), run: nano README.mdPaste the content above.Save and Push:Bashgit add README.md
git commit -m "docs: create professional README for portfolio"
git push origin main

# Thesis Network Map

This project is an **interactive network map** of student thesis projects, clustered by research themes. It allows you to:
- **Filter students** by name, field keywords, or method keywords.
- **Isolate clusters** by interacting with the network.
- **Click on a student node** to view their details (name, research title, field/method keywords, and supervisors).

---

## How to Publish on GitHub Pages

1. **Create a GitHub Repository**:
   - Go to [GitHub](https://github.com) and create a new repository (e.g., `thesis-network-map`).

2. **Upload the Project Files**:
   - Upload the contents of this `thesis-network-map` folder to the repository.

3. **Enable GitHub Pages**:
   - In your repository, go to **Settings** > **Pages**.
   - Select the `main` branch and the `/root` folder.
   - Click **Save**.

4. **Access the Published Map**:
   - After a few minutes, your map will be available at:
     `https://<your-username>.github.io/thesis-network-map/`

---

## Project Structure
```
thesis-network-map/
├── index.html          # Main HTML file
├── style.css           # CSS styling
├── script.js           # JavaScript for the visualization
├── students.json       # JSON data file
└── README.md           # Instructions
```

---

## Customization
- **Update Data**: The map currently uses data embedded in `script.js`; `students.json` is a separate copy. Keep both files in sync when changing student records.
- **Student Privacy**: Student names in both files use the shortened display names shown in the map, not full names. Keep surnames out of files in the public repository. Thesis titles and supervisor names remain visible and could still identify students.
- **Change Styling**: Modify `style.css` to adjust the appearance.
- **Adjust Visualization**: Edit `script.js` to change the network behavior or filters.# TPC_topics_26_27

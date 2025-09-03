# Driver-Distraction-3D-Visualization
This project analyzes survey data on driver distraction factors and visualizes patterns across demographic groups using 3D surface plots. The aim is to understand how distractions such as music, phone calls, texting, eating, or passengers affect drivers differently by age, gender, or occupation.

---

## ⚙️ Features
- **Data Cleaning & Preprocessing**
  - Removes unwanted characters (brackets, spaces) from column names.
  - Renames distraction factor columns for better readability.
  - Handles missing values by replacing with 0.

- **Data Transformation**
  - Groups distraction levels by demographics (age, gender, etc.).
  - Computes mean distraction values for each category.

- **3D Visualization**
  - Creates interactive **3D surface plots** of distraction levels.
  - Applies **cubic interpolation** for smooth surfaces.
  - Customizes axes, labels, and rotation for clear visualization.

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Driver-Distraction-3D-Visualization.git
   cd Driver-Distraction-3D-Visualization

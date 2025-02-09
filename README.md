# Learning Journey: Uploading a Repository to GitHub and Working with Jupyter Notebook

## 1. **Learning to Upload a Repository to GitHub**
To upload a project to GitHub, I followed these steps:

1. **Create a GitHub Account:**
   - I signed up for a free GitHub account and familiarized myself with its interface.

2. **Create a New Repository:**
   - Clicked on the "+" icon in the top right corner and selected "New Repository."
   - Named the repository and chose whether it would be public or private.

3. **Initialize the Repository:**
   - I selected "Initialize this repository with a README" to add a basic project description.

4. **Clone the Repository Locally:**
   ```bash
   git clone <repository-url>
   ```
   This command downloads the repository to my computer.

5. **Stage, Commit, and Push Changes:**
   - Added files using:
     ```bash
     git add .
     ```
   - Committed the changes:
     ```bash
     git commit -m "Initial commit"
     ```
   - Pushed the changes back to GitHub:
     ```bash
     git push origin main
     ```

## 2. **Using Jupyter Notebook: Online vs Local Installation**
I explored two methods for working with Jupyter Notebook.

### **Online Environment (Google Colab)**
- I used [Google Colab](https://colab.research.google.com/) as a convenient way to run Jupyter notebooks without any installation.
- Benefits: No installation required, easy to share notebooks, and access to powerful GPUs.


## 3. **Creating My First Notebook**
In the Jupyter interface:
1. Clicked on "New" and selected "Python 3 (ipykernel)."
2. Wrote a simple Python script:
   ```python
   print("Hello, Jupyter!")
   ```
3. Ran the cell using `Shift + Enter`.

## 4. **Making Changes and Saving to GitHub**
1. Saved my notebook (`.ipynb` file) locally.
2. Added and committed changes in the terminal:
   ```bash
   git add my_notebook.ipynb
   git commit -m "Added my first Jupyter Notebook"
   ```
3. Pushed the changes back to GitHub:
   ```bash
   git push origin main
   ```

## Conclusion
Through this process, I learned to effectively use GitHub, set up Jupyter Notebook, and create/share my first notebook. This foundational experience has set me up for future programming and data analysis projects.

# 🤝 How to Contribute to This Project (Using `practice` Branch)

Welcome! If you’d like to collaborate or contribute to this project, please follow these steps carefully.  
These commands will help you clone the repository, work safely on the `practice` branch, and create a pull request to merge your changes into the main branch.

---

## 🪶 Step 1: Clone the Repository
Clone this repository to your local system:
```
git clone https://github.com/vishalprasad1912/Epileptic-Seizure-Identification-Project.git
```

Move into the project directory:
```
cd Epileptic-Seizure-Identification-Project
```

---

## 🌿 Step 2: Create or Switch to the `practice` Branch
If you’re contributing for the first time:
```
git checkout -b practice
```

If the branch already exists:
```
git checkout practice
git pull origin practice
```

---

## 🧑‍💻 Step 3: Make Your Changes
Now you can edit code, add notebooks, update documentation, or make improvements.

---

## 📦 Step 4: Stage and Commit Your Work
Once your changes are ready:
```
git add .
git commit -m "Describe what you’ve changed or added"
```

---

## 🚀 Step 5: Push Changes to the Remote `practice` Branch
```
git push -u origin practice
```

If you get an error about upstream, try:
```
git push --set-upstream origin practice
```

---

## 🔄 Step 6: Create a Pull Request (PR)
1. Go to the GitHub repository page:  
   https://github.com/vishalprasad1912/Epileptic-Seizure-Identification-Project
2. You’ll see a message saying **“Compare & pull request.”**
3. Click it and make sure:
   - **Base branch:** `main`
   - **Compare branch:** `practice`
4. Add a short title and description for your changes.
5. Click **“Create pull request.”**

---

## 🧹 Step 7: Keep Your Branch Updated
Before starting new work, always make sure your branch is up to date:
```
git checkout practice
git pull origin practice
```

---

## ⚙️ Step 8: (Optional) Sync After Merge
Once your PR is merged into `main`, update your local setup:
```
git checkout main
git pull origin main
git branch -D practice
git checkout -b practice
```

---

### ✅ Summary
| Action | Command |
|--------|----------|
| Clone repo | `git clone https://github.com/vishalprasad1912/Epileptic-Seizure-Identification-Project.git` |
| Create/switch to branch | `git checkout -b practice` |
| Stage changes | `git add .` |
| Commit changes | `git commit -m "message"` |
| Push branch | `git push -u origin practice` |
| Pull updates | `git pull origin practice` |
| Merge via PR | Done on GitHub |

---

Following these steps will ensure smooth collaboration and help maintain a clean, conflict-free workflow.  
Thank you for contributing! 💫

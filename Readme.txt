# Initialize git repository
git init

# Add remote repository (replace with your repo link)
git remote add origin <your-repo-link>

# Add all files
git add .

# Commit files
git commit -m "Initial commit - Master Folder"

# Push to GitHub (main branch)
git branch -M main
git push -u origin main

# -------- Branch 1 --------
git checkout -b LastName_B1
# Edit only Profile.txt
git add Profile.txt
git commit -m "Updated Profile.txt"
git push -u origin LastName_B1

# -------- Branch 2 --------
git checkout main
git checkout -b LastName_B2
# Edit only Education.txt
git add Education.txt
git commit -m "Updated Education.txt"
git push -u origin LastName_B2

# -------- Branch 3 --------
git checkout main
git checkout -b LastName_B3
# Edit only Background.txt
git add Background.txt
git commit -m "Updated Background.txt"
# Remove Test.py
git rm Test.py
git commit -m "Removed Test.py"
git push -u origin LastName_B3

# -------- Branch 4 --------
git checkout main
git checkout -b LastName_B4
# Edit only Readme.txt
git add Readme.txt
git commit -m "Updated Readme.txt"
# Remove Test.py
git rm Test.py
git commit -m "Removed Test.py"
git push -u origin LastName_B4

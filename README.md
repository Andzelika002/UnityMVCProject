# UnityMVCProject

A clean, modular, and open-source Unity 3D project template using the MVC architecture.

This template provides a well-organized project structure, example scripts to help developers quickly start building Unity projects following Model-View-Controller principles. It is designed for clarity, maintainability, and ease of collaboration.

## ⚡ Key Features:
- MVC Architecture: Clear separation of Models, Views, and Controllers.
- Open-Source Friendly: Structured for contribution and learning.
- Unity Version: 2022.3.53f1 LTS (3D Build-in Render Pipeline).

## 💡 Rule of Thumb:
- Placeholder explanation scripts (e.g., Prefabs.cs) are optional — remove in production.
- Use logical subfolders: Group by asset type or usage, not by asset name. Keep in mind: wide hierarchy + shallow is better for small projects or templates, deep hierarchy + structured is better for large projects with hundreds/thousands of assets.
- Maintain consistent naming conventions for clarity (PascalCase for scripts, descriptive names for prefabs/materials).

## 🚀 Create your new repository from the template :
1. Click the green “Use this template” button → choose “Create a new repository”.
2. Fill in:
   - Repository name: (your new project’s name)
   - Owner: (your account or organization)
   - Choose Public or Private
3. Click “Create repository”.
4. Clone your new repository locally

`git clone https://github.com/<your-username>/<your-new-repo>.git`

⚠️ Don’t clone the template directly — clone your newly created repo.

6. Install and enable Git LFS
   - If you haven’t already set up Git LFS on your machine:

     `git lfs install`
     
7. Pull down LFS files

   `cd <your-new-repo>`
   
   `git lfs pull`
   
9. Now make your changes, then commit and push.

## ✅ Recommended approach:

`# Windows users`

`git config --global core.autocrlf true`

`# macOS/Linux users`

`git config --global core.autocrlf input`

That combo:
* Stores LF in repo (always)
* Gives CRLF to Windows devs on checkout (so scripts still run fine)
* Converts back to LF on commit

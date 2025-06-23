 What This Will Do
Trigger on push to main or manual run.

Build your Python package into dist/:

.whl file

.tar.gz source archive

Uploads the dist/ directory as an artifact so you can download it.

🧪 To Run This Workflow
Push your code to GitHub (main branch), or

Go to Actions tab → "Build Python Package" → Run Workflow

📥 To Download Built Package
Go to Actions → build run → Artifacts

Click python-package-dist

Download and extract it — you’ll get .whl and .tar.gz

✅ Next Steps (Optional)
Want to automatically publish to PyPI? (I can help you add a twine step)

Want to build only when you push a tag like v0.1.0?

Want to include test & linting steps too?

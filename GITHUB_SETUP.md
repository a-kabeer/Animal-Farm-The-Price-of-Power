# Upload this project to GitHub

## 1. Extract the ZIP

Extract `Animal_Farm_The_Price_of_Power_GitHub_Project_NO_APPROVED_VIDEOS.zip` to a folder on your computer. **Do not upload the ZIP archive itself as the repository.** Open a terminal/PowerShell in the extracted project root (the folder containing this `README.md`). This is a lightweight documentation-and-reference package; approved video binaries and Scene 001 source/Full HD exports are excluded by request.

## 2. Recommended: install Git LFS before adding media

This repository includes `.gitattributes` configured to store MP4/MOV files with Git LFS. Install Git LFS, then run:

```bash
git lfs install
git lfs track "*.mp4"
git lfs track "*.mov"
```

The `.gitattributes` file is already present for future media additions. Git LFS storage and bandwidth availability depend on the GitHub account/plan. Approved video binaries are not in this archive. If you later add approved clips or exports, use Git LFS and update the Shot Register; update the Asset Register only if reusable references change.

## 3. Create the GitHub repository

Create an empty repository on GitHub, for example `animal-farm-the-price-of-power`. Do not initialize it with a README or license because this project already contains those project files.

## 4. Initialize and push

Replace `<YOUR_GITHUB_REPO_URL>` with the HTTPS or SSH URL from your new repository:

```bash
git init
git branch -M main
git add .
git status
git commit -m "Add Animal Farm production project and tracking baseline"
git remote add origin <YOUR_GITHUB_REPO_URL>
git push -u origin main
```

## 5. Fast project update workflow

Do not update every document after each shot.

- **Normal shot update:** change `02_SHOT_REGISTER.csv` and `project_status.json`.
- **New reusable asset/reference:** also change `03_ASSET_REGISTER.csv`.
- **Story, prompt or continuity change:** change only the affected `SCENE_BREAKDOWN.md`.
- **Major owner decision or sequence milestone:** append one row to `09_CHANGE_HISTORY.csv`.
- Update the human dashboard or README only when the overall milestone/next action changes.
- Keep approved video binaries in external media storage by default. If the owner chooses GitHub, use Git LFS. Rejected/superseded media stays in the audit folder.
- Commit the related changes together.

The Shot Register is the source of truth for shot versions, Flow media IDs, charges, metadata and review notes. The Asset Register is the source of truth for reusable reference IDs. Do not duplicate the same event in a long diary, several checklists and multiple status boards.

## 6. Ask ChatGPT to track the GitHub project

When you return to ChatGPT, provide the GitHub repository URL or upload the latest ZIP/status documents and any new media. If a GitHub connection is available, the repository can be inspected through that connection; otherwise, ChatGPT can track the project from the files you provide. There is no automatic background synchronization from this ZIP or the Flow project into ChatGPT.

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

The `.gitattributes` file is already present for future media additions. Git LFS storage and bandwidth availability depend on the GitHub account/plan. Approved video binaries are not in this archive. If you later add approved clips or exports, use Git LFS and update the media index, shot register and manifests.

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

## 5. Update the project after each production session

After every new shot generation/review/approval/rejection/export:

1. Store new approved media in the external media store by default; if the owner chooses to version it in GitHub, add it to `MEDIA/APPROVED` using Git LFS. Rejected/superseded audit media belongs in `MEDIA/REJECTED_AND_SUPERSEDED`.
2. Update `02_SHOT_REGISTER.csv` with version, status, duration, asset IDs, prompt, credits and review notes.
3. Update `03_ASSET_REGISTER.csv` for new character/location/prop references.
4. Append the decision to `05_DECISION_AND_CONTINUITY_LOG.md` and `09_CHANGE_HISTORY.csv`.
5. Update `01_MASTER_PROGRESS_TRACKER.md` and `project_status.json`.
6. Update scene breakdown and master assembly status.
7. Commit and push the changes.

Suggested commit style:

```bash
git add .
git commit -m "Approve ACT01_SCENE002_SHOT007_V01"
git push
```

## 6. Ask ChatGPT to track the GitHub project

When you return to ChatGPT, provide the GitHub repository URL or upload the latest ZIP/status documents and any new media. If a GitHub connection is available, the repository can be inspected through that connection; otherwise, ChatGPT can track the project from the files you provide. There is no automatic background synchronization from this ZIP or the Flow project into ChatGPT.

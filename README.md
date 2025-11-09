# Matrix Build with Artifacts - GitHub Actions Demo

This repository demonstrates a GitHub Actions workflow with matrix build strategy and artifact management.

## 📧 Contact Information

**Email:** 22f2000136@ds.study.iitm.ac.in.


## 🎯 Project Overview

This project showcases a CI/CD pipeline that:
- Builds across multiple Node.js versions (14, 16, 18, 20)
- Runs matrix jobs in parallel
- Generates unique artifacts for each build variant
- Uploads artifacts with proper naming convention

## 🚀 Workflow Features

### Matrix Strategy
- **Node.js Versions:** 14, 16, 18, 20
- **Parallel Execution:** All versions build simultaneously
- **Identifier:** `matrix-e1511e6` step included

### Artifacts Generated
Each matrix job generates:
- `build-info.json` - Build metadata
- `output.txt` - Build output log
- `hello.js` - Sample JavaScript file

### Artifact Naming
All artifacts follow the pattern: `build-e1511e6-node{version}`

Example artifacts:
- `build-e1511e6-node14`
- `build-e1511e6-node16`
- `build-e1511e6-node18`
- `build-e1511e6-node20`

## 📋 Validation Checklist

✅ At least 3 successful matrix jobs  
✅ At least 3 artifacts with `build-e1511e6` prefix  
✅ All artifacts contain non-empty content  
✅ Step identifier `matrix-e1511e6` included  
✅ README.md contains email address  

## 🔍 Viewing Results

1. Go to the **Actions** tab in this repository
2. Click on the latest workflow run
3. View the matrix jobs (should see 4 parallel jobs)
4. Scroll down to see uploaded artifacts
5. Download artifacts to verify content

## 📦 Artifact Contents

Each artifact contains:
- Build information (JSON format)
- Build output log
- Sample JavaScript file
- Timestamps and version information

## 🛠️ Technologies Used

- GitHub Actions
- Node.js (multiple versions)
- Matrix build strategy
- Artifact upload/download (v4)

---

**Repository Created For:** GitHub Actions Matrix Build Assignment  
**Assignment ID:** matrix-e1511e6

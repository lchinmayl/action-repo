# action-repo

# GitHub Action Repository – `action-repo`

This repository is used to **trigger GitHub webhook events** (Push, Pull Request) that are handled by a separate Flask app in webhook-repo.

## 📦 Purpose

This repo is part of a developer assessment project where:

- GitHub events like **push**, **pull request** in this repo
- Are sent to a webhook URL
- That URL is managed in another project (`webhook-repo`)
- Events are stored in **MongoDB** 

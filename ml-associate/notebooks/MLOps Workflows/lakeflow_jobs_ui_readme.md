# 📘 Creating and Managing LakeFlow Jobs using UI

This Databricks lab demonstrates how to use the **LakeFlow Jobs UI** to configure and deploy a **multi-step machine learning workflow** with manual triggers and email notifications.

---

## ✅ Objectives

You will complete the following tasks:

- 🔧 Create a LakeFlow Job with multiple tasks using the UI
- 📧 Enable email notifications for job status updates
- 🖱️ Manually trigger the deployment workflow
- 📊 Monitor the run status to verify successful execution

---

## 💻 Prerequisites

Before running the notebook:

- Attach to a **Classic Compute** cluster (not Serverless)
- If needed, restart the cluster and select it manually

**Steps:**

1. Click compute selector (top-right)
2. Choose a classic compute cluster
3. If not listed: _More → Select cluster manually_

---

## 🛠️ Workflow Summary

This notebook is not code-heavy. It focuses on **UI-based job creation**.

| Component          | Description                                 |
|--------------------|---------------------------------------------|
| LakeFlow Job       | Created via Databricks UI                   |
| Tasks              | Include notebook runs and model deployment |
| Email Notifications| Enabled for success/failure alerts         |
| Manual Trigger     | Used to run the workflow on demand         |
| Monitoring         | Checked via UI and job run history         |

---

## 🧪 Skills Practiced

- Using the Databricks UI to create multi-step jobs
- Understanding task dependencies and flows
- Configuring email notifications
- Monitoring and debugging job runs

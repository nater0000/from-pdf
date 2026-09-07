# Serverless PDF to Markdown Pipeline

An automated, zero-server pipeline that converts PDF documents into Markdown using `marker-pdf`.

**How to use:**
1. Navigate to the **Issues** tab.
2. Click **New Issue**.
3. Drag and drop your `.pdf` file into the issue description box.
4. Click **Submit new issue**.

Within a few minutes, a GitHub Action bot will comment on your issue containing direct download links for the raw `.md` file and a `.zip` archive containing the Markdown and any extracted images.

**Maintenance:**
Processed files are stored in the `conversions/` directory and are automatically purged after 30 days to optimize repository storage.

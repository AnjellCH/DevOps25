# DevOps25 🚀

This project is part of my **Cloud Resume Challenge**, showcasing my hands-on skills in DevOps, cloud infrastructure, and automation. It features a secure, scalable, and automated static resume website hosted on **Amazon S3** with a custom domain and HTTPS via **CloudFront**. The site is continuously deployed via **GitHub Actions**.

---

## 🌐 Live Site
🔗 https://anjellscloud.com

---

## 💼 Features

- **Responsive static website** styled with HTML/CSS
- **HTTPS-secured** via AWS Certificate Manager + CloudFront
- **Custom domain** purchased through Route 53
- **Hosted** on S3 with static website hosting
- **CI/CD** pipeline powered by GitHub Actions
- **Resume PDF download** with animated CTA
- **Badging** using AWS Certification badge via Credly
- **Technical skills** section with cloud/dev tools
- Infrastructure aligned with **AWS best practices**

---

## ⚙️ Tech Stack

| Category              | Tools & Services                             |
|-----------------------|-----------------------------------------------|
| Cloud Hosting         | AWS S3, CloudFront, Route 53, ACM            |
| CI/CD Pipeline        | GitHub Actions                               |
| Frontend              | HTML, CSS, JavaScript                        |
| Version Control       | Git + GitHub                                 |
| Resume Certification  | AWS Solutions Architect – Associate (SAA-C03)|

---

## 📁 Folder Structure

```
.
├── assets/                  # CSS/JS assets
├── images/                 # Images & headshot
├── index.html              # Main HTML page
├── AnjellHanley_Resume.pdf # Downloadable resume
├── .github/workflows/      # GitHub Actions pipeline
├── buildspec.yml           # (Optional for AWS CodeBuild)
```

---

## 🚀 CI/CD Workflow Summary

Every push to the `main` branch triggers the following:

- ✅ Sync files to S3 bucket (`anjellscloud.com`)
- 🔄 (Optional) Invalidate CloudFront cache
- 🔐 All secrets stored securely in GitHub Actions

---

## 🗄️ Certification Badge

I am an **AWS Certified Solutions Architect – Associate**

![AWS Badge](https://images.credly.com/size/220x220/images/0eaeaa7a-cb91-45ad-89ef-bb6f2cace90c/image.png)

---

---

## 📌 License

This project is free to use under the [MIT License](LICENSE).

---

## 📦 Deployment

The site is automatically deployed to an S3 bucket using AWS CodeBuild. Here's how deployment is handled:

1. On push to `main`, CodeBuild is triggered.
2. `buildspec.yml` defines the build steps.
3. Artifacts are pushed to S3 for public hosting.

---

## 📁 Folder Structure



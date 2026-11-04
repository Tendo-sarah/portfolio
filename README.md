# portfolio
# Tendo Sarah | AI & Machine Learning Portfolio

Personal portfolio website of **Tendo Sarah**, an AI and machine learning student focused on using technology to solve real-world challenges, with a special interest in AI for sustainable development and innovation.

**Live site:** https://ecoai-uganda-waste-management.vercel.app/

## About me

I am an AI and machine learning student based in Uganda. My work covers computer vision for waste recognition and classical machine learning for detecting fake social media accounts. I lead and work in teams of six and seven, and I care about the full path from dataset to a model people can actually try.

**Focus areas:** computer vision, applied machine learning, AI for sustainability

## Highlights

- **0.999** ROC-AUC from the Random Forest model in the Fake Profile Detector
- **4,934** Instagram profiles cleaned and balanced for training
- **7** team members led on the Fake Profile Detector
- **3** models compared: Logistic Regression, Decision Tree and Random Forest

## Projects

### EcoAI Uganda: Intelligent Waste Management System
AI-powered smart waste management that combines computer vision, IoT and machine learning to improve waste sorting, monitoring and collection efficiency in Uganda.
- Repository: https://github.com/Tendo-sarah/EcoAI-Uganda-Intelligent-Waste-Management-System
- Stack: computer vision, IoT, machine learning

### Fake Profile Detector for Social Media
A machine learning system that flags fake social media profiles, built by a team of seven that I led from planning to a working app.
- Cleaned an Instagram dataset of 5,000 profiles (12 columns) down to 4,934 unique rows with a balanced split of real and fake accounts
- Trained and compared Logistic Regression, Decision Tree and Random Forest; Random Forest performed best with a ROC-AUC of 0.999
- Shipped the saved model inside a Streamlit app, with documentation and tests on GitHub
- Stack: Python, Random Forest, Logistic Regression, Decision Tree, Streamlit, GitHub

### Smart Waste Recognition
An image classifier that recognizes garbage types using MobileNetV2 transfer learning, built with a team of six. The live demo streams a phone camera into a Google Colab notebook.
- Dataset: Kaggle garbage classification dataset
- Stack: MobileNetV2, transfer learning, Google Colab, ngrok

### Data Calculator
A Python program for working through data calculations from the command line.
- Repository: https://github.com/Tendo-sarah/data_calculator
- Stack: Python

## Skills

| Area | What I work with |
| --- | --- |
| Machine learning | Classification models, model evaluation with ROC-AUC, feature engineering and EDA, dataset cleaning and balancing |
| Computer vision | Image classification, transfer learning with MobileNetV2, live camera demos |
| Tools | Python, Google Colab, Kaggle, Streamlit, Git and GitHub |
| Teamwork | Leading a seven-person team, splitting work across pairs, documentation and testing |

## Education

**ISBAT University**: student in AI and machine learning, applying coursework through team projects in computer vision and applied machine learning.

## Website details

### Sections
About, Projects, Skills, Education and Contact, plus a hero with an animated neural network graphic, a highlights strip, project pipeline diagrams and a data panel for the Fake Profile Detector results.

### Built with
- Plain HTML, CSS and JavaScript in a single `index.html` file
- Google Fonts: Bricolage Grotesque, Hanken Grotesk and JetBrains Mono
- Canvas for the neural network animation and inline SVG for the charts
- Hosted on GitHub Pages

No build step or dependencies are needed.

### Design palette

| Role | Color |
| --- | --- |
| Background | `#0F172A` deep slate navy |
| Panels and cards | `#1E293B` graphite |
| Text | `#E5E7EB` off-white |
| Main accent | `#06B6D4` quantum cyan |
| Secondary accent | `#3B82F6` electric blue |

The colors are defined once as variables at the top of the stylesheet in `index.html`, so you can change the whole look by editing that block.

### Repository structure

```
tendo-sarah.github.io/
├── index.html   # the whole website
└── README.md    # this file
```

### Run it locally
1. Download or clone this repository.
2. Open `index.html` in any modern browser.

### Deploy with GitHub Pages
1. Name the repository `<your-username>.github.io` and keep it public.
2. Put `index.html` in the root of the repository.
3. Go to **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save.
4. The site goes live at `https://<your-username>.github.io` within a few minutes.

### Update the content
Open `index.html`, find the section you want to change (they are marked by `id` names such as `about`, `work`, `skills`, `education` and `contact`), edit the text, and commit the change. GitHub Pages republishes automatically.

## Connect

- LinkedIn: https://www.linkedin.com/in/tendo-sarah-2890bb385
- GitHub: https://github.com/Tendo-sarah

&copy; 2026 Tendo Sarah. All rights reserved.

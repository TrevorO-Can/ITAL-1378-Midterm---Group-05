# [Group 05]
2 Team Members
[Trevor Oakum] -
[W213587318@student.hccs.edu]
[Fiyinfoluwa Agbenohevi] -
[] (if applicable)
## Project Tier
Tier 2 [This project fits our tier because the simplicity of the basic components, and that we are not asking the algorithm to do complex reasoning of any sorts, just simple detection and classification].
## Problem Statement[Many people struggle to accurately identify wildlife species due to limited knowledge and the similarities between certain animals.An AI-powered animal identification system can provide quick and accurate species identification while helping users learn more about wildlife.]
## Solution Overview[To address this problem, our application will use a computer vision model to identify wildlife species from uploaded images. The model will analyze each image, predict the animal species, and display the species name, confidence score, and educational information to help users identify and learn about wildlife.]
## Technical Approach
- CV Technique:[Detection/Classification]
- Model Architecture:[CNN]
- Model: [YOLO]
- How we will use it:[Pretrained as is / Transfer learning / API, free tier or open source]
- Framework: [PyTorch]
- Why this approach:[Python's simple use is perfect for the flexibility we plan on working with this project.]
## Dataset
- Source:[Kaggle]
- Size:[762 images, 0 videos]
- Labels:[4 species of African Wild Animals]
- Link:[https://www.kaggle.com/datasets/biancaferreira/african-wildlife]
## Success Metrics (what we will measure and expect)
- Primary:[The algorithm correctly analyzes the animal, and gives it a basic profile of said species. Percentage Target: 80%]
- Secondary:[Good Performance, Attention to Detail, Little to no sign or clear indication of Bias]
## Milestone Plan
[Week 5: (MILESTONE) Blueprint: (GOAL): Complete the proposal slides, create the GitHub repository, and submit the project plan.

Week 6: (MILESTONE): First Working Demo: (GOAL): Test a pretrained MobileNetV2 model with sample wildlife images to make sure the application works.

Weeks 7–8: (MILESTONE): Build the Application: (GOAL): Train the model using our wildlife dataset and develop the wildlife identification application.

Week 9: (MILESTONE): Improve & Measure: (GOAL): Test the application, improve accuracy, and evaluate the model against our success metrics.

Week 10: (MILESTONE):  Final Presentation: (GOAL): Finalize the application, update the GitHub repository and documentation, and present the completed project.]
## Resources
- Compute:[Colab / Kaggle]
- Cost:[$0, free tier]
## Risks and Mitigation
| Risk | Probability | Plan B |
|---|---|---|
|[Risk 1: Model Develops Confirmation Bias] | High |
[Backup plan: Force Reset the model] ||
[Risk 2: Correctly Classifies and Identifies, but fails to deliver any meaningful information] | High |
[Backup plan: Go back and adjust model, train it on more information, with the hope the AI doesn't form a bias.] |
## Demo Video[Link goes here at the Final]
## AI Usage Log
See docs/AI_usage_log.md
## Current Status
- [x] Repository created
- [ ] Proposal submitted
- [ ] First working demo
- [ ] System works on our data
- [ ] Metrics measured
- [ ] Final submitted

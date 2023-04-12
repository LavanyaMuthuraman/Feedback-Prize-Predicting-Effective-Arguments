# Feedback-Prize-Predicting-Effective-Arguments
### Rate the effectiveness of argumentative writing elements from students grade 6-12

### **Description**
In this project [Feedback Prize - Predicting Effective Arguments](https://www.kaggle.com/competitions/feedback-prize-effectiveness) by [Georgia State University](https://www.gsu.edu/) on Kaggle, a [Dataset](https://www.kaggle.com/competitions/feedback-prize-effectiveness/data) that contains argumentative essays written by U.S students in grades 6-12. As we will see, these essays were annotated by expert raters for discourse elements commonly found in argumentative writing. We are tasked to predict the effectiveness of these discourse elements in the essays. 
The goal is that such a predictive model can provide automated feedback to students to help them become more confident, proficient writers.

Our goal in this competition is to classify sections (or "elements") of student's essays, in 3 categories:
- Ineffective
- Adequate
- Effective

In this notebook, I give an overview of the project and explore the dataset before training a baseline model. I also perform additional analysis using the trained model.

**The notebook includes:**
* An example of using pseudo-labels on the larger [2021 Feedback Prize Competition](https://www.kaggle.com/competitions/feedback-prize-2021) dataset.
* A custom head for the [HuggingFace Transformers](https://huggingface.co/docs/transformers/index) framework.
* An implementation of [multi-sample dropout](https://arxiv.org/abs/1905.09788).

![fb best](https://user-images.githubusercontent.com/109660074/231601921-6aa80de4-9553-4d6c-83fd-40ebef393a7f.jpg)

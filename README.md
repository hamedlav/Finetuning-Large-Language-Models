# Finetuning Large Language Models

Welcome to the **Finetuning Large Language Models** repository! This comprehensive resource is your gateway to mastering the art of finetuning large language models (LLMs). Whether you're a seasoned practitioner or just beginning your journey, this repository, accompanying the DeepLearning.AI course on finetuning large language models, offers valuable insights and practical guidance. To access the course, click [here](https://learn.deeplearning.ai/finetuning-large-language-models).

## Course Overview
The course is thoughtfully divided into several chapters, each unraveling a specific facet of LLM finetuning:

1. **Introduction**: Familiarize yourself with the course and the core concepts of LLM finetuning.
2. **Why Finetune**: Discover the motivations and rationale behind finetuning LLMs.
3. **Where Finetuning Fits In**: Explore the pivotal role of finetuning in the broader training process.
4. **Instruction Finetuning**: Dive into the world of instruction-based finetuning.
5. **Data Preparation**: Master the art of data preparation, a critical step in the finetuning journey.
6. **Training Process**: Gain insights into the intricate process of training LLMs.
7. **Evaluation and Iteration**: Learn how to effectively evaluate and refine your models.
8. **Considerations on Getting Started Now**: Receive practical advice and tips for embarking on your finetuning journey.

Throughout this course, you'll unlock the advantages of fine-tuning based on prompts, discern when and how to apply finetuning to LLMs, distinguish between finetuned and pretrained models, adapt data for finetuning in various formats, and effectively train and evaluate LLMs tailored to your specific tasks.

## Repository Contents
This repository serves as a treasure trove of resources to deepen your understanding and implementation of LLM finetuning:

- **data/**: A curated collection of example datasets and Outputs from model training used and created throughout the course.
- **notebooks/**: Jupyter notebooks that provide interactive, step-by-step guidance through the techniques covered in the course. Finetuning Large Language Models (local machine) and Finetuning Large Language Models (colab) are included numerous extra comments, slides and explanations based on the provided information during the training by the lecturers.
- **scripts/**: A repository of utility scripts, including those for data preprocessing and ARC evaluation functions.

## Getting Started
To get started and run the example notebooks within this repository, follow these straightforward steps:

1. **Clone this Repository**: Begin by cloning this repository to your local machine.

2. **Install Dependencies**: Ensure you have the necessary dependencies installed by executing the following command in your terminal or command prompt:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up Your Lamini API Key**: To access the full capabilities of this repository, you'll need a Lamini API key. We provide two convenient methods for your convenience:

   - **Google Colab (Recommended)**: For a hassle-free experience, we recommend using the "Finetuning Large Language Models (Colab).ipynb" notebook in Google Colab. This notebook streamlines the process, including API key setup.

   - **Local Machine**: If you prefer running the code on your local machine, follow these detailed steps:
       - Create a `.env` file in the root directory of the project.
       - Open the `.env` file in your text or code editor.
       - Add the following line, replacing `your_actual_api_key_here` with your authentic Lamini API key:
         ```
         LAMINI_API_KEY=your_actual_api_key_here
         ```
       - Save and close the `.env` file. This file should remain confidential, as it grants access to Lamini services.
       - In the notebook, use the provided code to securely load the API key.

4. **Run the Notebooks**: With your environment set up and the API key in place, you're ready to explore the course materials. Start Jupyter notebook and open the notebooks in the `notebooks/` directory.

Please note that the provided instructions are based on best practices, ensuring smooth code execution. We welcome your contributions and suggestions for improvement!

## Course Resources
You can access the complete course materials and lectures on the [DeepLearning.AI website](https://learn.deeplearning.ai/finetuning-large-language-models).

If you have any queries or require further clarification, please don't hesitate to reach out. We wish you a productive and rewarding journey into the world of LLM finetuning!

**License**: This repository is open-source and operates under the MIT License, allowing you to use, modify, and distribute the code, with attribution. Please review the [LICENSE](LICENSE) file for details.

---

**Notification**: To unlock the full potential of this repository, you'll need a Lamini API key. Here are two convenient methods for running the provided code:

1. **Google Colab (Recommended)**: Utilize the "Finetuning Large Language Models (Colab).ipynb" notebook for a streamlined experience, including simplified API key setup.

2. **Local Machine**: If you prefer running the code on your local machine, follow the detailed instructions above on creating a `.env` file and securely adding your Lamini API key. This ensures smooth execution while safeguarding your API key.

Let's embark on this exciting journey of LLM finetuning!
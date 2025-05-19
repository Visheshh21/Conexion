
# Conexion: AI-Powered Social Media Content Generation

Conexion is a cutting-edge generative AI project designed to empower users in creating engaging and visually appealing content for popular social media platforms such as LinkedIn, Twitter, Threads, and Instagram. By leveraging advanced generative models, Conexion enables users to craft high-quality posts with contextually relevant visuals, streamlining the content creation process.

> [!NOTE]
> The Model is hosted on **Hugging Face🤗** for easy loading and deployment. [**View**](https://huggingface.co/krimson1/Llama2-7b-chat-hf-linkedin)

## 🚀 Features

#### **AI-Generated Social Media Posts:**
- Powered by Meta’s **LLAMA 2 7B** chat model, fine-tuned on a meticulously curated dataset of **5,500** posts to ensure high-quality and engaging captions.
#### **Fine-Tuned for Enhanced Performance:**
- Utilized **LoRA (Low-Rank Adaptation)** with **PEFT (Parameter-Efficient Fine-Tuning)**, achieving an impressive model loss of 1.89 for optimized content generation.
#### **Contextual Image Generation:**
- Integrated **Stable Diffusion 3** Medium to generate visually stunning and contextually aligned images that complement the generated text.
#### **Handcrafted Dataset:**
- Data was collected from several sources, then processed and formatted using **LLAMA 3.2** to align with **LLAMA 2 7B’s input requirements**, ensuring high-quality training data.

## 📂 Project Structure
- [**Dataset_generator_llama3.ipynb:**](https://github.com/Visheshh21/Conexion/blob/main/Dataset_generator_llama3.ipynb) Demonstrates how we fabricated the dataset using LLAMA 3.2 3B to generate training prompts.
- [**Model_fine_tuning.ipynb:**](https://github.com/Visheshh21/Conexion/blob/main/Model_fine_tuning.ipynb) Provides a step-by-step guide on fine-tuning LLAMA 2 7B with LoRA and PEFT.
- [**Final_model_finetuned.ipynb:**](https://github.com/Visheshh21/Conexion/blob/main/Final_model_finetuned.ipynb) Shows how to load and use the fine-tuned model from Hugging Face for content generation.
## 📥 How to Use
1. Clone the Repository
- ```git clone https://github.com/Visheshh21/Conexion.git```   
- ```cd conexion```
2. Run the Model
- Use [**Final_model_finetuned.ipynb**](https://github.com/Visheshh21/Conexion/blob/main/Final_model_finetuned.ipynb) to load the model and generate captions.
## 🛠️ Future Enhancements
- Expand dataset to improve model performance.
- Implement a User Friendly UI. 
- Try latest and computationally efficient models.


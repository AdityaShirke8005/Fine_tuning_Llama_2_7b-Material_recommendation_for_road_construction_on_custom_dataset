# Material Recommendation and Optimization for Road Construction using Llama-2

This repository contains the fine-tuned Llama-2 model for material recommendation and optimization in road construction projects in India. The model is trained on a custom dataset specifically tailored for this purpose.

## Fine-tuning Process

### Custom Dataset

The fine-tuning process involves using a custom-made dataset that consists of 105 rows of diverse data related to material recommendation and optimization in road construction projects. Each row represents a dialogue between a human (presumably someone involved in the road construction project) and the assistant (the Llama-2 model), discussing different aspects of material selection and optimization.

### Fine-tuning the Model

To fine-tune the Llama-2 model, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies using the provided `requirements.txt`.
3. Prepare your custom dataset in the format described in the [Hugging Face datasets documentation](https://huggingface.co/docs/datasets/).

4. Implement the fine-tuning process using the `SFTTrainer` from the `trl` library.

5. Once the fine-tuning is complete, save the fine-tuned model and tokenizer for future use.

### Hugging Face Model Card

The fine-tuned Llama-2 model can be accessed on the Hugging Face model hub: [Aditya8005/llama2-qlora-finetunined-Material-recommendation-and-optimization-for-road-construction](https://huggingface.co/Aditya8005/llama2-qlora-finetunined-Material-recommendation-and-optimization-for-road-construction)

## Example Output

**Input Prompt**: Explain different ways to construct roads.

**Output generated**:
Road construction is the process of improving roads, which includes laying asphalt, concrete, or gravel on the ground. Road construction is important because it improves the safety of the road and makes it easier to drive on.

There are many different ways to construct roads. The most common way is to use asphalt or concrete.
- Asphalt is a black, sticky substance that is used to make roads. Concrete is a white, hard substance that is used to make roads.
- Another way to construct roads is to use gravel. Gravel is a small, round stone that is used to make roads. Gravel is cheaper than asphalt or concrete, but it is not as durable.

Note that the dataset used for fine-tuning is manually generated, and the quality may be relatively low. Despite this, the model has achieved a certain level of accuracy and utility.


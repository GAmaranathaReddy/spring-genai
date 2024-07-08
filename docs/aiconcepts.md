# AI Concepts
This section describes core concepts that Spring AI uses. We recommend reading it closely to understand the ideas behind how Spring AI is implemented.

## Models
AI models are algorithms crafted to process and generate information, often emulating human cognitive functions. By discovering patterns and insights within large datasets, these models can produce predictions, text, images, or other outputs, thereby enhancing various industry applications.

AI models come in various types, each tailored for specific use cases. While ChatGPT has gained attention for its generative AI capabilities in text input and output, numerous models and companies offer a variety of inputs and outputs. Prior to ChatGPT, text-to-image generation models like Midjourney and Stable Diffusion intrigued many users.

The table below categorizes several models based on their input and output types:
[AI Concepts models](images/spring-ai-concepts-model-types.jpg)


Spring AI currently supports models that process input and output as language, image, and audio. The last row in the previous table, which accepts text as input and outputs numbers, is more commonly known as embedding text and represents the internal data structures used in an AI model. Spring AI has support for embeddings to support more advanced use cases.

What sets models like GPT apart is their pre-trained nature, as indicated by the "P" in GPT—Chat Generative Pre-trained Transformer. This pre-training feature transforms AI into a general developer tool that does not require an extensive machine learning or model training background.

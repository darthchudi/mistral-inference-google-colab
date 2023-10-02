# mistral-inference-google-colab

This repo includes a notebook that runs Inference on [Mistral's 7B model](https://mistral.ai/) on Google Colab.

This is based on [Josh Bickett's notebook](https://colab.research.google.com/github/joshbickett/run-mistral-7b/blob/main/inference.ipynb#scrollTo=5r6GrJzvNWFQ
) which runs inference on the [sharded Mistral 7B](https://huggingface.co/filipealmeida/Mistral-7B-Instruct-v0.1-sharded) instruct model.

Previously, I tried running inference directly on the Mistral 7B model on Google Colab but ran out of memory. Josh's notebook uses a sharded version of the Mistral model + uses 4-bit quantization so the Neural Network's parameters/weights take up less memory.


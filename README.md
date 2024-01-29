# cs50_ai_attention

This is an AI program that predicts a masked word in a text sequence.
It forms part of the projects for the course [CS50’s Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/2024/).

The program has below listed dependencies:
- [Pillow](https://pypi.org/project/pillow/) It is the friendly PIL fork. Python Imaging Library adds image processing capabilities to your Python interpreter.
- [tensorflow](https://www.tensorflow.org/) It is an end-to-end open source platform for machine learning.
- [transformers](https://huggingface.co/docs/transformers/index) It provides APIs and tools to easily download and train state-of-the-art pretrained models.

## Usage

All the following commands assume that your current working directory is _this_ directory. I.e.:

```console
$ pwd
.../cs50_ai_attention
```

1. Install the required Python packages (Pillow, tensorflow and transformers) for the project:

   ```sh
   pip3 install -r requirements.txt
   ```
   
1. Run the application:

   ```sh
   py mask.py
      Text: We turned down a narrow lane and passed through a small [MASK].
   ```
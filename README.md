# NLP-Video-Summarization-with-Watson-and-GPT and Youtube Video Transcript Summarisation with Hugging Face Transformers

## Problem definition
As per current pandemic situation the college and school lectures are going online due to which making notes is not that much efficient and might miss some points so to over come this we have come up with the solution of NLP Video Summarisation with-Watson and GPT and Youtube Video Transcript Summarisation with Hugging Face Transformers


## Libraries list/software
- Google Colab
- ffmpeg
  ffmpeg is a very fast video and audio converter that can also grab from a live audio/video source. It can also convert between arbitrary sample rates and resize video on the fly with a high quality polyphase filter.
- ibmwatson
  I used IBM Watson because it lets you use 500 minutes of speech to text for free without putting any credit card information, unlike Google Cloud and Azure.
- Gpt 2
  With the GPT2 model we kept the probability low and usage of vocabulary high, so GPT2 do not make any new information from itself and make the Lecture summary totally wrong
  we have trained the GPT 2 model, so it can summarize the 500 lines of text written by Watson to 10 lines.
- pytorch
  PyTorch is an optimized tensor library primarily used for Deep Learning applications using GPUs and CPUs. It is an open-source machine learning library for Python, mainly developed by the Facebook AI Research team. It is one of the widely used Machine learning libraries
- Hugging with Transformers
  Hugging Face initially supported only PyTorch.
  - Following is a general pipeline for any transformer model:
      Tokenizer definition →Tokenization of Documents →Model Definition →Model Training →Inference
- Pydub
  Python provides a module called pydub to work with audio files. pydub is a Python library to work with only.wav files. By using this library we can play, split, merge, edit our. wav audio files.


## steps/flowchart
The transcoding process in ffmpeg for each output can be described by the following diagram below:
![Screenshot (274)](https://user-images.githubusercontent.com/54675828/138396479-621040f3-e15b-4af9-b268-148ef5f848b5.png)

This is the flow chart of our project:
![WhatsApp Image 2021-10-22 at 12 44 14 AM](https://user-images.githubusercontent.com/54675828/138342624-4d5cbb69-346c-4ab1-b3f7-cfac66b721bf.jpeg)





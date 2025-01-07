# Microsoft Markitdown Utility: Practical Use Cases and LLAMA, LLAVA Integration

The Microsoft Markitdown utility facilitates the conversion of PDF, HTML, CSV, JSON, XML, and Microsoft Office files into markdown files with ease.
![Project](./img/markitdown_bg_final.png)

## Overview

This article examines various use cases that can be developed using the Markitdown utility, including:

- Conversion of PDF and Excel files into markdown.
- Generation of transcripts from YouTube videos and creating summaries of the transcript using Llama 3.2.
- Obtaining descriptions of images using Llava.

---

## Project Setup

1. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

---

## Use Cases

### 1. Convert PDF File into Markdown

The first use case involves converting a PDF document into markdown. For this example, I used the _"Attention is All You Need"_ research paper PDF for conversion into markdown.

### 2. Convert Excel File into Markdown

Following a similar approach to PDF conversion, the same steps are applied to convert an Excel spreadsheet into markdown. For this use case, I utilized the Annual Population Growth Rate data from the Australian Bureau of Statistics.

### 3. Generate Transcript from YouTube Video and Create Summary Using Local Llama 3.2

In this use case:

- A transcript is generated from a YouTube video.
- The transcript is processed using the local Llama model to produce a summary in bullet points.

### 4. Obtain Description for the Image Using Llava

This use case demonstrates how to generate an image description using the local Llava model.

---

## Conclusion

The Microsoft Markitdown utility provides an efficient way to convert various file formats into markdown. When combined with AI models like Llama and Llava, it unlocks powerful use cases for content generation, file processing, and more.

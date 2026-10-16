# Clinical Data Analysis Using LLM APIs

A hands-on tutorial for analyzing clinical notes, extracting structured information from medical images, and building LLM-powered healthcare applications.

## Presentation slides
https://docs.google.com/presentation/d/1Z5xI6xjkuoyp-j_Qoy_jhvWyhXRCmRvk/edit?usp=sharing&ouid=117012909535028081696&rtpof=true&sd=true

The tutorial consists of three main sessions:

## Practice Session List
### [Session 1 - Clinical Note Analysis]
**Description:** Leveraging OpenAI models to extract clinically relevant insights from free-text medical notes.  
**Contact:** Soungmun Kim ([email](mailto:soungmun@snu.ac.kr))

### [Session 2 - InBody Report Extraction]
**Description:** Using OpenAI vision models to extract body composition measurements from InBody report images and convert them into structured Excel data.  
**Contact:** Soungmun Kim ([email](mailto:soungmun@snu.ac.kr))

### [Session 3 - Building Gene Embeddings]
**Description:** Leveraging OpenAI to learn low-dimensional gene representations from biomedical context.
**Contact:** Sungmin Kwon ([email](mailto:sungminkwon@snu.ac.kr))

## How to Start: Open Notebooks Directly in Google Colab
You can run the tutorial notebooks directly in Google Colab without downloading or installing anything.

### [Step 1: Open Google Colab]
1. Go to [Google Colab](https://colab.google/)
2. Select **File → Open notebook**.
3. Click the **GitHub** tab.
4. Paste the following repository URL:
   ```
   https://github.com/leelabsg/clinical-llm-tutorial
   ```

### [Step 2: Select a Tutorial Notebook]
Choose the notebook you want to run from the search results:
- `Session1/Tutorial1_OpenRouter.ipynb`
- `Session2/Tutorial2.ipynb`
- `Session3/Tutorial3.ipynb`

Alternatively, click the links below to open each notebook directly in Google Colab:

| Session | Notebook | Open in Colab |
|---------|----------|---------------|
| Session 1 | Tutorial 1: OpenRouter | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/leelabsg/clinical-llm-tutorial/blob/main/Session1/Tutorial1_OpenRouter.ipynb) |
| Session 2 | Tutorial 2 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/leelabsg/clinical-llm-tutorial/blob/main/Session2/Tutorial2.ipynb) |
| Session 3 | Tutorial 3 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/leelabsg/clinical-llm-tutorial/blob/main/Session3/Tutorial3.ipynb) |

### [Step 3: API Key Information]  
The API Key required for the practice can be found at the link below.  
**Note**: This API Key is strictly for use during the KOGO workshop sessions only.  

[API Key Document](https://docs.google.com/document/d/1qjIP4VclHwBh7nfssnprqitnWXlVVmh8IEvcOg1M424/edit?usp=sharing)

The API Key required for the practice can be found at the link below.  
**Note:** This API Key is strictly for use during the KOGO workshop sessions only.

After opening the notebook, find the API key field:

```python
API_KEY = ""
```

Copy the provided API key and paste it **between the quotation marks (`" "`)**, as shown below:

```python
API_KEY = "YOUR_API_KEY_HERE"
```

> **Important:** `YOUR_API_KEY_HERE` is only an example. Replace it with the API key provided for the workshop.  
> Do not remove the quotation marks (`" "`).

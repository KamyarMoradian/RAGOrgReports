# ReportRAG

A Retrieval-Augmented Generation (RAG) system designed to efficiently generate, analyze, and respond to organizational reports using advanced natural language processing techniques.

## Introduction

This project employs state-of-the-art RAG methodologies to combine information retrieval with large language models, including **LLaMA 3** and **LaBSE**, enabling precise and contextual responses to organizational queries. The system enhances report generation, organizational analysis, and user experience by delivering accurate, relevant, and timely insights to decision-makers.

### Key Features
- **Information Retrieval**: Uses indexed data to retrieve the most relevant sections of organizational content.
- **Content Generation**: Generates detailed responses using advanced models like LLaMA 3.
- **Multilingual Support For Evaluation**: Handles multilingual content with LaBSE embeddings.
- **Evaluation Mechanism**: Employs cosine similarity to evaluate the accuracy and relevance of generated responses.

## Installation

Follow these steps to set up the project:

1. Clone the repository:
 
  ```bash
  git clone https://github.com/yourusername/rag-org-reports.git
  ```

3. Navigate to the project directory:
   
  ```bash
  cd rag-org-reports
  ```

3. Install the required dependencies:
   
  ```bash
  pip install -r requirements.txt
  ```

4. Ensure you have a GPU-enabled environment for optimal performance.

## Usage

### Input Preparation

1. Organize your organizational data in structured formats (e.g., Excel or PDF).
2. Normalize input files for compatibility with the system's indexing tools.

### Running the System

#### Indexing Phase:

- Use the llama-index module to process and index your data.
  
#### Retrieval Phase:

- Query the indexed data to fetch the most relevant information.

#### Generation Phase:

- Leverage LLaMA 3 to generate detailed responses based on the retrieved content.

### Evaluation

The system evaluates output quality using cosine similarity between query embeddings and generated responses, ensuring high relevance and accuracy.

## Challenges and Future Improvements

### Challenges Addressed

- Handling input data in various formats, resolved by converting files to structured formats like Excel.
- Managing memory and GPU limitations by optimizing model parameters.

### Future Directions

- Enhancing multilingual support.
- Reducing processing time for large datasets.
- Incorporating additional evaluation metrics for deeper analysis.

### License

This project is licensed under the MIT License.

### References

1. [RAG Processing Using LlamaIndex](https://medium.com/@tejaswi_kashyap/rag-processing-using-llamaindex-43d9786f9d8e4)  
2. [Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks](https://arxiv.org/abs/2005.11401)  
3. [Mastering RAG from Scratch](https://www.freecodecamp.org/news/mastering-rag-from-scratch/)  
4. [Guide to Retrieval-Augmented Generation](https://www.smashingmagazine.com/2024/01/guide-retrieval-augmented-generation-language-models/)  
5. [RAG from Scratch](https://learnbybuilding.ai/tutorials/rag-from-scratch)  
6. [Meta LLaMA 3 - 8B Instruct](https://huggingface.co/NousResearch/Meta-Llama-3-8B-Instruct)   

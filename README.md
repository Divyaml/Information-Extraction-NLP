# Information-Extraction-NLP
Program to extract information from text and fill pre-defined templates using Natural Language Processing.

Requirements:

<li>1.Python 3.7
<li>2.SpaCy 2.2.4
<li>3.nltk 3.4.5
<li>4.neuralcoref 4.0 (Install from source https://github.com/huggingface/neuralcoref)

File Description:

<li>1.buyTemplate.py : Extracts buy event templates from the document
<li>2.workTemplate.py : Extract work event templates from the document
<li>3.partTemplate.py : Extracts location templates from the document

To run the demo:

<li>1.Task 1 : Run "Task1_FeatureExtraction.py"
<li>2.Task 3 : Run "Task3_InformationExtraction.py"

Objectives:

<li>1.Implement an NLP pipeline to extract features. The features include sentence splitting, tokenization, lemmatization, part-of-speech tagging, dependency parsing and word relation extraction.
<li>2.Implement a machine-learning, statistical, or heuristic (or a combination) based approach to extract filled information templates from the corpus of text articles. The templates are BUY (Buyer, Item, Price, Quantity, Source), WORK (Person, Organization, Position, Location), PART (Location, Location)
<li>3.Implement a program that will accept an input text document and output a JSON file with extracted/filled information templates from the input text document.

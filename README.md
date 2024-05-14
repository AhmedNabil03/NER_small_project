<h1>Named Entity Recognition (NER) with spaCy</h1>
This project utilizes spaCy, a natural language processing library, to perform Named Entity Recognition (NER).<br>
NER is a task in NLP that involves identifying named entities such as persons, organizations, locations, dates, and more in a given text.<br>

<h3>Usage</h3>

<b>Installation:</b> Ensure you have spaCy installed. If not, you can install it via pip:<br>
pip install spacy<br>

<b>Download Language Model:</b> Download the English language model 'en_core_web_sm':<br>
python -m spacy download en_core_web_sm<br>

<h3>Entities Identified</h3>
<b>PERSON</b>: People, including fictional characters.<br>
<b>ORG</b>: Companies, organizations, institutions, etc.<br>
<b>LOC</b>: Non-GPE locations, mountain ranges, bodies of water.<br>
<b>DATE</b>: Absolute or relative dates or periods.<br>
<b>MONEY</b>: Monetary values, including unit.<br>

<h3>Visualization</h3>
spaCy provides visualization tools like <b>displacy</b> to visualize named entities in the text.<br>

<h3>Custom Entities</h3>
You can also set custom entities using spaCy's <b>Span</b> class.<br>

<h3>Conclusion</h3>
This project demonstrates the use of spaCy for Named Entity Recognition, a crucial task in natural language understanding.<br>
It showcases spaCy's ability to identify entities in text efficiently.<br>
Explore further by trying out different texts and customizing entity recognition as needed.

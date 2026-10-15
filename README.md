Project Agenda
SMS Message Cleaning and Entity Audit: A mobile-service quality team must standardize
real SMS messages before spam analysis. Students clean the UCI SMS Spam Collection,
compare NLTK and spaCy tokenization and lemmatization, create POS summaries, and
inspect named entities and preprocessing errors without exposing personal messages.


Software Requirements
• Python 3.x
• Jupyter Notebook or Google Colab
• NLTK
• spaCy and an English language model
• Pandas and regular expressions

Suggested Dataset
UCI Machine Learning Repository — SMS Spam Collection (5,574 labelled SMS messages).
Official page: https://archive.ics.uci.edu/dataset/228/sms+spam+collection

Dataset Access
Recommended: from ucimlrepo import fetch_ucirepo; sms = fetch_ucirepo(id=228).
Alternatively download the ZIP from the official UCI page. No account is required.

Recommended Lab Subset
Use the complete dataset for cleaning statistics; use a stratified sample of 500 messages for
detailed NLTK–spaCy comparison.

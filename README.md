# language-translation-of-scraped-data-using-LLM-model

This project consist 2 parts:-
1 Real time data collection of 2nd hand cars from cars24.com through web scraping.
 * Name of the car
 * Model of the car
 * Km run
 * Fuel type
 * Transmission
 * Price of the car
 * Description of the car
   Are some of the data's which are scraped from the website and stored in the saperate dataframe,
   And to do so I have used request and BeautifulSoup library along with pandas and numpy library.

2 Translating the description of the cars from english to hindi language using Facebook's mbart model
In this part the description of the cars are preprocessed tokenized and then translated from english to hindi language using Facebook's mbart llm pretrained model and the translated data is stored in the dataframe in the saperate column.
And the library i have used in this is pandas, numpy, hugging Face(transformers), tokenizer.

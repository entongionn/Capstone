# Capstone
# Presentazione Personale del Progetto Manga Epicode

In questo progetto ho voluto capire quali titoli manga fossero più popolari sulle piattaforme Mangadex e Mangaworld, integrando i dati ufficiali di MyAnimeList per offrire un quadro completo.

Ho iniziato scrivendo uno scraper in Python per MangaWorld, sfruttando Selenium per navigare in modalità headless, pandas per gestire i dati e unidecode per pulire i titoli. Parallelamente, ho imparato JavaScript e Node.js per curiosità: in un file `index.js` ho utilizzato axios per chiamare l’API V5 di MangaDex e fs per salvare i risultati in CSV.

Successivamente, ho pulito e normalizzato i dati con pandas, numpy e unidecode all’interno di notebook Jupyter. Per assicurarmi di confrontare correttamente gli stessi titoli, ho utilizzato fuzzywuzzy (basato su Levenshtein) per fare il matching tra i nomi estratti e quelli di MyAnimeList.

Per sintetizzare l’interesse degli utenti, ho calcolato due indici di popolarità usando pandas, numpy e MinMaxScaler di sklearn.preprocessing: il GlobalPopularityIndex, che combina follows, views, membri, score e favorites, e l’ItalianPopularityIndex, dedicato alle metriche italiane. I risultati sono stati esportati in un file CSV.

Infine, ho progettato una dashboard chiara in Power BI per visualizzare i risultati in modo immediato.

Con questo lavoro ho affinato competenze di web scraping, API REST con JavaScript, data cleaning, matching dei dati e visualizzazione interattiva, dimostrando anche la capacità di apprendere autonomamente nuove tecnologie.

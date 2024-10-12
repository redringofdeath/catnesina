# Catnesina
[![Awesome plugin](https://custom-icon-badges.demolab.com/static/v1?label=&message=awesome+plugin&color=F4F4F5&style=for-the-badge&logo=cheshire_cat_black)](https://github.com/cheshire-cat-ai/awesome-plugins)

<img src="https://github.com/redringofdeath/catnesina/blob/eda20f8e6e1e75582ee7d355c944be3f9c560b33/catnesina.jpg" width="200">

# Introduction
Catnesina is a virtual assistant designed to support travellers by providing essential and up-to-date information on security, safety and health risks for international destinations. 

Powered by the data from “Viaggiare Sicuri” portal of the Italian Ministry of Foreign Affairs, this assistant offers quick answers to travellers’ questions regarding safety and security advisories, health headsup, and travel requirements.

This assistant is particularly valuable for Italian citizens planning to travel abroad, providing them with relevant and accurate guidance to make informed decisions. 

However, it may also accommodates travellers from other countries, offering reliable and universally applicable information to suit a wide range of travel needs.
By delivering real-time information directly from official sources, Catnesina serves as a reliable travel companion, offering peace of mind to those exploring the world.

## Features
Catnesina is a customizable system designed to manage information related to country-specific risks, and it's built for people that need to receive up-to-date information efficiently in a conversational manner. 

At its core, the system includes a feature that allows for the download, storage, and retrieval of reports for various countries, leveraging ISO country codes for precise mapping. 
In particular, documents are downloaded directly from the [ViaggiareSicuri](https://www.viaggiaresicuri.it/home) website, and are saved and processed within a streamlined workflow that checks for updates, preventing unnecessary duplicates / embeddings.
Information validity is checked daily to ensure the latest updates are always available: this parameter can be configured, from 1 to 30 days of information retention.

To optimize document management, the system offers automatic summarization of contents _(based on [Summarization](https://github.com/Furrmidable-Crew/ccat_summarization) plugin)_.

Lastly, the system integrates all three types of memory from the [Cheshire Cat](https://github.com/cheshire-cat-ai/core) - episodic, declarative, and procedural - each with configurable parameters.
The assistant is further enhanced with a personalized language and context adaptation feature: it responds in a formal, business-oriented tone and automatically adjusts the language to that of the user, using memory functions to enrich interactions with relevant context and information _(based on [C.A.T. Cat Advanced Tools](https://github.com/Furrmidable-Crew/cat_advanced_tools) plugin)_.

## Special Thanks
A special thanks goes to [Alessandro Spallina](https://github.com/AlessandroSpallina) for his valuable insights, and to the [Italian Ministry of Foreign Affairs and International Cooperation](https://www.esteri.it/en/) that, through the website [ViaggiareSicuri](https://www.viaggiaresicuri.it/home), provides guidance and information to all travellers. 

[![MAECI](https://www.viaggiaresicuri.it/assets/images/logoFarnesina.png "MAECI")](https://www.esteri.it/en/)

# PlotMatch – An AI-Based Recommendation Engine for Manga and Manhwa  
Final project for the Building AI course

## Summary  
PlotMatch is an AI-powered recommendation engine for manga and manhwa that focuses on emotional tone, character dynamics, and narrative themes. Instead of relying solely on genres or popularity, it suggests titles that resonate with what the user actually enjoys in a story, such as specific character archetypes or story arcs.

## Background  
Most manga/manhwa recommendation systems are based on genre tags or overall popularity. But readers often connect more deeply with specific emotional elements or character types in a story. It can be frustrating and time-consuming to search for new titles with similar vibes manually.

This project addresses:
* The lack of story driven recommendations in manga/manhwa platforms  
* The difficulty of finding titles with similar emotional or narrative structure  
* A desire for more personalized and meaningful discovery  

My motivation comes from being a fan of storytelling driven manga/manhwa who often struggles to find similar content once a favorite series ends. PlotMatch aims to fill that gap using natural language understanding and semantic matching.

## How is it used?  
1. The user inputs a favorite title, character archetype, or story keyword (e.g. "tragic hero", "redemption arc", "grumpy/sunshine dynamic").
2. PlotMatch builds a semantic profile from their input using NLP techniques.
3. It searches a database of manga/manhwa metadata and fan descriptions for similar patterns.
4. The user receives 5 - 10 recommendations, each with short explanations of why it was matched.

PlotMatch is ideal for:
* Manga/manhwa fans looking for story based suggestions
* New readers unsure where to start
* Writers seeking story inspiration

<img src="[https://eight-trees.net/wp-content/uploads/2022/07/animate-kyoto-shop-front.jpg](https://eight-trees.net/wp-content/uploads/2023/03/1-1.jpg)![image](https://github.com/user-attachments/assets/982e5607-40fa-4729-a2cb-2602ffbf2795)
" width="300">

## Data sources and AI methods  
PlotMatch uses:
* Publicly available synopsis and metadata from sites like [MyAnimeList] [(https://www.myanimelist.net)](https://www.myanimelist.net)([https://myanimelist.net](https://myanimelist.net), [MangaUpdates][(https://www.mangaupdates.com)](https://www.mangaupdates.com)
* Fan-generated tags and reviews from Reddit, NovelUpdates, Tumblr
* Sentence embedding models (e.g. BERT, Sentence Transformers) to analyze and compare narrative similarity
* Optionally, collaborative filtering in later versions

| Data Type           | Source                              |
|---------------------|-------------------------------------|
| Synopsis/Metadata   | MyAnimeList, MangaUpdates  |
| Fan Tags & Reviews  | Reddit, NovelUpdates, Tumblr        |
| Embedding Models    | Pretrained BERT, SBERT              |

## Challenges  
PlotMatch does not:
* Guarantee 100% accuracy - emotional tone and character dynamics are subjective
* Support multilingual data processing yet – this may lead to bias toward English tagged titles
* Cover the entire manga/manhwa landscape – niche series may be underrepresented

Ethical considerations:
* Attribution of metadata and fan generated content  
* Preventing bias toward popular or mainstream titles  
* Ensuring diversity in recommendations

## What next?  
To improve PlotMatch, future steps include:
* Building a front end interface or chatbot for user interaction
* Expanding multilingual support and more robust text normalization
* Collecting user feedback to train a reinforcement learning component
* Adding visual input (e.g. art style recognition via computer vision)

Skills or help needed:
* Frontend development (React or similar)
* More diverse datasets for story and character types
* NLP optimization for creative storytelling domains

## Acknowledgments  
* Inspired by real frustrations as a manga/manhwa lover  
* Based on research into semantic search and NLP (HuggingFace Transformers)  
* Synopses from [MyAnimeList](https://myanimelist.net), licensed under fair use  
** Image: [Manga Store in Kyoto](https://eight-trees.net/wp-content/uploads/2023/03/1-1.jpg) / [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0)

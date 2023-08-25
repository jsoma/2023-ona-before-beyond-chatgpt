# AI Tools from Before (and Beyond!) ChatGPT

**ONA 2023**, August 2023

> I added links, but **THERE WILL BE SO MUCH MORE HERE LATER!!!!**

Hi, I'm Jonathan Soma! I run the [Data Journalism MS](https://journalism.columbia.edu/data) and [Lede Program](https://ledeprogram.com/) at Columbia, where I am Knight Chair in Data Journalism.

Contact me at [js4571@columbia.edu](mailto:js4571@columbia.edu) or [on Twitter](https://twitter.com/dangerscarf).

**Talk content:**

- [Slides here](ai-tools-before-beyond-chatgpt.pdf)

**Some of my websites:**

- [aifaq.wtf](http://aifaq.wtf/) - collection of weird AI stuff
- [normalai.org](https://normalai.org/) - many examples like what we did in the session
- [https://investigate.ai/](https://investigate.ai/) - more traditional ML
- [A few blog posts](https://jonathansoma.com/words/)

## Links from the slides

- [How ChatGPT turned generative AI into an “anything tool”](https://arstechnica.com/ai/2023/08/how-chatgpt-turned-generative-ai-into-an-anything-tool/) (Ars Technica)
- [Hugging Face models page](https://huggingface.co/models)
- [Prompt Engineering for Developers course](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/)
- **Washington Post classification example**
    - [Apple says its App Store is ‘a safe and trusted place.’ We found 1,500 reports of unwanted sexual behavior on six apps, some targeting minors.](https://www.washingtonpost.com/technology/2019/11/22/apple-says-its-app-store-is-safe-trusted-place-we-found-reports-unwanted-sexual-behavior-six-apps-some-targeting-minors/) (WATCH THE VIDEO!!! It has spreadsheets!!!)
    - [Predicting reports of bullying, racism, and unwanted sexual behavior from app store reviews](https://investigate.ai/wapo-app-reviews/predict-reviews/) - an old-school, traditional machine learning approach to the Washington Post app reviews classification problem
    - [Stemming and lemmatization](https://investigate.ai/text-analysis/stemming-and-lemmatization/) - how to deal with words with different endings (fishes/fishing/fished, running/runs/ran) in traditional machine learning
    - [creepy-wapo](https://huggingface.co/spaces/wendys-llc/wendys-llc-creepy-wapo) - a Hugging Face space where you can demo my fine-tuned [creepy-wapo](https://huggingface.co/wendys-llc/creepy-wapo) model (warning: it's pretty awful at classifying things)
    - [Hugging Face AutoTrain](https://ui.autotrain.huggingface.co) - the "just upload your spreadsheet or images" way to fine-tune models
- [Zero-shot classification](https://jsoma.github.io/2023-abraji-ai-workshop/#zero-shot-classification) - a tiny example from a workshop I gave in Brazil
- [Leprosy of the land](https://texty.org.ua/d/2018/amber_eng/) - an investigation into illegal amber mines in Ukraine, powered by machine learning
- **Named entity recognition:**
    - [Named entity recognition several ways in Python](https://jsoma.github.io/2023-abraji-ai-workshop/#named-entity-recognition)
    - [GENIE from La Nación](https://www.lanacion.com.ar/sociedad/nuevas-herramientas-la-nacion-presenta-genie-un-monitor-de-brecha-de-genero-y-como-lo-digo-nid26032023/) – gender gap source analysis tool
    - [Source Matters](https://sourcematters.com/) - "track and improve the diversity of sources in your news stories," from American Press Institute
- [Basics of text embeddings](https://investigate.ai/text-analysis/word-embeddings/)
- **Older examples of using embeddings:**
    - [Conceptual document similarity with word embeddings](https://investigate.ai/text-analysis/document-similarity-using-word-embeddings/)
    - [Comparing documents across languages with Universal Sentence Encoding and Tensorflow](https://investigate.ai/text-analysis/comparing-documents-in-different-languages/)
- **More modern approaches to embeddings:** (using LangChain mostly)
    - [Multi-language document Q&A](https://jonathansoma.com/words/multi-language-qa-gpt.html) - a more modern usage of text embeddings
    - [How I convinced GPT to teach me about Hungarian folktales (without speaking a word of Hungarian)](https://github.com/jsoma/mediaparty-folktales) - a talk on text embeddings/multi-language document Q&A/document search from MediaParty Chicago 2023
    - [Intro to document search and similarity](https://jsoma.github.io/2023-abraji-ai-workshop/#document-search-and-similarity)
- ["Chat with your data" online course](https://www.deeplearning.ai/short-courses/langchain-chat-with-your-data/) - there are so many of these jeez
- [Doing translation with Hugging Face](https://huggingface.co/docs/transformers/tasks/translation)
- **Image tasks**
    - [Object Detection](https://normalai.org/images/instance-segmentation.html) - (finding "things") aka instance segmentation, [live example](https://huggingface.co/spaces/wendys-llc/OWL-ViT)
    - [Semantic segmentation](https://normalai.org/images/semantic-segmentation.html) (finding "stuff") to identify vegetation - [live example](https://huggingface.co/spaces/thiagohersan/maskformer-satellite-trees-gradio)
    - [Panoptic segmentation](https://huggingface.co/spaces/wendys-llc/panoptic-segment-anything)
- **Fine-tuning image models**
    - [Hugging Face autotrain](https://ui.autotrain.huggingface.co)
    - [Prodi.gy](https://prodi.gy/) - a product from explosion, the same company as spaCy
    - [Roboflow](https://roboflow.com/) - an online tool to do fine-tuning of image/video models
- Object detection of facts + classification of the results can turn into...
    - [How to hide faces and scrub metadata when you photograph a protest](https://www.theverge.com/21281897/how-to-hide-faces-scrub-metadata-photograph-video-protest)
    - [How The New York Times Uses Software To Recognize Members of Congress](https://open.nytimes.com/how-the-new-york-times-uses-software-to-recognize-members-of-congress-29b46dd426c7)
    - [The AIJO Project](https://www.aijoproject.com/) - gender detection of faces on news segments
    - [BBB 23: Inteligência artificial revela quem mais apareceu nos VTs do programa](https://estadao.com.br/emais/tv/bbb-23-inteligencia-artificial-revela-quem-mais-apareceu-nos-vts-do-programa/) - using facial recognition to analyze screen time of members of Big Brother Brasil
- **Video**
    - [Runway ML](https://runwayml.com/) - an example of generative video
- **Audio**
    - [Whisper](https://github.com/openai/whisper) - a great model for transcription (this is easier than trying to use it with Hugging Face tools, too) - [live example](https://jsoma.github.io/2023-abraji-ai-workshop/#audio-models)
    - [Speaker diarization with pyannote](https://huggingface.co/pyannote/speaker-diarization)
    - [SpeechX from Microsoft](https://www.microsoft.com/en-us/research/project/speechx/) - the demos are INSANE
- Build dashboards/interactives/playgrounds with [Gradio](https://www.gradio.app/) or [Streamlit](https://streamlit.io/)
- [Document Summaries in Danish with OpenAI](https://generative-ai-newsroom.com/summaries-in-danish-with-openai-cbb814a119f2) - a great example of testing/tracking AI use in the newsroom
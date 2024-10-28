
<!-----

You have some errors, warnings, or alerts. If you are using reckless mode, turn it off to see useful information and inline alerts.
* ERRORs: 0
* WARNINGs: 0
* ALERTS: 1

Conversion time: 0.974 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β40
* Mon Oct 28 2024 05:51:58 GMT-0700 (PDT)
* Source doc: Large Language Model (LLM) - Notes - 2024
* This document has images: check for >>>>>  gd2md-html alert:  inline image link in generated source and store images to your server. NOTE: Images in exported zip file from Google Docs may not appear in  the same order as they do in your doc. Please check the images!

----->


<p style="color: red; font-weight: bold">>>>>>  gd2md-html alert:  ERRORs: 0; WARNINGs: 0; ALERTS: 1.</p>
<ul style="color: red; font-weight: bold"><li>See top comment block for details on ERRORs and WARNINGs. <li>In the converted Markdown or HTML, search for inline alerts that start with >>>>>  gd2md-html alert:  for specific instances that need correction.</ul>

<p style="color: red; font-weight: bold">Links to alert messages:</p><a href="#gdcalert1">alert1</a>

<p style="color: red; font-weight: bold">>>>>> PLEASE check and correct alert issues and delete this message and the inline alerts.<hr></p>



# **Large Language Model **


# **(LLM)**


# **Notes**


# **Year 2024**


[TOC]




<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.jpg "image_tooltip")



# **What is a large language model (LLM)?**

LLMs can be trained to do a number of tasks. One of the most well-known uses is their application as [generative AI](https://www.cloudflare.com/learning/ai/what-is-generative-ai/): when given a prompt or asked a question, they can produce text in reply. The publicly available LLM ChatGPT, for instance, can generate essays, poems, and other textual forms in response to user inputs.

Any large, complex data set can be used to train LLMs, including programming languages. Some LLMs can help programmers write code. They can write functions upon request — or, given some code as a starting point, they can finish writing a program. LLMs may also be used in:



* Sentiment analysis
* DNA research
* Customer service
* [Chatbots](https://www.cloudflare.com/learning/bots/what-is-a-chatbot/)
* Online search

Examples of real-world LLMs include ChatGPT (from OpenAI), Bard (Google), Llama (Meta), and Bing Chat (Microsoft). GitHub's Copilot is another example, but for coding instead of natural human language.


## What are some advantages and limitations of LLMs?

A key characteristic of LLMs is their ability to respond to unpredictable queries. A traditional computer program receives commands in its accepted syntax, or from a certain set of inputs from the user. A video game has a finite set of buttons, an application has a finite set of things a user can click or type, and a programming language is composed of precise if/then statements.

By contrast, an LLM can respond to natural human language and use data analysis to answer an unstructured question or prompt in a way that makes sense. Whereas a typical computer program would not recognize a prompt like "What are the four greatest funk bands in history?", an LLM might reply with a list of four such bands, and a reasonably cogent defense of why they are the best.

In terms of the information they provide, however, LLMs can only be as reliable as the data they ingest. If fed false information, they will give false information in response to user queries. LLMs also sometimes "[hallucinate](https://www.cloudflare.com/learning/ai/what-are-ai-hallucinations/)": they create fake information when they are unable to produce an accurate answer. For example, in 2022 news outlet Fast Company [asked](https://www.fastcompany.com/90819887/how-to-trick-openai-chat-gpt) ChatGPT about the company Tesla's previous financial quarter; while ChatGPT provided a coherent news article in response, much of the information within was invented.

In terms of security, user-facing applications based on LLMs are as prone to bugs as any other application. LLMs can also be manipulated via malicious inputs to provide certain types of responses over others — including responses that are dangerous or unethical. Finally, one of the security problems with LLMs is that users may upload secure, confidential data into them in order to increase their own productivity. But LLMs use the inputs they receive to further train their models, and they are not designed to be secure vaults; they may expose confidential data in response to queries from other users.

How do LLMs work?


#### Machine learning and deep learning

At a basic level, LLMs are built on machine learning. Machine learning is a subset of AI, and it refers to the practice of feeding a program large amounts of data in order to train the program how to identify features of that data without human intervention.

LLMs use a type of machine learning called deep learning. Deep learning models can essentially train themselves to recognize distinctions without human intervention, although some human fine-tuning is typically necessary.

Deep learning uses probability in order to "learn." For instance, in the sentence "The quick brown fox jumped over the lazy dog," the letters "e" and "o" are the most common, appearing four times each. From this, a deep learning model could conclude (correctly) that these characters are among the most likely to appear in English-language text.

Realistically, a deep learning model cannot actually conclude anything from a single sentence. But after analyzing trillions of sentences, it could learn #enough to predict how to logically finish an incomplete sentence, or even generate its own sentences.


#### Neural networks

In order to enable this type of deep learning, LLMs are built on neural networks. Just as the human brain is constructed of neurons that connect and send signals to each other, an artificial neural network (typically shortened to "neural network") is constructed of network nodes that connect with each other. They are composed of several "layers”: an input layer, an output layer, and one or more layers in between. The layers only pass information to each other if their own outputs cross a certain threshold.


#### Transformer models

The specific kind of neural networks used for LLMs are called transformer models. Transformer models are able to learn context — especially important for human language, which is highly context-dependent. Transformer models use a mathematical technique called self-attention to detect subtle ways that elements in a sequence relate to each other. This makes them better at understanding context than other types of machine learning. It enables them to understand, for instance, how the end of a sentence connects to the beginning, and how the sentences in a paragraph relate to each other.

This enables LLMs to interpret human language, even when that language is vague or poorly defined, arranged in combinations they have not encountered before, or contextualized in new ways. On some level they "understand" semantics in that they can associate words and concepts by their meaning, having seen them grouped together in that way millions or billions of times.


## How developers can quickly start building their own LLMs

To build LLM applications, developers need easy access to multiple data sets, and they need places for those data sets to live. Both cloud storage and on-premises storage for these purposes may involve infrastructure investments outside the reach of developers' budgets. Additionally, training data sets are typically stored in multiple places, but moving that data to a central location may result in massive [egress fees](https://www.cloudflare.com/learning/cloud/what-are-data-egress-fees/).

Fortunately, Cloudflare offers several services to allow developers to quickly start spinning up LLM applications, and other types of AI. Vectorize is a globally distributed vector database for querying data stored in no-egress-fee object storage ([R2](https://www.cloudflare.com/developer-platform/r2/)) or documents stored in [Workers Key Value](https://www.cloudflare.com/developer-platform/workers-kv/). Combined with the development platform [Cloudflare Workers AI](https://developers.cloudflare.com/workers-ai/), developers can use Cloudflare to quickly start experimenting with their own LLMs.

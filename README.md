# Transformers-GENAI
Title: Exploring Text Generation with GPT-2 and Transformers
Introduction
Transformers are a type of deep learning architecture that revolutionized natural language processing (NLP). Unlike traditional models like RNNs or LSTMs, transformers use self-attention mechanisms to understand contextual relationships across entire sequences, making them more efficient and accurate in understanding language. They are the foundation of many modern AI models such as GPT, BERT, and T5, and are widely used in applications like text generation, translation, summarization, and question-answering.

Experiment Summary
For this project, I used the GPT-2 model via the transformers library provided by Hugging Face. I loaded the model using the pipeline function for text generation and tested various prompts to observe how the model responds to different input types and parameter settings.

I tested three types of prompts:

A futuristic factual statement

Prompt: "In the future, education will"

A topic-based sentence

Prompt: "The impact of AI on the future of work"

A short story opener

Prompt: "Once upon a time, there was a kingdom"

Observations
Below are the outputs from the GPT-2 model using different prompts and settings:

Prompt: In the future, education will

Temperature: 0.7

Result: “In the future, education will be critical in the fight against climate change, as we are facing a rapidly changing climate and must have a plan in place to help meet that challenge," said Dr. Richard G. Kieren, director of the Center”

Comment: The model completed the sentence in a logical and relevant way.

Prompt: The impact of AI on the future of work

Temperature: 0.8

Result: “The impact of AI on the future of work will depend on how it will be implemented. While it is certainly true that we will see a variety of AI innovations from companies like Google to Facebook and Amazon to Microsoft, which will allow for better collaborative work”



Prompt: Once upon a time, there was a kingdom

Temperature: 0.6

Result: “The impact of AI on the future of work will depend on how it will be implemented. While it is certainly true that we will see a variety of AI innovations from companies like Google to Facebook and Amazon to Microsoft, which will allow for better collaborative work
Once upon a time, there was a kingdom of saints. This kingdom was called the kingdom of Christ. The name of this kingdom was the kingdom of the saints. This kingdom was called the kingdom of the saints.

The kingdom of Christ was called the kingdom of the saints. This kingdom was called the kingdom of the saints. The kingdom of Christ was called the kingdom of the saints.

The kingdom of Christ was called the kingdom of the saints. This kingdom was called the kingdom of”

Comment: Lower temperature made it more predictable and storybook-like.

Reflection
This experiment showed how GPT-2 uses its transformer architecture to predict and generate coherent language based on context. I learned that:

Prompt phrasing matters: A simple rewording can lead to significantly different outputs.

Temperature controls creativity: Lower values make outputs more logical and focused, while higher values make them more imaginative but potentially less accurate.

Transformers are incredibly versatile: With just a few lines of code, GPT-2 can generate news articles, stories, and opinions.

Surprises:
Sometimes, the model generated text that felt “too human,” including speculative or opinionated content.

Even with factual prompts, the output may not always be accurate.

Limitations:
GPT-2 doesn’t understand context in the human sense—its knowledge is fixed up to 2021.

It may hallucinate facts or generate biased/unrealistic content.

Sample Outputs
Included in the report:

Output 1: In the future, education will...

Output 2: The impact of AI on the future of work...

Output 3: Once upon a time, there was a kingdom..



Reflection on GPT-2 Prompt Experiment
This experiment helped me understand how powerful and flexible transformer-based models like GPT-2 are in generating human-like text. By experimenting with different prompts - news headlines, story openers, dialogues, and factual questions—I observed how GPT-2 adapts its tone, structure, and context to fit the input.

Adjusting parameters like temperature and max_length had a noticeable effect: higher temperatures led to more creative and unpredictable responses, while lower values made the output more structured and focused. Using num_return_sequences showed how diverse the outputs can be even from the same prompt.

Overall, this exercise gave me deeper insight into how prompt engineering and parameter tuning influence language generation. It also highlighted GPT-2's strength in creativity and its limitation in factual accuracy.




output : 
--- News Headline Outputs ---
Output 1: Breaking news: Scientists discover a new'superior' gene

Researchers at Harvard Medical School have discovered that the transcriptional regulation of DNA is highly conserved, allowing for improved survival in patients with advanced diseases such as heart disease or cancer.


The scientists, led by Harvard Medical School research
Output 2: Breaking news: Scientists discover a new way to extract methane from fossil fuels

A team led by Australian research scientist Greg McBride, also from the University of Adelaide, has discovered a method that can extract the methane from ice-age petroleum resources – a process known as ice-age hydrolysis
Setting `pad_token_id` to `eos_token_id`:50256 for open-end generation.

--- Short Story Output ---
It was a cold and stormy night when I woke up in the middle of the night. I was lying on the floor in my room, trying to keep my head up. I noticed a hole in the ceiling. I turned around and saw the girl lying on the floor. I looked down and saw her face. She was naked. She had a hole in her face. I could see it through her hair. I told her to look at me. She said, "I need to see
Setting `pad_token_id` to `eos_token_id`:50256 for open-end generation.

--- Dialogue Output ---
Alice: Where are we going?
Bob: I just got off the bus.
Bob: Oh, I'm glad to see you.
Bob: I'm sorry.
Bob: Why are you asking about me?
Bob: Well

--- Dialogue Output ---
Alice: Where are we going?
Bob: I just got off the bus.
Bob: Oh, I'm glad to see you.
Bob: I'm sorry.
Bob: Why are you asking about me?
Bob: Well

--- Factual Question Outputs ---
Output 1: What are the benefits of renewable energy?

A. Renewable energy has the potential to significantly reduce greenhouse gas emissions. It also has the potential to reduce the amount of energy that is wasted in the economy.

Q. What is the cost of renewable energy?

A. The cost of renewable energy is the cost of electricity.
Output 2: What are the benefits of renewable energy?

The benefits of renewable energy are obvious. The cost of electricity is lower than in the past. The cost of energy is lower than in the past. The cost of energy is lower than in the past. The cost of energy is lower than in the past. The cost of energy is lower than in





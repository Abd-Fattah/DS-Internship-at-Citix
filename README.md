# DS Internship at Citix

##Introduction

Firstly, I wanted to make a full analysis of the dataset, with pointing coefficient to each feature of the dataset, and then got a filtered sample, then work with that. I have a plan and some sketches of the solution. But, after a little work, it was acknowledged that a straightforward approach would be accurate for this type of problem. Hence, I analyzed the whole dataset and got a bunch of the best records with the highest rate of price and quality. Then I just prompted them to the Chat GPT 3.5 turbo with API key provided by Dmitriy. 

## Answers to the questions.

###1. How to mimic the style of successful Instagram posts?

Answer: Obviously, the model knows how to mimic, and I will conclud according to how the gpt model doing it. Initially, write captions that are concise, yet engaging. Use emojis and hashtags strategically to add personality. Moreover, share compelling and relatable stories in your captions. Make your audience feel connected to your content. Research and use relevant and popular hashtags in your niche to expand your reach and connect with a wider audience. That's how the model mimic the Instagram posts. I agree with chat gpt, but it will be more relatable if we just add some tone of writing and maintain the story, some background of our account owner.

###2. What prompt engineering techniques can improve quality?

Answer: During the work, I found out the temprature technique. Adjust the "temperature" parameter to control the randomness of the output. Lower values (e.g., 0.2) produce more focused responses. Experiment with the "max tokens" parameter to limit the response length.
Additionally, we allways need to control the prompt for the explicit instructions. For example, specify the format of the response, request the model to think step-by-step. Of course, it is obviously to use multiple prompts and combine or select the most suitable responses. Ensemble approaches involve generating responses with different prompts and selecting the best one.

###3. How to ensure the model doesn't invent extra features?

Answer: I thoroughly don't understand what the question was about, but In my context of understanding, how I instructed above, we need to use explicit instructions and assemble our response by using several response, so how the generator models work. I heard that if we give to the model, the negative experience of respone that doesn't accurate, we will see more suitable response without 'extra features'.

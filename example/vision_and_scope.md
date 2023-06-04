# Movie Chat

Every good project starts with a great vision for what the end product can be. For example, let's pick something wildly ambitious that we are somewhat reasonably confident is possible. ***Movie Chat!***

How does it work - Movie Chat is an interactive LLM-based agent you can interact with as a writer to easily and quickly craft your own stories.

Movie Chat specializes in long-form film narrative. 

You’ll start by chatting with the agent about types of movies you like, what you are interested in, and what type of message you’d like to share with the world.

Then you can work with Movie Chat to figure out what the basic plot of your narrative is. 

For most films that includes who are your main characters, what happens to them, what struggles they encounter, how they overcome those struggles, and how they change as a result.

MovieChat is great at understanding the basics of narrative construction, so you don’t have to be a total pro. 

MovieChat is also really good at helping visually describe scenes, including camera angles and shots, to help make the movie come to life. 

You’ll have multiple chats available, letting you move between them as you work on different parts of the overall narrative. 

Once you have a clear written form, MovieChat can interact in the visual domain with you to generate visuals for your characters, scenes, and the overall storyboard. 

# Datasets
Now that we have a killer idea, let's flesh out a few example datasets we could use to take some steps towards actually building this. You are probably already thinking about the famous ***IMDB*** dataset, with a sample available on Hugging Face [here](https://huggingface.co/datasets/imdb). While is is a great set of reviews, I don't actually think those would help us with producing a net new story from stratch, let alone the storyboard. It might be useful eventually as a signal for the quality of the movies we write, so we'll keep it on the back burner.

One amazing dataset I'd love to work with is the ***IMSDb***, which has the largest collection of screenplays available online for free [here](https://imsdb.com/).  This will come in handy when we move into generating the dialogue for the movie, line-by-line.

But what does it actually look like to generate a movie? Let's think about the user journey.

# User journey
On a side note, I actually took quite a few courses on playwrighting in college, where I minored in creative writing. So I have some idea of what the actual creative process looks like for at least getting from an idea to a workable play! Now let's figure out how to do this using LLM's. You'll notice that, across the board, the writer is utterly at the helm of the entire process and operates as the final decision maker and owner. The technology, however, operates as a helpful frame of reference. It's a side-kick :).

1. I interact with an LLM to find a few cool ideas for a new movie I want to make.
2. I generate a short, 5-line synopsis I'm happy with.
3. From the short synopsis, I move into the character development.
4. Having some idea of the characters on paper, I use an image generator to create pictures of them!
5. I generate more detailed written descriptions of my characters: who they are, what they want, what they struggle with, and how they change.
6. Using all of this rich content about the characters, I move into the full plot. This is a detailed 500+ word description of the entire movie. It includes a clear beginning, middle, and end, with a strong plot narrative. The LLM and agent help me write all of this, piece by piece. It gives me a variety of options when I get stuck, including tips for what audiences usually like to see.
7. Once I have the full plot, I pick a few key scenes. This might be the opening, a plot twist, a reveal, a chase, and the conclusion.
8. With a few of these scenes in mind, I move back to the vision model. Using the image I generated of my own character, I create some pictures themselves.
9. Working like this I create the story board for most of the parts of the film.
10. Then I go back and write the dialogue for each scene, and I'm done!

At the end of this journey, the user has everything they need to get started producing a net new movie! 

# Map key points in user journey back to concepts from the book
Now that we know what product we want to build, let's map the steps back to what we learned from the book. Given the excellent state of many open-source foundation models today, including those in langauge and vision, I strongly doubt we'll need to pretrain one from scratch to solve this problem. 

However, for the sake of argument, let's imagine we had more than 1TB of relevant, rich data to work with, and we're interested in pretraining a model like this from scratch. How might we go about it?

***1. Dataset analysis***. The first thing I'd do is look at our datasets in Python, just to get a sense of their dimensions and characteristics.
***2. Model analysis***. Next, work with a few top LLMs and vision models on this dataset. I'll produce that chart to tell me how far prompt engineering and fine-tuning take me.
***3. Scaling law analysis***. 


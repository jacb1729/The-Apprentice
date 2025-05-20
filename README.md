# The Apprentice

I've often wondered how formulaic The Apprentice UK can be from time to time. We get archetipical characters, consistent task categories with common mistakes, similar structure. How simply can we fully encapsulate the story that plays out in The Apprentice UK?

## Getting the data
My first try, when I first wanted to do this project, was to see what Chat GPT 3.x could infer from a simple prompt. At the time, x was such that this GPT hallucinated at some point mid response.
Luckily, the Wikipedia page for The Apprentice UK is a *highly* consistent format. The URL, page structure, and even the structures of crucial tables are (virtually) identical. This makes it easy to scrape the data.

## Summarising episodes from their text descriptions

Having staged the data properly, I have since wondered whether I can also use language models to classify the tasks, which should be doable, from the description given in other Wikipedia pages. This would save labelling tasks so to get useful context - one might wonder if winners are best picked from advertising and sales tasks, for instance, over the events management tasks or procurement. The progress I've made is to begin experimenting with minimally downstream-trained models for this (I could just get someone to label tasks, but wouldn't an automation be nice for the future, as well as just fun for me to play with?).

I'm mostly just following my curiousity, but I'm hoping that this period of experimenting meditation puts me in a good place to describe how the show has evolved and consider how formulaic task format can be.
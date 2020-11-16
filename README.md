# My-First-Project

Building AI course Project

## Summary

A story generator, with user defined vocabulary as input.


## Background
I’m learning German, while using Lingvist to expand my vocabulary, I found there are some words which I can hardly makes any connection with them. Once it’s out of the sentence I read/remember, I can’t really recall them - hence, not knowing it by heart.

* problem 1: I work with my own vocabulary list, with fixed sentence examples
* problem 2: The different sentences have too wide of a coverage, make it hard to memorize
* problem 3: If I need to learn different meaning of the word, I need to search different sentences manually on internet
* problem 4: If I need to see different words in one context, I need to hire people to write it for me 

This happens everyday - as long as I try to keep a routine on learning vocabulary. What drives me is my frustration from constant demotivation because of the the incapability of using German for communication, and of course the urgency to understand this culture and be able to use the language to experience the culture.

Why important or interesting?
* Time saving for learners
* Save a lot of effort to make the context for vocabulary expansion 

## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```

* In context of horning the “hard candies”. 
* By language learner. Learner, Teachers, will all be affected 
* It might also generate a new service (value) for monetisation - proof reading.

## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

I dont see this project to solve any output accuracy issues.
It doesn’t have to learn from the inputs, or to use inputs to train any model?

## What next?

1. Make it possible to generate stories in series, aka, the new story have certain connected to the old ones, so build consistency/relevancy.
2. Make the story relevant to current affairs and news? - so that learner already have some kind of “knowledge” about the subject

## Acknowledgments

Sources of inspiration 
* [Building AI fromUniversity of Helsinki and Reaktor](https://buildingai.elementsofai.com/Conclusion/your-ai-idea) / unknown licenses
* ["Zamia AI project - German GPT-2 Model](http://zamia-speech.org/brain/2019/11/20/384M-German-GPT-2-Model-Finished.html) / unknown licenses


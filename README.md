# NLP-project

Inspired by by sophinisba on AO3, I came across to this idea of using NLP technology to generate crossover conversations, to deepen my understanding toward crossover by the randomness of language models.

The idea is to train numbers of language models using lines from several different fiction movies, and eventually make each of them generating prefix for on another, so to create a ‘back and forth’ conversation.

Over 1000 lines were compiled from eleven films, sorted by character. In these four characters, Gandalf and Dumbledore were trained purly on movie dialogues, while Bilbo and Hagrid were trained on dialogues with extra persona, to give them more personality and stronger opinions.

Constructing ‘back and forth’ conversation wasn’t easy, because using generated text as prefix is risky for those text has it’s own randomness. I found a way to make the conversation more consistent by making all the sentence end with comma(,), so as a result I have to improv a little to add punctuation mark at the end of every line. Apart from training the cross over conversation generator, i also hired some human writers to write some dialogues with the exact same theme and structure and characters. And I extracted some sentence form those human creations I gathered as initial prefix for the generator, all the out comes are in the out come folder.

The note book only works on colab, and before generating anything, all the checkpoint files need to be uploaded into a ‘checkpoint’ folder under the ‘content’ folder.There are four checkpoint folders for four characters, because those files are too big to be uploaded to github so please get access to those files through the link I put in the txt file.

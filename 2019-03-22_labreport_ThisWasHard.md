# Lab 8: Building a Bot

I started this lab report out by telling myself that I'd start with a poem I already knew pretty well, and just do some simple modifications. Once, I kind of had the hang of it, I could start to get a little crazy and a little creative. I chose _O Captain, My Captain_ by Walt Whitman, a poem endlessly analyzed in nearly every English class I took in high school. I knew it almost like the back of my hand; this couldn't be too hard I thought.

Jokes on me because I never really got the hang of it! There was a point as I was building this bot where I ran into an issue, and because I didn't know what to do I just kept hitting run, over and over again. This obviously led to me getting the same error message, over and over again, which led to me experiencing the same frustrations, over and over again.  

```whitman <- "whitman"
> 
> whitman <- paste(c(poem_word("interjection"), "captain, my captain! our", poem_word("adjective"),  "trip is done ",
+ "The ship has ", poem_word("verb"), " every ", poem_word("noun"), ", the prize we sought is",
+ " won,", 
+ "The port is ", poem_word("preposition"), "the bells I hear, the people all exulting,"
+ "While follow eyes the steady keel, the vessel "poem_word("adjective"), "and", poem_word("adjective")
Error: unexpected string constant in:
""The port is ", poem_word("preposition"), "the bells I hear, the people all exulting,"
"While follow eyes the steady keel, the vessel ""
> collapse = "")
Error: unexpected ')' in "collapse = "")"

```

Often times, the notion of creativity suggests that there isn't exactly one way to do something, that there is no right or wrong answer. Using creativity in code is interesting because the creativity involved isn't as limitless as I initially expected it to be. There is a right way and a wrong way to write code. After staring at my failing string of code for a while, I decided to enlist the help of some more computer-oriented friends to see if they could figure out where I was going wrong. 

 While some of my friends tried to look over my code and see exactly where I was going wrong, I couldn't help but feel like it was somewhat similar to helping my younger brother study for his SATs or proofreading my friends' essays. As I go through papers and questions and try to explain why certain things are more grammatically correct than others, I find myself saying things like "that's just how it is" or "you have to listen for it, it'll sound wrong." In the same way that parts of r and other computer languages have some sort of innate rules, so does the English language. 
 
The difference between English and r is that I already posess a fluency in English. This fluency allows me to manipulate the language, without unintentionally breaking the rules of the language. My lack of fluency in r, makes it difficult to use creatively because I can barely articulate the simple functions I would like it to run. 

One of the biggest differences I noticed between English and coding languages is that while there is technically a right and wrong in English, it is much easier to push those boundaries and change those rules. In code, those boundaries of right and wrong seem a lot more absolute and rigid. If someone writes with poor grammar unintentionally, their ideas are usually for the most part still comprehensible. Though their message may lose some of its credibility (a small aside: frankly this is dumb, and grammar is elitist because it privileges those who grew up with English as their first language and too heavily shifts the focus from content to fluency of medium which I don't think is always the point), it still exists. In some situations, it is acceptable to ignore certain conventions of grammar (texting, email, twitter all have their own rules). If enough people start speaking in a certain way or with a certain syntax, the English language can adapt to include that. In code, I don't think this is exactly the case. The creativity with code doesn't come from pushing against the boundaries, but rather discovering new ways to operate within them. 

The source of my unexpected symbol error message? A missing comma. A missing comma was enough to render all of my work essentially useless. A missing comma in an essay or a book or a poem could very well go entirely unnoticed by its audience. I think this might be one of the barriers to entry for those no accustomed to working with code. The idea that code either works or it doesn't reinforces the view of computer programming as black and white, even though there may be a huge range of gray in between the two.
 
 
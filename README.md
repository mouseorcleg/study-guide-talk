# Less effort, more learning: study guides with Claude
Most study advice assumes you learn like everyone else, with time you don't have.  
This talk is about using Claude to build a study guide that fits you.

### What you need to know beforehand
- your [learning style](https://www.learningstylequiz.com);
- your subject;
- your constraints.

#### Initial prompt
```
// What
I want to create an interactive study guide for my interview prep. 
I need a refresher on theory and actual coding exercises for Swift Testing. 
Make sure I would be able to use it offline, and it will persist my progress locally

// HOW
I prefer text over video or audio this time.
With a focus on writing tests manually and recalling how the main theory concepts work (KISS, DRY, etc.). 
I have access to an iPad and the Playground app. 

// CONSTRAINS
I will have 3-5 hours of preparation time over two days + a refresher bit around half an hour right before the interview. 
Note that I would not have access to the internet for a few hours of my prep time. 
So if you want to include an article in my study guide, it can’t be a link - you’ll have to download it in a nice format beforehand

Ask clarifying questions before you start, and confirm the plan with me before building.  
I prefer a clean girl aesthetic in my study guides. 
```

#### Additional prompt
```
Okay, coding on iPad is not the most comfortable. 
Let’s update practice for tests: for each task, I want you to create a coding setup, class/struct/protocol to test and the task written as a comment. 
Add a copy button so I can copy it with one click and paste in a new Playground file. 
And work solely there without switching back and forth. 
And make a test setup so I can get the assets there. 
Update the guide
```

The result: [01-Swift-Testing-Study-Guide.html](https://github.com/mouseorcleg/study-guide-talk/blob/2ea13d14ef48b3ad081edce844f9643bb83663bd/01-Swift-Testing-Study-Guide.html)
To preview: [https://raw.githack.com](https://rawcdn.githack.com/mouseorcleg/study-guide-talk/2ea13d14ef48b3ad081edce844f9643bb83663bd/01-Swift-Testing-Study-Guide.html)

P.S.: Take a learning style quiz during coffee break!

<img width="352" alt="link to https://www.learningstylequiz.com" src="https://github.com/user-attachments/assets/1460d4ce-7d27-40ba-ac8e-f7ad796c907d" />




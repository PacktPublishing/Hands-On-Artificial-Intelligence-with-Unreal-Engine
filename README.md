## [Get this title for $10 on Packt's Spring Sale](https://www.packt.com/B09594?utm_source=github&utm_medium=packt-github-repo&utm_campaign=spring_10_dollar_2022)
-----
For a limited period, all eBooks and Videos are only $10. All the practical content you need \- by developers, for developers

# Hands-On Artificial Intelligence with Unreal Engine

<a href="https://prod.packtpub.com/in/game-development/hands-artificial-intelligence-unreal-engine-4?utm_source=github&utm_medium=repository&utm_campaign=9781788835657"><img src="https://prod.packtpub.com/media/catalog/product/cache/e4d64343b1bc593f1c5348fe05efa4a6/b/0/b09594_mocku.png" alt="Hands-On Artificial Intelligence with Unreal Engine" height="256px" align="right"></a>

This is the code repository for [Hands-On Artificial Intelligence with Unreal Engine](https://prod.packtpub.com/in/game-development/hands-artificial-intelligence-unreal-engine-4?utm_source=github&utm_medium=repository&utm_campaign=9781788835657), published by Packt.

**Everything you want to know about Game AI using Blueprints or C++**

You can find the code files here: http://hog.red/AIBook2019ProjectFiles

## What is this book about?
Learning how to apply artificial intelligence ( AI ) is crucial and can take the fun factor to the next level, whether you're developing a traditional, educational, or any other kind of game. If you want to use AI to extend the life of your games and make them challenging and more interesting, this book is for you.

This book covers the following exciting features:
* Get an in-depth knowledge about all the AI Systems within Unreal Engine
* Create complex AIs, understanding the art of designing and developing Behavior Tree
* Learn how to perform Environmental Queries (EQS)
* Master the Navigation, Perception, and Crowd Systems
* Profile and Visualize the AI Systems with powerful debugging tools

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1788835654) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>

The code will look like the following:
```
void AMyFirstAIController::OnPossess(APawn* InPawn)
{
  Super::OnPossess(InPawn);
  AUnrealAIBookCharacter* Character = Cast<AUnrealAIBookCharacter>(InPawn);
  if (Character != nullptr)
  {
    UBehaviorTree* BehaviorTree = Character->BehaviorTree;
    if (BehaviorTree != nullptr) {
      RunBehaviorTree(BehaviorTree);
    }
  }
}
```

**Following is what you need for this book:**
Hands-On Artificial Intelligence with Unreal Engine is for you if you are a game developer with a bit experience in Unreal Engine, and now want to understand and implement believable game AI within Unreal Engine. The book will be both in Blueprint and C++, allowing people from every background to enjoy the book. Whether you're looking to build your first game or expand your knowledge to the edge as a Game AI Programmer, you will find plenty of exciting information and examples of game AI in terms of concepts and implementation, including how to extend some of these systems.

With the following software and hardware list you can run all code files present in the book (Chapter 1-14).

### Software and Hardware List

| Chapter  | Software required                   | OS required                        |
| -------- | ------------------------------------| -----------------------------------|
| 1 - 14   | Unreal Engine 4, Visual Studio      | Windows and Mac OS X               |

We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://www.packtpub.com/sites/default/files/downloads/9781788835657_ColorImages.pdf).

### Related products <Other books you may enjoy>
* Unreal Engine 4.x Scripting with C++ Cookbook - Second Edition [[Packt]](https://prod.packtpub.com/in/game-development/unreal-engine-4x-scripting-c-cookbook-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781789809503) [[Amazon]](https://www.amazon.com/dp/1789809509)

* Mastering Game Development with Unreal Engine 4 - Second Edition [[Packt]](https://prod.packtpub.com/in/game-development/mastering-game-development-unreal-engine-4-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781788991445) [[Amazon]](https://www.amazon.com/dp/1788991443)

## Get to Know the Author
**Francesco Sapio**
received his Master of Science in Engineering in Artificial Intelligence and Robotics degree from Sapienza University, Rome, Italy, a couple of semesters in advance, graduating with summa cum laude; he is currently a researcher at the same university.
He is an Unreal and Unity 3D expert, skilled game designer, and an experienced user of major graphics programs. He helped the development of many games (both educational and commercial). He is also an active writer on the topic of game development.
Finally, Francesco loves math, philosophy, logic, and puzzle solving, but most of all, creating video games—thanks to his passion for game designing and programming.

## Other books by the author
* [Practical Unity Game Development](https://prod.packtpub.com/in/game-development/practical-unity-game-development-video?utm_source=github&utm_medium=repository&utm_campaign=9781788837286)
* [Unity 2017 2D Game Development Projects](https://prod.packtpub.com/in/game-development/unity-2017-2d-game-development-projects?utm_source=github&utm_medium=repository&utm_campaign=9781786460271)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSdy7dATC6QmEL81FIUuymZ0Wy9vH1jHkvpY57OiMeKGqib_Ow/viewform) if you have any feedback or suggestions.

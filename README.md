# Hands-On Artificial Intelligence with Unreal Engine

<a href="https://prod.packtpub.com/in/game-development/hands-artificial-intelligence-unreal-engine-4?utm_source=github&utm_medium=repository&utm_campaign=9781788835657"><img src="https://prod.packtpub.com/media/catalog/product/cache/e4d64343b1bc593f1c5348fe05efa4a6/b/0/b09594_mocku.png" alt="Hands-On Artificial Intelligence with Unreal Engine" height="256px" align="right"></a>

This is the code repository for [Hands-On Artificial Intelligence with Unreal Engine](https://prod.packtpub.com/in/game-development/hands-artificial-intelligence-unreal-engine-4?utm_source=github&utm_medium=repository&utm_campaign=9781788835657), published by Packt.

**Everything you want to know about Game AI using Blueprints or C++**

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

With the following software and hardware list you can run all code files present in the book (Chapter 1-15).

### Software and Hardware List

| Chapter  | Software required                   | OS required                        |
| -------- | ------------------------------------| -----------------------------------|
| 1        | R version 3.3.0                     | Windows, Mac OS X, and Linux (Any) |
| 2        | Rstudio Desktop 0.99.903            | Windows, Mac OS X, and Linux (Any) |
| 3        | Rstudio Desktop 0.99.903            | Windows, Mac OS X, and Linux (Any) |
| 4        | Rstudio Desktop 0.99.903            | Windows, Mac OS X, and Linux (Any) |
| 5        | Rstudio Desktop 0.99.903            | Windows, Mac OS X, and Linux (Any) |
| 6        | Rstudio Desktop 0.99.903            | Windows, Mac OS X, and Linux (Any) |
| 7        | Rstudio Desktop 0.99.903            | Windows, Mac OS X, and Linux (Any) |
| 8        | Rstudio Desktop 0.99.903            | Windows, Mac OS X, and Linux (Any) |
| 9        | Rstudio Desktop 0.99.903            | Windows, Mac OS X, and Linux (Any) |

We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](Graphics Bundle Link).

## Code in Action

Click on the following link to see the Code in Action:

[Placeholder link](www.youtube.com/URL)

### Related products <Other books you may enjoy>
* Linux: Powerful Server Administration [[Packt]](https://www.packtpub.com/networking-and-servers/linux-powerful-server-administration?utm_source=github&utm_medium=repository&utm_campaign=9781788293778) [[Amazon]](https://www.amazon.com/dp/1788293770)

* Linux Device Drivers Development [[Packt]](https://www.packtpub.com/networking-and-servers/linux-device-drivers-development?utm_source=github&utm_medium=repository&utm_campaign=9781785280009) [[Amazon]](https://www.amazon.com/dp/1788293770)

## Get to Know the Author(s)
**Author Name**
Bio

**Author Name**
Bio


## Other books by the authors
* [Mastering Linux Network Administration](https://www.packtpub.com/networking-and-servers/mastering-linux-network-administration?utm_source=github&utm_medium=repository&utm_campaign=9781784399597)
* [Linux Mint Essentials](https://www.packtpub.com/networking-and-servers/linux-mint-essentials?utm_source=github&utm_medium=repository&utm_campaign=9781782168157)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSdy7dATC6QmEL81FIUuymZ0Wy9vH1jHkvpY57OiMeKGqib_Ow/viewform) if you have any feedback or suggestions.

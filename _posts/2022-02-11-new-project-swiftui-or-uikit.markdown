---
layout: post
title:  "New project: SwiftUI or UIKit?"
date:   2022-02-11 11:23:27 -0800
categories: iOS UI
---
The purpose of this post is not to discuss benefits of using one framework over another (there are countless of discussions about it already), but rather to focus on my thought process when deciding on UI framework used for my new side app.

Main reasons for my decision to use SwiftUI as main framework was:
- I could target latest OS release (hence use the latest API and not to worry about backward compatibility)
- I wanted to have "playground" to stay up-to-date with SwiftUI and latest releases of it
- Whenever I need functionality that is not supported by SwiftUI, I can easily embed UIKit components (which I am doing - I will talk about it in one of my other posts)
- My app is purely hobby app, unlike some enterprises that rely on stability of the API

I still feel WAY more comfortable with imperative UI over declarative, but the learning curve is not high to pick up basics of SwiftUI.
One challenge that I constantly run into, is what are proper patterns to build resuable SwiftUI components. Later in another post I will try to describe my process of building interactive Doughnut Chart visualization that can be seen here:

<img src="/assets/doughnut_chart.png" alt="chart" width="200"/>

So the bottom line is, I decided to go with SwiftUI purely as a learning process and getting out of my UIKit comfort zone. Let's hope I will not regret that decision ✌️.

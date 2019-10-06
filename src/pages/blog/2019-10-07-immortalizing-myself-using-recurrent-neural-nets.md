---
templateKey: blog-post
title: Immortalizing Myself Using Recurrent Neural Nets
date: 2019-10-06T19:27:20.218Z
description: How is this possible?
featuredpost: false
featuredimage: /img/afterlife_.png
tags:
  - natural language generation
  - deep learning
---




Have you ever wondered what would happen to your social media accounts when you die? Would they become desolate relics of what I once was, an inanimate wall of texts and memes incapable of witty responses. Could I change this?



I do post a lot on my facebook wall. Now given advances in natural language processing could I generate a faithful replica of myself? So thus begun my quest to create an replica of myself.

**Step 1) Extracting my Facebook Feed**



I had thought of scraping my Facebook feed for information but thankfully that was not necessary. Facebook offers the option to download all your social media posts since the time you registered and starting posting on their platform in your settings. Facebook sent me a link in my email to access the data. I downloaded it and used beautiful soup to extract the posts. Python makes this impressively straightforward to do. Soon a bunch of txt files emerged and the learning process could begin

**Step 2) Creating a Model**



I started the project with the interest in learning how to use and deploy pytorch on a webapp via flask or django (I went with django for the lulz). Using a really helpful tutorial I found here. I trained the model using a GRU (Gated Recurrent Unit) neural network with the model learning the relations between each ascii character. This was fairly straightforward. The learning process was highly amusing. The network managed to figure out that I use “XD” and “lol” idiosyncrasies in my speech



\    Training for 2000 epochs…

\    5%|██▊ | 99/2000 \[01:50<35:20, 1.12s/it]\[1m 51s (100 5%) 2.0344]

\    What gavely surs of a mell ball in the to the too ceducic thit is use.

\    I a made thing groce and to loo



\    10%|█████▋ | 199/2000 \[03:52<35:04, 1.17s/it]\[3m 53s (200 10%) 1.7711]

\    What is thim herk of the fantual to comvita vally clooves the dewter the level.

\    Action if isn’t on the



\    15%|████████▌ | 299/2000 \[06:07<34:52, 1.23s/it]\[6m 9s (300 15%) 1.7089]

\    Which where a rise videos and a discomment sounds pirm and harding of thought a saparate and for drick



\    20%|███████████▎ | 399/2000 \[10:10<40:48, 1.53s/it]\[10m 12s (400 20%) 1.6338]

\    Where you have lest in are internet undinows better the sculate.

\    Trolf I deftic in lower stortence hav



\    25%|██████████████▏ | 499/2000 \[13:56<41:55, 1.68s/it]\[13m 58s (500 25%) 1.6302]

\    What evento theirs greater main deally ok of a real needs that for sensulting metal are proper univer



\    30%|█████████████████ | 599/2000 \[17:54<41:53, 1.79s/it]\[17m 57s (600 30%) 1.6073]

\    Whimise all attarian designed to creatize lol fad simility.

\    It is always rideow with berobadant to do



\    35%|███████████████████▉ | 699/2000 \[21:28<39:57, 1.84s/it]\[21m 30s (700 35%) 1.5762]

\    Which get lay where locks that your’d or a more a been cour exists.

\    Why flaster tray… Ttthe power i



\    40%|██████████████████████▊ | 799/2000 \[24:44<37:11, 1.86s/it]\[24m 45s (800 40%) 1.5848]

\    Wh stumbers is the at rolloogener.

\    The of a stree of Joh has been herbing that we level away as the wo



\    45%|█████████████████████████▌ | 899/2000 \[27:11<33:18, 1.82s/it]\[27m 13s (900 45%) 1.5547]

\    When you can evolution of repeat how to learns not going to will be a big terman.

\    Speameas of a cool a



\    50%|████████████████████████████▍ | 999/2000 \[29:45<29:49, 1.79s/it]\[29m 47s (1000 50%) 1.5336]

\    When the natures generally determ.

\    The school me will be fire, the things out they online think to our



\    55%|██████████████████████████████▊ | 1099/2000 \[31:34<25:53, 1.72s/it]\[31m 35s (1100 55%) 1.5512]

\    Whind through this matter mires the adictfert analytics to staftch to kind of helps I saging work koun



\    60%|█████████████████████████████████▌ | 1199/2000 \[33:28<22:21, 1.68s/it]\[33m 29s (1200 60%) 1.5318]

\    Where is meaningp is if you predictics that the science to a piano to types with people when I almost



\    65%|████████████████████████████████████▎ | 1299/2000 \[35:49<19:19, 1.65s/it]\[35m 50s (1300 65%) 1.5231]

\    When what the succesing the not agre to the future to reproving our better, my forms in the armer beco



\    70%|███████████████████████████████████████▏ | 1399/2000 \[38:09<16:23, 1.64s/it]\[38m 10s (1400 70%) 1.5126]

\    Where of the A see is that the Singapore that the 50 past everything sapitally win the goms; change ag



\    75%|█████████████████████████████████████████▉ | 1499/2000 \[40:34<13:33, 1.62s/it]\[40m 35s (1500 75%) 1.5190]

\    What order to really do first produch this avauating the probably believe for the faintance snet job v



\    80%|████████████████████████████████████████████▊ | 1599/2000 \[42:46<10:43, 1.61s/it]\[42m 48s (1600 80%) 1.5219]

\    What you ever to be a children break from die from a fully responsion.

\    2) Ramposed that any assle.

\    It



\    85%|███████████████████████████████████████████████▌ | 1699/2000 \[45:00<07:58, 1.59s/it]\[45m 2s (1700 85%) 1.5298]

\    When so blue and history actually by a bug.

\    Autometic this controlling materials

\    When you are problem



\    90%|██████████████████████████████████████████████████▎ | 1799/2000 \[47:03<05:15, 1.57s/it]\[47m 5s (1800 90%) 1.4984]

\    When the probably imagine designed stere time from the truth of entisting to find a way of money don’t



\    95%|█████████████████████████████████████████████████████▏ | 1899/2000 \[49:01<02:36, 1.55s/it]\[49m 3s (1900 95%) 1.5166]

\    Who get the come is only bird book great for XD

\    I didnt be so claimp and memore a paint and this emani



\    100%|███████████████████████████████████████████████████████▉| 1999/2000 \[51:05<00:01, 1.53s/it]\[51m 6s (2000 100%) 1.5151]

\    What they are lived of restrorization.

\    Lol

\    All the family from emplies the think that either promial s



\    (I think the bot is retarded, but still impressive that it figured out word and some syntax just by learning relations between characters)



**Step 3) Creating and Deploying the WebApp**



Creating the WebApp was fun, who doesn’t like playing with css and html? Interfacing pytorch with django was straightforward during the development stage, you could simple import it as a package. However, deployment was not so fun. I had originally thought that deployment would have been straightforward and idiot-proof. I was quite wrong. Most of the complications came from pytorch you couldn’t just dump the dependencies into a requirements.txt and let it roll. Unfortunately, pytorch packages aren’t available on the python package index so automated installers in Elastic Beanstalk or Heroku won’t get it. I decided to create an EC2 instance and configure the server from scratch. Setting up nginx was confusing if you don’t do it often and are rather inexperienced with it, fortunately I found a nice walkthrough that guided me through the process. The link to the nginx tutorial can be found here. With some luck I eventually got the app to work.

**Conclusions**



The bot was not close to the ideal. Despite the lofty aspirations the bot turned out to be retarded. I was surprised that it figured out some grammar and words by learning relations between characters. That was impressive. Maybe there was not enough data? Maybe the training model could be improve. One thing is for sure, I will revisit this project sometime in the future and see how far this goes.

**Link To Repository**



https://github.com/JSeam2/ShitpostBot2000

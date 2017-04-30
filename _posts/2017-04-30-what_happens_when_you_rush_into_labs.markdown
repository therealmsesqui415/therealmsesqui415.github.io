---
layout: post
title:  "What happens when you rush into labs?"
date:   2017-04-30 12:36:43 +0000
---


Recently, I was working on the Mylittlerainbow lab apart of the CSS portion of the curriculum. Now, to most of you this might seem like a simple lab, and I too thought this at first. But apparently I have a hard time following instructions. And when you do, you end up with results such as this....

![](http://i.imgur.com/brip1av.png)

***WHAT IS GOING ON!?!?!*** 

My problem was that I was trying to insert the CSS text in the index.html file, instead of the style sheet, like an idiot... So I did a couple things like this:

```
<div> <!-- the grandest grandparent div -->
      <div id="red">
			#red {
			border-top-color: #f00;
			}
        <div>
          <div>
            <div>
              <div>
                <div></div> <!-- the grandest child div -->
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
```
Didnt work. Then I tried

```
<div id="red"> <!-- the grandest grandparent div -->
#red {
border-top-color: #f000;
}
      <div>
        <div>
          <div>
            <div>
              <div>
                <div></div> <!-- the grandest child div -->
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
```
Definitely did not work. (Had to ask myself, "why do you repeat the same mistakes?", once I found out what I was doing wrong...)

It wasnt until, I went back and carefully skimmed the directions like you should before you ever attempt any lab, that I found the mentioning of the main.css file was where we were supposed to be inserting the coloring information... So the moral of the story? ALWAYS READ THE DIRECTIONS FIRST!

![](http://i.imgur.com/6WeCTEY.png)

:)


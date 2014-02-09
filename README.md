My_Website
==========
This is just my first website.  I was playing around with learning git 
and also playing around with learning html and css.

It was fun.  It was informative.  Here are my reflections on the exercise:


Reflection:

1.  CSS and HTML can take forever to get what you want.  And I have an issue with wanting to get exactly what I want.     If I have a vision of something I can't stop doing it until it's done in the complete way.  This turned what         could have been a short challenge to the longest one yet.  At the end of it, I walk away having learned a lot        from working through the end until my vision was achieved.  I walk away from the exercise with a much better         understanding of CSS.  However, I have suspect that I have may have spent too much time on it.  And I know that      this quality of mine which gives me tunnel vision when I suddenly set out to do something, is not something that     will work in the real business world.  So I need to improve on this.

Lessons Learned in Building The Website:

1.  The concept of inline, block and inline-block is crucial to understanding how to build websites.

2 . For some reason I realized that a div with an image acts differently than a div with text even if everything is      inline-block.    I don't quite understand this, but it drove me wild for a long time.

3.  Even after you normalize or use a reset, there is some basic hidden styling, such as small margins that show up      between divs that will get in the way of lining up things right next to each other.  To fix this you can use a       negative margin to close that tiny gap.

4.  Centering things both horizontally and vertically can be done in a lot of different ways.  When it comes to          centering vertically is kind of a mess.  To do this you need to create a div within a div and then you can do        this a number of ways.  
    For example this works for two divs filled with text: 
    [Two text boxes line up straight]http://codepen.io/anon/pen/CGwgn
    
    But, if you fill one of them with an img the div with the text moves down for some reason, it doesn't line up.       And when I try to change the size it pushes down and not up.  
    Here is the text NOT in a new div: 
    [Text Not in Div but Not working]]http://cdpn.io/veshx
    
    and then even if you put the text in its own div, you still get the gap, like this:
    [Text in Div Not Lining up]http://cdpn.io/CpLbu
    
    I don't know what to do about this, but I found the only way for it to not do this was to float the second div to     the right.

5.  It's important to edit your photos so that they are not huge, but formatted for the web so that they don't take      forever to load.

6.  I have questions about how many divs is too many divs.  I found myself creating a lot of divs so I could then go     an adjust them in css.  Also I would adjust the regular h1 or h2 or a elements within a specific class of divs to     get it to act differently then it does in the rest of the page.  I'm not sure if this is a good practice or not.

  

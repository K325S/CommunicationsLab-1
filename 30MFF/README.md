# P A T T E R N S 

Patterns is a short film on the intersection of art and our everyday lives. As part of the 30MFF at NYUAD, Patterns stands to tell the story of repeated instances in our daily lives that we tend to ignore. A little on the melancholic side, it explores artistic ways of understanding space through what can be classified as unrelated instances. 

We draw inspiration from the patterned posters around the CommLab classroom to create a backbone for our narrative. These posters sit infront of us during every class yet we overlook them as part of a static setting while we continue with our dynamic lives. *When does other people's dynamic living become a static in our world?*

## Process:

After coming up with and presenting the 30MFF site during our first class, it was time to make a wireframe for our website. Since I knew the website would be mine, I chose the colour scheme and the complete visuals of the site to work off of when the code comes. Creating a wireframe might have been one of my favourite parts as the initial planning made what came next much easier. I took inspiration from the repeated circles and colours on the posters we used as the backbone for my website. 

Three overlapping circles for the navigation and a rectangular content block is all it took for the website. I wanted it to be creative and to tell the story of the film as a complement to the idea not an afterthought. Here is an example of the main page of my wireframe, all my pages follow the exact same distribution as I wanted the main focus to be on the film rather than the information. 

![Website Wireframe](wireframe.png "Homepage Wireframe")

As the coding started, it was fun yet frustrating to experiment with different settings and to find example code for the issues I encountered. CSS was much more of a hassle to breakdown than both HTML and JS. Styling the site came at the expense of serious positioning and centering therefore styling took the longest to create. I did, however, include and credit some open source code shared on the web to ease the workload for certain things such as the contact form. 

### Reflection:

Reflecting on the site, I faced NUMEROUS difficulties when coding. Whether the code was too long, too complicated, or just too restrictive and convoluted, I went over many questions on [StackOverflow](https://stackoverflow.com) and examples on [W3Schools](https://www.w3schools.com) to overcome them. 

#### Main Difficulties: 

- When creating the wireframe, I did not think that overlapping navigation circle would be a problem. Soon to find out, positioning might be one of the most difficult things I had to work around.
- Figuring out whether FlexBox or Table was more beneficial in position.
- Making a responsive and dynamic sizing of the page to respond to different window sizes. `vw` and `vh` were extremely benificial here.
- Margins and paddings were very confusing to figure out.
- Centering items was also extremely difficult. `align-items: center` and `justify-content: center` were not that beneficial at times, so I had to resort to padding and margins. 
- Overflowing content had to be restricted, but sometimes hiding it was unnecessary as the information was still important. `overflow: scroll` helped tremendously here. 
- Although I referenced [W3Schools](https://www.w3schools.com) for the animated tab gallery, their code seemed to not work with mine. It distorted my divs and containers, therefore playing with that was very difficult. 
- The expanding image would not expand for a whole day until I figured out the importance of function naming. 

#### Main Verdict: 

Once I completed my site and was killed and reborn many times on this journey, I wanted to figure out a solution that would rid me of the convoluted coding systems and the misalignment of my rectangular div to my circle navigations, which were my main issue. While searching on how to make custom shapes on websites, I came across an html tag called svg. Now, what makes `<svg>` particularly helpful, is that I am able to copy the svg code from Adobe XD to extract the shapes I made. I tried to play around with it yesterday and it really minimised the code drastically as the whole background was taken care of. However, since I already finished my site previously, I did not give this experimentation enough time. I did find it difficult to place my text over the svg but I think with a little maneuvering I would solve it. This finding will be very helpful in future web development, but for now it is a very fun quirk and code hack I found. 

# CSS-animation
# Basic of CSS
CSS3 can make whatever kinds of animation you want.

Basically, you know the normal form of CSS language :

div {
  font-color : #FFF
}


this is a sentence that make the text in div tag white-colored.

div {                      <- this is the part that you want to decorate(1)
  font-color : #FFF        <- this is how you decorate the part.
}

the object you want to decorate,
 - if it's just plain text, it is the name of the tag;
 - if it starts with .(dot), it is the class of the tag;
 - if it starts with #, it is the id of the tag.
 
# Animation

I explained the object you want to decorate can be started with different signs.
Have you ever seen it starts with "@"?

Normally it is "@keyframes animation-name"
It will be used as the name of a animation.
before this, we need a "animation" attribute in the object you want to move.

div {
  animation : animation-name 3s linear infinite
}

@keyframes animation-name {
  0% {top: 20%; left: 50%;}
  33% {top: 80%; left: 84.5%;}
  66% {top: 80%; left: 15%;}
  100% {top: 20%; left: 50%;}
}

This is the simple form of CSS3 animation.
Can you guess what this animation does?
it makes the div object moves in a form of triangle.

The attribute there was "top, left" only.
but you can try it with all different attributes to make it move.
color, width, text-style, whatever you want.
You should try yourself to learn more!

the end




# Entry 4

<h1>Tool(wow.js)</h1>
 2/26/24

### Wow.js context 

<P>My tool i decided wow.js.For my blog4 entry Wow.js is a website that has anitmations for your style.CSS. When you choose the animation you want that won't be the set animation. When you pick the animation you can customize how ever you want. I'm talking like tyle, delay, length, offset, iterations. I think this is very useful because if none of the animations is for you you can go here cause it has tons of animations for you to choose from.
</P>

### Tinkering 

i Tinkerd with wow.js in github by making a new repository and adding CSS with some animations with wow.js.
```language
return DefaultTextStyle(
  style: const TextStyle(
    fontSize: 20.0,
  ),
  child: AnimatedTextKit(
    animatedTexts: [
      WavyAnimatedText('Hello World'),
      WavyAnimatedText('Look at the waves'),
    ],
    isRepeatingAnimation: true,
    onTap: () {
      print("Tap Event");
    },
  ),
);
```



[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)

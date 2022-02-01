 # This is a random Code project name generator!

Have you ever gone on sites like replit or code sandbox and wondered how they generated the names? This is not exactly how, but it generates the same results.

# How do I use it? 

```html
<script src="https://cdn.jsdelivr.net/gh/RoboSapiens2021/random-code-project-name-gen@main/index.js"></script>
```

All you do is put this script in your body tag.

After you do that, you can run 

```Javascript
console.log(rand())
```
in your own javascript file. It will print out something like this:

`cutting-breath-658 
`
 #### What goes on inside? 
`RandomWord + - + RandomWord + - + RandomNumber + RandomNumber + RandomNumber`

Great! 

The 
`
rand()
`
function returns a random name. 

If you want to set the name to a variable, you can do it like this:

```Javascript
var randName = rand();
```
`randName` is set to a random name, but will stay the same until the website is reloaded. Because of this, running 

```Javascript
var randName = rand();

console.log(randName);
console.log(randName);
console.log(randName);
console.log(randName);
```
will return the same name four times. 

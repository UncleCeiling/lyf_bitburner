# The function 'main'

> Bitburner executes your script [`hello-doc-multiline.js`](/01%20Hello%20World/03%20Any%20comments?/hello-doc-multiline.js) starting from the line:

[`hello-doc-multiline.js`](/01%20Hello%20World/03%20Any%20comments?/hello-doc-multiline.js)

```javascript
export async function main(ns) {
```

> This is the function `main()`.  
> Don’t worry yet about the segment `export async function` or the `ns` between the parentheses.  
> We will come back to it later in the tutorial.  
> All you need to know for now is `ns` is a parameter of `main()` and `ns` encapsulates all functions defined by Bitburner for you to interact with the game.  
> The functions defined by Bitburner are collectively called the [Netscript API](https://github.com/bitburner-official/bitburner-src/blob/stable/markdown/bitburner.ns.md), which is separate from the standard [JavaScript API](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference).  
> Your code is to be inserted at the place shown below:

[`template.js`](/01%20Hello%20World/04%20The%20function%20'main'/template.js)

```javascript
/**
 * Explain what the function is trying to accomplish.
 *
 * @param {NS} ns The Netscript API.
 */
export async function main(ns) {
    // Insert your code here.
}
```

> The opening brace `{` delimits the start of the function `main()`. The ending brace `}` delimits the end of the function. Your code goes between the opening and closing braces.

## Exercise 1

> You might have guessed that the function `ns.tprint()` is Bitburner’s way of allowing you to print a message to the terminal.  
> Let’s use the function to output a different message to the terminal. Copy the code below to another script, say `intro.js`.  
> Run the script from the terminal.  
> What is printed to the terminal?

[`intro.js`](/01%20Hello%20World/04%20The%20function%20'main'/intro.js)

```javascript
/**
 * Introduce myself.
 *
 * @param {NS} ns The Netscript API.
 */
export async function main(ns) {
    ns.tprint("I'm Byte, the Bitburner bot.");
}
```

___

📜 [`intro.js`](/01%20Hello%20World/04%20The%20function%20'main'/intro.js)

```log
intro.js: I'm Byte, the Bitburner bot.
```

## Exercise 2

> Edit the script `intro.js` so it would print your name when executed.

___

📜 [`intro-name.js`](/01%20Hello%20World/04%20The%20function%20'main'/intro-name.js)

```log
intro-name.js: I'm Chris.
```

## Exercise 3

> Modify your script from the [previous exercise](#exercise-2) to also print your favourite food.

___

📜 [`intro-food.js`](/01%20Hello%20World/04%20The%20function%20'main'/intro.js)

```log
intro-food.js: I'm Chris.
intro-food.js: My favourite food is: the edible kind
```

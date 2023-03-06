### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.
```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (!hungry) {
    return console.log("Wait until you are hungry.");
  }
  if (availableTime > 30) {
    console.log("This is an intense program after all and you should probably reconsider");
  } else if (availableTime >= 20 && availableTime <= 30) {
    console.log("You deserve a break and should take time to cook a tasty meal.");
  } else if (availableTime < 20) {
    console.log("Pick up a snack or grab something you have ready at home.");
  }
};

# module4-solutionjs
This JavaScript code iterates over an array of names through checking conditions if a name start with J or j to  display GoodBy name display to display hello name otherwise.

const names = ["Joby", "boby", "james", "Alex"];

for (const name of names) {
  const firstLetter = name.charAt(0);
  if (firstLetter === "J" || firstLetter==="j") {
    console.log(`Goodbye ${name}`);
  } else {
    console.log(`Hello ${name}`);
  }
}

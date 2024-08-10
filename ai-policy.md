<script setup>
    import HowManyYearsAgo from "./components/HowManyYearsAgo.vue";
</script>

# AI Policy

###### Every SHEEP class has an AI policy.

## Can I use AI?

**Yes and No**. The problem with Programming and AI is that we live somewhere between the absolutes.

### Use AI

You can use AI to answer questions about code, get code snippets, understand what you are doing, and generally help you. Give it the text from your errors and ask why it is happening. Use AI to generate images for projects and presentations. Ask AI to give you hints and creative ideas, or help troubleshoot a problem.

### Do Not Use AI

Do not use AI to build applications for you or complete your homework.

This requires further explanation.

We usually start every program in class, together. While you may ask AI to help you with problems or ideas, we require that you use our code from class.

For example, imagine a project where we are building a dice simulator. In class, we come up with this code:

```js
class Die {
	constructor(faces) {
		this.faces = faces;
	}
	roll() {
		return Math.floor(Math.random() * this.faces) + 1;
	}
}
let rollMyDice = function (dice) {
	return dice.map((die) => die.roll());
};
let myDice = [new Die(6), new Die(12)];
console.log(rollMyDice(myDice));
```

Students will be asked to build on this, perhaps to make a rendition of the classic game Yahtzee. If a student asks an AI to complete the code or write a game of Yahtzee for them, It's usually obvious that they used AI. If we see the markers, we will assume 100% of your code was written by AI.

---

Programming today is in a difficult place with AI. On one hand, it seems as though AI can replace all of the thinking that a programmer may need. On the other hand, our class requires that students use their head and their hands to do the work because we need them to learn the code for their personal mental growth.

While an AI chatbot may understand how to finish assignments in our class, a professional career in IT requires that the _human_ understands.

## Why not?

Using AI to complete assignments means the student does not learn the material, so in a sense, this is a form of cheating, and it steals the growth that a student should experience.

_Computer Coding and Programming_ is a challenging class, meant to force a student's brain to grow in new ways. This produces long-term change, increasing their intelligence for life, and teaching them how to think logically. Using an AI assistant to get past a hard project takes away any growth they might have.

## What if I get stuck?

I will mention this about 100 times throughout the school year: **Ask Me** (Mr. Nathan). I have the answer to every coding problem you can come up with. I've been coding since before you were born. I'm an expert. I want to solve your problems. I want to help you succeed. I don't want you to be frustrated.

-   [How to ask for help](how-to-ask-for-help)

## What if I use AI to do my homework anyway?

Please attribute which AI was used when turning in your code, with a percentage of how much was written by the AI assistant. Your code will be marked down by half of that value. The percentage may be calculated by amount of code, or by complexity of code, on the teacher's discretion.

In a 100 point assignment, if 100% of your code was written by AI, your maximum point value is 50. This is better than zero points, but is still a failing grade.

In a 20 point assignment, if 50% of your code was written by AI, your maximum point value is 15 points.

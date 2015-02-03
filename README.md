# REACTO: BossFight.js

You're creating the final level of the role playing game, Final Stackery 7. Implement an object-oriented Javascript based 'final battle scenario', where your hero, Stacky, fights against the boss, the Evil Lord Exception. Simulate 100 battles, and determine how often your hero would win as well as how often the boss would win.

Heroes and bosses should have the ability to have health, attack for a certain amount of damage, and dodge (where their opponents would fail their attacks a certain percentage of the time).

Your hero, Stacky, should have the following abilities/properties:
```Health: 60HP,
	Attack: -8 HP from opponent,
	Dodge: Dodges attacks from opponents 50% of the time```

The boss should have the following abilities/properties:
```Health: 100HP,
	Attack: -12 HP from opponent,
	Dodge: Dodges attacks from opponents 10% of the time```

<b>Extra Credit</b>: Your hero finds the [Sword of Refactoring](https://www.youtube.com/watch?v=OBtsMTnstZM)! They now have a special attack, which means that 25% of the time, their attacks hit for 1/5 of the boss's health <i>(eg, if the boss's health is 100HP, your hero's attack will -20HP from the boss)</i>. Implement this method in your solution, but only have your hero Stacky use it if it's beneficial to do so.
# friday

Friday can perform several functions and has a unique personality:

1. If you say "hi," "hello" or "howdy" to friday he/she/it will respond very enthusiastically by randomly accessing an array of several greetings.

2. Friday is more insecure than you would think considering he/she/it is a robot, and really just wants to fit in. If he/she/it hears a "lol" or "haha" friday will invariably want to join in on the fun even if he/she/it doesn't get the joke (and he/she/it never really does). Friday will chime in with a random abbreviation for laughter stored in an array called lulz.

3. Curiously, friday does not like bees. If anyone mentions the word "bee" or even if friday thinks he hears "bee" (such as "please BE on time" or "BEEtlejuice Beetlejuice Beetlejuice") it makes friday uncomfortable and he/she/it will choose a way to express his/her/its feeling about bees by picking randomly from an array called beeReactions.

4. Friday can also summon the wisdom of the great Jedi Warrior, Yoda. If anyone uses the word "try", friday will say "Do or do not. There is no try".

5. Friday can tell you the capital of any US state. If you ask friday, "what is the capital of [insert name of state]," he/she/it will capture the state you request with res.match[1] and store it in a variable ("state"). Friday then iterates through an array of 50 anonymous objects that contain the name of each state and it's corresponding capital city. If the inputed state matches the property of an object, friday will return the answer to the question (e.g. "The capital of Utah is Salt Lake City").

6. If you'd like to see a gif of some nature beauty, you can command friday to "nature me" and friday will randomly select a beautiful nature gif from an array of gif links from giphy.com.

7. You can also have friday send any member of the slack channel a kitten gif. The command is "kitty @[insert username]." Friday will capture the username and store it in a variable, select a random link from an array of kitty gifs and send that while mentioning the user.

8. You can also order food from friday. There is an array of objects that represents the menu. Each object contains the food item name and a corresponding gif. The menu is space themed. You can ask friday to list what's available and he/she/it will reply with a list of food items like "Space tacos." If you'd like to order a food item you can say "I'll have the/[insert food item]" and friday will iterate through the menu, match the food item, and send the corresponding gif.

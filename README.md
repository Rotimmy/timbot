# friday

Friday can perform several functions and has a unique personality:

1. If you say "hi," "hello" or "howdy" to friday he/she/it will respond very enthusiastically by randomly accessing an array of several greetings.

2. Friday is more insecure than you would think considering he/she/it is a robot, and really just wants to fit in. If he/she/it hears a "lol" or "haha" friday will invariably want to join in on the fun even if he/she/it doesn't get the joke (and he/she/it never really does). Friday will chime in with a random abbreviation for laughter stored in an array called lulz.

3. Curiously, friday does not like bees. If anyone mentions the word "bee" or even if friday thinks he hears "bee" (such as "please BE on time" or "BEEtlejuice Beetlejuice Beetlejuice") it makes friday uncomfortable and he/she/it will choose a way to express his/her/its feeling about bees by picking randomly from an array called beeReactions.

4. Friday can also summon the wisdom of the great Jedi Warrior, Yoda. If anyone uses the word "try", friday will say "Do or do not. There is no try".

5. Friday can tell you the capital of any US state. If you ask friday, "what is the capital of [insert name of state]," he/she/it will capture the state you request with res.match[1] and store it in a variable ("state"). Friday then iterates through an array of 50 anonymous objects that contain the name of each state and it's corresponding capital city. If the inputed state matches the property of an object, friday will return the answer to the question (e.g. "The capital of Utah is Salt Lake City").

  Unresolved issues:
    a. Allow user input to not be case sensitive (ie utah and Utah)
    b. Allow user to use question mark

6. If you're feeling restless and would like to see some natural beauty, you can command friday to randomly select a beautiful nature gif from an array of gif links from giphy.com for you.

7. You can also have friday send you or any member of the slack channel a kitten gif. Just command "kitty [input]." Friday will capture your input and see if it matches the name of a user in the channel. If it does, it will send that user a kitten gif. If it does not, friday will check if your input is "me" (ie "kitty me"), and if it is friday will send you a kitty gif. If your input is not you or a member of the channel, friday will respond "I don't think [input] is in this channel."

8. You can also order food gifs from friday. There is an array of objects that represents the menu. Each object contains the food item name and a gif url. The menu is space themed. You can ask friday, "What's for (lunch|dinner)," and friday will reply with a list of food items like "Space tacos." If you'd like to order a food item you can say, "I'll have the [insert food item]" and friday will iterate through the menu, match the food item, and send a gif of the food item.

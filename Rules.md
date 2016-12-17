<link rel="stylesheet" href="Rules.css">
<meta charset="utf-8">

Monopoly Two (2.3)
==================

This guide is written with the classic Monopoly in mind. Terminology and units will change depending on the version you are playing.

This is a work in progress and changes will likely be made, if I can get people to play-test with; playing Monopoly is generally not something a lot of people care to do.

The rules of Monopoly 2 are the same as in the original game but with the following exceptions.

How Many Players
----------------

The game does not work with 2 people. It probably only works with 3-6 players. [^players]

Win Condition
-------------

The game is won, when a player gains 5 monopolies or is the only player remaining, although that is an unlikely scenario to occur. In the rare event that multiple players gain 5 monopolies simultaneously, the player with the highest total value of all assets wins. If those are equal, it is a draw between those players.

Money
-----

All monetary values are rounded up to the nearest £5. [^Nearest5] Thus when the starting money is dealt to players an additional £5 note can be given instead of 5 £1 notes, as they are no longer needed. [^1pounds]

Buying Properties
-----------------

Players can not purchase any properties by landing on them, unless a Chance or Community Chest card states that they can. Auctions do not exist.

The title deed cards are shuffled and placed face down on the board. The top 4 cards are turned over and placed face up on the board. During a player's turn, they can choose to purchase at most one of these face up properties for the price printed on the board. When one is bought, another title deed is turned over to replace it, until the deck is empty.

Movement and Dice Rolling
-------------------------

During a player's turn, they must roll 2 six-sided dice, then they choose a player to move that distance along the board. The player being moved receives any effects of the space they land upon. If no player is eligible to move, no player is moved. [^MovementStrats]

Rolling a double has no effect.

Chance and Community Chest Cards
--------------------------------

All players start with 1 Chance and 1 Community Chest card in their hand.

When a player lands on a Chance or Community Chest space, all players draw one of that card from the deck. If there aren't enough cards in a deck for all players to draw at once, the discard pile is shuffled; enough cards to bring the number of remaining cards up to the number of people trying to draw are taken from the shuffled discard pile and put into the deck. The deck is shuffled; the cards are drawn; and the remaining shuffled discarded cards become the new deck. This is so that it can't be known who's received a recycled card from the discard pile.

Chance and Community Chest cards do not have to be used immediately. They are kept by players and do not have to be shown to others until they are played. During a player's turn, they can activate any number of Chance or Community Chest cards from their hand on any player. The player they choose to play the card on receives that card's effects.

Chance and Community Chest cards have no value and must not be exchanged, gifted, or sold. [^CCCValue]

Buying Houses and Hotels
------------------------

A single House or Hotel purchase affects an entire monopoly. Houses and Hotels are placed in the middle of a run of properties to indicate that they apply to the entire monopoly. [^HHPlacement]

Trading
-------

There is no direct trading or haggling. During a player's turn, they may buy any un-monopolised property that another player owns from them for 1.5 times its board price. [^stealing] [^trading]

Re-selling and Payment
----------------------

Owned property and buildings can not be sold back to the bank. Buildings and property are treated as an indivisible units of currency.

If a payment is to be made, a player can pay with a combination of cash and properties. Change can be given by the payee (bank or player) up to the amount of money given in the transaction. [^change] If a payer overpays by this method, it does not matter as far as the rules are concerned.

Any properties returned to the bank are placed at the bottom of the title deed deck.

Properties can not be exchanged in this way if any buildings are built upon them, but they can be exchanged if they are part of a monopoly.

Only in the event of making a payment can buildings be used in a transaction. All buildings are worth the amount used to buy them. When exchanging a Hotel, it can be exchanged for Houses on that monopoly at the same time. The value of a hotel equals `(5 - the_number_of_houses_replacing_it) * the_value_of_a_house_on_that_monopoly`. [^SellingHotels]

When a Hotel/House is received in a payment, it must be exchanged with the bank for the amount of money that it is worth. [^clarification]

Jail
----

Players can only be sent to Jail by landing on "Go To Jail" or by having a "Go To Jail" Chance or Community Chest card played on them.

When in jail, a player will still be paid money by every usual means, however:

* Their token cannot be moved;
* they can not roll the dice for movement;
* they can not buy property;
* they can not collect money from players landing on their property
* they can not play Chance or Community Chest cards, except for a "Get out of Jail Free Card";
* they can not draw Chance or Community Chest cards;
* they can roll 2 dice on their turn with the effect that if they match, they become "Just Visiting" and can continue their turn like a normal turn;
* at the end of a second turn in Jail, they become "Just Visiting".

None of these effects apply while "Just Visiting".

Player's can not pay money to leave Jail.

If a player goes to Jail during their own turn, their turn immediately ends and does not count towards the maximum of 2 turns in Jail.

Mortgages
--------

Properties can't be mortgaged.

Free Parking
------------

Technically I don't have to mention that nothing happens when you land on Free Parking as it's already an official rule. I don't think all money paid by Tax, Chance, and Community Chest should put on Free Parking to be collected by anyone who lands on it. The high number of Chance and Community Chest cards played will keep the pot quite large, meaning that someone landing on it will swing the game too much. Players will also be keen to make sure no one stays near it for too long, increasing the size of the eventual payout.

Summary of Reasoning
--------------------

Some reasoning is provided in footnotes, but here is a general idea about what I was trying to achieve.

The game of Monopoly needs to be improved by:

* it ending sooner;
* it being more strategic.

Aspects of the game that would happen eventually but would take a long time now take place quicker:

* buying buildings on all properties in a monopoly;
* having all the properties bought;
* all properties being grouped into monopolies;
* properties changing ownership.

Aspects of the game that weren't very strategic now require more thought:

* applying the effect of a Chance or Community Chest card the moment it was picked up
* all movement being random
    - not controlling what you have the chance of buying (we can ignore auctions because everyone knows it's a bad idea to cause one to happen);
    - not controlling the likelihood of your properties being landed on

Potential Changes to the Changes
--------------------------------

The following ideas are untested, so I can only speculate about whether they'll improve the game.

* Houses and Hotels apply to individual properties instead of Monopolies, but make them much cheaper (perhaps something like 20, 40, 60, 80 instead of 50, 100, 150, 200). Then when a property is used in a transaction, the value of its buildings could be taken into consideration, and then the complicated rules around selling buildings only in certain scenarios won't be a thing. The problem with this is that it might discourage buying houses because you've got bigger indivisible units, so there will be a greater loss if you don't maintain a larger monetary buffer.
* A building used in a transaction can be put on a property of the recipient and is valued at however much it's worth on the property they put it on. If they don't have anywhere to put it, they get the money for it from the bank the way they do now. The problem with this could be that the receiver has to decide how much it's worth, making it harder and take longer for the payer to decide in what materials they'll pay.
* The number of Chance and Community Chest that a player can hold at once should have a maximum limit in order to prevent hording of situational cards such as "Advance to Mayfair", which can only be really bad in someone else's hands and really good or mediocre in yours. This would also force people to make decisions early about who to make lose money, instead of saving them for when they take someone's money and need to hit into their properties. It's most advantageous surely to not neg people money by these small amounts until they're in that point. This hasn't been tested yet but will almost certainly be added in some way.
* The number of buildings you can buy on each Monopoly per turn should be 1. This will mean that it's not possible to throw all of your money into buildings with no risk. There shouldn't be significant risk to building. I think this change makes it so that massive payouts don't happen too early once one monopoly has been achieved before the natural inflation due to cards and passing go has happened. This hasn't been tested yet but will almost certainly be added in some way.
* Preventing a player from being moved twice in one turn should help prevent a player from being hit multiple times with the likes of various movement cards that are very powerful when used in succession. It would be an illegal move to make it so that nobody can be moved by a dice roll. This can always be avoided.

Footnotes
---------

[^players]:
    The game is usually 2-6 people. So ruling out 2, it's 3-6. Who played it with 2 people before anyway? It was even less fun.

[^Nearest5]:
    If it wasn't obvious, rounding a multiple of 5 up to the nearest 5 keeps it the same.

[^1pounds]:
    How useful were they ever? They've just been a nuisance all this time. I thought to get rid of them before remembering [John Green's tirade against pennies](https://www.youtube.com/watch?v=77C47XYm_3c). Money exists in order to facilitate commerce, but Monopoly's £1 note doesn't do that it *dificilitates* it. If we want Monopoly to last a reasonable amount of time we have to look at the opportunity cost of things players have to do, and every moment people spend fiddling with £1 notes or exchanging 5s for them at the bank is a moment on for which the game drags.

[^CCCValue]:
    I'm not 100% sure about the fact that they can't be exchanged. But I am firm about them having no value. There is no bartering with other player's built into this game, so allowing this would be the only exception.

[^MovementStrats]:
    It is beneficial to move yourself to increase the frequency with which you pass Go. And it is beneficial to move other players when you know that they will land somewhere detrimental to that player.

[^HHPlacement]:
    I'm not certain whether instead each property should gain a House/Hotel when one is bought, instead of putting them in the middle. The difference here is that this alternative will run out of houses or hotels if too many are built. However it is much fiddlier to add and remove them as needed, which happens frequently.

[^stealing]:
    I feel like buying it for double the price makes it too difficult to complete monopolies in a timely manner. Previously required an amount equal to the board price.

[^trading]:
    A lot of people will think this is an awful change because that's kind of what the game was largely about. However the problem is that once a property is bought, its value sky-rockets because everybody knows how much they are worth later on in the game, and so there is a lot of refusal to trade and shouts about how "you mustn't let them have that or they're guaranteed to win". People are stubborn especially when they are keen to win. This wastes time and is not fun for other players waiting for their turn.

[^change]:
    This one might take a little bit of thinking. It basically means that you only get any monetary change if you paid with money. It's written so that you don't pay a £300 sum with a £400 property and a £5 note and demand £105 change because you paid in part with money.

[^SellingHotels]:
    There should always be at 4 houses to replace a Hotel in the box because monopolies share buildings and fewer are needed. But this information will be crucial if the rules change such that all Houses can be used up.

[^clarification]:
    If it wasn't clear: This money will not be given in change and it can cause a payer to over-pay.

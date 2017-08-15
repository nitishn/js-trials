# Code Learnings

# JavaScript!

-  **Deck of Cards** 

    01/19/2017

    Create a JS program without ES6 classes representing a deck of cards. Use the following closure to finish the deck of cards instance. At the end of this exercise, please explain why JS closures are important. Please use [https://jsbin.com/?html,output](https://jsbin.com/?html,output) or [https://jsfiddle.net/](https://jsfiddle.net/) to submit your solution. 

    Note: You can use any internet resource to look up functions. Just don't look up "how to implement a deck of cards in JS". For example, you may look up "how to shuffle an array in JS". 

        var Deck = (function() {
        
        return { ... };
        
        })();

     **I should be able to…** 

    1. Create an array representing a deck of 52 cards. The deck should have 4 sets of [A, K, Q, J] and 4 sets of [2 to 10]. Don’t worry about suits.
    2. Shuffle the deck so the cards are randomized.
    3. Cut the deck in half.
    4. Deal a card from the top of the deck (this should remove the card from the deck and display to screen/console).
    5. Deal a card randomly from the deck (this should remove the card from the deck and display to screen/console).

    So function calls should look something like this…

        Deck.create();
        Deck.shuffle();
        Deck.cut();
        var card = Deck.deal();
        var card = Deck.dealRandom();

     **I should NOT be able to…** 

    1. Access and modify the internal cards array directly.
    2. Access any internal functions.

    So I **shouldn’t ** be able to do something like this…

        console.log(Deck.cards) // This should output "undefined"

     **CHALLENGE ROUND** 

    Do not use the following iterators

    1. for
    2. forEach
    3. Array.prototype.forEach


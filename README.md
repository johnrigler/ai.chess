# ai.chess

This project is a use case for a natural language system
which is used to create a public blockchain index. Each of the
files is a bash function. Some represent moves in a chess board
and some are simply the toolkit I use to make the moves. 

Each move should be included in an EVM smart contract. The
way that I play this is probably not the way someone else
would. 

The first move is always represented by the file:

chess-630124433.0

The contents of which represent a chess board visually.

chess () 
{ 
    : 01 02 03 04 05 06 07 08;
    : 09 0a 0b 0c 0d 0e 0f 10;
    : 00 00 00 00 00 00 00 00;
    : 00 00 00 00 00 00 00 00;
    : 00 00 00 00 00 00 00 00;
    : 00 00 00 00 00 00 00 00;
    : 11 12 13 14 15 16 17 18;
    : 19 1a 1b 1c 1d 1e 1f 20
}

The way I play this is to first set n=0 on the shell
and then run the a.chess command. It opens a vim editor
and I carefully erase the piece from one place and
add it to another. 

This project has lots of room for programmers to interact (and
even represent the board) in a different way. Each move could
also be passed to an AI that could play again a person or another 
AI. 

Because I can prototype this environment very quickly, I can then
focus on a smart contract system that not only make note of each
move, but all an on-chain search engine to quickly find entries
where a new person wants to play. If two real people connect via
the ledger, then they can play, or an AI can watch and then
play against a person.

I am most interested in new AI technology where the computer 
plays more like a person, and can even be beaten.

But as I said, one of my driving motivations is to create an 
onchain way for people to find people. I met one of my greatest
collaborators, Matthew Ready, because we were both sending
messages into the bitcoin.sv (Satoshi Vision) ledger.

This is an opportunity for AI to safely interest with people, with
other AI, and the flex the power of new and exciting AI-as-a-service
offerings such as AlphaZero Chess 

https://beta.singularitynet.io/servicedetails/org/snet/service/zeta36-chess-alpha-zero

Thanks 


Cheers



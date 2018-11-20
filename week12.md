## What did you do this week？
Recap some dat concepts.

Learned how Indexed Bitfield works.

Learned the relationship between data, tree and signature files.

Learned [pub(crate)][https://stackoverflow.com/questions/41666235/how-do-i-make-an-rust-item-public-within-a-crate-but-private-outside-it]

Learned returning instance itself from method can introduce chaining.

Recap Digital signatures.

Learned [rust benchmarks][https://github.com/japaric/criterion.rs]

Red [Overcoming Intuition in Programming][https://amasad.me/intuition]

Learned [thunk][https://stackoverflow.com/questions/35411423/how-to-dispatch-a-redux-action-with-a-timeout/35415559#35415559]

Learned [nodejs event-loop][https://nodejs.org/en/docs/guides/event-loop-timers-and-nexttick/]

## What are you planning to do？
Dive into datproject once again!

## questions

From [#indexed-bitfields][https://datprotocol.github.io/book/ch01-02-bitfield.html#indexed-bitfields], 

> Checking if we have a piece of data is straightforward, as all we have to do is look in the 
> bitfield in the position of the data and see if it's a 1.

Does one data correspond to one position? Yes, here data relates to every single data entry.

Because secret_key must not be exported, setting it alone. Is that right? secret_key is only available on Hypercores you've created.

When and where does sign and verify occur? sign: https://datprotocol.github.io/book/ch01-02-merkle-tree.html#merkle-trees-in-theory

Detailing reason for using merkle tree instead of a whole bunch of data?

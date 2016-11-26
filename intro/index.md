Introduction
============

Rust is a language developed at Mozilla Research. The goal is to offer
a system language with a safe memory model, and with concurrency in
mind. Coming from Mozilla you can imagine what would be their use case
for Rust: a parallelisable and memory safe web engine.

But Rust isn't easy to learn, as the language goes far into specifying
behaviour in order to make sure bugs are avoided as early as
possible. My experience learning it meant that I spend a lot of time
figuring out how to get my code compiled, because the compiler needed
to know more to protect us from ourselves.

With all of that in mind, I feel like Rust is made to be used
everywhere C or C++ is used, and even more.

And here come GNOME. I'm convinced that GNOME has to play an essential
part in the future of computing. And to make sure it does, I'm certain
that Rust has a lot to bring so that we can write application that are
more secure, while still maintaining high performance.

This is what that guide tries to provide: a comprehensive developer
manual for developing in Rust for GNOME. It will try to cover
important topic from the bindings, FFI, build system and even
progressive rewrite. That last part is probably what has to happen,
because rewriting your code all at once will never be.

I'll try to keep that book collaborative. Feel free to submit changes.

Montreal, November 2016.

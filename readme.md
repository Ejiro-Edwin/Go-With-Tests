## Software

The promise of software is that it can change. This is why it is called _soft_ ware, it is malleable compared to hardware. A great engineering team should be an amazing asset to a company, writing systems that can evolve with a business to keep delivering value.

So why are we so bad at it? How many projects do you hear about that outright fail? Or become "legacy" and have to be entirely re-written (and the re-writes often fail too!)

How does a software system "fail" anyway? Can't it just be changed until it's correct? That's what we're promised!

A lot of people are choosing Go to build systems because it has made a number of choices which one hopes will make it more legacy-proof.

-   Compared to my previous life of Scala where [I described how it has enough rope to hang yourself](http://www.quii.dev/Scala_-_Just_enough_rope_to_hang_yourself), Go has only 25 keywords and _a lot_ of systems can be built from the standard library and a few other small libraries. The hope is that with Go you can write code and come back to it in 6 months time and it'll still make sense.
-   The tooling in respect to testing, benchmarking, linting & shipping is first class compared to most alternatives.
-   The standard library is brilliant.
-   Very fast compilation speed for tight feedback loops
-   The Go backward compatibility promise. It looks like Go will get generics and other features in the future but the designers have promised that even Go code you wrote 5 years ago will still build. I literally spent weeks upgrading a project from Scala 2.8 to 2.10.

Even with all these great properties we can still make terrible systems, so we should look to the past and understand lessons in software engineering that apply no matter how shiny (or not) your language is.

In 1974 a clever software engineer called [Manny Lehman](https://en.wikipedia.org/wiki/Manny_Lehman_%28computer_scientist%29) wrote [Lehman's laws of software evolution](https://en.wikipedia.org/wiki/Lehman%27s_laws_of_software_evolution).

> The laws describe a balance between forces driving new developments on one hand, and forces that slow down progress on the other hand.

These forces seem like important things to understand if we have any hope of not being in an endless cycle of shipping systems that turn into legacy and then get re-written over and over again

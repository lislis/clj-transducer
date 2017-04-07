Transducers

Disclaimer

This talk contains scenes from the Rocky Horror Picture Show and therefore partcial nudity.
If you have never seen the movie, I'm very sorry for the next 5 minutes.
I hope you can enjoy it nonetheless.


Screenshots from clojuredocs saying `or returns a transducer`

clip seduce-ya.mov

intro slides 1 - 3

clip transport-device.mov

Not really


<real explanation>

clip mental-mindfuck.mov

Thank you slide



----



https://stackoverflow.com/questions/26317325/can-someone-explain-clojure-transducers-to-me-in-simple-terms#26322910


http://blog.cognitect.com/blog/2014/8/6/transducers-are-coming



http://blog.cognitect.com/blog/2014/8/6/transducers-are-coming


http://clojure.com/blog/2012/05/15/anatomy-of-reducer.html

http://blog.cognitect.com/blog/2015/6/30/clojure-17?rq=transducers

https://ianrumford.github.io/clojure/transducers/reducers/2014/08/08/Some-trivial-examples-of-using-Clojure-Transducers.html


http://conscientiousprogrammer.com/blog/2014/08/07/understanding-cloure-transducers-through-types/
-> tranducers explained in haskell


https://bendyworks.com/blog/transducers-clojures-next-big-idea


Transducer = transform + reducer


reducer = function you pass to reduce


``` clojure
;;reducing function signature
whatever, input -> whatever
```

``` clojure
;;transducer signature
(whatever, input -> whatever) -> (whatever, input -> whatever)
```

It's a function ignorant of whatever and of input.

Stack transducers like other functions with `comp`

`reduce`

`transduce`

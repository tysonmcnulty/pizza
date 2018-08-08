# Pizza

A nexus point for conversations about distributed systems design and delicious, oven-baked meals.

## Subprojects

* [Pizza Consumer](git@github.com:tysonmcnulty/pizza-consumer.git)
* [Pizza Mediator](git@github.com:tysonmcnulty/pizza-mediator.git)
* [Pizza Producer](git@github.com:tysonmcnulty/pizza-producer.git)

## Problems

1. Let's build the MVP for our pizza consumer users!
   * Build a web interface for `pizza-consumer` Users should be able to request a pizza, and requested pizzas should be            ultimately show up in the browser.
   * The producing application (`pizza-producer`) should be the source of the pizza. You get to decide what a pizza is, as          long as it's something that (`pizza-consumer`) can consume.
   * There is a third application, `pizza-mediator`, that you should feel free to use and modify to suit your needs, if you        want.
   
1. Challenges
   * We want build and deploy all of our applications independently. How do we drive toward this principle with our testing        strategy?
   * Even if your projects don't refer to each other, have you introduced any design coupling? How can we mitigate indirect        coupling?
   * Did you use the middleman? Why or why not? What value does it provide?

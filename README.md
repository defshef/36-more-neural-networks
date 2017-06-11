# (def shef 36) More Neural Networks

A neural network consists of nodes and connections, where inputs flow
to outputs to answer questions. A classic question is "what digit is
this hand-written representation most likely to be?". Training a
neural network requires flow in the opposite direction, updating the
components in the network to answer the question.

Following
[Andrej Kaparthy's "Hacker's Guide to Neural Networks"](http://karpathy.github.io/neuralnets/)
in [(def shef 34)](https://defshef.github.io#ep34), we got as far as constructing the
network, which led to interesting questions about how to deal with the
training problem in a functional way. Solutions like the JavaScript
implementation in Andrej's post rely on mutable objects in the network
for the training operation.

This session will focus on the question of how to deal with updating
networks like this in a functional style. Anyone wanting to look at
any other aspects of neural networks is also welcome to come along and
participate!

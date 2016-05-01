# Friendly DeepQ
[Website](https://greydanus.github.io/friendly_deepq/index.html)

This is a project I designed in order to study how DeepQ networks learn to interact with other agents. The reinforcement learning JavaScript library and much of the world's physics taken from work by Andrej Karpathy.

## Details
The items in this world begin as 'flipme' items. The agents come in two types: apple-loving and poison-loving. Once an agent touches one of these items, the item becomes the opposite of what the agent likes. My hope is that two different agents will learn an optimal strategy of 'hanging out' together so that they can flip items for each other's mutual benefit. Yay cooperation!

This machine learning project is built purely in JavaScript. As such, it is not optimized for speed. Instead, it is meant to serve as a toy example with which you can easily test out ideas before implementing them more rigorously with a library like Theano, Torch, or Keras.

## License

MIT.

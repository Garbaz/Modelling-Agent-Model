# The Modelling Agent Model

## Agent

An _Agent_ exists inside an _Environment_. The Agent can not read or manipulate this Environment directly.\
However, the Agent can sense the Environment through their _Senses_, giving them an _Image_ of it, and interact with the Environment through _Actions_, which in turn transform the Environment.\
Through a feedback loop of sensing and acting, the Agent pursues their _Goals_. What mechanism stands between an Agent's Senses, Goals and Actions, is the Agent's _Decider_.

### Hard-Wired Agent

Perhaps the simplest possible non-trivial Agent, is one that, for any given Image of the world, executes a fixed predetermined Action.
The Agent's success or failure in achieving their goals is determined by the Decider they come into existence with and the Environment they find themselves in.

### Soft-Wired Agent

While still having a fixed Action for a given Image of the Environment, an Agent could have a mechanism for evaluating how it's Actions serve towards achieving it's Goals, which instruct a direct adaption of it's Decider.

### Modelling Agent

With an Agent's inability to directly read the Environment, instead of taking the Image their Senses take of it directly in determining their Actions, an Agent could attempt to construct a _Model_ of the Environment, a representation of it inside their Decider, which is in turn constructed and adapted through their Image of the Environment.

## Model

In having a Model of the Environment, the Agent can consider Actions as if they had the ability to directly read and manipulate the Environment, with only the accuracy of the Model their decisions are based upon being restricted by the representativeness of the Image their Senses produce and their Decider's capacity.\
In having a representation of the Environment that the Agent can directly read and manipulate, the Agent is capable of taking Actions as if they were capable to reading the Environment itself.\

### Advantage

An innacurate direct Model of the Environment is stronger than an accurate indirect Image of the Environment in deciding Goal-achieving Actions.
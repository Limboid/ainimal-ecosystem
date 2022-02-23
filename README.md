# **AI**nimal Zoo / Zookeeper / Leash

I should make this repo public once the subrepo's are figured out. This README will help people understand how things fit together.

As heterogeneous, distributed, and exoitc AI systems (**AI**nimals :tiger:) continue to pervade the real world, it is incrinsingly important to observe, care for, and stay in touch with them. **AI**nimal Zoo, Zookeeper, and Leash form an AI management ecosystem to facilitate observing, interacting with, and managing AI systems in the wild.

These tools are designed for:

1. ML engineers to make quick user-friendly, professional cross-platform interfaces to their apps and be able to customize the interface easily
2. ML operators to monitor, train, and control robots, computer bots, and other persistent or on-demand resources securely in real time
3. Self-directed ML agents performing runtime introspection, optimization, and self-reinforcement learning

To support these diverse functions, AInimals adopt the agent-envionrment paradigm and every AInimal must provide a `dna` file which contains the following:

```python
name: str
version: str
model: Model|Callable
init_fn: Callable
train_fn: Callable
init_args: dict
other_fns: dict  # optional
input_modalities: dict  # optional
output_modalities: dict  # optional
# TODO: this needs more thought
```

everything is an agent. Environments are agents period zookeepers can define arbitrary  execution orders for the agents. some agents our singleton consensus period for example common winning robot registers itself in the zoo come on the robot body is cannot be initialize multiple times gary it is already initialized and

 it should be very easy for a person to start using and robot from the leash interface. they simply it and answer their credentials and then the robot will automatically connect to a server and start running. if they once users can select advance through customize which zoo they connect sale and whether a policy is automatically watched or not.

## **AI**nimal :elephant: Zoo

Depending on the AInimal type, AInimal Zoo manages model versioning, monitoring observations, actions, and environment state in realtime, optional introspection like viewing and/or overriding the value of any tensor (hidden state, input, output, parameter, reward, optimizer and other runtime configurable hyperparameters) and viewing the graph structure, data collection and asynchronous training, A/B testing and other evolutionary meta-learning paradigms, and arbitrary functions defined by individual AInimals. For instance, multi-agent networks (MAN's) support runtime merging, splitting, and growth. AInimal Zoo also optionally manages cloud compute provider placement for AInimal models. The entire Zoo exposes a graphQL API to perform its operations. Various authentication providers are supported. Authorization schemes range from no authorization to AInimal-operation-level authorization (i.e.: individualized permissions assigned to each node in the graphql schema) with roles, users, and groups.

## **AI**nimal :tiger: Zookeeper

Generic cross platform (react-native: iOS, iPadOS, watchOS (?), Android OS; react: web; electron: macOS, windows, linux) composable interface for ML agents with support for audio/visual/text/speech/arbitrary modality bidrectional streams and MLops stuff like model versioning, deployment, runtime introspection, and remote server control. Not all features must be used but bidirectional data streaming is the primary use-case. For MAN-based AInimals, runtime introspection allows merging two MAN agents into one to maximize syngery. This is useful in massive multiagent systems like factory complexes, limboid festivals, and global limboid networks.

Also useful to provide a remote control or remote reward button for human-in-the-loop training.

## **AI**nimal :dog: Leash

Robot sensorymotor interface. Facilitates streaming camera, microphone, motion, display, and speaker content. Also provides access to arduino nano connected to USB port and defines a communication protocol for generic sensory motor peripheral interface. No plans to store data or support federated learning.

there is a simple interface that allows users to enter their credentials and then automatically connect to the default and zoo and launch and associated neural network. users can also select the advanced options tab under this tab they are able to enter the zoo that they wish to connect to as well as whether they want to launch a new neural network or connect to an existing neural network and the zoo.

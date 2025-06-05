<div align="center">

  <h3>TrackMania Nations Forever Reinforcement Learning</h3>
  Experimental ML for Trackmania
  <br>

</div>

## Linesight

Linesight is a reinforcement learning project seeking to push what can be done with AI in Trackmania as far as possible.

[Linesight Source Code](https://github.com/Linesight-RL/linesight)

## Trackmania

Trackmania is a racing game that sacrifices some of the realism of sim-racers for a wide variety of track types with all kinds of tricks like wall riding, stunt jumps and wallbangs. Furthermore, Trackmania was designed for equality of input devices which means that keyboard inputs are a viable way to play and therefore that discrete input algorithms like DQN can be applied. In other words, Trackmania is a deep game which can serve as a benchmark to work on any RL algorithm.

## Trackmania Interface

Linesight, combined with the efforts of [donadigo](https://github.com/donadigo) and [Kim](https://github.com/koyaanis) of the [Trackmania Interface team](https://donadigo.com/tminterface/) allow interfacing to [Trackmania Nations Forever](https://en.wikipedia.org/wiki/TrackMania#TrackMania_United). Allowing you to programmatically send inputs, get car states, get screenshots, etc... This part of our codebase could be useful to other RL projects.

## What's new in this fork?

This fork is a continuation of the original Linesight project, with the goal of making it more accessible and easier to use. The main changes include:

### Features


### Roadmap
- [ ] Move to modern package manager [UV](https://uv.dev/)
- [ ] Seperate the Game interface from the RL code
- [ ] Containerize the project for easy setup
- [ ] Enable training on multiple Game Servers
- [ ] Add dockerfile for easy setup
- [ ] Support for multiple Trackmania maps
- [ ] Support for training on Apple Silicon

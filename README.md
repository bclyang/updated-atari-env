# A new wrapper on the new Arcade Learning Environment which supports different difficulty levels and game modes.

A python wrapper on the new [Arcade Learning Environment](https://github.com/mgbellemare/Arcade-Learning-Environment) v0.6.0. This wrapper is fully inspired by [OpenAI gym](https://github.com/openai/gym) and supports different difficulties and game modes for various Atari games for experimenting with different game dynamics within the gym framework.

## Installation
1. Install the latest Arcade Learning Environment by following the instructions at https://github.com/mgbellemare/Arcade-Learning-Environment.

2. Download a ROM-file for the Atari game, or use a ROM file included in the repository. Title the ROM-file all lowercase, such as 'pong.bin'.

3. Import UpdatedAtariEnv and follow the OpenAI gym API. An introduction the new ALE is available here: https://arxiv.org/pdf/1709.06009.pdf. 

This wrapper is initially develoed and used in [Sample-Efficient Deep RL with Generative Adversarial Tree Search](https://arxiv.org/pdf/1806.05780.pdf).

This is a list of the available modes and difficulties for each game from the paper. 

![ALE Modes and Difficulties](https://raw.githubusercontent.com/bclyang/updated-atari-env/master/modes_difficulties.png)

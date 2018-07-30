# Updated Atari Environment for OpenAI Gym

An environment for Atari on [OpenAI gym](https://github.com/openai/gym) using the updated [Arcade Learning Environment](https://github.com/mgbellemare/Arcade-Learning-Environment) v0.6.0. It supports different difficulties and game modes for various Atari games for experimenting with different game dynamics within the gym framework.

Installation
1. Install the latest Arcade Learning Environment by following the instructions at https://github.com/mgbellemare/Arcade-Learning-Environment.

2. Download a ROM-file for the Atari game, or use a ROM file included in the repository. Title the ROM-file all lowercase, such as 'pong.bin'.

3. Import UpdatedAtariEnv and follow the OpenAI gym API. An introduction the new ALE is available here: https://arxiv.org/pdf/1709.06009.pdf. This is a list of the available modes and difficulties for each game.

![ALE Modes and Difficulties](https://raw.githubusercontent.com/bclyang/updated-atari-env/master/modes_difficulties.png)

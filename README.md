TODO:

- off by one bug when removing a preset?
- free strings?
- more CLI flags for settings

cmake --build . --config Release && \
./projectMSDL --audioDevice="BlackHole 2ch" -f1  --monitor=2 -p. --presetFilter="Waveform - Wire Rising ---" --shuffleEnabled=0
# Chapter 3 - Generating polyphonic melodies

This chapter will show the importance of Long Short-Term Memory (LSTM) networks in generating longer sequences. We'll see how to use a monophonic Magenta model, the Melody RNN—an LSTM network with a loopback and attention configuration. You'll also learn to use two polyphonic models, the Polyphony RNN and Performance RNN, both LSTM networks using a specific encoding, with the latter having support for note velocity and expressive timing.

## Code

### [Example 1](chapter_03_example_01.py) or [notebook](notebook.ipynb)

This example shows a melody (monophonic) generation using the Melody RNN model
and 3 configurations: basic, lookback and attention. For
the Python script, while in the Magenta environment (`conda activate magenta`):

```bash
# Runs 3 melody rnn generation using the basic, lookback and attention config
python chapter_03_example_01.py
```

For the Jupyter notebook:

```bash
jupyter notebook notebook.ipynb
```

### [Example 2](chapter_03_example_02.py)

This example shows polyphonic generations with the Polyphony RNN model. For
the Python script, while in the Magenta environment
(`conda activate magenta`):

```bash
# Runs 4 polyphonic generations using polyphony rnn and
# different configurations
python chapter_03_example_02.py
```

### [Example 3](chapter_03_example_03.py)

This example shows polyphonic generations with the Performance RNN model. For
the Python script, while in the Magenta environment
(`conda activate magenta`):

```bash
# Runs 3 polyphonic generations using performance rnn and 
# different configurations
python chapter_03_example_03.py
```

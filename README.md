# CMU-10701-MusicGeneration
Shared repository for 10-701 music generation task. 
Collaborator: Daniel (danielhu@andrew.cmu.edu), Jared (jsantama@andrew.cmu.edu), and Xiaoqi (xiaoqih1@andrew.cmu.edu)


* The main two notebooks to run are 

  a. ``LSTM_baseline.ipynb`` in the top level of the repo for LSTM baseline
  
  b. ``musicautobot/notebooks/music_transformer/transformer_XL_end2end.ipynb`` for Transformer XL.
  
  
* All our generated music samples are in the folder ``generated_output``.
* Classifcal MIDI data collection can be found under ``midi_data``, grouped by instruments

* The folder `musicautobot` contains source code from [repo](https://github.com/bearpelican/musicautobot) as well as our modified ``transformer_XL_end2end.ipynb``
* `beethoven` folder contains the notewise text representation that we use in the BLEU score evaluation as the benchmark.
* `/midi-to-encoding.py` is the simple script that converts MIDI to notewise text representation. 

# NeuroReach: move a robot with your mind

**Play:** https://kkonnerharris.github.io/neuroreach-web/

A first-person neuro-engineering game. You can't use your hands; an EEG headset reads the
movement you imagine, and an assistive robot arm does everyday tasks for you.

- **Real EEG:** every brain-signal tile is a held-out recording from the
  [PhysioNet EEG Motor Movement/Imagery Dataset](https://physionet.org/content/eegmmidb/1.0.0/)
  (Schalk et al., 2004; Goldberger et al., 2000; ODC-BY).
- **Live decoding in your browser:** a per-subject CSP + LDA decoder (21 sensorimotor channels)
  classifies each recording when you drop it on the robot.
- **Physics from PyBullet:** robot motion was recorded from a KUKA iiwa simulation and is replayed here.

This repo contains only the built game. Source code is kept separately.

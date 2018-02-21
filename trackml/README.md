
# TrackML hackathon

At HL-LHC, the seven-fold increase of multiplicity w.r.t. 2018 conditions poses a severe challenge to ATLAS and CMS tracking experiments. Both experiments are revamping their tracking detector, and are optimizing their software. But are there not new algorithms developed outside HEP which could be invoked: for example  MCTS, LSTM, clustering, CNN, geometric deep learning and more?
We organize on the Kaggle platform a  data science competition to stimulate both the ML and HEP communities to renew core tracking algorithms in preparation of the next generation of particle detectors at the LHC.   

In a nutshell : one event has 100.000 3D points  ; how to associate the points onto 10 000 unknown approximately helicoidal trajectories ? avoiding combinatorial explosion ? you have a few seconds. But we do give you 100 000 events to train on.

We ran ttbar+200 minimum bias events into ACTS, a simplified (yet accurate) simulation of a generic LHC silicon detectors, and wrote out the reconstructed hits, with matching truth. We devised an accuracy metric which capture with one number the quality of an algorithm  (high efficiency/low fake rate). 
The challenge will run in two phases:  the first on accuracy (no stringent limit on CPU time) running March to June 2018, and the second (starting in the summer 2018) on the throughput, for a similar accuracy.

We propose during the IML hackathon to walk through TrackML dataset and starting kit, and hold a Q&A session for anyone
already participating to the challenge.

Useful links:
 - [Challenge page on Kaggle](https://www.kaggle.com/c/trackml-particle-identification) (when officially opened in March 2018)
 - [Challenge web's site](https://sites.google.com/site/trackmlparticle/)






# Harmonizer
Input a melody, get accompanying chords back.

The goal is to be able to input a midi file containing a melody and to output another midi file with accompanying chords to go with it.

This is my first personal machine learning project, and I'm trying to implement a conditional GAN that is able to take in a vector
of a one hot encoded mode, pitch inventory of current accompanying chords, and pitch inventory of the melody coming
immediately after the chords. With this, the conditional GAN will ideally output a one hot encoded pitch inventory of the accompanying
chords for the melody coming up. 

I wrote a straight up algorithm myself in MIDI_Processing.ipynb. It is also used to extract training examples out of MIDI files.

This project is still a work in progress!

For now, you may read a write-up of this project at my website: https://eliascho.com/

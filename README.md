# Music Generation using RNN
Chord composition based on a monophonic melody is a tedious task for most of the music amateurs as it requires a decent understanding of music theory and chord progression. In this paper we present different methods for generating musical chords that correspond to an inputted melody in Musical Instrument Digital Interface (MIDI) format.

For that, we preprocess the monophonic melody and normalize it in order to ensure the uniformity of the note duration, the time signature and the key amongst all the dataset. We train the Recurrent Neural Networks (RNNs) on the preprocessed data with long short-term memory (LSTM) cells on one hand and Gated Recurrent Unit (GRU) on the other. For further testing, we add an attention layer for each network configuration, resulting with a total of four different models.

The quantitative comparative analysis shows GRU based RNN outperformed all the other networks (67.41% accuracy). Knowing that music can be subjective, and many chord generations might be satisfactory, a user qualitative study was also conducted which resulted in the same conclusion. 

---> Link to youtube demo:  https://youtu.be/DZDoU_zTR3Y

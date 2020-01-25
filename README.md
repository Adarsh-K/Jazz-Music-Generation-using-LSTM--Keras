# I've made a Jazz Music generator using LSTMs. The code is in Python and uses Keras.
Note: All the files are well documented and commented wherever I felt necessary

Run the file named JazzGenerationUsingLSTM.ipynb which does the following:
1. Imports all necessary requirements- mentiones explicitly as there are a lot, which is generally the case when using Machine    Learning Frameworks like Keras plus a lotof Music dependent stuff as well ;) 
2. Loads the raw music data and preprocess it into values in load_music_utils()
3. Since we want shared weights I've defined a few Global Variables
4. Implement the model ,compile it and fit the model made 
5. Sampled or Generates the sequence of "values" using music_inference_model(..,..,) and predict_and_sample(..,..,)
6. Lets Generate some Jazz: run- generate_music(inference_model)
7. The output ie. Jazz Generated(nemd my_music.midi) is saved in Output Folder- I've also converted it into .mp3 file 

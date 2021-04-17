# Talking To AI-Generated People 
### [[Project Video](https://www.youtube.com/watch?v=OCdikmAoLKA)] [[Code Tutorial](./Talking_to_AI_Generated_People.ipynb)] 
### Fake Faces, Script, Voice and Lip-Sync Animation with Deep Learning
This notebook combines different state-of-the-art image and speech generation neural networks into one single Google Colab Notebook so that we can generate a random fake person's talking head video replying to our input text question.

![Fake People](res/combined.gif)

#### Different Tools/Repositories used:-
1) Face Generation - www.thispersondoesnotexist.com - StyleGAN2
2) Text Generation - www.textsynth.org - OpenAI GPT-2
3) Text-to-Speech Conversion - https://github.com/NVIDIA/flowtron - Flowtron
4) Lip Animation - https://github.com/Rudrabha/LipGAN - LipGAN

#### TODO Improvements (Any Volunteers??) :-
1) Use motion model to animate the face before performing lip-sync.
2) Use the newer GPT-3 model for better, more coherent text responses.

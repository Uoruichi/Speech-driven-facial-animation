# Speech-driven-facial-animation
- This is my Btech final year Major project.

- Face synthesis is essential to many applications, such as computer games, animated movies,teleconferencing, talking agents, among others.
- We present a deep learning framework for speech-driven 3D facial animation from speech audio. We focus on the entire face, not just the mouth and lips.
- Intuitively, this work is analogous to visual 3D face tracking however, it is more challenging as we try to map acoustic sequence to visual space, instead of conveniently relying on textural cues from input images.
- Our deep neural network directly maps an input sequence of speech spectrograms to a series of micro facial action unit intensities to drive a 3D blendshape face model.
- In particular, our deep model is able to learn the latent representations of time-varying contextual information and affective states within the speech. Hence, our model not only activates appropriate facial action units at inference to depict different utterance generating actions, in the form of lip movements, but also, without any assumption, automatically estimates emotional intensity of the speaker and reproduces their ever-changing affective states by adjusting strength of related facial unit activations. 
- For example, in a happy speech, the mouth opens wider than normal, while other facial units are relaxed; or both eyebrows raise higher in a surprised state.

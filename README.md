# Machine Learning Music Generation
This repo aims to build on and alter the methods created in the MusicLM paper by Google Research https://arxiv.org/abs/2301.11325. The goal is to create a text-to-audio machine learning model which as input takes a description of a custom song designed by the user and outputs a corresponding music file of that song as interpreted by the model.

__*Note: In the directory dedicated to each respective part there is (planned to be) another README file with a display that contains a UML diagram of the component*__


## |   Installation and Running Tests
*coming soon*

## |   Base Model Components
There are three main components of MusicLM that will need to be generalized. The following three sections are titled as the functions of those components and what we’ll call them in the codebase. Each section details MusicLM’s method of accomplishing it and ours. Each section is designed to be swapped out and improved in parallel without impact to the overall function of the model by encapsulating each part that is described in the following three sections.

### Music Encoder
![alt text](https://github.com/rmzaldivar/MachineLearningMusicGeneration/blob/main/README_pngs/base_model_pngs/simple_music_encoder.png)

*coming soon*

### Text Encoder
![alt text](https://github.com/rmzaldivar/MachineLearningMusicGeneration/blob/main/README_pngs/base_model_pngs/simple_text_encoder.png)

*coming soon*

### Joint Text+Audio Embedder
![alt text](https://github.com/rmzaldivar/MachineLearningMusicGeneration/blob/main/README_pngs/base_model_pngs/simple_joint_text_audio_embedder.png)

*coming soon*

## |   Model Interface Components
These are three components that are resonsible for interacting with the model. They handle the input, output, and training of the model according to input from a user.

### Input Handler
![alt text](https://github.com/rmzaldivar/MachineLearningMusicGeneration/blob/main/README_pngs/model_handler_pngs/simple_input_handler.png)

*coming soon*

### Output Handler
![alt text](https://github.com/rmzaldivar/MachineLearningMusicGeneration/blob/main/README_pngs/model_handler_pngs/simple_output_handler.png)

*coming soon*

### Trainer
![alt text](https://github.com/rmzaldivar/MachineLearningMusicGeneration/blob/main/README_pngs/model_handler_pngs/simple_trainer.png)

*coming soon*



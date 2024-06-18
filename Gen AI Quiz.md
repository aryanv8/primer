<h1 style="color:teal;text-align:center;border-bottom:1px solid teal"> Gen AI Quiz </h1>

# Sequence Generation with RNN pre ☑️
## Question 1
Which RNN architecture utilizes update and reset gates to manage memory?

- Bidirectional RNN
- **_GRU_**
- Hopfield Network
- LSTM
- Echo State Network

**Explanation:** The Gated Recurrent Unit (GRU) architecture uses update and reset gates to control the flow of information and manage memory within the network, making it more efficient than traditional RNNs.

## Question 2
During the training of RNNs for sequence generation, what is the common technique used to mitigate the vanishing gradient problem?

- Data augmentation
- Dropout
- L1 regularization
- **_Gradient clipping_**
- Batch normalization

**Explanation:** Gradient clipping is used to mitigate the vanishing gradient problem by limiting the gradients' size during backpropagation, preventing them from becoming too small or too large.

## Question 3
In NLP, what does RNNs help to predict?

- Next image
- Next video frame
- **_Next word_**
- None of the options given
- Next song note

**Explanation:** In natural language processing (NLP), Recurrent Neural Networks (RNNs) are used to predict the next word in a sequence, which is crucial for tasks like language modeling and text generation.

## Question 4
In the context of natural language processing, how are RNNs typically utilized for machine translation?

- **_Encoding the input sequence and decoding the output sequence_**
- For clustering text data
- As discriminators in GANs
- As a replacement for CNNs
- For image classification

**Explanation:** RNNs are used in machine translation by encoding the input sequence in one language and decoding it into another language, facilitating accurate translation between languages.

## Question 5
Which of the following is NOT a type of RNN architecture?

- Simple RNN
- GRU
- ***CNN***
- Bidirectional RNN
- LSTM

**Explanation:** Convolutional Neural Networks (CNNs) are not a type of RNN architecture. CNNs are primarily used for image and spatial data, while RNNs are designed for sequential data.

## Question 6
RNNs are primarily used for which type of data?

- Image
- None of the options given
- Tabular
- **_Sequential_**
- Audio

**Explanation:** RNNs are designed to handle sequential data, such as time series, text, and audio, where the order of the data points is significant.

## Question 7
What does RNN stand for?

- Random Neural Network
- None of the options given
- Regular Neural Network
- **_Recurrent Neural Network_**
- Recursive Neural Network

**Explanation:** RNN stands for Recurrent Neural Network, which is a type of neural network designed to handle sequential data by maintaining a memory of previous inputs in the sequence.

## Question 8
What is the key advantage of using LSTMs over basic RNNs in sequence generation tasks?

- Simpler architecture
- Less prone to overfitting
- Lower computational cost
- Faster training speeds
- **_Ability to remember long-term dependencies_**

**Explanation:** LSTMs (Long Short-Term Memory networks) have the ability to remember long-term dependencies in the data, which is a significant advantage over basic RNNs that struggle with long-term memory due to the vanishing gradient problem.

## Question 9
Which problem in RNNs does LSTM help to address?

- Overfitting
- **_Vanishing gradient_**
- All of the options given
- High variance
- Bias

**Explanation:** LSTMs are specifically designed to address the vanishing gradient problem by using memory cells and gates to maintain long-term dependencies in the data.

## Question 10
When using RNNs for music generation, what does each neuron in the output layer typically represent?

- A specific instrument
- A note in the C major scale
- A time step in the generated sequence
- A frequency band
- **_A possible note or rest in the musical vocabulary_**

**Explanation:** In music generation, each neuron in the output layer of an RNN typically represents a possible note or rest in the musical vocabulary, allowing the network to generate sequences of musical notes.

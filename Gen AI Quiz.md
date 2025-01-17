[🔙  Back to Menu](./)

<h1 style="color:teal;text-align:center;border-bottom:1px solid teal"> Gen AI Quiz </h1>

## Generative Adversarial Networks - Pre ☑️
### Question 1
In GANs, which component is responsible for evaluating the authenticity of data?
- Encoder
- Generator
- ***Discriminator***
- Decoder
- None of the given options

**Explanation:** The Discriminator in a GAN evaluates the authenticity of data by distinguishing between real and generated samples. It helps the Generator improve by providing feedback on how realistic the generated data is.

### Question 2
In the GAN architecture, what is the primary goal of the Discriminator?
- Generate realistic data samples
- ***Distinguish between real and generated samples***
- Replicate the generator's output
- Ensure mode diversity
- Minimize the loss function

**Explanation:** The primary goal of the Discriminator in a GAN is to distinguish between real and generated samples. This helps in training the Generator to produce more realistic data by constantly improving its ability to deceive the Discriminator.

### Question 3
What is mode collapse in the context of GANs?
- When the model converges too quickly
- When the discriminator becomes too powerful
- When the model overfits
- When the model underfits
- ***When the generator produces limited varieties of outputs***

**Explanation:** Mode collapse occurs when the Generator in a GAN produces limited varieties of outputs, resulting in a lack of diversity in the generated data. This is a common issue where the Generator finds a few modes of data that the Discriminator cannot distinguish well and repeatedly generates those modes.

### Question 4
The training process of GANs is often likened to which game?
- Poker
- ***Minimax***
- None of the given options
- Sudoku
- Chess

**Explanation:** The training process of GANs is likened to the minimax game, where the Generator and Discriminator are in a two-player game with opposing goals. The Generator tries to minimize the Discriminator's ability to distinguish real from fake, while the Discriminator tries to maximize its accuracy.

### Question 5
Progressive GANs are designed to address which challenge in traditional GANs?
- Mode collapse
- ***Training stability and generating high-resolution images***
- Discriminator overpowering the generator
- Slow training speeds
- Inability to generate colored images

**Explanation:** Progressive GANs are designed to improve training stability and the ability to generate high-resolution images. They do this by gradually increasing the resolution of the images during training, which helps to produce more detailed and higher-quality outputs.

### Question 6
Which component of a GAN is responsible for generating new data samples?
- Discriminator
- ***Generator***
- Optimizer
- Encoder
- Decoder

**Explanation:** The Generator in a GAN is responsible for creating new data samples. It learns to produce data that mimics the real data distribution, which the Discriminator then evaluates.

### Question 7
What does GAN stand for?
- Generalized Artificial Network
- None of the given options
- ***Generative Adversarial Network***
- Generative Analytical Network
- Gradient Augmented Network

**Explanation:** GAN stands for Generative Adversarial Network. It is a framework for training generative models through an adversarial process, where a Generator and a Discriminator compete to improve the quality of generated data.

### Question 8
Which type of GAN allows for generating data based on specific categories?
- Minimax GAN
- Mode Collapse GAN
- Progressive GAN
- ***Conditional GAN***
- None of the given options

**Explanation:** Conditional GANs allow for generating data based on specific categories by conditioning both the Generator and the Discriminator on additional information, such as class labels, to produce data that belongs to those categories.

### Question 9
What is a challenge faced during GAN training due to the minimax game concept?
- ***Oscillations and non-convergence***
- Generator producing only a single mode
- Quick convergence to a suboptimal solution
- Discriminator becoming too weak
- Overfitting to the training data

**Explanation:** One of the main challenges in GAN training due to the minimax game concept is oscillations and non-convergence. This happens because the Generator and Discriminator continuously try to outdo each other, which can lead to unstable training dynamics.

### Question 10
Which of the following is a real-world application where GANs have shown significant promise?
- Text summarization
- Image classification
- Speech recognition
- ***Image-to-image translation***
- Time series forecasting

**Explanation:** GANs have shown significant promise in image-to-image translation, which involves transforming images from one domain to another, such as converting sketches to photorealistic images, or enhancing low-resolution images to high-resolution ones.

## Generative Adversarial Networks - Post ☑️

### Question 1
In the minimax game of GANs, what is the discriminator's goal?
- Generate realistic data
- Maximize the generator's loss
- Minimize its own loss
- ***Distinguish between real and fake data***
- None of the given options

**Explanation:** The Discriminator's goal in the minimax game of GANs is to distinguish between real and fake data. It aims to accurately identify which data samples are real and which are generated by the Generator.

### Question 2
Mode collapse is problematic because...
- ***It limits the diversity of generated outputs***
- None of the given options
- It makes the discriminator weak
- It speeds up training
- It requires more data

**Explanation:** Mode collapse is problematic because it limits the diversity of generated outputs. The Generator repeatedly produces the same or similar outputs, reducing the variety and usefulness of the generated data.

### Question 3
Which statement about GANs is true?
- They always converge to a solution
- They are a type of supervised learning
- ***They can generate new, previously unseen data***
- None of the given options
- They only work with images

**Explanation:** GANs can generate new, previously unseen data by learning the underlying distribution of the training data and producing samples that mimic it.

### Question 4
Which component of a GAN tries to produce fake data?
- None of the given options
- Encoder
- Discriminator
- ***Generator***
- Decoder

**Explanation:** The Generator in a GAN is responsible for producing fake data that resembles the real data in order to fool the Discriminator.

### Question 5
Which is NOT a real-world application of GANs?
- ***Real-time weather prediction***
- Data augmentation
- Super-resolution imaging
- Art generation
- Style transfer

**Explanation:** GANs are not typically used for real-time weather prediction. Their applications include data augmentation, super-resolution imaging, art generation, and style transfer.

### Question 6
The generator's objective in GANs is to...
- Reduce mode collapse
- None of the given options
- Improve model accuracy
- Classify real vs. fake
- ***Fool the discriminator***

**Explanation:** The Generator's objective in GANs is to produce data that is realistic enough to fool the Discriminator into classifying it as real data.

### Question 7
Which GAN variant focuses on gradually increasing the resolution of generated images?
- ***Progressive GAN***
- Mode Collapse GAN
- Conditional GAN
- None of the given options
- Minimax GAN

**Explanation:** Progressive GANs focus on gradually increasing the resolution of generated images during training, which helps in creating high-quality, high-resolution images.

### Question 8
What is a challenge in evaluating the performance of GANs?
- They are too fast
- ***Determining the quality of generated data***
- They require large datasets
- None of the given options
- They always outperform other models

**Explanation:** One of the challenges in evaluating GANs is determining the quality of generated data, as traditional metrics may not effectively measure the realism and variety of the outputs.

### Question 9
Which GAN variant can be conditioned on labels to generate specific outputs?
- ***Conditional GAN***
- Progressive GAN
- Minimax GAN
- Mode Collapse GAN
- None of the given options

**Explanation:** Conditional GANs can be conditioned on labels or other information to generate outputs specific to those conditions, allowing for more controlled and targeted generation of data.

### Question 10
In GANs, if the discriminator becomes too powerful, what can happen?
- None of the given options
- The model achieves perfect accuracy
- The generator becomes powerful too
- ***The generator may struggle to improve***
- The training process speeds up

**Explanation:** If the Discriminator becomes too powerful, it can easily distinguish between real and fake data, making it difficult for the Generator to improve and produce more realistic outputs.

## CASE STUDY - GANS - CIFAR - Quiz

### Question 1
Which architecture can help address convergence issues in traditional GANs?
- RNN
- CNN
- ***WGAN***
- LSTM
- DBN

**Explanation:** WGAN (Wasserstein GAN) introduces a new loss function that improves the convergence properties of the GAN training process, making it more stable compared to traditional GANs.

### Question 2
In the provided code, why is discriminator.trainable set to False when setting up the combined system?
- To increase discriminator's accuracy
- To prevent overfitting
- ***To make sure only the generator is trained in this step***
- None of the given options
- To speed up training

**Explanation:** Setting discriminator.trainable to False ensures that during the training of the combined model, only the generator's weights are updated, while the discriminator remains unchanged.

### Question 3
In the generator code, what is the purpose of the Reshape layer?
- To critique the images
- To normalize the image values
- To flatten the images
- To upsample the images
- ***To reshape the dense layer into a 3D tensor for images***

**Explanation:** The Reshape layer is used to transform the output of the dense layer into a 3D tensor that has the shape of an image, which is necessary for further convolutional layers in the generator.

### Question 4
During training, what does the generator use to improve itself?
- Feedback from both the user and the discriminator
- Real images
- ***Feedback from the discriminator***
- Feedback from the user
- CIFAR-10 dataset

**Explanation:** The generator improves itself by receiving feedback from the discriminator, which tells it how realistic or fake its generated images are, allowing the generator to refine its output.

### Question 5
What is used to refine the models during training?
- Conv2D
- LeakyReLU
- Batch Normalization
- Adam Optimizer
- ***All of the given options***

**Explanation:** All of the given options were used in the given case study.

### Question 6
Why might someone want to use GANs on the CIFAR-10 dataset?
- To reduce the size of the dataset
- To delete images from the dataset
- To critique the images in the dataset
- ***To generate novel and relevant images to augment dataset***
- To classify the images in the dataset

**Explanation:** GANs can be used to generate new, synthetic images that are similar to those in the CIFAR-10 dataset, which can be used to augment the dataset for training other models.

### Question 7
What are the two main components of a GAN?
- Discriminator & Sampler
- Generator & UpSampler
- Discriminator & Evaluator
- Generator & Evaluator
- ***Generator & Discriminator***

**Explanation:** A GAN consists of two main components: the generator, which creates fake images, and the discriminator, which evaluates whether the images are real or fake.

### Question 8
What does the discriminator do in a GAN?
- Combines images
- Enhances image resolution
- Creates images
- Both create and evaluate images
- ***Evaluates if an image is real or fake***

**Explanation:** The discriminator's role is to evaluate the images generated by the generator and distinguish between real and fake images, providing feedback to the generator.

### Question 9
Which challenge refers to the generator producing limited varieties or even the same sample every time?
- Training Instability
- Convergence Issues
- Data Augmentation
- All of the given options
- ***Mode Collapse***

**Explanation:** Mode collapse occurs when the generator produces a limited variety of outputs or even the same output repeatedly, which reduces the diversity of generated samples.

### Question 10
Which of the following is NOT a feedback given to the generator during training?
- This is a genuine image
- This image looks like a car
- ***This image is pixelated***
- This image looks blurry
- This is a fake image

**Explanation:** "This image is pixelated" is not a typical feedback given to the generator. The feedback usually involves whether the image is real or fake and qualitative aspects like blurriness or specific content.

### Question 11
Which technique can help in dealing with training instability in GANs?
- ***Gradient clipping***
- All of the given options
- Dropout
- Data augmentation
- Noise addition

**Explanation:** Gradient clipping helps in dealing with training instability by limiting the magnitude of the gradients during backpropagation, preventing the problem of exploding gradients.

### Question 12
Which activation function is used in the final layer of the generator model?
- softmax
- sigmoid
- leakyrelu
- ***tanh***
- relu

**Explanation:** The tanh activation function is commonly used in the final layer of the generator to scale the output pixel values between -1 and 1, which is suitable for image generation.

### Question 13
Which of the following best describes the role of the generator in a GAN?
- ***To produce images***
- To critique images
- None of the given options
- To evaluate the loss
- To combine images

**Explanation:** The primary role of the generator in a GAN is to produce images that are as realistic as possible in order to fool the discriminator.

### Question 14
How many images are there in each class of the CIFAR-10 dataset?
- ***6000***
- 12000
- 10000
- 5000
- 15000

**Explanation:** Each class in the CIFAR-10 dataset contains 6000 images, making a total of 60000 images across 10 classes.

### Question 15
In the discriminator's code, which layer helps in reducing the dimensions of the input image?
- ***Conv2D with strides***
- BatchNormalization
- Dense
- Reshape
- UpSampling2D

**Explanation:** The Conv2D layer with strides is used to reduce the dimensions of the input image by applying convolution operations with a specified stride, effectively downsampling the image.


## Sequence Generation with RNNs pre ☑️
### Question 1
Which RNN architecture utilizes update and reset gates to manage memory?

- Bidirectional RNN
- **_GRU_**
- Hopfield Network
- LSTM
- Echo State Network

**Explanation:** The Gated Recurrent Unit (GRU) architecture uses update and reset gates to control the flow of information and manage memory within the network, making it more efficient than traditional RNNs.

### Question 2
During the training of RNNs for sequence generation, what is the common technique used to mitigate the vanishing gradient problem?

- Data augmentation
- Dropout
- L1 regularization
- **_Gradient clipping_**
- Batch normalization

**Explanation:** Gradient clipping is used to mitigate the vanishing gradient problem by limiting the gradients' size during backpropagation, preventing them from becoming too small or too large.

### Question 3
In NLP, what does RNNs help to predict?

- Next image
- Next video frame
- **_Next word_**
- None of the options given
- Next song note

**Explanation:** In natural language processing (NLP), Recurrent Neural Networks (RNNs) are used to predict the next word in a sequence, which is crucial for tasks like language modeling and text generation.

### Question 4
In the context of natural language processing, how are RNNs typically utilized for machine translation?

- **_Encoding the input sequence and decoding the output sequence_**
- For clustering text data
- As discriminators in GANs
- As a replacement for CNNs
- For image classification

**Explanation:** RNNs are used in machine translation by encoding the input sequence in one language and decoding it into another language, facilitating accurate translation between languages.

### Question 5
Which of the following is NOT a type of RNN architecture?

- Simple RNN
- GRU
- ***CNN***
- Bidirectional RNN
- LSTM

**Explanation:** Convolutional Neural Networks (CNNs) are not a type of RNN architecture. CNNs are primarily used for image and spatial data, while RNNs are designed for sequential data.

### Question 6
RNNs are primarily used for which type of data?

- Image
- None of the options given
- Tabular
- **_Sequential_**
- Audio

**Explanation:** RNNs are designed to handle sequential data, such as time series, text, and audio, where the order of the data points is significant.

### Question 7
What does RNN stand for?

- Random Neural Network
- None of the options given
- Regular Neural Network
- **_Recurrent Neural Network_**
- Recursive Neural Network

**Explanation:** RNN stands for Recurrent Neural Network, which is a type of neural network designed to handle sequential data by maintaining a memory of previous inputs in the sequence.

### Question 8
What is the key advantage of using LSTMs over basic RNNs in sequence generation tasks?

- Simpler architecture
- Less prone to overfitting
- Lower computational cost
- Faster training speeds
- **_Ability to remember long-term dependencies_**

**Explanation:** LSTMs (Long Short-Term Memory networks) have the ability to remember long-term dependencies in the data, which is a significant advantage over basic RNNs that struggle with long-term memory due to the vanishing gradient problem.

### Question 9
Which problem in RNNs does LSTM help to address?

- Overfitting
- **_Vanishing gradient_**
- All of the options given
- High variance
- Bias

**Explanation:** LSTMs are specifically designed to address the vanishing gradient problem by using memory cells and gates to maintain long-term dependencies in the data.

### Question 10
When using RNNs for music generation, what does each neuron in the output layer typically represent?

- A specific instrument
- A note in the C major scale
- A time step in the generated sequence
- A frequency band
- **_A possible note or rest in the musical vocabulary_**

**Explanation:** In music generation, each neuron in the output layer of an RNN typically represents a possible note or rest in the musical vocabulary, allowing the network to generate sequences of musical notes.

## Sequence Generation with RNNs Post ☑️
### Question 1
In sequence generation tasks, what is the primary input to an RNN at each time step?

- Current input
- **_Previous output_**
- Previous error
- Current weight
- None of the given options

**Explanation:** In sequence generation tasks, the primary input to an RNN at each time step is typically the previous output, which helps the network generate coherent sequences by maintaining context from prior steps.

### Question 2
Which of the following is NOT a typical use case for RNNs?

- **_Image classification_**
- Text generation
- None of the given options
- Time series prediction
- Speech recognition

**Explanation:** RNNs are not typically used for image classification, which is more suited for Convolutional Neural Networks (CNNs). RNNs excel in tasks involving sequential data like text generation, time series prediction, and speech recognition.

### Question 3
Why might one use GRU over LSTM?

- LSTM is outdated
- None of the given options
- **_GRU is simpler and sometimes faster_**
- LSTM can't handle sequences
- GRU is always more accurate

**Explanation:** GRUs are simpler than LSTMs because they have fewer gates, which can result in faster training and inference times while still effectively managing long-term dependencies.

### Question 4
In music generation, what might an RNN be trained to predict?

- Next song genre
- Next album cover
- **_Next note or chord_**
- None of the given options
- Next instrument

**Explanation:** In music generation, an RNN is typically trained to predict the next note or chord in a sequence, helping to create a coherent musical piece.

### Question 5
Which problem arises when training RNNs on long sequences?

- Overfitting
- Underfitting
- High bias
- **_Vanishing or exploding gradients_**
- All of the given options

**Explanation:** When training RNNs on long sequences, the network can suffer from vanishing or exploding gradients, making it difficult to learn long-term dependencies.

### Question 6
How do RNNs handle variable-length sequences in NLP?

- **_Through padding and truncation_**
- By skipping them
- By changing the network size
- They don't
- None of the given options

**Explanation:** In NLP, variable-length sequences are handled by padding shorter sequences to a fixed length and truncating longer sequences, ensuring uniform input sizes for the RNN.

### Question 7
Which RNN architecture uses a reset and update gate?

- Bidirectional RNN
- **_GRU_**
- Simple RNN
- None of the given options
- LSTM

**Explanation:** GRU (Gated Recurrent Unit) architecture uses reset and update gates to control the flow of information and manage memory efficiently.

### Question 8
What is the main advantage of LSTM over basic RNN?

- More layers
- Lower computational cost
- None of the given options
- **_Handling long-term dependencies_**
- Faster computation

**Explanation:** The main advantage of LSTMs over basic RNNs is their ability to handle long-term dependencies through their unique cell state and gating mechanisms.

### Question 9
What is the primary difference between LSTM and GRU?

- LSTM is faster, GRU is slower
- **_LSTM has input, forget, and output gates; GRU has reset and update gates_**
- LSTM has 3 gates, GRU has 2
- LSTM is older, GRU is newer
- LSTM is for sequences, GRU is for images

**Explanation:** The primary difference between LSTM and GRU is that LSTM has three gates (input, forget, and output) while GRU has two gates (reset and update), making GRU simpler and often faster.

### Question 10
Which of the following is a common application of RNNs in NLP?

- Face recognition
- Image generation
- Image classification
- Object detection
- **_Text generation_**

**Explanation:** A common application of RNNs in NLP is text generation, where the model learns to predict and generate the next word or character in a sequence based on the context provided by previous words or characters.

## Sentiment Analysis with RNNs case study ☑️
### Question 1
What is the role of the `<OOV>` token?

- Delete out-of-vocabulary words
- Placeholder for numbers
- Regular expression matcher
- **_Placeholder for out-of-vocabulary words_**
- Ignore out-of-vocabulary words

**Explanation:** The `<OOV>` token serves as a placeholder for out-of-vocabulary words in natural language processing tasks, allowing the model to handle unseen words.

### Question 2
Which layer in the RNN model represents words as detailed feature lists?

- Dense Layer
- SimpleRNN Layer
- **_Embedding Layer_**
- LSTM Layer
- Dropout Layer

**Explanation:** The Embedding Layer in an RNN model represents words as detailed feature lists by mapping each word to a dense vector representation.

### Question 3
Why is padding used in the preprocessing step?

- To reduce memory usage
- To increase vocabulary size
- To improve accuracy
- **_To handle variable review length_**
- For beautification

**Explanation:** Padding is used to ensure all sequences (e.g., text reviews) have the same length, enabling efficient batch processing and consistent input size for the model.

### Question 4
What advantage does LSTM have over traditional RNNs?

- Requires fewer layers
- Simpler architecture
- Faster convergence
- **_Tackles the vanishing gradient problem_**
- Lower memory usage

**Explanation:** LSTM (Long Short-Term Memory) networks address the vanishing gradient problem by maintaining a more complex memory structure, allowing them to learn and retain dependencies over longer sequences.

### Question 5
What is the purpose of the Dropout layer in the LSTM with Dropout model?

- ***Regularization to prevent overfitting***
- Tokenization
- Embedding
- Recurrence
- Activation function

**Explanation:** The Dropout layer in the LSTM with Dropout model serves the purpose of reducing overfitting. Overfitting occurs when a model learns not only the underlying patterns in the training data but also noise and random fluctuations specific to the training dataset. Dropout addresses this issue by randomly dropping (i.e., setting to zero) a fraction of the units (neurons) in the network during training. This prevents neurons from co-adapting too much to each other and encourages the network to learn more robust features that are generalizable to new, unseen data. Thus, the Dropout layer acts as a regularization technique to improve the model's ability to generalize to new data by reducing overfitting.

### Question 6
What might be a concern if the training accuracy is high but validation accuracy is significantly low?

- Model needs more layers
- Model is underfitting
- **_Model is overfitting_**
- Data is incorrectly labeled
- Model is perfectly trained

**Explanation:** A high training accuracy and significantly low validation accuracy typically indicate that the model is overfitting to the training data and not generalizing well to unseen data.

### Question 7
In which scenario might you prefer a simple RNN over an LSTM?

- Large datasets
- Complex sentence structures
- When high accuracy is a must
- **_Fast training with limited resources_**
- Long-range dependencies in data

**Explanation:** A simple RNN might be preferred over an LSTM when there is a need for fast training with limited computational resources, as LSTMs are more computationally intensive.

### Question 8
Which parameter in `model.fit()` signifies the number of times the model is exposed to the dataset?

- optimizer
- batch_size
- loss
- **_epochs_**
- validation_data

**Explanation:** The `epochs` parameter in `model.fit()` specifies the number of iterations over the entire dataset during training.

### Question 9
Why is the loss function important during model compilation?

- ***Specifies how errors are measured***
- Adjusts learning rate
- Specifies number of epochs
- Assigns weights to layers
- Determines model layers

**Explanation:** The loss function during model compilation specifies how errors between predicted and actual values are measured, which guides the optimization process during training.

### Question 10
How does the model handle reviews of varying lengths?

- Ignores reviews outside a certain length range
- Uses multiple RNN layers
- **_Uses padding_**
- Changes tokenizer's vocabulary
- Uses LSTM layers

**Explanation:** The model handles reviews of varying lengths by padding shorter reviews to match the length of the longest review in the dataset, ensuring uniform input size.

### Question 11
Why might the vanishing gradient problem be a challenge in RNNs?

- Makes model evaluation faster
- Reduces training speed
- **_Impedes learning of long-range dependencies_**
- Increases accuracy
- Requires more memory

**Explanation:** The vanishing gradient problem in RNNs impedes the learning of long-range dependencies, as gradients diminish exponentially over time, making it difficult for the model to learn from earlier time steps.

### Question 12
In the given LSTM model, which layer(s) help in retaining memory and context?

- Dense layer
- **_LSTM layer_**
- Dropout layer
- Embedding layer
- SimpleRNN layer

**Explanation:** The LSTM layer (Long Short-Term Memory) in the model helps in retaining memory and context by selectively remembering and forgetting information over time steps.

### Question 13
When using a tokenizer with a fixed number of words, what could be a potential drawback?

- ***Limited understanding due to missed words***
- Simplifies the model
- Increases memory usage
- Enhances accuracy
- Slows down training

**Explanation:** Using a tokenizer with a fixed vocabulary size can lead to limited understanding due to missed words that are not included in the tokenizer's vocabulary.

### Question 14
What is the primary function of an Embedding Layer?

- ***Representing words in dense vector format***
- Tokenization
- Regularization
- Handling out-of-vocabulary words
- Reducing sequence length

**Explanation:** The primary function of an Embedding Layer is to represent words in a dense vector format, allowing the model to learn relationships between words based on their meanings and context.

### Question 15
After training, what can be inferred if the validation loss keeps decreasing but training loss remains high?

- Training data is corrupted
- ***Model is underfitting***
- Model is overfitting
- Model is perfectly trained
- Model architecture is flawed

**Explanation:** 
- **Underfitting** occurs when a model is too simple to capture the underlying patterns of the training data. As a result, it performs poorly not only on the training data but also on new, unseen data (validation data in this case). When the validation loss decreases while the training loss remains high, it indicates that the model has not learned enough from the training data to generalize well to the validation data. This situation suggests that the model lacks complexity or capacity to adequately learn the patterns present in the data.
- **Model is overfitting** would be the case if the training loss were very low but the validation loss started increasing or remained high, indicating that the model is memorizing the training data too well and not generalizing to new data.
- **Model is perfectly trained** would imply that both training and validation losses are low and stable, which is rarely the case in practice.
- **Model architecture is flawed** might be true in some cases where there are fundamental issues with how the model is structured or designed, but underfitting specifically relates to the model's inability to sufficiently learn from the training data.

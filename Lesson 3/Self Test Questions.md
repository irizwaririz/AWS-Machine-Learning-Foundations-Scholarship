## Test your knowledge with the following questions about Lesson 3: Machine Learning with AWS

NOTE: **The questions might provide clues to the previous questions so skipping questions might ruin the experience.**

* This branch of AI allows machines to detect patterns in images and videos.
    <details>
      <summary>Show answer</summary>

      Computer Vision (CV)

    </details>

* Modern CV uses Neural Networks. What layer generates the prediction?
    <details>
      <summary>Show answer</summary>

      Output layer

    </details>

* Modern CV uses Neural Networks. What layer finds important features that have predictive power?
    <details>
      <summary>Show answer</summary>

      Hidden layer

    </details>

* Modern CV uses Neural Networks. What layer receives the input data?
    <details>
      <summary>Show answer</summary>

      Input layer

    </details>

* Hidden layers are used to extract information/features about the images. What is this process called?
    <details>
      <summary>Show answer</summary>

      Feature extraction

    </details>

* What popular CV task answers the questions: What is in this image? Does this image contain what we're looking for?
    <details>
      <summary>Show answer</summary>

      Image Classification

    </details>

* What popular CV task answer the question: Which pixels in an image represent our object of interest?
    <details>
      <summary>Show answer</summary>

      Segmentation

    </details>

* What popular CV task answers the questions: How many of the objects of interest are in the image? What different classes of objects appear in the image?
    <details>
      <summary>Show answer</summary>

      Object Detection

    </details>

* What popular CV task aims to analyze videos to understand human actions?
    <details>
      <summary>Show answer</summary>

      Activity Recognition

    </details>

* What popular CV task is best suited for car counting in parking lots?
    <details>
      <summary>Show answer</summary>

      Object Detection

    </details>

* What popular CV task is best suited for distinguishing buildings, roads, and foliages in satellite imagery?
    <details>
      <summary>Show answer</summary>

      Segmentation

    </details>

* What popular CV task is best suited for sorting applications?
    <details>
      <summary>Show answer</summary>

      Image Classification

    </details>

* What popular CV task is best suited for text detection (OCR)?
    <details>
      <summary>Show answer</summary>

      Image Classification

    </details>

* What popular CV task is best suited for video captioning?
    <details>
      <summary>Show answer</summary>

      Activity Recognition

    </details>

* True or False: The learning objective of reinforcement learning (RL) is to maximize the total cumulative reward.
    <details>
      <summary>Show answer</summary>

      True

    </details>

* In RL, what do you call the information within the environment that is currently visibile, or known, to an agent?
    <details>
      <summary>Show answer</summary>

      State

    </details>

* In RL, what do you call the thing the agent can do in every state in order to be closer to achieving the goal?
    <details>
      <summary>Show answer</summary>

      Action

    </details>

* In RL, what do you call the feedback given to an agent for each action it takes in a given state?
    <details>
      <summary>Show answer</summary>

      Reward

    </details>

* In RL, what do you call the piece of software you are training that interacts with the environment?
    <details>
      <summary>Show answer</summary>

      Agent

    </details>

* In RL, what do you call the surrounding area the agent can interact within?
    <details>
      <summary>Show answer</summary>

      Environment

    </details>

* In RL, what do you call a period of trial and error when an agent makes decisions and gets feedback from its environment?
    <details>
      <summary>Show answer</summary>

      Episode

    </details>

* In RL, what do you call the "incentive plan" that assigns numbers as rewards to different aspects of the current state?
    <details>
      <summary>Show answer</summary>

      Reward function

    </details>

* In RL, the models aren't naturally motivated to gather as many rewards as possible. So, what do you call the thing that tells the model to do so?
    <details>
      <summary>Show answer</summary>

      Model training algorithm or just training algorithm

    </details>

* In RL, what do you call the set of all valid actions available to an agent as it interacts with an environment?
    <details>
      <summary>Show answer</summary>

      Action space

    </details>

For the next two questions, refer to this information: AWS DeepRacer uses 2 training algorithms for RL, Soft Actor Critic (SAC) and Proximal Policy Optimization (PPO).

* Which training algorithm is more stable and works on both discrete and continuous actions spaces but is data-hungry?
    <details>
      <summary>Show answer</summary>

      PPO

    </details>

* Which training algorithm embraces exploration and is more data efficient but lacks stability and only works with a continuous action space?
    <details>
      <summary>Show answer</summary>

      SAC

    </details>

* What is the trade-off for decreasing or increasing the learning rate hyperparameter?
    <details>
      <summary>Show answer</summary>

      The trade-off is faster training time VS higher model quality.

      A higher learning rate makes training time faster but a lower learning rate increases the model quality.

    </details>

* True or False: Discriminative algorithms deal with creating new data from the dataset
    <details>
      <summary>Show answer</summary>

      False

      Generative algorithms deal with creating/generating new data.

    </details>

* True or False: A limitation of generative algorithms is that it can only generate new things based on the style of data it has been trained on.
    <details>
      <summary>Show answer</summary>

      True

      Since data make the model specific, the things the model creates should be based from the data it was trained on.

    </details>

* What popular generative AI model puts two neural networks against each other?
    <details>
      <summary>Show answer</summary>

      Generative Adversarial Networks (GANs)

      The word "Adversarial" means conflict.

    </details>

* Is generative AI a supervised, unsupervised, or reinforcement machine learning task?
    <details>
      <summary>Show answer</summary>

      It is an unsupervised learning task.

      An untrained GAN does not need a labeled dataset. The training occurs by generating a classification problem between the two networks (hence the "Adversarial" in GAN). The labels of this problem are not provided with the data, but a trivial consequence of the training process. Images/audio "Generated" by one part of the network have the trivial label of fake, and the training data the trivial label of real. These are not provided with the data. No person at any point needs to label the data before training. Hence the process as a whole is unsupervised.

      However, there are people who classify it as a "self-supervised" task.

    </details>

* What popular generative AI model relies on previous time data to generate new accurate data?
    <details>
      <summary>Show answer</summary>

      Autoregressive models (AR-CNN)

    </details>

* What popular generative AI model is used on data that is sequential in nature?
    <details>
      <summary>Show answer</summary>

      Transformer-based models

    </details>

* True or False: Generator networks in a trained GAN model need input data to generate new data.
    <details>
      <summary>Show answer</summary>

      False

      Trained generator networks can produce new data without input data.

    </details>

* In GANs, this feedback measures how far the generated data deviate from real data.
    <details>
      <summary>Show answer</summary>

      Generator loss

    </details>

* In GANs, this feedback measures how well the differentiation between real and fake data works.
    <details>
      <summary>Show answer</summary>

      Discriminator loss

    </details>

* In using AR-CNNs in AWS DeepComposer, what do you call the event when a note is added or removed from the input track during inference?
    <details>
      <summary>Show answer</summary>

      Edit event

    </details>

* What do you call the 2D matrix that represents music tracks? Time is on the horizontal axis and pitch is on the vertical axis.
    <details>
      <summary>Show answer</summary>

      Piano roll

    </details>


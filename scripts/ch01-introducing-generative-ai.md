You've probably heard of tools like ChatGPT, Midjourney, Stable Diffusion, and LLaMA. These are quickly becoming household names. Collectively, these tools fall under the category of generative artificial intelligence, or generative AI for short. Generative AI is a unique set of techniques within the larger AI field that create something new—whether it's images, text, or even video. This is different from the more common discriminative AI, which focuses on categorizing new inputs or determining relationships between variables in data.

Generative AI is booming. If you're in business leadership, it's crucial to figure out how to use generative AI to drive growth, boost creativity, and streamline operations in your organization. If you're a developer, you'll want to know how generative AI could impact your work and how you can use it to increase your productivity. And if you're a hobbyist, you might be wondering if generative AI is worth your time to learn and experiment with. This report aims to give you the knowledge and insights you need to navigate the exciting world of generative AI.

Of course, like any new technology, generative AI can be challenging to implement. We'll also cover the ethical, legal, and technological concerns surrounding its use and how some of these issues can be avoided or mitigated. By the end of this report, you'll understand the history, applications, benefits, and potential pitfalls of generative AI. You'll be equipped to incorporate this cutting-edge technology into your daily life, business, or creative projects, evaluate its return on investment, and manage generative AI initiatives effectively.

Now, let's talk about A Brief History of Generative AI.

To understand generative AI and how it works, it's important to know where it came from. Even though it might seem like generative AI appeared out of nowhere in the past year or two, research in this field has been ongoing for decades. Artists and computer scientists were creating programs to generate visual art as far back as the 1970s.

The foundation for generative AI, and much of the discriminative AI you might be familiar with, is the deep neural network. This is a neural network architecture with many layers of neurons, including some hidden layers. Neurons, the base units of a neural network, are mathematical functions that behave like simplified versions of biological neurons. Neural networks were first introduced as early as the 1960s, but they were too computationally intensive to outperform simpler machine learning methods until around 2009. That's when a recurrent neural network, a kind of deep neural network, won several handwriting recognition competitions for the first time.

Improvements in hardware and network architectures over the next few years made deep neural networks a dominant force in machine learning and artificial intelligence, especially in computer vision, where they excelled in tasks like object detection and recognition.

Now, let's consider Modern Generative AI Architectures.

The introduction of the variational autoencoder (VAE) and generative adversarial networks (GANs) in 2014 really kicked off the modern era of generative AI. Before then, deep neural networks were mainly used for classification tasks, but these new architectures allowed them to be used for generative AI.

First, let's talk about Variational Autoencoders.

The VAE network architecture was introduced in the 2014 paper "Auto-Encoding Variational Bayes" by Diederik P. Kingma and Max Welling. In this architecture, two deep neural networks are used: an encoder and a decoder. The encoder learns how to reduce an input into an internal representation called a latent space, while the decoder learns how to reconstruct the input from that internal representation. Both networks learn simultaneously by comparing the difference between the generated image and the input image, known as loss, and trying to reduce that. What sets VAEs apart from similar architectures is that they also try to organize the internal representations so the model can generate something new.

VAEs are used for data generation, data augmentation, and anomaly detection, among other applications. They can generate text and audio data in addition to images.

Next, let's discuss Generative Adversarial Networks.

The GAN architecture was also introduced in 2014, in the paper "Generative Adversarial Nets" by Ian J. Goodfellow and others. Like VAEs, GANs use two deep neural networks: the generator and the discriminator. The generator is fed random noise and generates images from that noise, while the discriminator is trained on real images of interest, such as a large set of pictures of faces, and tries to determine whether an image given to it by the generator or the image source is real or generated. The generator aims to trick the discriminator into predicting the incorrect label for the generated images, while the discriminator aims to accurately label both real and synthesized images. This is a zero-sum game: the better the generator does, the worse the discriminator does, and vice versa.

Also like VAEs, GANs are used for data augmentation, drug discovery, image processing tasks like upscaling, inpainting, and colorizing black-and-white photos, and creating realistic, high-resolution images. A great example of this is the website "This Person Does Not Exist."

Now, let's talk about Seq2seq.

Along with VAEs and GANs, the sequence-to-sequence (seq2seq) architecture was introduced in 2014 by Google for use in machine translation. Models created with this architecture excel at natural language processing (NLP) tasks in general because they are designed to map one sequence to another. Like VAEs, seq2seq models use an encoder-decoder design. But in seq2seq, the outputs of the encoder are discarded, and the hidden or internal states of the networks within the encoder are fed directly to the decoder, which processes the encoder’s internal states, discards its own outputs, and generates its own hidden states. The important innovation with seq2seq models was the addition of an attention mechanism. This enabled the decoder to focus on the most relevant input(s) when generating the output for that part of the input sequence.

Today, seq2seq models are used for chatbots, machine translation (most notably as part of the Google Translate product), text summarization, and more.

Finally, let's consider Transformers.

The major breakthrough that led to the performance of the current state-of-the-art generative AI models was the introduction of the transformer. This was proposed in the 2017 paper "Attention Is All You Need" by Ashish Vaswani and others. This architecture uses an encoder and decoder like seq2seq; however, it uses a set of six encoders and six decoders, with each encoder feeding its output to all six decoders. In a general transformer architecture, any equal number of encoders and decoders can be used. The encoders and decoders use attention layers and simple feed-forward neural networks instead of the sequential networks used in seq2seq. This allows transformers to process input sentences in parallel, making them faster than older architectures, as well as understand to what extent the more distant words in a given input affect the current word being processed.

The transformer architecture revolutionized generative AI, forming the basis of the current large language models (LLMs) available today, such as the GPT family, PaLM, and LLaMA, among others, along with the DALL-E family of image generator models.

Now, let's talk about The Two Types of Generative AI.

From our brief history lesson, you might see some separation in the types of generative AI available: image generators and text generators. These are the most popular types of generative AI, the types that are likely most relevant to you, and the types we will be covering in the remainder of this report.

But for the sake of completeness, it's important to note that researchers, creatives, software companies, and others are also exploring generative AI for making music, videos (such as the opening sequence of Marvel’s Secret Avengers), and other kinds of content. Many of these cutting-edge applications of generative AI are still based on image generators, text generators, or some combination of the two, making them a solid foundation on which to build your own generative AI knowledge.

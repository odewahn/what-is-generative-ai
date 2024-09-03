ChatGPT, Midjourney, Stable Diffusion, LLaMA—you probably have heard of some or all of these tools, which are quickly becoming household names. Collectively, these tools, and many more, are categorized as generative artificial intelligence, or generative AI. Generative AI is a distinct set of techniques within the larger AI field that generate something new: images, text, even video. Generative AI is separate from the more common discriminative AI, which is focused on reliably categorizing previously unseen inputs, classification, or determining the mathematical relationship between a dependent variable and the independent variables that describe some set of data, regression.

Here's a really important point: Generative AI is an exploding field. If you’re in business leadership, it is imperative to determine how to harness generative AI to drive growth, enhance creativity, and streamline operations in your organization. If you’re a developer, you will want to know how generative AI could impact your craft and how you can harness it to boost your productivity. If you’re a hobbyist, you might want to know whether generative AI is worth spending your time to learn and tinker with. This report aims to provide you with the knowledge and insights you need to navigate the exciting realm of generative AI.

Of course, as with other nascent technologies, generative AI can be challenging to implement. To that end, we will also cover the ethical, legal, and technological concerns surrounding the use of generative AI and how some of them can be avoided or mitigated. After reading this report, you will understand the history, applications, benefits, and potential pitfalls of generative AI so that you can incorporate this cutting-edge technology into your daily life, your business, or your creative endeavors; evaluate its return on investment; and implement and manage generative AI initiatives.

Now, let's talk about A Brief History of Generative AI.

To gain a broad understanding of generative AI and how it works, it’s important to understand where it came from. Even though it can feel like generative AI popped up out of nowhere sometime over the past year or two, research in this field has been ongoing for decades, with artists and computer scientists creating programs to generate visual art as far back as the 1970s.

The foundation for generative AI, and much of the discriminative AI that you may be familiar with, is the deep neural network, a neural network architecture that has many “layers” of neurons, including one or more that are hidden from the input and output layers. Neurons, the base units of a neural network, are mathematical functions that behave like a simplified version of a biological neuron. Neural networks were first introduced as early as the 1960s, but they were too computationally intensive to outperform other, simpler machine learning methods until around 2009, when a recurrent neural network, a kind of deep neural network, was able to win several handwriting recognition competitions for the first time ever.

Improvements in hardware and network architectures over the next few years made deep neural networks one of the dominant forces in the world of machine learning and artificial intelligence, especially in computer vision, where they excelled in common tasks like object detection and recognition.

Now, let's talk about Modern Generative AI Architectures.

It was the introduction of the variational autoencoder, VAE, and generative adversarial networks, GANs, in 2014 that really kicked off the modern era of generative AI. Up until then, deep neural networks were used primarily for classification tasks, but with these architectures, they began to be used for generative artificial intelligence.

First, let's discuss the Variational Autoencoder.

The VAE network architecture was introduced in the 2014 paper “Auto-Encoding Variational Bayes” by Diederik P. Kingma and Max Welling. In this architecture, two deep neural networks are used: an encoder and a decoder. The encoder learns how to reduce an input into an internal representation called a latent space, while the decoder learns how to reconstruct the input from that internal representation. Both networks learn simultaneously by comparing the difference between the generated image and the input image, loss, and trying to reduce that. But what sets VAEs apart from similar architectures is that they also try to organize the internal representations such that the model is able to generate something new.

VAEs are used for data generation, data augmentation, and anomaly detection, among other applications, and are capable of generating text and audio data in addition to images.

Next, let's discuss Generative Adversarial Networks.

The GAN architecture was also introduced in 2014, in the paper “Generative Adversarial Nets” by Ian J. Goodfellow et al. Like VAEs, GANs make use of two deep neural networks: the generator and the discriminator. The generator is fed random noise and generates images from that noise, while the discriminator is trained on real images of interest, such as a large set of pictures of faces, and tries to determine whether an image given to it by the generator or the image source is real or generated. The generator is incentivized to successfully “trick” the discriminator into predicting the incorrect label for the generated images, while the discriminator is incentivized to accurately label both real and synthesized images. This is a zero-sum game: the better the generator does, the worse the discriminator does, and vice versa.

Also like VAEs, GANs are used for data augmentation, typically for creating new training and test data for other machine learning models; drug discovery; image processing tasks such as upscaling, inpainting, and colorizing black-and-white photos; and creating realistic, high-resolution images. The latter use is illustrated brilliantly through the website This Person Does Not Exist.

Next, let's discuss Seq2seq.

Along with VAEs and GANs, the sequence-to-sequence, seq2seq, architecture was introduced in 2014 by Google for use in machine translation. Models created with this architecture excel at natural language processing, NLP, tasks in general, though, because they are designed to map one sequence to another. Like VAEs, seq2seq models use an encoder–decoder design. But in seq2seq, the outputs of the encoder are discarded, and the hidden or internal states of the networks within the encoder are fed directly to the decoder, which processes the encoder’s internal states, discards its own outputs, and generates its own hidden states. The important innovation with seq2seq models was the addition of an attention mechanism. This enabled the decoder to focus on the most relevant input(s) when generating the output for that part of the input sequence.

Today seq2seq models are used for chatbots, machine translation, most notably as a part of the Google Translate product, text summarization, and more.

Next, let's discuss Transformers.

The major breakthrough that led to the performance of the current state-of-the-art generative AI models was the introduction of the transformer. This was proposed in the 2017 paper “Attention Is All You Need” by Ashish Vaswani et al. This architecture uses an encoder and decoder like seq2seq; however, it uses a set of six encoders and six decoders, with each encoder feeding its output to all six decoders. In a general transformer architecture, any equal number of encoders and decoders can be used. The encoders and decoders use attention layers and simple feed-forward neural networks instead of the sequential networks used in seq2seq. This allows transformers to process input sentences in parallel, making them faster than older architectures, as well as understand to what extent the more distant words in a given input affect the current word being processed.

The transformer architecture revolutionized generative AI, forming the basis of the current large language models, LLMs, available today, such as the GPT family, PaLM, and LLaMA, among others, along with the DALL-E family of image generator models.

Now, let's talk about The Two Types of Generative AI.

From our brief history lesson, you might be able to see some separation in the types of generative AI available: image generators and text generators. These are the most popular types of generative AI, the types that are likely most relevant to you, and the types we will be covering in the remainder of this report.

But for the sake of completeness, it’s important to note that researchers, creatives, software companies, and others are also exploring generative AI for making music, videos, such as the opening sequence of Marvel’s Secret Avengers, and other kinds of content. Many of these cutting-edge applications of generative AI are still based on image generators, text generators, or some combination of the two, making them a solid foundation on which to build your own generative AI knowledge.

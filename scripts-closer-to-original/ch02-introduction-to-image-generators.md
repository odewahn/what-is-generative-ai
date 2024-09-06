Image generation AI might be one of the most gratifying recent advances in generative AI. With a Discord bot or a web application and some clever words, you can get a unique and ready-made piece of art in no time. Modern image generation AI makes clever use of many of the technologies and processes discussed in Chapter 1, along with some that weren’t introduced, such as latent diffusion, another encoder–decoder architecture.

What is even more exciting about image generators is that they don’t just take a text prompt and create an image to match it. They can also improve existing images with minor text guidance, generate or regenerate selected parts of an existing image, colorize black-and-white photos, and handle other, similar workflows that are often overlooked. Figures 2-1 and 2-2 show the power of image generators, beginning with a simple geometric image and the prompt “A castle on a field surrounded by a moat. Realistic fantasy art, oil painting” and resulting in a significantly higher-quality image that mostly correctly interprets the original.

Brands are experimenting with generative AI for everything from brand design to flavor design. Construction technology startups are using generative AI to prototype building designs. Architects and designers are using image generators to create mood boards and to prototype designs for clients before spending time on the final product. Businesses with high data needs, such as those training their own AI models, are using generative AI to augment their datasets, allowing them to build more accurate discriminative AI models.

Now, let's talk about Image Generation AI Tools.

The number of image generation AI tools out there is staggering. From standalone desktop applications like DiffusionBee to Discord-based tools like Midjourney to application plug-ins like Adobe’s Firefly and Canva’s Text to Image, almost every kind of application interface that exists can be found among the image generators and will be discussed in this section. In this list, I excluded models and approaches themselves, such as GANs, to focus on what you might end up incorporating into your own toolkit right away.

Let's consider Midjourney.

Midjourney may be one of the most popular AI image generators out there, despite its current restriction to being used via a bot within the Discord chat application. Midjourney has several advantages:

First, it is easy to use. Simply provide your prompt to a Discord bot, and get your images back in a reply. Second, it plays host to a huge community built into the Discord server that hosts the Midjourney bot, with 15 million registered users at the time of this writing. Third, it has a relatively simple flat monthly pricing structure. Fourth, it is able to produce great-looking images with relative ease.

There are also some potential weaknesses that could affect your own adoption of Midjourney:

First, it has a strict content moderation policy. Second, it has a smaller feature set than other tools listed here and only supports text-to-image prompting. Third, it is currently restricted to Discord.

Now, let's talk about DALL-E.

Introduced by OpenAI in January 2021, DALL-E is a family of image generation models based on a modified GPT, generative pretrained transformer, model. At the end of 2022, DALL-E 2 was released to public beta with additional capabilities such as higher resolution, inpainting, outpainting, and creating variations of an input image. These new features and quality improvements were enabled by integrating CLIP and a diffusion model, abandoning the GPT approach of its predecessor. DALL-E’s advantages include API access as well as a web application for testing; however, it uses a pay-per-usage pricing model, which can be a benefit or a limitation depending on your use case. API calls are also limited by default to a $120 monthly quota, which at current prices limits you to 6,000 of the highest-resolution images per month. Like Midjourney, this is a hosted service, rather than something you can run on your own infrastructure.

Here's a really important point. CLIP is a model created by OpenAI that is able to predict a natural language description of any given image. This is a major improvement over traditional image classification models that were restricted to labels or descriptions that they were trained with.

Now, let's talk about DreamStudio.

DreamStudio is a web application developed by Stability AI, the same group that created the open source Stable Diffusion model on which DreamStudio is based. In addition to being a web application, DreamStudio has an API available for programmatic use as well as a Blender plug-in. It’s also very accessible to beginners and comes with a prompting guide to help users craft effective prompts. The downside to DreamStudio is that pricing can be complex. DreamStudio offers new users 25 credits, and beyond that $10 will get you 1,000 credits. The credit cost per generated image depends on the model you choose, the generation steps for each image, and the resolution of the generated image.

DreamStudio offers the same features as DALL-E: image generation, inpainting, outpainting, and image variations, along with negative prompts and prompt weighting. While the pricing can be difficult to predict, Stability AI does provide a cost calculator, API availability, model choice, and Blender integration. Another advantage is that it uses a number of open source models.

Now, let's talk about DiffusionBee.

Like DreamStudio, DiffusionBee is based on the open source Stable Diffusion family of models. Unlike DreamStudio, it’s a free and open source desktop application designed for macOS. Although it is easy enough for most users to get up to speed quickly, it provides a large number of options that can be overwhelming. It balances that with prompt ideas for text-to-image generation and helpful explanations of the available options. DiffusionBee is able to do text-to-image and image-to-image generation, a technique that’s also known as variations in other tools, inpainting, and outpainting. Another feature useful for tinkerers is that you can load other open source models into DiffusionBee, allowing you to experiment with image generation and editing more freely.

While DiffusionBee is free, you must run the image generation on your own machine, which, depending on your system, may or may not pose a problem. In my experience with an M1 MacBook Pro, it takes just a few minutes to generate four images with default settings. Figure 2-3 shows the main interface of DiffusionBee, which has tabs for its supported workflows, a prompt input area, as well as settings, prompt ideas, and style suggestions.

Being locally installed, DiffusionBee gives you a lot of power that the previously mentioned tools do not. However, it doesn’t have an available API to build into your own software.

Now, let's talk about Firefly.

Adobe Firefly is one of the first generative AI tools released by a major incumbent company. Using Adobe’s existing application and data infrastructure, Firefly includes many features such as text-to-image generation, inpainting, outpainting, and generation of 2D images from 3D models. Firefly is available both as a standalone web application and as a tool within Adobe’s application offerings, including Photoshop, Illustrator, and Adobe Express. Standalone pricing is credit based: the free plan gives users 25 credits per month, and the premium plan gives users 100 credits per month, removes watermarks, and offers a subscription to Adobe’s Creative Cloud service, which provides additional credits.

Here's a really important point. By “incumbent company,” I mean an existing business that has a product and customer base that predates its adoption of generative AI. This is in contrast to companies such as OpenAI and Stability AI, which were founded to sell generative AI products.

Beyond integration into existing applications, another strength of Firefly is its commercially safe model. The model is trained on existing Adobe stock images, images in the public domain, and images with open licensing structures, which would mitigate one of the most prominent risks of using generative AI: copyright infringement.

Now, let's talk about Text to Image.

In its Text to Image tool, Canva has also folded text-to-image generative AI into its existing design suite, with a free model limited to 50 total queries and a premium model that offers 500 monthly queries. Query-based pricing is simpler to navigate than credit-based pricing, which is a big advantage of Text to Image, but the tool doesn’t come with the same commercially safe dataset that Adobe Firefly does. Canva also offers a Stable Diffusion–powered photo editing tool called Magic Edit that marries AI techniques like inpainting with traditional photo editing tools.

Now, let's talk about Other Tools.

Naturally, this list isn’t exhaustive, nor can it be. With more open source models being released as well as investment dollars flowing to more and more businesses in this space, you can expect to find an explosion of tools aimed at the end user. Keep an eye out for experimentation in the tooling space as the major vendors fight over market share.

Now, let's talk about Problems Facing Image Generation AI.

There are myriad uses and tools available right now for image generation AI models, but as with any new technology, there are also challenges that aren’t always as well publicized as the opportunities are. Some of the challenges include:

First, unresolved questions around permission to use existing images to train generative models and the ownership of the resulting images. Second, tools created to interfere with or block the use of images for training generative models. Third, increasing numbers of AI-generated images in the wild, potentially making training datasets less useful.

Chief among these are ethical and legal concerns: Whose work was the model trained on? Did they consent to the use of that work in training the model? What if my generated image looks too much like existing work? Do I own the images an AI tool generated?

Now, let's talk about Ethics and Copyright.

Many of these questions are still unanswered, and some are unanswerable, but work is being done to clarify issues such as ownership, the rights of creators to not be included in training data, and more. Adobe’s Firefly, mentioned previously, claims to be specifically trained on Adobe’s stock images, images with open licenses, and images in the public domain. This would mitigate the ethical issues around the use of other models that may have been trained on images without permission from the creators. To reduce that risk for all involved going forward, the Coalition for Content Provenance and Authenticity, of which Adobe, Microsoft, and others are a part, is an effort to create and promote a standard provenance credit within digital images that will credit the artist or AI involved in creating it.

The copyright status of AI-generated images is also somewhat of an open question. While there has been a single ruling that proclaimed that AI-generated images with no human guidance aren’t copyrightable, that particular case is still making its way through the appeals process, and it is unclear how much human direction, if any, qualifies AI-generated images to be copyrighted. If you decide to create images with a generative AI tool, you’ll have to decide whether the risk of not being able to copyright those images is worth the tool’s use.

Now, let's talk about Adversarial Tools.

Some people aren’t exactly happy with the new, uncertain landscape brought about by generative AI, and they are working to find ways to protect their creations from being used in a training set without their consent. Some of these tools are adversarial, meaning they attempt to make a given image useless for training or, worse, pollute the entire training set. Only a few of these tools exist now, but it is possible that more will be developed and that future generative AI models may actually be worse than current ones.

The major adversarial technique available right now is glazing, which uses a tool called Glaze to make small changes to an image that purportedly “trick” the training AI into thinking the image is of a style other than that of the artist in question. It’s unclear whether Glaze truly works, and works on all models, but it did set off a sort of arms race with the introduction of a tool that claims to remove those changes published to GitHub in response.

Now, let's talk about Poor Datasets.

The current crop of adversarial tools focuses on poisoning potential training data, but it’s possible that generative models will end up doing this all on their own. Much of the work being done to improve generative models requires building bigger models with larger datasets. For example, Stable Diffusion v1 was trained on a dataset containing nearly 6 billion images. However, there is a limit as to how much data currently exists or could potentially exist to feed these models, and with the proliferation of AI-generated images, and, as we will see, text, newer models may end up being iteratively trained on more and more AI-generated data, with unknown consequences.

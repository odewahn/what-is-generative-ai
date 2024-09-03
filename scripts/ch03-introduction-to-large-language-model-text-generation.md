We've all tried asking computers questions before. I remember the first time I used Ask Jeeves and got frustrated when it gave me websites instead of direct answers. But with the release of ChatGPT and other large language models, the dream of interacting with computers in a natural way is becoming a reality.

Researchers are now using the incredible power of these models to do things like translate languages without extra training, design new drugs, and detect data anomalies and financial fraud. While these applications are exciting, the more immediately practical uses might be even more thrilling because of their widespread potential impact.

Right now, large language models are being used to summarize long documents, rewrite ad copy in different voices, interact with customers via chatbots, write code, simplify writing, and ask questions about documents. In the next section, we'll explore various tools using these models to perform these tasks. We'll start with popular chat tools and their applications, move on to coding and marketing assistants, and then look at knowledge management integration.

Now, let's talk about Text Generation Tools.

There are several tools on the market that let users interact with text-generating large language models. Unlike image generators, you won't find many local-first or local-only tools for these models because of their size and the computational power needed to generate text. This is slowly changing with more efficient models, but most tools currently interact with an external model via an API.

Let's consider ChatGPT.

ChatGPT was publicly released by OpenAI in November 2022, and for many, it was their first exposure to generative AI. It uses OpenAI’s GPT family of models, trained on data from across the internet and fine-tuned for conversational responses. A key part of ChatGPT’s success is a technique called reinforcement learning from human feedback, or RLHF. This uses feedback from human trainers to develop a reward system that encourages responses preferred by humans. For ChatGPT, this means friendlier, more conversational responses and avoiding illegal or harmful activity.

Another key to ChatGPT’s success is its user-friendly interface. By focusing on a conversational interface, OpenAI has made the power of its models clear. OpenAI also offers a tiered subscription model: free for personal use, a paid premium plan for $20 per month, and an enterprise plan with no usage limits and more features. They also provide an API for integrating ChatGPT with your own applications.

Next, let's talk about Bard.

Google released Bard in March 2023 in response to ChatGPT’s popularity. The initial rollout had issues with inaccurate responses, but improvements and changes, like moving to the newer PaLM model and integrating with Google’s products, are setting Bard apart. Bard is currently free but marked as an experiment, with warnings that your conversations will be used to improve Google services and seen by human reviewers for training future models.

Now, let's discuss Claude.

Anthropic’s Claude models come in a familiar chat assistant interface, but their real power lies in API access. They focus on performance and safety, with one of the largest available context windows at 100,000 tokens. Claude uses a technique called constitutional AI, which relies on a human-provided list of rules during the model’s learning phase, rather than human feedback. This protects human moderators from harmful material while improving the model’s responses. Claude’s pricing model is similar to ChatGPT’s, with free limited access, a $20 monthly pro plan, and a separate API pricing plan billed per 1 million tokens.

Next up, let's consider Copilot.

Copilot is a generative AI programming assistant based on the GPT family of models, fine-tuned on publicly available code from GitHub. It functions as an advanced autocomplete, using code comments and function signatures as context to write the code itself. It’s available as a plug-in for most popular code editors. Copilot won’t replace programmers because hallucinations are still an issue, and skilled programmers are needed to detect subtle bugs. Pricing is straightforward: $10 per month for individuals or $100 per year, and $19 per user per month for businesses.

Now, let's talk about Cody.

Sourcegraph’s Cody is another generative AI programming assistant with features beyond code generation, like explaining code, creating unit tests, and optimizing existing code. Cody uses embeddings, a technique from natural language processing, to intelligently select the most appropriate code snippets for query context. Sourcegraph has a zero-retention policy with its third-party LLM partners, meaning they won’t retain any model inputs or outputs. Cody is currently in beta, with a free tier for individual developers and an enterprise tier with more features.

Next, let's discuss Jasper.

Jasper is a marketing-focused generative AI tool that aims to be a one-stop shop for marketing content creation. It leverages several models like GPT-4, Claude, Bard, and its own internal model to generate marketing campaigns, translate copy, write blog posts, and more. Jasper claims its platform can learn any brand’s voice and accurately recreate it in the generated copy. Pricing is tier-based: $49 per month for single users, $125 per month for teams of up to three users, and an enterprise tier.

Now, let's consider Sensei GenAI.

Sensei GenAI is Adobe’s answer to generative AI marketing products like Jasper. It leverages several different LLMs and can incorporate a user’s existing data. Sensei’s features include brand-specific chatbots, sales conversation summaries, and a natural language interface to brand data analytics. Unlike other tools, Sensei GenAI only offers a demo request form, highlighting Adobe’s focus on large enterprise customers.

Next, let's talk about Notion AI.

Notion is a popular knowledge management application, and Notion AI is a paid add-on that handles many common text generation tasks like summarization, translation, tone editing, and more. Notion AI is built directly into Notion, making it easy for existing users. Pricing is user-friendly: every user has a number of free AI actions before paying $10 per user per month.

Now, let's discuss Prompt Engineering.

Prompt engineering is the process of writing prompts for generative AI models using natural language. Techniques fall into categories like zero-shot, one-shot, or few-shot prompting. Zero-shot prompting is when you directly ask the model a question with no examples. One-shot prompting adds a single example to guide the model. Few-shot prompting uses several examples to guide the output. For end users, prompt engineering can become a discipline unto itself and should be factored into any ROI calculations.

Now, let's talk about Problems Facing Text Generation AI.

While the potential uses of text generation AI are exciting, there are risks and pitfalls to be aware of.

First, let's consider Hallucinations.

Hallucinations occur when an AI tool gives a confidently wrong answer. This can be a problem if you’re using a chatbot for customer support or relying on an LLM for factual data without expert review. Mitigation tactics include human review or writing prompts with more context and constraints. Retrieval-augmented generation, or RAG, can also help by enriching prompts with contextual information from vector databases.

Next, let's discuss Data Safety.

Data safety is a major concern. Most interactions with these models occur via an API on third-party infrastructure, which can lead to IP or sensitive information being leaked. Companies selling access to LLM tools have data safety policies, but users must be vigilant about not leaking sensitive information.

Now, let's consider Ethics and Copyright.

Text generation AI faces ethical and copyright issues, especially around training data provenance and attribution. There are lawsuits concerning whether using existing works in training data without consent is copyright infringement. It’s also unclear whether anything produced by text generation AI can be copyrighted.

Finally, let's talk about Prompt Injection.

Prompt injection attacks are a risk, similar to SQL injection attacks. Direct prompt injection, or jailbreaking, involves crafting prompts to bypass model restrictions. Indirect prompt injection involves using external sources like files or web pages to control the LLM.

To wrap up, you should now have a solid foundation in the current state of generative AI. This will help you evaluate available tools, see if they match your use cases, and dive deeper if you choose. This is a rapidly growing and exciting field, and I hope you continue to learn and use generative AI more effectively while pushing the boundaries of what is possible.

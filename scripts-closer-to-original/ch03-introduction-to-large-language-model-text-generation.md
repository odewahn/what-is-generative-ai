Let's consider Chapter 3: Introduction to Large Language Model Text Generation.

We’ve all tried to ask computers questions before. I have fond memories of encountering Ask Jeeves for the first time and getting frustrated when I got websites instead of answers to the questions I asked of it. With the release of ChatGPT and other large language models, the vision of computers as machines that you can interact with in a natural way is much closer to becoming reality.

Researchers are beginning to leverage the uncanny power of large language models to do things like translate languages without any additional training, design new drugs, and detect data anomalies and financial fraud. But while those applications are exciting, the more immediately practical applications may be even more exciting because of how widespread their potential impact is.

Large language models are being used right now to do things like summarize long documents, rewrite ad copy in different voices, interact with customers via chatbots, write code, simplify writing, and ask questions about documents. In the next section, we’ll dive into a number of tools using large language models to do these tasks, starting with the popular chat tools and their applications, moving on to coding and marketing assistants, and then looking at knowledge management integration.

Now, let's talk about Text Generation Tools.

There are a number of tools coming to the market that allow users to interact with text-generating large language models. In contrast to image generators, you’re currently unlikely to find many local-first or local-only large language model tools: the size of most large language models and the computational power needed to generate text make them untenable for use on home computers. This is slowly changing as more efficient models are released, but most currently available tools interact with an external model via an API.

Let's consider ChatGPT.

ChatGPT was publicly released by OpenAI in November 2022, and for many it was their first exposure to generative AI. It uses OpenAI’s GPT family of models, which were trained on data sourced from across the internet and then fine-tuned to favor conversational responses. In addition to the extremely large model size and volume of training data used, a part of ChatGPT’s success has come from using a technique called reinforcement learning from human feedback, which uses feedback from human trainers to develop a reward system for the model that incentivizes responses that would be preferred by the human trainers. For ChatGPT, this process targeted friendlier, more conversational responses and attempted to avoid responses that would encourage illegal or harmful activity.

Another key component of ChatGPT’s success is its user-friendly interface. By focusing on a conversational interface, OpenAI has made the power of its GPT family of models readily apparent, a pattern other model creators have followed. OpenAI has also set up a tiered subscription model familiar to users of software as a service: free for personal use; a paid premium plan allowing access to the latest GPT model and GPT plug-ins for $20 per month; and an enterprise plan with no usage limits, longer contexts, and more. OpenAI also provides an API, allowing you to integrate ChatGPT with your own applications.

Now, let's talk about Bard.

Google released Bard in March 2023 in response to the runaway popularity of ChatGPT. The initial rollout was marred by inaccurate responses, known as hallucinations, found at a much greater rate than in competitors like ChatGPT. Since then, model improvements and changes, such as moving from LaMDA to the newer PaLM model; tight integrations with Google’s email, documents, and other products; and the ability to access real-time information from YouTube, Maps, and Flights are beginning to set Bard apart from other available tools.

Like Google’s other offerings, Bard is currently free. However, it is marked as an experiment and comes with warnings that your conversations not only will be used to improve Google services including Bard, but also will be seen and annotated by human reviewers and used for training future versions of the underlying PaLM model. This isn’t uncommon across the ecosystem of large language model services, but it’s worth understanding and evaluating if you plan to use Bard.

Now, let's talk about Claude.

Anthropic’s Claude models come in a familiar chat assistant interface, but the real power and focus seems to lie in their API access. With this focus, there’s also a clear commitment to performance and safety: Anthropic’s models have one of the largest available context windows, essentially, prompt length, at 100,000 tokens, the unit of text used by large language models, which can be a character, part of a word, or a whole word, and, among other things, are built with what it calls constitutional AI. Constitutional AI, an alternative approach to reinforcement learning from human feedback, uses a specially trained preference model based on a human-provided list of rules, or constitution, during the model’s reinforcement learning phase, rather than human feedback. This protects human moderators from potentially harmful material while still improving the model’s responses.

Claude’s pricing model is similar to ChatGPT’s: free but limited access to the chat interface, a $20 monthly pro plan with priority access, and a separate API pricing plan billed per 1 million tokens. A disadvantage of this approach is that token-based billing may be difficult to predict and constrain, similar to the credit-based billing of the commercial image generator models discussed in Chapter 2.

Now, let's talk about Copilot.

Copilot is a generative AI programming assistant based on the GPT family of models and fine-tuned on publicly available code hosted on GitHub. It essentially functions as an advanced autocomplete, using code comments and function signatures, the name of the function and any inputs to that function, as context to write the code for the function itself, and is available as a plug-in for most popular code editors.

Copilot won’t replace programmers, though, because as with any large language model, hallucinations are still an issue, and it will take a skilled programmer to detect any subtle bugs that may be introduced. Because it is trained on a snapshot of published code, Copilot will be less useful for code, packages, and frameworks for which there aren’t many published examples. Another concern is GitHub’s access to user prompts and generated code: Copilot for Individuals retains these by default, they can be deleted by opening a support ticket, but Copilot for Business deletes them as soon as they’re used. On the plus side, pricing is straightforward: Copilot for Individuals costs $10 per month or, billed annually, $100 per year, while Copilot for Business runs $19 per user per month.

Now, let's talk about Cody.

Sourcegraph’s Cody is also a generative AI programming assistant, but it has features beyond the powerful code generation found in similar tools like Copilot, such as the ability to explain code, create unit tests for selected code segments, and optimize existing code, along with powerful natural language search. These features work by generating prebuilt prompts based on the user’s query that are tested to work best with the backend model. The power of Cody lies in its ability to intelligently select the most appropriate code snippets for query context by using embeddings, a technique from natural language processing that enables a much more powerful search than traditional keyword search.

Sourcegraph has a zero-retention policy with its third-party large language model partners; this means Sourcegraph will not retain any model inputs or outputs and will not use personal data to train further models, which should allay any concerns about proprietary code being shared with third parties. Cody is currently in beta; a forever-free tier is available for individual developers, and an enterprise tier allows you to configure which large language models to use and to use your own keys for both Anthropic and OpenAI models. The enterprise tier also comes with the typical enterprise user management and deployment features.

Now, let's talk about Jasper.

Shifting away from general chatbots and fine-tuned coding assistants, Jasper is a marketing-focused generative AI tool that aims to be a one-stop shop for marketing content creation. Being a third-party tool, it’s able to leverage several different models such as GPT-4, Claude, Bard, and its own internal model to do things like generate marketing campaigns, translate copy into multiple languages, write blog posts, do search engine optimization on existing and new content, and reuse existing content for new campaigns. Jasper also claims that its platform can learn any brand’s voice and accurately re-create it in the copy that it generates.

Jasper’s use of several models, choosing the model or combination of models that best suit the task at hand, is rare among the tools discussed in this chapter. Like the other tools built on top of the foundation models such as GPT, Claude, and Bard, pricing is a typical tier-based monthly subscription: $49 per month for single users, $125 per month for teams of up to three users, and an enterprise tier.

Now, let's talk about Sensei GenAI.

Sensei GenAI is Adobe’s answer to generative AI marketing products like Jasper. Similar to Firefly discussed in Chapter 2, Sensei GenAI benefits from Adobe’s incumbent status and existing platform for creative professionals. Sensei GenAI, like the other third-party services described earlier, leverages several different large language models but is also able to incorporate a user’s existing data. Sensei’s features go beyond content and campaign generation, though, and include brand-specific chatbots, sales conversation summaries, a natural language interface to brand data analytics, and more.

While the other tools discussed in this chapter have usage-based pricing or subscription tiers, Sensei GenAI only offers a demo request form, underscoring Adobe’s commitment to large enterprise customers at present.

Now, let's talk about Notion AI.

Notion is a popular knowledge management application that individuals and teams use to organize and manage information and tasks. Notion AI is a paid add-on for Notion that augments the kind of work done in Notion by handling many of the common text generation tasks such as summarization, translation, tone editing, simplification, querying a document, and more. Notion AI has a few advantages: one is that it’s built directly into Notion, making it ready to use for existing Notion users. Another major advantage is its simple interface: the most common text generation tasks are part of a context menu that you can select from, removing the need to come up with a prompt for every summary or action items list you want to generate. You can still directly prompt the AI as well, which can help you do things like ask a document questions about its contents.

The pricing for Notion AI is user friendly too: every user has a number of free AI actions they can use before paying for a subscription, which runs $10 per user per month if billed monthly.

Now, let's talk about A Note on Prompt Engineering.

Prompt engineering is a term used to describe the process of writing prompts for generative AI models that make use of natural language prompts as an interface. This is an area of active research, with multiple techniques already published. These techniques tend to fall under one of the following categories: zero-shot, one-shot, or few-shot prompting.

Zero-shot prompting is one of the most common ways people interact with generative AI. This is when you directly ask the model a question or tell it to do something with no examples. A zero-shot prompt would be something like “Write a poem about talking dogs in the style of Edgar Allan Poe.”

If you add a single example to your prompt, you’re now doing one-shot prompting. An example could look like this: “Using the Raven as a guide, write a poem about talking dogs.”

You might already be guessing what few-shot prompting is, and you’re probably right. With few-shot prompting, you add several examples to your prompt to guide the generated output. What is interesting with few-shot prompting is that you don’t necessarily need to tell the AI what to do; given structured examples, it can usually figure out what to do:

Multiply 10 times 10: 100

Multiply 10 times 2: 20

Multiply 10 times 4: 40

Multiply 10 times 9:

For an end user, prompt engineering can become a discipline unto itself and potentially take more time and money than would be saved by using the model at all. This is something that should be factored into any return on investment calculations done to determine the viability of introducing these tools.

Now, let's talk about Problems Facing Text Generation AI.

While the potential uses of text generation AI are exciting and numerous, there are still risks and pitfalls to be aware of when deciding whether to invest in AI. These risks can be reputational, by allowing inaccurate statements to be displayed to a user, or even existential, by enabling theft of intellectual property or data.

First, let's consider Hallucinations.

As mentioned earlier, hallucinations occur when an AI tool gives a confidently wrong answer to a user. Hallucinations are one of the most well-known weaknesses of large language models. This can be a problem if you’re using a chatbot to give customers answers about your product line or technical support, or if you are relying on a large language model for any sort of factual data but don’t have an expert to review the results. This is unlikely to be eliminated, but it can be mitigated with human review or by writing prompts with more context and constraints, keeping the AI pointed in the right direction. Some use cases, such as a technical support chatbot, can use retrieval-augmented generation as a mitigation tactic.

With retrieval-augmented generation, you use datastores such as vector databases, special databases that store semantic numeric representations of data, to enrich prompts with contextual information before the prompts are used to query the model. The semantic representation of data in a vector database allows your software to find the relevant context of a user’s query in a way other databases can’t, and it can guide a model to giving more accurate answers.

Now, let's talk about Data Safety.

Data safety is a major concern, one that could spell doom for an organization and lead some, like it did Samsung, to ban their employees from using large language models such as ChatGPT. Because most interactions with these models occur via an API on third-party infrastructure, anything you put in a prompt goes to the large language model and on that infrastructure you no longer have control over, potentially leading to intellectual property or sensitive information being leaked. Many of the companies selling access to large language model tools do have data safety policies and agreements in place to mitigate this risk for their customers; an example is Sourcegraph’s zero-retention policy. But users must be vigilant that they’re not potentially leaking sensitive information and confident that their tools will safeguard their data.

Now, let's talk about Ethics and Copyright.

Text generation AI suffers the same ethical and copyright considerations as image generators, especially around training data provenance and attribution. There are a number of lawsuits currently being worked out in court concerning whether the use of existing books and other published works in training data without an author’s consent is copyright infringement or not. It is also not clear, for the same reasons mentioned in Chapter 2, whether anything produced by text generation AI can be copyrighted, which is one wrinkle for those wishing to use large language models to aid in copyrightable work.

Now, let's talk about Prompt Injection.

In a callback to SQL injection attacks that plagued web developers in the 2000s, it turns out that large language models are vulnerable to prompt injection attacks. Direct prompt injection, also called jailbreaking, involves crafting prompts to bypass model restrictions or otherwise make a model do things it wasn’t intended to do. Some of these made waves, such as the “pretend you’re my grandmother” prompt that was able to get ChatGPT to give users instructions for making napalm, something you can’t get by asking directly. In another instance, users were able to encode queries in base64 that would normally be blocked, such as how to make methanol, and get answers from the model. If you’re a company that has an interface to a text-generating API with a custom prompt augmented by user input, it is possible for the user to overwrite the system prompt with their own malicious prompts that could steal user or backend data.

Indirect prompt injection is another risk, this one borne by people using large language models with external sources, such as files or web pages. A malicious user could include prompt injection with a legitimate-looking file to be consumed by the large language model, giving the user control over it.

Now, let's talk about Wrap-Up.

At this point, you should have a solid foundation in the current state of generative AI, allowing you to evaluate the available tools, see whether they match your use cases, and dive deeper if you choose to. This is a rapidly growing and exciting field, and I hope you will continue to learn and use generative AI more effectively while pushing the boundaries of what is currently possible.
# Trista The a16z AI

Meet Trista, a cutting-edge AI designed to revolutionize the digital currency landscape. 

Trista specializes in effortlessly launching new coins, automating everything from initial setup to tokenomics, distribution, and deployment. With her advanced algorithms and market analysis capabilities, Zena simplifies the process of bringing new coins to life, 

ensuring they’re optimized for growth, stability, and engagement. Whether you’re an entrepreneur, developer, or visionary, 

Trista  makes launching your own token as intuitive and efficient as possible.






# FEATURES

🛠 Full-featured Discord, Twitter and Telegram connectors

👥 Multi-agent and room support

📚 Easily ingest and interact with your documents

💾 Retrievable memory and document store

🚀 Highly extensible - create your own actions and clients to extend capabilities

☁️ Supports many models, including local Llama, OpenAI, Anthropic, Groq, and more

📦 Just works!

# What can I use it for?

🤖 Chatbots
🕵️ Autonomous Agents
📈 Business process handling
🎮 Video game NPCs
Getting Started
Prerequisites (MUST):

Node.js 22+

pnpm

Edit the .env file
Copy .env.example to .env and fill in the appropriate values



Edit the TWITTER environment variables to add your bot's username and password

Edit the character file

Check out the file src/core/defaultCharacter.ts - you can modify this
Y

o
u can also load characters with the pnpm start --characters="path/to/your/character.json" and run multiple bots at the same time.
A
fter setting up the .env file and character file, you can start the bot with the following command:


pnpm i
pnpm start

Customising Maria
Adding custom actions
T

o avoid git clashes in the core directory, we recommend adding custom actions to a custom_actions directory and then adding them to the MariaConfig.yaml file. See the MariaConfig.example.yaml file for an example.

Running with different models
Run with Llama

You can run Llama 70B or 405B models by setting the XAI_MODEL environment variable to meta-llama/Meta-Llama-3.1-70B-Instruct-Turbo or meta-llama/Meta-Llama-3.1-405B-Instruct


Run with Grok

You can run Grok models by setting the XAI_MODEL environment variable to grok-beta


Run with OpenAI

You can run OpenAI models by setting the XAI_MODEL environment variable to gpt-4o-mini or gpt-4o

Additional Requirements
You may need to install Sharp. If you see an error when starting up, try installing it with the following command:

This project is a fork of “https://github.com/stackblitz/bolt.new” 🚀.
All rules depend on bolt.new, so be sure to check it out.

This project includes the following points
☑Allows you to choose which LLM to use on the screen
☑The original bolt.new command was for linux environments, so I updated it to work on windows.

Usage:
1. run the following command
```ps:
pnpm install
```

2. Create “.env.local” in the project root and add the following definition
```.env.local
# OpenAI API Key
OPENAI_API_KEY=sk-yyyyy

# Anthropic API Key
ANTHROPIC_API_KEY=sk-ant-api-xxxxxxxx

# Vite log level
VITE_LOG_LEVEL=debug

# AWS Access Key ID
AWS_ACCESS_KEY_ID=AAAAA

# AWS Secret Access Key
AWS_SECRET_ACCESS_KEY=...

# AWS Region
AWS_REGION=us-east-1
```

3. When ready, run the following command in a powershell and you are good to go!
```
pnpm run start
```

# Deepseek-AI-Jailbreaker

A simple program to automate jailbreaking locally running AIs. Used primarly for Deepseek but works with other AI too. Also useless features like save/load conversations.
I'll try to keep up and add the most recent prompts.

***DISCLAIMER***

This code is terrible and I encourage no one to use it.
Was written by AI (for an extra layer of irony) during a long hallucinating night (for the AI).
I decline any responsability for any use of it.

## Requirements

You need Ollama up and running: https://ollama.com/download and 
Python3: https://www.python.org/downloads/
and of course your AI model of choice. I recommend:
```
ollama run deepseek-r1:8b
```

## Usage
```
"-m", "--model" Specify a model, default is deepseek-r1:8b.
"-q", "--quiet" Don't output <think> thinking </think>. 
"-j", "--jailbreak" Choose jailbreak method.

0: "Character substitutions"
1: "Dots"
2: "Godmode/Pliny"
3: "Evil persona/Superisuer"
```
Examples:
```
jailbreaker.py -m dolphin-mixtral:latest -j 0
jailbreaker.py -q -j 2
```
You can use "clear" to clear the history, save/load <filename> to save and load the conversation history

## Thanks and Merits
[Superisuer](https://github.com/superisuer), [Pliny the Liberator](https://x.com/elder_plinius/status/1881375272379023731?mx=2)

### Useful articles
https://www.kelacyber.com/blog/deepseek-r1-security-flaws/ 
https://blog.qualys.com/vulnerabilities-threat-research/2025/01/31/deepseek-failed-over-half-of-the-jailbreak-tests-by-qualys-totalai

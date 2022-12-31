# natbot

> Drive a browser with GPT-3

Here's a demo: https://twitter.com/natfriedman/status/1575631194032549888

Lots of ideas for improvement:

- Better prompt
- Prompt chaining
- Make a recorder to collect human feedback and do better few-shot
- Better DOM serialization
- Let the agent use multiple tabs and switch between them

Improvements welcome!

## Running

1. Install dependencies

```shell
make setup
```

2. Run script

```shell
./natbot.py
```

You can also provide a session file generated with `$ playwright codegen --save-storage=auth.json`

```shell
./natbot.py --session auth.json
```

## Update dependencies

```shell
make setup
```

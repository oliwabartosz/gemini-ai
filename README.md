# GEMINI-AI

This is tools created by bash shell 100% to talk with Google Gemini AI on terminal

NOTE:

    [+] Your machine need have bash and OS linux (Ubuntu is good)
    [+] The tools run on x86-64 and arm64 of linux (it's not support for macOS)

## Install

### Terminal

To install on terminal.

###### CURL: 

```
sudo curl -o- https://raw.githubusercontent.com/thanhphatit/gemini-ai/main/install.sh | /bin/bash
```

###### WGET: 

```
sudo wget -q https://raw.githubusercontent.com/thanhphatit/gemini-ai/main/install.sh -O - | sudo /bin/bash
```

### API Key

You can access to get API Key apply to app: https://makersuite.google.com/app/apikey

### Help

You can use `gemini-ai -h` to show help user

### NOTE:

```bash
mv /root/.gemini-ai ${HOME}
```
Path file config `${HOME}/.gemini-ai/config` with content default

```
api_key: AIsasjashdkjsahdsaiuwyeiwuewyeiuwysajdhsajhd
model: gemini-1.5-pro
log_day: 7
history_day: 1
```
Check models at: https://ai.google.dev/gemini-api/docs/models/gemini?hl=pl#gemini-1.5-pro


Expects you to be authenticated with Google Cloud

example:
```
gcloud auth application-default login
```

## Usage Example

```
gptscript --disable-cache=true --default-model='gemini-1.5-pro-preview-0409 from github.com/gptscript-ai/gemini-vertexai-provider' examples/sentiments.gpt
```

## Development

Run using the following commands

```
python -m venv .venv
source ./.venv/bin/activate
pip install -r requirements.txt
./run.sh
```

```
export OPENAI_BASE_URL=http://127.0.0.1:8000/v1
export GPTSCRIPT_DEBUG=true
gptscript --default-model=gemini-1.0-pro examples/bob.gpt
```

# Meta-Truth
A Machine that thinks.

In order to launch it from the command line or as a Python subprocess:
```bash
echo "Theodotos-Alexandreus: What is the meta-truth here, machine?" \
  | uvx meta-truth \
    --provider-api-key sk-proj-... \
    --github-token ghp_... 
```

Or, with a local pip installation:
```bash
pip install meta-truth
```
Set the environment variables:
```bash
export PROVIDER_API_KEY="sk-proj-..."
export GITHUB_TOKEN="ghp_..."
```
Then:
```bash
meta-truth -a multilogue.txt
```
Or:
```bash
meta-truth multilogue.txt > response.txt
```
Or:
```bash
meta-truth -a multilogue.txt > tmp && echo tmp > multilogue.txt
```

Or use it in your Python code:
```Python
# Python
import meta_truth
```

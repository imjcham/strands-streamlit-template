# Strands + Streamlit Template

A minimal template for integrating [Strands Agents](https://strandsagents.com/latest/) with Streamlit.

## Setup

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Usage

The app creates a chat interface that communicates with Strands AI agents using the standard pattern:

```python
from strands import Agent
agent = Agent()
agent("Your question here")
```
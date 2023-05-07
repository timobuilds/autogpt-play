
## Intro to Langchain
Exploring use of sequential chains of prompts, memory, and tools in Langchain.



## Installation

#### 1. Clone the repository

```bash
git clone https://github.com/your-username/autogpt-play.git
```

#### 2. Create a Python environment

Python 3.6 or higher using `venv` or `conda`. Using `venv`:

``` bash
cd autogpt-play
python3 -m venv env
source env/bin/activate
```

Using `conda`:
``` bash
cd autogpt-play
conda create -n autogpt-play-env python=3.8
conda activate autogpt-play-env
```

#### 3. Install the required dependencies
``` bash
pip install -r requirements.txt
```

#### 4. Set up your keys in a .env file

First, create a `.env` file in the root directory of the project. Inside the file, add your OpenAI API key:

```makefile
OPENAI_API_KEY="your_api_key_here"
```

Save the file and close it. In your Python script or Jupyter notebook, load the `.env` file using the following code:
```python
from dotenv import load_dotenv, find_dotenv
load_dotenv(find_dotenv())
```

Access the `OPENAI_API_KEY` as an environment variable:
```python
import os
api_key = os.environ['OPENAI_API_KEY']
```

You're set!

x Timo


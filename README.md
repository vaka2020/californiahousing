# California Housing

## Software and Tools Required

1. [Github Account](https://github.com)
2. [Heroku Account](https://heroku.com)
3. [Git CLI](https://git-scm.com/downloads)
4. [VS Code](https://code.visualstudio.com)

## Create a New Virtual Environment

Creating a virtual environment prevents installing packages globally and keeps your project dependencies isolated.

### Using Conda

```bash
# Create virtual environment
conda create -p venv python==3.7 -y

# Activate the virtual environment
conda activate venv/
```

### Using Python venv

```bash
# Create virtual environment
python -m venv venv

# Activate on Windows
venv\Scripts\activate

# Activate on Mac/Linux
source venv/bin/activate
```

## Installing Packages

```bash
pip install -r requirements.txt
```

Or install individual packages:

```bash
pip install requests
```

## Saving Dependencies

Save all installed packages to a requirements file:

```bash
pip freeze > requirements.txt
```

## Project Setup

1. Clone the repository
2. Create and activate virtual environment
3. Install dependencies: `pip install -r requirements.txt`
4. Run the project
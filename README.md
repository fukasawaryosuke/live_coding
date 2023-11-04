# Python Live Coding Environment Setup

## Requirements
- Python
- FoxDot
- sc3-plugins 
- SuperCollider
- Git

## Python

For Python, we recommend using Anaconda with version 3.10.

```
conda create -n py310 python=3.10
conda activate py310
```

## FoxDot

```
pip install FoxDot
pip install --upgrade FoxDot
```

## sc3-plugins 

https://github.com/supercollider/sc3-plugins/releases/tag/Version-3.13.0.

## SuperCollider

https://supercollider.github.io/.

1.　Launch SuperCollider.

2.　Run the following command to find the folder path.

```
Platform.userExtensionDir
```

3.　Place the downloaded sc3-plugins in the identified folder path.

4.　Restart SuperCollider.

5.　install the FoxDot Quark.

```
Quarks.install("FoxDot")
```

## Running FoxDot

1.　Run the following command in SuperCollider to start FoxDot.

```
FoxDot.start
```

2.　Run the following command in your terminal to run FoxDot.

```
python -m FoxDot
```

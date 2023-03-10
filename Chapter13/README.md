# Chapter 13 - Inference and Advanced Transforms

This folder contains the code examples referenced in Chapter 13 - Inference and Advanced Transforms.

## Exporting Trained Models with elasticsearch-py

The script `export_model.py` in this repository contains the code to export a trained model.
To run the script follow these instructions. 


1. Create a virtual environment to manage your Python dependencies

```
python3 -m venv env
```

To read more about managing Python dependenvies and various options you have, head over to
[here](https://docs.python-guide.org/). 

2. Activate your environment by running

```
source env/bin/activate
```

If you chose your own name for the environment in step 1, substitute that here instead of `env`. 

3. Install the requirements from the `requirements.txt` file.

```
pip install -r requirements.txt
```

4. Once the requirements have been installed, you are ready to run the script.
Run the command below to see all of the commandline arguments that the script accepts.

```
python export_model.py --help
```

5. Make note of the arguments you need to change, for example, to point the script to work with your particular instance of Elasticsearch.
Then run the script above again passing in the suitable arguments. 

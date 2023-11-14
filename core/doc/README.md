# Building the Sphinx Documentation

We can compile and build the docs using pipenv.
From the root of the docs folder:

```
# Configure the environment
python3 -m pip install --user --upgrade --quiet pipenv==2023.7.23 -r requirements.txt

# Run the builder
$ python3 -m pipenv run sphinx-build . output
```
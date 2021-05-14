## About
This repository can be used as a starting point for python projects. Pre-commit hooks, isort, black, flake are setup.

### How to use
- Create a bare clone of the repository.
	```
	$ git clone --bare https://github.com/lifelonglearner127/python-template.git
	```
- Mirror-push to the new repository.
	```
	$ cd python-template
	$ git push --mirror https://github.com/exampleuser/new-repository.git
	```

- Remove the temporary local repository you created earlier.
	```
	$ cd ..
	$ rm -rf python-template
	```

### Setup
- Clone your own repository
    ```
    git clone https://github.com/exampleuser/new-repository.git
    cd new-repository
    ```
- Update `name` or `author` in `pyproject.toml`.
- Intall Dependencies
    ```
    poetry install
    poetry shell
    pre-commit install
    ```

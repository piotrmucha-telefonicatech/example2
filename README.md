Run `uv init` to create a new project
```
uv init example
```
or `uv init --package example-pkg` to create package type app

`uv` automatically creates .venv


Run below to execute the app (assuming we are in folder C:\Users\Piotr.Mucha\Repos\LearningRepos\UV_POC\example-pkg)
```
uv run example-pkg
```

Run uvicorn to initilise the server
```
uv run uvicorn example_pkg:app --reload
```
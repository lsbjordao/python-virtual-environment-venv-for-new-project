# Create a virtual environment (venv) for a new Python project

For Windows.

## Creating a new environment

Access the directory in which the project will be created, and type:

```bash
python -m venv projectName
```

A `projectName` directory will be created.

## Activating the venv

- Navigate to the `projectName\Scripts` directory, and type:

```bash
.\Activate.ps1
```

You should see `(projectName) {{projectName path}}` at the prompt.

## Deactivate the venv

- Navigate to the `projectName\Scripts` directory, and type:

```bash
deactivate
```
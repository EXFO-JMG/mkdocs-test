
# Installation

```bash
poetry install mike --group dev
```

# Configuration

Add this section in the **mkdocs.yml** file.

```yaml
extra:
  version:
    provider: mike```
```

# Publish a version

```bash
poetry run mike deploy --push --update-aliases 0.5.0 latest
```

 poetry run mike deploy --push 0.6.0

# Set default version

```bash
poetry run mike set-default 0.5.0 
```

# List all version

```bash
poetry run mike list 
```

# Run web site with Mike locally

```bash
poetry run mike serve -a localhost:8001 
```



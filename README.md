# recipe_mcp
[Cookiecutter](https://cookiecutter.readthedocs.io/en/stable/) recipe to create a [Model Context Protocol](https://modelcontextprotocol.io/introduction) (MCP) tool for use by a large language model.

- The MCP should execute inside a sandboxed container
    - Strictly limit access to local file system, network, executables, running processes
    - No elevated permissions

## To Do
- [ ] Create a Docker / Podman container with pre-approved library versions
- [ ] Figure out how to map host directories to
    - Configuration files
    - Logging output
    - Source code
    - Tainted data files
- [ ] Decide how to handle the static files (best practices, etc)
- [ ] Figure out how to create a new git repository as part of the cookiecutter install


- README.md
    - source tree layout
- PROJECT.md
    - tools and how to use them
- pyoroject.toml
    - standard dependencies 
    - set entry point for main
    - Use 'src/' layout
- uv.lock
- .gitignore


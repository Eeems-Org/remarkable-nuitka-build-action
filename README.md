[![rm1](https://img.shields.io/badge/rM1-supported-green)](https://remarkable.com/store/remarkable)[![rm2](https://img.shields.io/badge/rM2-supported-green)](https://remarkable.com/store/remarkable-2)

# remarkable-nuitka-build-action
Compile a python script with nuitka into a binary that will run on a reMarkable tablet.

See [action.yml](action.yml) for the possible inputs.

# Usage
```yaml
- uses: Eeems-Org/remarkable-nuitka-build-action@v2
  with:
    main: hello.py
```

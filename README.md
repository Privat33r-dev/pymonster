<p align="center"><picture><img src="https://github.com/Privat33r-dev/pymonster/assets/39376984/e72cd944-6d2a-42c4-8c3e-a560d0c565aa" width="20%" style="pointer-events: none" /></picture></p>

<h1 align="center">Pymonster</h1>

**Pymonster** is a GitHub [action](https://docs.github.com/en/actions) that setups Python, installs and caches Poetry, and then resolves and caches Poetry dependencies.


## 🤖 Basic Usage
See [action.yml](/action.yml)
```yaml
  - name: Setup Python and resolve Poetry dependencies
    uses: Privat33r-dev/pymonster@master
    with:
      python-version: '3.12'
  - name: Custom step
    run: python my_script.py
```

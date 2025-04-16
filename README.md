# Universal Foundry BuildGraph

Supporting BuildGraph to use with the Universal Foundry platform.

## Usage

Copy the contents of this repo to `./UniversalFoundry/`. The `UniversalFoundry` folder should be a sibling of `Engine`.

### Referencing Agent Types

Include `<Include Script="$(RootDir)/UniversalFoundry/Support/AgentTypes.xml" />` in your BuildGraph immediately after the `<BuildGraph ...>` element.

# Universal Foundry BuildGraph

Supporting BuildGraph to use with the [Universal Foundry](https://universalfoundry.io) Horde platform.

## Usage

Copy the contents of this repo to `./UniversalFoundry/`. The `UniversalFoundry` folder should be a sibling of `Engine`.

### Referencing Agent Types and UF Properties

Include the following XML early in your BuildGraph immediately after the `<BuildGraph>` element:

```xml
<Include Script="$(RootDir)/UniversalFoundry/Support/AgentTypes.xml" />
<Include Script="$(RootDir)/UniversalFoundry/Support/CommonProperties.xml" />
```

See [the Quickstart](Build/Quickstart.xml) for a complete example.

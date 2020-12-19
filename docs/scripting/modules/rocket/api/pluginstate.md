# Rocket.API.PluginState

The plugin state.

```csharp
public enum PluginState
```

### Values:

Name | Description
------------ | -------------
[Loaded](scripting/modules/rocket/api/pluginstate/loaded) | Plugin successfully loaded
[Unloaded](scripting/modules/rocket/api/pluginstate/unloaded) | Plugin unloaded from the server
[Faulure](scripting/modules/rocket/api/pluginstate/faulure) | When an error occurred while uploading the plugin to the server
[Cancelled](scripting/modules/rocket/api/pluginstate/cancelled) | When the server denied a request to load the specified plugin
# SDG.Unturned.SteamPlayer.isPro

<blockquote><p><b>This page is incomplete, please help finish it by contributing.<p></b></blockquote>

> This member is client and server compatible.

Gets whether the player owns the Gold DLC or not.

```csharp
public bool isPro { get; }
```

### Returns:

Type | Description
------------ | -------------
[bool](https://docs.microsoft.com/en-us/dotnet/api/system.boolean?view=netframework-3.5) | Whether the player owns the DLC

### Remarks:
This will always return false on a client with streamer mode enabled, even if it's true.

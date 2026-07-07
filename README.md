# scoop-mcrl

Scoop bucket for [mcrl](https://github.com/Sm0keSkreen/mcrl), the JVM agent that lifts
Minecraft's account chat restriction.

```
scoop bucket add mcrl https://github.com/Sm0keSkreen/scoop-mcrl
scoop install mcrl
```

`JDK_JAVA_OPTIONS` is set automatically and stays pointed at the right place across
`scoop update mcrl`. See the [mcrl README](https://github.com/Sm0keSkreen/mcrl#readme)
if you also want the Realms/telemetry/profanity extras, those need `config.json`
from the full installer.

# Base

```
swift package describe --type json > project.json
mockingbird generate --project project.json --targets Base --outputs Tests/BaseTests/BaseMocks.swift
```

Open `BaseMocks.swift`, observe that `BaseProtocol` is still mocked

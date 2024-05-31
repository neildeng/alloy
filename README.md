

`config.alloy`

```
import.git "infra" {
  repository = "https://github.com/neildeng/alloy.git"
  revision   = "main"
  path       = "infra.alloy"
}
infra.add "default" {
  a = 15
  b = 17
}
```

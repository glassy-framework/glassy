# Glassy Framework

Website: https://glassy-framework.github.io/

```crystal
require "glassy-http"

class HomeController < Glassy::Http::Controller
  @[Route("GET", "/")]
  def index
    "Hello World!"
  end
end
```

## Official bundles/libraries

- [Kernel](https://github.com/glassy-framework/glassy-kernel)
- [Console](https://github.com/glassy-framework/glassy-console)

## Skeleton App

https://github.com/glassy-framework/glassy-skeleton

# api-blueprint-use-aglio

api blueprintとaglioを利用してAPI仕様書を作成する


## Usage

```sh
> git clone https://github.com/kai-kou/api-blueprint-use-aglio.git
> cd api-blueprint-use-aglio
> npm install -g aglio --unsafe-perm
> aglio -i md/sample.md -s
> open http://localhost:3000/
```

use Docker

```sh
> git clone https://github.com/kai-kou/api-blueprint-use-aglio.git
> cd api-blueprint-use-aglio
> docker-compose up -d
> docker-compose exec api bash

>> aglio -i md/sample.md -s -h 0.0.0.0


# other Terminal
> open http://localhost:3000/
```

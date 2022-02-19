### Oathkeeper Examples

`docker build -t ory-oathkeeper-demo .`

`docker run --rm --name ory-oathkeeper-demo -p 4455:4455 -p 4456:4456 ory-oathkeeper-demo --config ./config.yaml serve`

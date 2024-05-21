# example-voting-app

```mermaid
graph LR;
  voting_app--> Postgres;
  worker--> Redis & Postgres;
  result_app--> Redis;
```

## Links
- [dockersamples/example-voting-app](https://github.com/dockersamples/example-voting-app)
- [rotoro-cloud/example-voting-app](https://github.com/rotoro-cloud/example-voting-app)

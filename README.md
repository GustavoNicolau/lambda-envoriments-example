# Simple application serveless with Lambda and DynamoDB to show examples of multiple envoriments

## Commands:

- configure serverless

```bash
  npm install -g serverless
```

- configure application

```bash
  npm install
```

- run qa local

```bash
  sls invoke local -f commit-message-scheduler
```

or

```bash
  sls invoke local --stage qa -f commit-message-scheduler
```

- run prod local

```bash
   sls invoke local --stage prod -f commit-message-scheduler
```

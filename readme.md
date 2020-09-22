# GitHub Actions Playground

> Repository to play around with GitHub Actions 🤹‍♂️

### Repository Dispatch

https://docs.github.com/en/rest/reference/repos#create-a-repository-dispatch-event

> Post Request

```
https://api.github.com/repos/bntzio/github-actions-playground/dispatches
```

> Headers

```
Content-Type: application/json
Accept: application/vnd.github.v3+json
```

> Basic Auth

```
Your personal access token as password on basic auth
```

> Body (JSON)

```
{
  "event_type": "build",
  "client_payload": {
    "env": "production"
  }
}
```

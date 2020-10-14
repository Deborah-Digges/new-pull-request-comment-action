# Pull Request Welcome Action

This action comments on pull requests made by new contributors on a repository.

## Inputs

### `access-token`

**Required** A GitHub Personal Access Token

### `message`

A message template of the form `message message {}`


## Example usage

Include this in your workflow file:

```
uses: deborah-digges/new-pull-request-comment-action@v1.0
with:
  access-token: ${{ secrets.ACCESS_TOKEN }}
```
# CLI app - to cache and track builds

## Objective

- A CLI app to cache and track your build files/scripts.
- If the build step takes more time, we can cache the results of the build and run the build again only if there are any changes
- This should be universal. (If there are additional scripts in the repository, for example: lint, type check etc; They shouldn’t be run again if there are no related file changes)
- Cache should be hit and the results should be fetched from the remote location if there are no file changes
- This remote caching system can be pointed to a self hosted machine or storage solution

---

Further details can be found in [the notion doc](https://www.notion.so/CLI-app-to-cache-and-track-builds-4338b31cba6241aba670f369c7744146?pvs=4)

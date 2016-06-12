# HOW TO

## Serve locally

```shell
# compass watch
jekyll serve --watch
```

## Deploy (serve globally)

1. Generate the files

    ```shell
    rake site:generate
    ```

2. Sync

    Use _Transmit_ to do it for you.

    **Previously**

    ```shell
    # rake deploy:rsync
    ```

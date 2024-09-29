# docker-images

### Ubuntu-rust-gtk4

```
docker run --rm --platform [linux/amd64] -v ${{ github.workspace }}:/app -v ./entrypoint.sh:/entrypoint.sh [image]
```

> [!NOTE]  
> use your own `entrypoint.sh` and mount `/app` to your project root dir. need `root` privilege to access the `target`

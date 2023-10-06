![qrcode](homework/MyGitHub.png)
```bash
docker run -v ${pwd}:/home/myuser -e QR_CODE_IMAGE_DIRECTORY='"homework"' -e QR_CODE_DEFAULT_FILE_NAME="MyGitHub.png" -e QR_CODE_DEFAULT_URL="https://github.com/bentzi-shuster" qrcode
```

```bash
docker run -v ${pwd}:/home/myuser -e QR_CODE_IMAGE_DIRECTORY='"homework"' -e QR_CODE_DEFAULT_FILE_NAME="MyGitHub.png" -e QR_CODE_DEFAULT_URL="https://github.com/bentzi-shuster" qrcode hello.py Ben
```


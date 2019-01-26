#How to run a simple RS5 image

1. Clone this repo


1. Make sure the windows version of your desktop is at least 1809

1. Start Docker CE and *Switch to Windows containers ...*

1. Build image
    ```
    docker build --rm -f "Dockerfile.windows-amd64" -t simplers5 .
    ```

1. Run image
    ```
    docker run simplers5
    ```
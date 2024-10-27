# Futu OpenD
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/chasenlabs/futu-opend/main.yml)
![GitHub last commit (branch)](https://img.shields.io/github/last-commit/chasenlabs/futu-opend)
![GitHub Release Date](https://img.shields.io/github/release-date/chasenlabs/futu-opend)
![GitHub Release](https://img.shields.io/github/v/release/chasenlabs/futu-opend?&color=fff)
![](https://img.shields.io/badge/futu-opend-ff6900.svg?logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxOTYuNzIgMTk2LjcyIj48ZGVmcz48c3R5bGU+LmNscy0xe2ZpbGw6I2ZmZjt9LmNscy0ye2ZpbGw6IzMyMzQzOTt9LmNscy0ze2ZpbGw6I2ZmNjkwMDt9PC9zdHlsZT48L2RlZnM+PHRpdGxlPmljb24tbml1bml1LWVuX25ldzwvdGl0bGU+PGcgaWQ9ImxheWVyLTEiIGRhdGEtbmFtZT0ibGF5ZXItMSI+PGNpcmNsZSBjbGFzcz0iY2xzLTEiIGN4PSI5OC4zNiIgY3k9Ijk4LjM2IiByPSI5OC4zNiIvPjxwYXRoIGNsYXNzPSJjbHMtMyIgZD0iTTk4LjM2LDBBOTguMzEsOTguMzEsMCwwLDAsLjYyLDEwOS4zM0gzNi4wOEw1OCw3MS4zNCw0OS4xMSw2Ni4yYTIzLjIxLDIzLjIxLDAsMCwxLTQuNy0zNi42MWwxLjIxLTEuMkE2MC42NSw2MC42NSwwLDAsMSw5MS4zLDExbDIuNDkuMTItMiwuODlBNjAuNjUsNjAuNjUsMCwwLDAsNjcuMTgsMzEuNjFsLS4xNS4yMWE4Ljg1LDguODUsMCwwLDAsMy4wOSwxMi4zNWwyLjcsMS41NiwxMC41Myw2LjA4LDEzLjQxLDcuNzQsNDEuOTEsMjQuMmEyMy4yMywyMy4yMywwLDAsMSw4LjUxLDMxLjczbC0yOC43NCw0OS43OGEyMy4yMywyMy4yMywwLDAsMS0zMS43Myw4LjVsLTEyLjUzLTcuMjNhMjcuNTcsMjcuNTcsMCwwLDAsMTAuNDksMTAuODV2MGw0LjgsMi43OFYxOTYuM2MyLjk0LjI2LDUuOS40Miw4LjkuNDJBOTguMzYsOTguMzYsMCwwLDAsOTguMzYsMFptODYuNDgsMTExYTIzLjIsMjMuMiwwLDAsMS0zNCwxNGwtMy4yNS0xLjg3LDMuMi01LjUzQTI3LjM2LDI3LjM2LDAsMCwwLDE1MS4yNyw5MWw4LjE2LDQuNzFhOC44NSw4Ljg1LDAsMCwwLDEyLjI1LTMuNTJsLjItLjQ0YTYwLjY2LDYwLjY2LDAsMCwwLDQuNTMtMzEuODdsLS4xOS0xLjQ2LjgsMS4xOWE2MC42MSw2MC42MSwwLDAsMSw4LjIxLDQ5LjlaIi8+PGNpcmNsZSBjbGFzcz0iY2xzLTMiIGN4PSI4Mi44NyIgY3k9IjEwMy44NSIgcj0iMTQuMzUiIHRyYW5zZm9ybT0ibWF0cml4KDAuMDEsIC0xLCAxLCAwLjAxLCAtMjIuMDcsIDE4NS4zNCkiLz48L2c+PC9zdmc+Cg==&logoColor=ff6900)
![](https://img.shields.io/badge/moomoo-opend-ff6900.svg?logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAzMDAgMTUzLjcyIj4KICAgIDxkZWZzPgogICAgICAgIDxzdHlsZT4uY2xzLTF7ZmlsbDojMjYyNzJiO30uY2xzLTJ7ZmlsbDojZmY2OTAwO308L3N0eWxlPgogICAgPC9kZWZzPgogICAgPGcgaWQ9ImxheWVyLTEiIGRhdGEtbmFtZT0ibGF5ZXItMSI+CiAgICAgICAgPHBhdGggY2xhc3M9ImNscy0yIiBkPSJNMi42NSwxNTMuNTdIMTQuNzhBMy4xLDMuMSwwLDAsMCwxNy41MSwxNTJsLjgxLTEuNDdhMjguNzYsMjguNzYsMCwwLDEsMjEtMTQuNTlsMi43OC0uNDFhNC40Miw0LjQyLDAsMCwwLDQuMDYtMi42OWw0MS4yLTk2LjlhMS42MiwxLjYyLDAsMCwwLTEuODEtMi4yM2wtMi4xOS40NUM1OS4xMyw0MCw0Mi43NSw1NS4xMiwzMS43Miw3NS44M0wzMS4xOSw3N2wtMzEsNzNBMi42NSwyLjY1LDAsMCwwLDIuNjUsMTUzLjU3WiIvPgogICAgICAgIDxwYXRoIGNsYXNzPSJjbHMtMiIgZD0iTTUwLjU1LDE1My43Mkg4MC4zMmwxLjYtLjg4LDUuMS04LjEyYzI1LjIxLTQwLjEsODQuNTMtMzUuNDIsMTAzLjQ3LDcuNTJhMi40OSwyLjQ5LDAsMCwwLDIuMzEsMS40OGgyMWEyLjY1LDIuNjUsMCwwLDAsMi42NC0yLjkxbC01LjU2LTU3YTEsMSwwLDAsMC0yLS4xN2wtNC44OSwxNy42NWEyLjYsMi42LDAsMCwxLTIuODYsMS44OGwtMzMtNC40NGE2Ljg1LDYuODUsMCwwLDEtNS4xMy00TDE1MS4zLDc4YTIuNywyLjcsMCwwLDEsMi44Ny0zLjc1bDE5LjU4LDIuNjFhMi44NywyLjg3LDAsMCwxLDIuMzEsMS44NmwzLjMzLDlhMSwxLDAsMCwwLDEuODItLjA3bDMuMjgtMTEuODNhMi41OSwyLjU5LDAsMCwwLTIuMTUtMy4yNmwtMzguNTEtNS4xNGMtMjcuNDktMy42OC0zMi40LTQxLjM2LTYuNzctNTJsNy4zMy0zYTEsMSwwLDAsMSwxLjI4LDEuNDZsLTYuMjQsMTAuNTVhMTQsMTQsMCwwLDAsMTAuMiwyMWw0My4xLDUuNzZhMTEuMywxMS4zLDAsMCwwLDExLjU5LTE2LjI4TDIwMywzMi4yOGMtMjIuNDMtNDQuNi04Ni44LTQyLjUzLTEwNi4zMywzLjQybC0xLjIxLDIuODZMNDguMTIsMTUwLjA1QTIuNjQsMi42NCwwLDAsMCw1MC41NSwxNTMuNzJaIi8+CiAgICAgICAgPHBhdGggY2xhc3M9ImNscy0yIiBkPSJNMjEzLjUsNzYuNzNsNC0uNjVhMjIuMzUsMjIuMzUsMCwwLDAsMTIuNzItMzcuM2wtNi45My03YTEuMDcsMS4wNywwLDAsMC0xLjc3LDEuMDlsMy4wNyw5YTEwLjY2LDEwLjY2LDAsMCwxLTUsMTNoMFoiLz4KICAgIDwvZz4KPC9zdmc+&logoColor=ff6900)

使用 docker 运行**富途OpenD**，并且每天检查更新到最新版。

Using docker to run **Futu OpenD / moomoo OpenD** and automatically update to the latest version daily.

- [Futu OpenAPI](https://www.futunn.com/OpenAPI)
- [moomoo OpenAPI](https://openapi.moomoo.com/moomoo-api-doc)

```shell
docker pull ghcr.io/chasenlabs/futu-opend:latest # futu
docker pull ghcr.io/chasenlabs/moomoo-opend:latest # moomoo
```

> [!IMPORTANT]
> This project is not officially supported by Futu, and the author is not responsible for any problems caused by the use of this project.
> 
> 这个项目不是富途官方支持的，作者对使用这个项目造成的任何问题不负责任。

## Configuration

run command in docker container, or see [Futu API](https://openapi.futunn.com/futu-api-doc/opend/opend-cmd.html#8799)

```shell
cat FutuOpenD.xml # fufu
cat OpenD.xml # moomoo
```

md5 your password

```shell
md5 -s <your_password>
```

## Example

using docker-compose start

启动之前请配置运行参数 [docker-compose](docker-compose.yml) / start before config [docker-compose](docker-compose.yml)

```shell
docker-compose up
```

or using docker run, more parameters see [Start with command](https://openapi.futunn.com/futu-api-doc/opend/opend-cmd.html#465)

```shell
# futu
docker run -d --name opend -p 11111:11111 ghcr.io/chasenlabs/futu-opend:latest \
    /docker-entrypoint.sh \
    -login_account=<account number> \
    -login_pwd_md5=<md5 string> \
    -api_port=11111 \
    -api_ip=0.0.0.0 \
    -telnet_port=22222 \
    -lang=chs
# moomoo
docker run -d --name opend -p 11111:11111 ghcr.io/chasenlabs/moomoo-opend:latest \
    /docker-entrypoint.sh \
    -login_account=<account number> \
    -login_pwd_md5=<md5 string> \
    -api_port=11111 \
    -api_ip=0.0.0.0 \
    -telnet_port=22222 \
    -lang=en
```

输入手机验证码 / enter mobile phone verification code, [ops docs is here](https://openapi.futunn.com/futu-api-doc/opend/opend-operate.html#815)
```shell
docker exec -it opend bash
# syntax: telnet <addr> <telnet port>
telnet 127.0.0.1 22222
input_phone_verify_code -code=<code>
```

testing prepare
```shell
pip install -r requirements.txt
# if you located in China, you can use aliyun mirror to speed up
pip install -r requirements.txt  -i https://mirrors.aliyun.com/pypi/simple/
```

testing with main.py
```shell
python main.py --addr <futu opend ip>
```

## Support

If you like this project, please consider supporting me for coffee ☕️

[![Buy Me A Coffee](https://img.shields.io/badge/buy%20me%20-coffee-%2322BC18.svg)](https://www.buymeacoffee.com/chasengao) [![get youtself link](https://img.shields.io/badge/get%20youtself%20link-buymeacoffee-orange.svg)](https://www.buymeacoffee.com/invite/chasengao)

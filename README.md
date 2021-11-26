<div align="center"><img src="https://darrennathanael.com/cdn/springtext.svg" alt="Logo" width="350" height="80">

<h1 align="center"><img src="https://darrennathanael.com/cdn/springboot.svg" width="30px"> Lavalink Server for deploy to Replit <img src="https://darrennathanael.com/cdn/springboot.svg" width="30px"></h1>

# Setup - Cài đặt
<p align="center">I.ĐỐI VỚI ĐỐI TƯỢNG MUỐN TRIỂN KHAI LÊN REPLIT!</p>

1. Bấm vào biểu tượng Replit ở bên dưới để bắt đầu triển khai Lavalink lên Replit:

[![Run on Repl.it](https://repl.it/badge/github/SudhanPlayz/Discord-MusicBot)](https://repl.it/github/maskiilovmai/lavalink)

2. Ở bên mục `CONSOLE` nhập lệnh bên dưới vào đó:

```sh
curl https://raw.githubusercontent.com/freyacodes/Lavalink/master/LavalinkServer/application.yml.example -o application.yml
```

3. Sau khi chạy xong, ở bên **`File`** sẽ có thêm file `application.yml`, với file này bạn có thể:
- Chỉnh sửa mục **`Password`**, bạn có thể để password bất kì mà bạn muốn, nếu bạn không cài đặt, password mặc định sẽ là `youshallnotpass`.

- ***⚠ LƯU Ý ⚠***: Ngoài mục password ra bạn không được chỉnh sửa bất kể mục nào khác nếu bạn không có hiểu biết về nó, tránh làm hỏng toàn bộ mã nguồn.

4. Sau khi cấu hình xong, hãy bấm **`Run`** để bắt đầu chạy Lavalink.

<p align="center">II.ĐỐI VỚI ĐỐI TƯỢNG MUỐN TRIỂN KHAI TRÊN LINUX/UBUNTU!</p>

- Lavalink Server by [Freyacode](https://github.com/freyacodes) ([Lavalink.jar Releases](https://github.com/freyacodes/Lavalink/releases)). Choose the latest version.
- Lavalink Server by [Darren Nathanael](https://darrennathanael.com/) ([Lavalink.jar](https://cdn.darrennathanael.com/jars/Lavalink.jar)).

## Configuration - Cấu hình
- By [Freyacode](https://github.com/freyacodes) ([application.yml.example](https://raw.githubusercontent.com/freyacodes/Lavalink/master/LavalinkServer/application.yml.example))
- Rename `application.yml.example` to `application.yml`.
3. After done, next step:
- In `application.yml` you can change password, default `youshallnotpass`.
- Do not change port in here, default `2333`.
- Address default `0.0.0.0`. That means you can connect it anywhere. You can change it if you understand its nature.
- In addition to the above conditions, don't change anything. That maybe corrupt the file of Lavalink.
- Make `Lavalink.jar` and `application.yml` same folder.
- Run command:
```sh
java -jar Lavalink.jar
```
4. For download with Console
- `application.yml` file:
```sh
curl https://raw.githubusercontent.com/freyacodes/Lavalink/master/LavalinkServer/application.yml.example --output application.yml
```
- `Lavalink.jar` by [Darren Nathanael](https://darrennathanael.com/):
```sh
curl https://cdn.darrennathanael.com/jars/Lavalink.jar --output Lavalink.jar
```

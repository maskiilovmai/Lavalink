<h1 align="center">
  <a href="https://github.com/maskiilovmai/Lavalink-Replit">
    <img src="https://darrennathanael.com/cdn/springtext.svg" alt="Logo" width="350" height="80">
  </h1>

<h1 align="center"><img src="https://darrennathanael.com/cdn/springboot.svg" width="30px"> Lavalink Server for deploy to Replit <img src="https://darrennathanael.com/cdn/springboot.svg" width="30px"></h1>

# Setup - Cài đặt
#### 1. Bấm vào biểu tượng Replit ở bên dưới để bắt đầu triển khai Lavalink lên Replit:

[![Run on Repl.it](https://repl.it/badge/github/SudhanPlayz/Discord-MusicBot)](https://repl.it/github/maskiilovmai/Lavalink-Replit)

#### 2. Ở bên mục `Console` nhập lệnh bên dưới vào đó:

```sh
curl https://raw.githubusercontent.com/freyacodes/Lavalink/master/LavalinkServer/application.yml.example -o application.yml
```

#### 3. Sau khi chạy xong, ở bên **`File`** sẽ có thêm file `application.yml`, với file này bạn có thể:
- Chỉnh sửa mục **`Password`**, bạn có thể để password bất kì mà bạn muốn, nếu bạn không cài đặt, password mặc định sẽ là `youshallnotpass`.

- ***⚠ LƯU Ý ⚠***: Ngoài mục password ra bạn không được chỉnh sửa bất kể mục nào khác nếu bạn không có hiểu biết về nó, tránh làm hỏng toàn bộ mã nguồn.

#### 4. Sau khi cấu hình xong, hãy bấm **`Run`** để bắt đầu chạy Lavalink.

# Configuration - Cấu hình cho bot
- Port luôn luôn là **`443`**
- Password là bạn đã cấu hình ở `application.yml`, nếu bạn không cấu hình thì mặc sẽ là `youshallnotpass`
- Host là link ở bảng điều khiển bên phải. VD: nếu tên dự án của bạn là `lavalink` còn tên tài khoản của bạn là `thomas` thì đường liên kết sẽ là `https://lavalink.thomas.repl.co`. Hãy xóa `https://`.
- Secure bạn sẽ phải để sang `true` nếu bạn triển khai nó trên Replit.

# Lavalink.jar Sources
1. Lavalink.jar bởi [Team City](https://ci.fredboat.com/)

1. Lavalink.jar bởi [Freyacode](https://github.com/freyacodes/Lavalink/releases)

1. Lavalink.jar bởi [Darren Nathan's](https://cdn.darrennathanael.com/jars/Lavalink.jar)
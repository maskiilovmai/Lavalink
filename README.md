## Setup - Cài đặt

1. Clone this:
```sh
git clone https://github.com/maskiilovmai/lavalink.git
```

2. If you don't want to clone and want to download from another source
- Lavalink Server by [Freyacode](https://github.com/freyacodes) ([Lavalink.jar Releases](https://github.com/freyacodes/Lavalink/releases)). Choose the latest version.
- Lavalink Server by [Darren Nathanael](https://darrennathanael.com/) ([Lavalink.jar](https://cdn.darrennathanael.com/jars/Lavalink.jar))

## Configuration - Cấu hình
1. Create or download `application.yml`
2. If you download:
- By [Freyacode](https://github.com/freyacodes) ([application.yml.example](https://raw.githubusercontent.com/freyacodes/Lavalink/master/LavalinkServer/application.yml.example))
- Rename `application.yml.example` to `application.yml`
3. After done, next step:
- In `application.yml` you can change password, default 'youshallnotpass'
- Address default '0.0.0.0'. That means you can connect it anywhere. You can change it if you understand its nature.
- In addition to the above conditions, don't change anything. That maybe corrupt the file of Lavalink.
- Make `Lavalink.jar` and `application.yml` same folder
- Run command:
```sh
java -jar Lavalink.jar
```
4. For download with Console
- `application.yml` file:
```sh
curl https://raw.githubusercontent.com/freyacodes/Lavalink/master/LavalinkServer/application.yml.example --output application.yml
```
- `Lavalink.jar` by [Darren Nathanael](https://darrennathanael.com/)
```sh
curl https://cdn.darrennathanael.com/jars/Lavalink.jar --output Lavalink.jar
```

## Deploy and hosting in Replit - Triển khai và host trong Replit
- STEP 1: You can deploy and archive to Replit, by clicking the button icon below:
[![Run on Repl.it](https://repl.it/badge/github/SudhanPlayz/Discord-MusicBot)](https://repl.it/github/maskiilovmai/lavalink)

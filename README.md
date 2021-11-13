## Setup - Cài đặt

1. Clone this:
```sh
git clone https://github.com/maskiilovmai/lavalink.git
```

2. If you don't want to clone and want to download from another source
- Lavalink Server by [Freyacode](https://github.com/freyacodes) ([Lavalink.jar Releases](https://github.com/freyacodes/Lavalink/releases)). Choose the latest version.
- Lavalink Server by [Darren Nathanael](https://darrennathanael.com/) ([Lavalink.jar](https://cdn.darrennathanael.com/jars/Lavalink.jar)).

## Configuration - Cấu hình
1. Create or download `application.yml`
2. If you download:
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

## Deploy and hosting in Repl.it - Triển khai và host trong Repl.it
- STEP 1: You can deploy and archive to Repl.it, by clicking the button icon below:

[![Run on Repl.it](https://repl.it/badge/github/SudhanPlayz/Discord-MusicBot)](https://repl.it/github/maskiilovmai/lavalink)

- STEP 2: Config `.repl` like in below:
```sh
language = "bash"
run = "bash start.sh"
```
- STEP 3: Config `application.yml`, read [Configuration](https://github.com/maskiilovmai/lavalink#configuration---c%E1%BA%A5u-h%C3%ACnh)
- STEP 4: After done, click 'RUN' and wait.
- STEP 5: Config in your bot:
+ Lavalink's port will always 443 in Repl.it.
+ You need set secure to `true` in Repl.it.
+ Default password is `youshallnotpass` if you not config `application.yml`.
+ if your app is named `lavalink` and your repl username is `test` Rep.it will make HTTP to https://lavalink.test.repl.co
+ Copy this link and paste in HOST of bot, remove `https://` form the link was pasted.
+ Run the bot and enjoy.
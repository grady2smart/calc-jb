# calc-jb for ce calc on 5.5 and up
cabri jr {y= --> open --> del to finish install
{ti boy rom converter}
https://calc84maniac.github.io/tiboyce/converter/

# zsign
Maybe is the most quickly codesign alternative for iOS12+ in the world, cross-platform ( Linux & macOS ), more features.
If this tool can help you, please don't forget to <font color=#FF0000 size=5>🌟**star**🌟</font> me. :)
### Compile

You must install openssl library at first.

#### macOS:

```bash
brew install openssl
```
and then (attention to replace your openssl version)
```bash
g++ *.cpp common/*.cpp -lcrypto -I/usr/local/Cellar/openssl@1.1/1.1.1k/include -L/usr/local/Cellar/openssl@1.1/1.1.1k/lib -O3 -o zsign
```



# electron-autoupdate-scaffold

## How

``` bash
git clone https://github.com/sunjiaying/electron-autoupdate-scaffold.git
cnpm i
cd electron-autoupdate-scaffold/server
cnpm i

mkdir packages/win32
npm start

cd electron-autoupdate-scaffold
npm run build:win32
```

将dist里面的文件COPY到server目录的packages/win32路径下面


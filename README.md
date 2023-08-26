# nitro-public-repo

nitro sends files in public efficiently in development, but occasionally 404s in
production.

<br />

## Usage

### dev

```shell
npm install 

npm run dev
```

Reopen multiple times →
[http://localhost:3000/hello.txt](http://localhost:3000/hello.txt) is ok!

### prod

```shell
npm install

npm run build

npm run serve
```

Reopen multiple times →
[http://localhost:3000/hello.txt](http://localhost:3000/hello.txt) may appear
404

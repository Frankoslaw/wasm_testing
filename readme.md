This project is plaing around with code from article https://blog.devgenius.io/lets-build-a-websockets-project-with-rust-and-yew-0-19-60720367399f

TODO:
    - rewrite server in pure rust
    - create own ui with yew
    - simplify code: refactorize / wrap native wasm functions into separete libs

How to run project:
    server( node js ):
        npm i -g typescript nodemon
        cd server
        npm start

    client( yew + trunk ):
        cd client
        trunk serve
## Babel(多用途的javascript编译器)

    作为一种语言，javascript在不断发展，各种新标准和提案层出不穷，但是由于浏览器的多样性导致可能几年内无法广泛普及。
    Babel可以让你提前使用这些语言特性，它是一种多用途的javascript编译器，它把最新版本的javascript编译成当下可以执行的版本。


### es6


    1.安装Babel CLI，这是一个可以在命令行中使用Babel编译的方法。

        npm install babel-cli -g
    
    2.新建一个测试Babel目录以及es6.js

    3.babel es6.js(文件) –o compiled.js(新建文件)

    4.配置
    
        (1) npm init

        (2) 创建一个配置文件.babelrc
            {
                "presets":[ ],
                "plugins":[ ]
            }
        
        (3) npm install --save-dev babel-preset-es2015

        (4) 将这个preset添加到配置文件中。
            {
                "presets":['es2015'],
                "plugins":[]
            }

        (5) babel es6.js –o compiled.js


# expresstest
express-generator そのまま

##　Usage
install　express-generator
    > npm install express-generator -g

make express
    > express --view=pug mytestapp

change directory:
    > cd mytestapp

install dependencies:
    > npm install

run the app:
    > SET DEBUG=mytestapp:* & npm start
    
##　express

    Usage: express [options][dir]

    Options:

        -h, --help          output usage information
            --version       output the version number
        -e, --ejs           add ejs engine support
            --hbs           add handlebars engine support
            --pug           add pug engine support
        -H, --hogan         add hogan.js engine support
            --no-view       generate without view engine
        -v, --view <engine> add view <engine> support (ejs|hbs|hjs|jade|pug|twig|vash) (defaults to jade)
        -c, --css <engine>  add stylesheet <engine> support (less|stylus|compass|sass) (defaults to plain css)
            --git           add .gitignore
        -f, --force         force on non-empty directory


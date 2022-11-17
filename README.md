# my simple template for front-end developming

`git clone https://github.com/zachey01/template.git .`

## getting started

install dependencies - `npm i`

update dependencies - `npm update --save`

run gulp - `npm start`

build - `npm build`

build zip - `npm zip`

editorconfig check - `npm check`

---

## structure

```
├── src/                          # source files
│   ├── js                        # js scripts
│   │   └── main.js               # main script
│   │   ├── _vars.js              # variables
│   │   ├── _module.js            # connection of libraries
│   │   ├── _functions.js         # function connection
│   │   ├── modules               # modules
│   │   ├── functions             # functions
│   ├── scss                      # style SCSS (SASS)
│   │   └── main.scss             # main style file
│   │   └── vendor.scss           # connection of libraries
│   │   └── _fonts.scss           # connection of fonts
│   │   └── _vars.scss            # variables
│   │   └── _globa;.scss          # global style
│   │   ├── components            # scss components
│   │   ├── modules               # modules
│   ├── partials                  # parts of the HTML page
│   ├── img                       # images
│   │   ├── svg                   # svg (sprites, icons)
│   ├── assets                    # assets
│   │   ├── fonts                 # fonts
│   │   ├── errors                # error files
│   │   ├── favicons              # favicons
│   └── home.html                 # home HTML file
└── gulpfile.js                   # gulp settings
└── package.json                  # npm settings
└── .editorconfig                 # editorconfig settings
└── README.md                     # little documentation
```

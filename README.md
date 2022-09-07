<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->

<a name="readme-top"></a>

<br />
<div align="center">
  <a href="https://rhine-one.vercel.app">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">URL Shortner</h3>

  <p align="center">
    A URL shortener made with laravel.
    <br />
    <br />
    <!-- <a href="https://drive.google.com/file/d/1oC_mWtU_nYJwzwnwgywwpvy1WZWieX1h/view?usp=sharing">View Demo</a> -->
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#tree">File Tree</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

Here we can short any url and also block IP for specific amount of time. This project is made with laravel.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

This section should list any major frameworks/libraries used for the project.

-   ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
-   ![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white)
-   ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
-   ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
-   ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
-   ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)

-   ![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Tree

-   File Tree
    ```sh
    ├───app
    │   ├───Console
    │   ├───Exceptions
    │   ├───Http
    │   │   ├───Controllers
    │   │   │   └───Auth
    │   │   └───Middleware
    │   ├───Listeners
    │   ├───Models
    │   └───Providers
    ├───bootstrap
    │   └───cache
    ├───config
    ├───database
    │   ├───factories
    │   ├───migrations
    │   └───seeders
    ├───images
    ├───MYSQL
    ├───node_modules
    │   ├───.bin
    │   ├───.cache
    │   │   └───babel-loader
    │   ├───@ampproject
    │   │   └───remapping
    │   │       ├───dist
    │   │       │   └───types
    │   │       └───node_modules
    │   │           └───@jridgewell
    │   │               └───gen-mapping
    │   │                   └───dist
    │   │                       └───types
    │   ├───@babel
    │   │   ├───code-frame
    │   │   │   └───lib
    │   │   ├───compat-data
    │   │   │   └───data
    │   │   ├───core
    │   │   │   ├───lib
    │   │   │   │   ├───config
    │   │   │   │   │   ├───files
    │   │   │   │   │   ├───helpers
    │   │   │   │   │   └───validation
    │   │   │   │   ├───gensync-utils
    │   │   │   │   ├───parser
    │   │   │   │   │   └───util
    │   │   │   │   ├───tools
    │   │   │   │   ├───transformation
    │   │   │   │   │   ├───file
    │   │   │   │   │   └───util
    │   │   │   │   └───vendor
    │   │   │   ├───node_modules
    │   │   │   │   ├───.bin
    │   │   │   │   ├───convert-source-map
    │   │   │   │   ├───debug
    │   │   │   │   │   └───src
    │   │   │   │   ├───json5
    │   │   │   │   │   ├───dist
    │   │   │   │   │   └───lib
    │   │   │   │   └───ms
    │   │   │   └───src
    │   │   │       └───config
    │   │   │           └───files
    │   │   ├───generator
    │   │   │   ├───lib
    │   │   │   │   ├───generators
    │   │   │   │   └───node
    │   │   │   └───node_modules
    │   │   │       └───.bin
    │   │   ├───helper-annotate-as-pure
    │   │   │   └───lib
    │   │   ├───helper-builder-binary-assignment-operator-visitor
    │   │   │   └───lib
    │   │   ├───helper-compilation-targets
    │   │   │   ├───lib
    │   │   │   └───node_modules
    │   │   │       └───.bin
    │   │   ├───helper-create-class-features-plugin
    │   │   │   └───lib
    │   │   ├───helper-create-regexp-features-plugin
    │   │   │   └───lib
    │   │   ├───helper-define-polyfill-provider
    │   │   │   ├───esm
    │   │   │   ├───lib
    │   │   │   │   ├───browser
    │   │   │   │   ├───node
    │   │   │   │   └───visitors
    │   │   │   └───node_modules
    │   │   │       ├───.bin
    │   │   │       ├───debug
    │   │   │       │   └───src
    │   │   │       └───ms
    │   │   ├───helper-environment-visitor
    │   │   │   └───lib
    │   │   ├───helper-explode-assignable-expression
    │   │   │   └───lib
    │   │   ├───helper-function-name
    │   │   │   └───lib
    │   │   ├───helper-hoist-variables
    │   │   │   └───lib
    │   │   ├───helper-member-expression-to-functions
    │   │   │   └───lib
    │   │   ├───helper-module-imports
    │   │   │   └───lib
    │   │   ├───helper-module-transforms
    │   │   │   └───lib
    │   │   ├───helper-optimise-call-expression
    │   │   │   └───lib
    │   │   ├───helper-plugin-utils
    │   │   │   └───lib
    │   │   ├───helper-remap-async-to-generator
    │   │   │   └───lib
    │   │   ├───helper-replace-supers
    │   │   │   └───lib
    │   │   ├───helper-simple-access
    │   │   │   └───lib
    │   │   ├───helper-skip-transparent-expression-wrappers
    │   │   │   └───lib
    │   │   ├───helper-split-export-declaration
    │   │   │   └───lib
    │   │   ├───helper-string-parser
    │   │   │   └───lib
    │   │   ├───helper-validator-identifier
    │   │   │   ├───lib
    │   │   │   └───scripts
    │   │   ├───helper-validator-option
    │   │   │   └───lib
    │   │   ├───helper-wrap-function
    │   │   │   └───lib
    │   │   ├───helpers
    │   │   │   ├───lib
    │   │   │   │   └───helpers
    │   │   │   └───scripts
    │   │   ├───highlight
    │   │   │   └───lib
    │   │   ├───parser
    │   │   │   ├───bin
    │   │   │   ├───lib
    │   │   │   └───typings
    │   │   ├───plugin-bugfix-safari-id-destructuring-collision-in-function-expression
    │   │   │   └───lib
    │   │   ├───plugin-bugfix-v8-spread-parameters-in-optional-chaining
    │   │   │   └───lib
    │   │   ├───plugin-proposal-async-generator-functions
    │   │   │   └───lib
    │   │   ├───plugin-proposal-class-properties
    │   │   │   └───lib
    │   │   ├───plugin-proposal-class-static-block
    │   │   │   └───lib
    │   │   ├───plugin-proposal-dynamic-import
    │   │   │   └───lib
    │   │   ├───plugin-proposal-export-namespace-from
    │   │   │   └───lib
    │   │   ├───plugin-proposal-json-strings
    │   │   │   └───lib
    │   │   ├───plugin-proposal-logical-assignment-operators
    │   │   │   └───lib
    │   │   ├───plugin-proposal-nullish-coalescing-operator
    │   │   │   └───lib
    │   │   ├───plugin-proposal-numeric-separator
    │   │   │   └───lib
    │   │   ├───plugin-proposal-object-rest-spread
    │   │   │   └───lib
    │   │   ├───plugin-proposal-optional-catch-binding
    │   │   │   └───lib
    │   │   ├───plugin-proposal-optional-chaining
    │   │   │   └───lib
    │   │   ├───plugin-proposal-private-methods
    │   │   │   └───lib
    │   │   ├───plugin-proposal-private-property-in-object
    │   │   │   └───lib
    │   │   ├───plugin-proposal-unicode-property-regex
    │   │   │   └───lib
    │   │   ├───plugin-syntax-async-generators
    │   │   │   └───lib
    │   │   ├───plugin-syntax-class-properties
    │   │   │   └───lib
    │   │   ├───plugin-syntax-class-static-block
    │   │   │   └───lib
    │   │   ├───plugin-syntax-dynamic-import
    │   │   │   └───lib
    │   │   ├───plugin-syntax-export-namespace-from
    │   │   │   └───lib
    │   │   ├───plugin-syntax-import-assertions
    │   │   │   ├───lib
    │   │   │   └───src
    │   │   ├───plugin-syntax-json-strings
    │   │   │   └───lib
    │   │   ├───plugin-syntax-logical-assignment-operators
    │   │   │   └───lib
    │   │   ├───plugin-syntax-nullish-coalescing-operator
    │   │   │   └───lib
    │   │   ├───plugin-syntax-numeric-separator
    │   │   │   └───lib
    │   │   ├───plugin-syntax-object-rest-spread
    │   │   │   └───lib
    │   │   ├───plugin-syntax-optional-catch-binding
    │   │   │   └───lib
    │   │   ├───plugin-syntax-optional-chaining
    │   │   │   └───lib
    │   │   ├───plugin-syntax-private-property-in-object
    │   │   │   └───lib
    │   │   ├───plugin-syntax-top-level-await
    │   │   │   └───lib
    │   │   ├───plugin-transform-arrow-functions
    │   │   │   └───lib
    │   │   ├───plugin-transform-async-to-generator
    │   │   │   └───lib
    │   │   ├───plugin-transform-block-scoped-functions
    │   │   │   └───lib
    │   │   ├───plugin-transform-block-scoping
    │   │   │   └───lib
    │   │   ├───plugin-transform-classes
    │   │   │   └───lib
    │   │   ├───plugin-transform-computed-properties
    │   │   │   └───lib
    │   │   ├───plugin-transform-destructuring
    │   │   │   └───lib
    │   │   ├───plugin-transform-dotall-regex
    │   │   │   └───lib
    │   │   ├───plugin-transform-duplicate-keys
    │   │   │   └───lib
    │   │   ├───plugin-transform-exponentiation-operator
    │   │   │   └───lib
    │   │   ├───plugin-transform-for-of
    │   │   │   └───lib
    │   │   ├───plugin-transform-function-name
    │   │   │   └───lib
    │   │   ├───plugin-transform-literals
    │   │   │   └───lib
    │   │   ├───plugin-transform-member-expression-literals
    │   │   │   └───lib
    │   │   ├───plugin-transform-modules-amd
    │   │   │   └───lib
    │   │   ├───plugin-transform-modules-commonjs
    │   │   │   └───lib
    │   │   ├───plugin-transform-modules-systemjs
    │   │   │   └───lib
    │   │   ├───plugin-transform-modules-umd
    │   │   │   └───lib
    │   │   ├───plugin-transform-named-capturing-groups-regex
    │   │   │   └───lib
    │   │   ├───plugin-transform-new-target
    │   │   │   └───lib
    │   │   ├───plugin-transform-object-super
    │   │   │   └───lib
    │   │   ├───plugin-transform-parameters
    │   │   │   └───lib
    │   │   ├───plugin-transform-property-literals
    │   │   │   └───lib
    │   │   ├───plugin-transform-regenerator
    │   │   │   └───lib
    │   │   ├───plugin-transform-reserved-words
    │   │   │   └───lib
    │   │   ├───plugin-transform-runtime
    │   │   │   ├───lib
    │   │   │   │   └───get-runtime-path
    │   │   │   ├───node_modules
    │   │   │   │   └───.bin
    │   │   │   └───src
    │   │   │       └───get-runtime-path
    │   │   ├───plugin-transform-shorthand-properties
    │   │   │   └───lib
    │   │   ├───plugin-transform-spread
    │   │   │   └───lib
    │   │   ├───plugin-transform-sticky-regex
    │   │   │   └───lib
    │   │   ├───plugin-transform-template-literals
    │   │   │   └───lib
    │   │   ├───plugin-transform-typeof-symbol
    │   │   │   └───lib
    │   │   ├───plugin-transform-unicode-escapes
    │   │   │   └───lib
    │   │   ├───plugin-transform-unicode-regex
    │   │   │   └───lib
    │   │   ├───preset-env
    │   │   │   ├───data
    │   │   │   ├───lib
    │   │   │   │   └───polyfills
    │   │   │   └───node_modules
    │   │   │       └───.bin
    │   │   ├───preset-modules
    │   │   │   ├───lib
    │   │   │   │   └───plugins
    │   │   │   │       ├───transform-async-arrows-in-class
    │   │   │   │       ├───transform-edge-default-parameters
    │   │   │   │       ├───transform-edge-function-name
    │   │   │   │       ├───transform-jsx-spread
    │   │   │   │       ├───transform-safari-block-shadowing
    │   │   │   │       ├───transform-safari-for-shadowing
    │   │   │   │       └───transform-tagged-template-caching
    │   │   │   └───src
    │   │   │       └───plugins
    │   │   │           ├───transform-async-arrows-in-class
    │   │   │           ├───transform-edge-default-parameters
    │   │   │           ├───transform-edge-function-name
    │   │   │           ├───transform-jsx-spread
    │   │   │           ├───transform-safari-block-shadowing
    │   │   │           ├───transform-safari-for-shadowing
    │   │   │           └───transform-tagged-template-caching
    │   │   ├───runtime
    │   │   │   ├───helpers
    │   │   │   │   └───esm
    │   │   │   └───regenerator
    │   │   ├───template
    │   │   │   ├───lib
    │   │   │   └───node_modules
    │   │   │       └───.bin
    │   │   ├───traverse
    │   │   │   ├───lib
    │   │   │   │   ├───path
    │   │   │   │   │   ├───generated
    │   │   │   │   │   ├───inference
    │   │   │   │   │   └───lib
    │   │   │   │   └───scope
    │   │   │   │       └───lib
    │   │   │   ├───node_modules
    │   │   │   │   ├───.bin
    │   │   │   │   ├───debug
    │   │   │   │   │   └───src
    │   │   │   │   └───ms
    │   │   │   └───scripts
    │   │   │       └───generators
    │   │   └───types
    │   │       ├───lib
    │   │       │   ├───asserts
    │   │       │   │   └───generated
    │   │       │   ├───ast-types
    │   │       │   │   └───generated
    │   │       │   ├───builders
    │   │       │   │   ├───flow
    │   │       │   │   ├───generated
    │   │       │   │   ├───react
    │   │       │   │   └───typescript
    │   │       │   ├───clone
    │   │       │   ├───comments
    │   │       │   ├───constants
    │   │       │   │   └───generated
    │   │       │   ├───converters
    │   │       │   ├───definitions
    │   │       │   ├───modifications
    │   │       │   │   ├───flow
    │   │       │   │   └───typescript
    │   │       │   ├───retrievers
    │   │       │   ├───traverse
    │   │       │   ├───utils
    │   │       │   │   └───react
    │   │       │   └───validators
    │   │       │       ├───generated
    │   │       │       └───react
    │   │       └───scripts
    │   │           ├───generators
    │   │           └───utils
    │   ├───@colors
    │   │   └───colors
    │   │       ├───examples
    │   │       ├───lib
    │   │       │   ├───custom
    │   │       │   ├───maps
    │   │       │   └───system
    │   │       └───themes
    │   ├───@discoveryjs
    │   │   └───json-ext
    │   │       ├───dist
    │   │       └───src
    │   ├───@jridgewell
    │   │   ├───gen-mapping
    │   │   │   ├───dist
    │   │   │   │   └───types
    │   │   │   └───src
    │   │   ├───resolve-uri
    │   │   │   └───dist
    │   │   │       └───types
    │   │   ├───set-array
    │   │   │   ├───dist
    │   │   │   │   └───types
    │   │   │   └───src
    │   │   ├───source-map
    │   │   │   └───dist
    │   │   │       └───types
    │   │   ├───sourcemap-codec
    │   │   │   ├───dist
    │   │   │   │   └───types
    │   │   │   └───src
    │   │   └───trace-mapping
    │   │       ├───dist
    │   │       │   └───types
    │   │       └───src
    │   ├───@leichtgewicht
    │   │   └───ip-codec
    │   │       └───types
    │   ├───@nodelib
    │   │   ├───fs.scandir
    │   │   │   └───out
    │   │   │       ├───adapters
    │   │   │       ├───providers
    │   │   │       ├───types
    │   │   │       └───utils
    │   │   ├───fs.stat
    │   │   │   └───out
    │   │   │       ├───adapters
    │   │   │       ├───providers
    │   │   │       └───types
    │   │   └───fs.walk
    │   │       └───out
    │   │           ├───providers
    │   │           ├───readers
    │   │           └───types
    │   ├───@popperjs
    │   │   └───core
    │   │       ├───dist
    │   │       │   ├───cjs
    │   │       │   ├───esm
    │   │       │   │   ├───dom-utils
    │   │       │   │   ├───modifiers
    │   │       │   │   └───utils
    │   │       │   └───umd
    │   │       └───lib
    │   │           ├───dom-utils
    │   │           ├───modifiers
    │   │           └───utils
    │   ├───@trysound
    │   │   └───sax
    │   │       └───lib
    │   ├───@types
    │   │   ├───babel__core
    │   │   │   └───node_modules
    │   │   │       └───.bin
    │   │   ├───babel__generator
    │   │   ├───babel__template
    │   │   │   └───node_modules
    │   │   │       └───.bin
    │   │   ├───babel__traverse
    │   │   │   └───ts4.1
    │   │   ├───body-parser
    │   │   ├───bonjour
    │   │   ├───bootstrap
    │   │   │   └───js
    │   │   │       └───dist
    │   │   ├───clean-css
    │   │   ├───connect
    │   │   ├───connect-history-api-fallback
    │   │   ├───eslint
    │   │   │   └───rules
    │   │   ├───eslint-scope
    │   │   ├───estree
    │   │   ├───express
    │   │   │   └───ts4.0
    │   │   ├───express-serve-static-core
    │   │   │   └───ts4.0
    │   │   ├───glob
    │   │   ├───http-proxy
    │   │   ├───imagemin
    │   │   ├───imagemin-gifsicle
    │   │   ├───imagemin-mozjpeg
    │   │   ├───imagemin-optipng
    │   │   ├───imagemin-svgo
    │   │   ├───json-schema
    │   │   ├───mime
    │   │   ├───minimatch
    │   │   ├───node
    │   │   │   ├───assert
    │   │   │   ├───dns
    │   │   │   ├───fs
    │   │   │   ├───stream
    │   │   │   └───timers
    │   │   ├───node-sass
    │   │   ├───parse-json
    │   │   ├───qs
    │   │   ├───range-parser
    │   │   ├───retry
    │   │   ├───sass
    │   │   ├───sass-loader
    │   │   ├───serve-index
    │   │   ├───serve-static
    │   │   ├───sockjs
    │   │   ├───source-list-map
    │   │   ├───svgo
    │   │   ├───tapable
    │   │   ├───uglify-js
    │   │   ├───webpack
    │   │   ├───webpack-sources
    │   │   │   ├───lib
    │   │   │   └───node_modules
    │   │   │       └───source-map
    │   │   │           ├───dist
    │   │   │           └───lib
    │   │   └───ws
    │   ├───@vue
    │   │   ├───compiler-sfc
    │   │   │   ├───dist
    │   │   │   └───node_modules
    │   │   │       └───.bin
    │   │   └───component-compiler-utils
    │   │       ├───dist
    │   │       │   ├───stylePlugins
    │   │       │   ├───styleProcessors
    │   │       │   └───templateCompilerModules
    │   │       ├───lib
    │   │       │   ├───stylePlugins
    │   │       │   ├───styleProcessors
    │   │       │   └───templateCompilerModules
    │   │       └───node_modules
    │   │           ├───.bin
    │   │           ├───picocolors
    │   │           └───postcss
    │   │               └───lib
    │   ├───@webassemblyjs
    │   │   ├───ast
    │   │   │   ├───esm
    │   │   │   │   ├───transform
    │   │   │   │   │   ├───ast-module-to-module-context
    │   │   │   │   │   ├───denormalize-type-references
    │   │   │   │   │   └───wast-identifier-to-index
    │   │   │   │   └───types
    │   │   │   ├───lib
    │   │   │   │   ├───transform
    │   │   │   │   │   ├───ast-module-to-module-context
    │   │   │   │   │   ├───denormalize-type-references
    │   │   │   │   │   └───wast-identifier-to-index
    │   │   │   │   └───types
    │   │   │   └───scripts
    │   │   ├───floating-point-hex-parser
    │   │   │   ├───esm
    │   │   │   └───lib
    │   │   ├───helper-api-error
    │   │   │   ├───esm
    │   │   │   └───lib
    │   │   ├───helper-buffer
    │   │   │   ├───esm
    │   │   │   └───lib
    │   │   ├───helper-numbers
    │   │   │   ├───esm
    │   │   │   ├───lib
    │   │   │   └───src
    │   │   ├───helper-wasm-bytecode
    │   │   │   ├───esm
    │   │   │   └───lib
    │   │   ├───helper-wasm-section
    │   │   │   ├───esm
    │   │   │   └───lib
    │   │   ├───ieee754
    │   │   │   ├───esm
    │   │   │   ├───lib
    │   │   │   └───src
    │   │   ├───leb128
    │   │   │   ├───esm
    │   │   │   └───lib
    │   │   ├───utf8
    │   │   │   ├───esm
    │   │   │   ├───lib
    │   │   │   ├───src
    │   │   │   └───test
    │   │   ├───wasm-edit
    │   │   │   ├───esm
    │   │   │   └───lib
    │   │   ├───wasm-gen
    │   │   │   ├───esm
    │   │   │   │   └───encoder
    │   │   │   └───lib
    │   │   │       └───encoder
    │   │   ├───wasm-opt
    │   │   │   ├───esm
    │   │   │   └───lib
    │   │   ├───wasm-parser
    │   │   │   ├───esm
    │   │   │   │   └───types
    │   │   │   └───lib
    │   │   │       └───types
    │   │   └───wast-printer
    │   │       ├───esm
    │   │       └───lib
    │   ├───@webpack-cli
    │   │   ├───configtest
    │   │   │   ├───lib
    │   │   │   └───node_modules
    │   │   │       └───.bin
    │   │   ├───info
    │   │   │   ├───lib
    │   │   │   └───node_modules
    │   │   │       └───.bin
    │   │   └───serve
    │   │       ├───lib
    │   │       └───node_modules
    │   │           └───.bin
    │   ├───@xtuc
    │   │   ├───ieee754
    │   │   │   └───dist
    │   │   └───long
    │   │       ├───dist
    │   │       └───src
    │   ├───accepts
    │   ├───acorn
    │   │   ├───bin
    │   │   └───dist
    │   ├───acorn-import-assertions
    │   │   ├───lib
    │   │   ├───node_modules
    │   │   │   └───.bin
    │   │   └───src
    │   ├───adjust-sourcemap-loader
    │   │   ├───codec
    │   │   │   └───utility
    │   │   └───lib
    │   │       └───process
    │   ├───ajv
    │   │   ├───dist
    │   │   ├───lib
    │   │   │   ├───compile
    │   │   │   ├───dot
    │   │   │   ├───dotjs
    │   │   │   └───refs
    │   │   └───scripts
    │   ├───ajv-keywords
    │   │   └───keywords
    │   │       ├───dot
    │   │       └───dotjs
    │   ├───ansi-html-community
    │   │   └───bin
    │   ├───ansi-regex
    │   ├───ansi-styles
    │   ├───anymatch
    │   ├───arity-n
    │   ├───array-flatten
    │   ├───array-union
    │   ├───asn1.js
    │   │   └───lib
    │   │       └───asn1
    │   │           ├───base
    │   │           ├───constants
    │   │           ├───decoders
    │   │           └───encoders
    │   ├───assert
    │   │   └───node_modules
    │   │       ├───inherits
    │   │       └───util
    │   │           ├───support
    │   │           └───test
    │   │               ├───browser
    │   │               └───node
    │   ├───atob
    │   │   └───bin
    │   ├───autoprefixer
    │   │   ├───bin
    │   │   ├───data
    │   │   ├───lib
    │   │   │   └───hacks
    │   │   └───node_modules
    │   │       └───.bin
    │   ├───axios
    │   │   ├───dist
    │   │   └───lib
    │   │       ├───adapters
    │   │       ├───cancel
    │   │       ├───core
    │   │       └───helpers
    │   ├───babel-loader
    │   │   ├───lib
    │   │   └───node_modules
    │   │       ├───.bin
    │   │       └───schema-utils
    │   │           ├───declarations
    │   │           │   ├───keywords
    │   │           │   └───util
    │   │           └───dist
    │   │               ├───keywords
    │   │               └───util
    │   ├───babel-plugin-dynamic-import-node
    │   │   └───lib
    │   ├───babel-plugin-polyfill-corejs2
    │   │   ├───esm
    │   │   ├───lib
    │   │   └───node_modules
    │   │       └───.bin
    │   ├───babel-plugin-polyfill-corejs3
    │   │   ├───core-js-compat
    │   │   ├───esm
    │   │   └───lib
    │   ├───babel-plugin-polyfill-regenerator
    │   │   ├───esm
    │   │   └───lib
    │   ├───balanced-match
    │   │   └───.github
    │   ├───base64-js
    │   ├───batch
    │   ├───big.js
    │   ├───binary-extensions
    │   ├───bluebird
    │   │   └───js
    │   │       ├───browser
    │   │       └───release
    │   ├───bn.js
    │   │   └───lib
    │   ├───body-parser
    │   │   └───lib
    │   │       └───types
    │   ├───bonjour-service
    │   │   ├───.github
    │   │   │   └───workflows
    │   │   ├───dist
    │   │   │   └───lib
    │   │   │       └───utils
    │   │   ├───examples
    │   │   ├───node_modules
    │   │   │   ├───.bin
    │   │   │   └───array-flatten
    │   │   └───types
    │   ├───boolbase
    │   ├───bootstrap
    │   │   ├───dist
    │   │   │   ├───css
    │   │   │   └───js
    │   │   ├───js
    │   │   │   ├───dist
    │   │   │   │   ├───dom
    │   │   │   │   └───util
    │   │   │   └───src
    │   │   │       ├───dom
    │   │   │       └───util
    │   │   └───scss
    │   │       ├───forms
    │   │       ├───helpers
    │   │       ├───mixins
    │   │       ├───utilities
    │   │       └───vendor
    │   ├───brace-expansion
    │   ├───braces
    │   │   └───lib
    │   ├───brorand
    │   │   └───test
    │   ├───browserify-aes
    │   │   └───modes
    │   ├───browserify-cipher
    │   ├───browserify-des
    │   ├───browserify-rsa
    │   │   └───node_modules
    │   │       └───bn.js
    │   │           └───lib
    │   ├───browserify-sign
    │   │   ├───browser
    │   │   └───node_modules
    │   │       ├───bn.js
    │   │       │   └───lib
    │   │       ├───readable-stream
    │   │       │   └───lib
    │   │       │       └───internal
    │   │       │           └───streams
    │   │       └───safe-buffer
    │   ├───browserify-zlib
    │   │   ├───lib
    │   │   └───src
    │   ├───browserslist
    │   │   └───node_modules
    │   │       └───.bin
    │   ├───buffer
    │   │   ├───bin
    │   │   └───test
    │   │       └───node
    │   ├───buffer-from
    │   ├───buffer-xor
    │   │   └───test
    │   ├───builtin-status-codes
    │   ├───bytes
    │   ├───call-bind
    │   │   ├───.github
    │   │   └───test
    │   ├───callsites
    │   ├───camel-case
    │   │   ├───dist
    │   │   └───dist.es2015
    │   ├───camelcase
    │   ├───caniuse-api
    │   │   ├───dist
    │   │   └───node_modules
    │   │       └───.bin
    │   ├───caniuse-lite
    │   │   ├───data
    │   │   │   ├───features
    │   │   │   └───regions
    │   │   └───dist
    │   │       ├───lib
    │   │       └───unpacker
    │   ├───chalk
    │   │   ├───node_modules
    │   │   │   ├───ansi-styles
    │   │   │   ├───color-convert
    │   │   │   └───color-name
    │   │   └───types
    │   ├───charenc
    │   ├───chokidar
    │   │   ├───lib
    │   │   └───types
    │   ├───chrome-trace-event
    │   │   └───dist
    │   ├───cipher-base
    │   ├───clean-css
    │   │   └───lib
    │   │       ├───optimizer
    │   │       │   ├───configuration
    │   │       │   │   └───properties
    │   │       │   ├───level-0
    │   │       │   ├───level-1
    │   │       │   │   ├───property-optimizers
    │   │       │   │   └───value-optimizers
    │   │       │   │       └───color
    │   │       │   └───level-2
    │   │       │       └───properties
    │   │       ├───options
    │   │       ├───reader
    │   │       ├───tokenizer
    │   │       ├───utils
    │   │       └───writer
    │   ├───cli-table3
    │   │   └───src
    │   ├───cliui
    │   │   └───build
    │   │       └───lib
    │   ├───clone-deep
    │   ├───collect.js
    │   │   ├───build
    │   │   ├───bundler
    │   │   ├───dist
    │   │   │   ├───helpers
    │   │   │   └───methods
    │   │   ├───docs
    │   │   │   ├───.vuepress
    │   │   │   └───api
    │   │   └───src
    │   │       ├───helpers
    │   │       └───methods
    │   ├───color-convert
    │   ├───color-name
    │   ├───colord
    │   │   └───plugins
    │   ├───colorette
    │   ├───commander
    │   │   └───typings
    │   ├───commondir
    │   │   ├───example
    │   │   └───test
    │   ├───compose-function
    │   │   └───module
    │   ├───compressible
    │   ├───compression
    │   │   └───node_modules
    │   │       └───bytes
    │   ├───concat
    │   │   ├───bin
    │   │   └───test
    │   │       └───folder
    │   ├───concat-map
    │   │   ├───example
    │   │   └───test
    │   ├───connect-history-api-fallback
    │   │   └───lib
    │   ├───consola
    │   │   ├───dist
    │   │   ├───src
    │   │   │   ├───reporters
    │   │   │   └───utils
    │   │   └───types
    │   ├───console-browserify
    │   │   └───test
    │   │       └───static
    │   ├───consolidate
    │   │   └───lib
    │   ├───constants-browserify
    │   ├───content-disposition
    │   │   └───node_modules
    │   │       └───safe-buffer
    │   ├───content-type
    │   ├───convert-source-map
    │   ├───cookie
    │   ├───cookie-signature
    │   ├───core-js-compat
    │   │   └───node_modules
    │   │       ├───.bin
    │   │       └───semver
    │   │           ├───bin
    │   │           ├───classes
    │   │           ├───functions
    │   │           ├───internal
    │   │           └───ranges
    │   ├───core-util-is
    │   │   └───lib
    │   ├───cosmiconfig
    │   │   └───dist
    │   ├───create-ecdh
    │   ├───create-hash
    │   │   └───node_modules
    │   │       └───.bin
    │   ├───create-hmac
    │   │   └───node_modules
    │   │       └───.bin
    │   ├───cross-spawn
    │   │   ├───lib
    │   │   │   └───util
    │   │   └───node_modules
    │   │       └───.bin
    │   ├───crypt
    │   ├───crypto-browserify
    │   │   ├───example
    │   │   └───test
    │   │       └───node
    │   ├───css
    │   │   └───lib
    │   │       ├───parse
    │   │       └───stringify
    │   ├───css-declaration-sorter
    │   │   ├───dist
    │   │   ├───orders
    │   │   └───src
    │   ├───css-loader
    │   │   ├───dist
    │   │   │   ├───plugins
    │   │   │   └───runtime
    │   │   └───node_modules
    │   │       ├───.bin
    │   │       ├───lru-cache
    │   │       ├───semver
    │   │       │   ├───bin
    │   │       │   ├───classes
    │   │       │   ├───functions
    │   │       │   ├───internal
    │   │       │   └───ranges
    │   │       └───yallist
    │   ├───css-select
    │   │   └───lib
    │   │       └───pseudo-selectors
    │   ├───css-tree
    │   │   ├───data
    │   │   ├───dist
    │   │   └───lib
    │   │       ├───common
    │   │       ├───convertor
    │   │       ├───definition-syntax
    │   │       ├───generator
    │   │       ├───lexer
    │   │       ├───parser
    │   │       ├───syntax
    │   │       │   ├───atrule
    │   │       │   ├───config
    │   │       │   ├───function
    │   │       │   ├───node
    │   │       │   ├───pseudo
    │   │       │   │   └───common
    │   │       │   └───scope
    │   │       ├───tokenizer
    │   │       ├───utils
    │   │       └───walker
    │   ├───css-what
    │   │   └───lib
    │   │       ├───commonjs
    │   │       └───es
    │   ├───cssesc
    │   │   ├───bin
    │   │   └───man
    │   ├───cssnano
    │   │   ├───src
    │   │   │   ├───postcss-discard-comments
    │   │   │   ├───postcss-discard-empty
    │   │   │   └───postcss-normalize-whitespace
    │   │   └───types
    │   ├───cssnano-preset-default
    │   │   ├───src
    │   │   └───types
    │   ├───cssnano-utils
    │   │   ├───src
    │   │   └───types
    │   ├───csso
    │   │   ├───dist
    │   │   └───lib
    │   │       ├───clean
    │   │       ├───replace
    │   │       │   ├───atrule
    │   │       │   └───property
    │   │       └───restructure
    │   │           └───prepare
    │   ├───csstype
    │   ├───d
    │   │   ├───.github
    │   │   └───test
    │   ├───de-indent
    │   ├───debug
    │   │   └───src
    │   ├───decode-uri-component
    │   ├───default-gateway
    │   ├───define-lazy-prop
    │   ├───define-properties
    │   │   └───.github
    │   ├───depd
    │   │   └───lib
    │   │       └───browser
    │   ├───des.js
    │   │   ├───lib
    │   │   │   └───des
    │   │   └───test
    │   ├───destroy
    │   ├───detect-node
    │   ├───diffie-hellman
    │   │   ├───lib
    │   │   └───node_modules
    │   │       └───.bin
    │   ├───dir-glob
    │   ├───dns-equal
    │   ├───dns-packet
    │   ├───dom-serializer
    │   │   └───lib
    │   │       └───esm
    │   ├───domain-browser
    │   │   └───source
    │   ├───domelementtype
    │   │   └───lib
    │   │       └───esm
    │   ├───domhandler
    │   │   └───lib
    │   ├───domutils
    │   │   └───lib
    │   ├───dot-case
    │   │   ├───dist
    │   │   └───dist.es2015
    │   ├───dotenv
    │   │   ├───lib
    │   │   └───types
    │   ├───dotenv-expand
    │   │   └───lib
    │   ├───ee-first
    │   ├───electron-to-chromium
    │   ├───elliptic
    │   │   └───lib
    │   │       └───elliptic
    │   │           ├───curve
    │   │           ├───ec
    │   │           ├───eddsa
    │   │           └───precomputed
    │   ├───emoji-regex
    │   │   └───es2015
    │   ├───emojis-list
    │   ├───encodeurl
    │   ├───enhanced-resolve
    │   │   └───lib
    │   │       └───util
    │   ├───entities
    │   │   └───lib
    │   │       └───maps
    │   ├───envinfo
    │   │   └───dist
    │   ├───error-ex
    │   ├───es-module-lexer
    │   │   ├───dist
    │   │   └───types
    │   ├───es5-ext
    │   │   ├───array
    │   │   │   ├───#
    │   │   │   │   ├───@@iterator
    │   │   │   │   ├───concat
    │   │   │   │   ├───copy-within
    │   │   │   │   ├───entries
    │   │   │   │   ├───fill
    │   │   │   │   ├───filter
    │   │   │   │   ├───find
    │   │   │   │   ├───find-index
    │   │   │   │   ├───keys
    │   │   │   │   ├───map
    │   │   │   │   ├───slice
    │   │   │   │   ├───splice
    │   │   │   │   └───values
    │   │   │   ├───from
    │   │   │   └───of
    │   │   ├───boolean
    │   │   ├───date
    │   │   │   └───#
    │   │   ├───error
    │   │   │   └───#
    │   │   ├───function
    │   │   │   └───#
    │   │   ├───iterable
    │   │   ├───json
    │   │   ├───math
    │   │   │   ├───acosh
    │   │   │   ├───asinh
    │   │   │   ├───atanh
    │   │   │   ├───cbrt
    │   │   │   ├───clz32
    │   │   │   ├───cosh
    │   │   │   ├───expm1
    │   │   │   ├───fround
    │   │   │   ├───hypot
    │   │   │   ├───imul
    │   │   │   ├───log10
    │   │   │   ├───log1p
    │   │   │   ├───log2
    │   │   │   ├───sign
    │   │   │   ├───sinh
    │   │   │   ├───tanh
    │   │   │   └───trunc
    │   │   ├───number
    │   │   │   ├───#
    │   │   │   ├───epsilon
    │   │   │   ├───is-finite
    │   │   │   ├───is-integer
    │   │   │   ├───is-nan
    │   │   │   ├───is-safe-integer
    │   │   │   ├───max-safe-integer
    │   │   │   └───min-safe-integer
    │   │   ├───object
    │   │   │   ├───assign
    │   │   │   ├───entries
    │   │   │   ├───keys
    │   │   │   └───set-prototype-of
    │   │   ├───promise
    │   │   │   └───#
    │   │   │       └───finally
    │   │   ├───reg-exp
    │   │   │   └───#
    │   │   │       ├───match
    │   │   │       ├───replace
    │   │   │       ├───search
    │   │   │       ├───split
    │   │   │       ├───sticky
    │   │   │       └───unicode
    │   │   └───string
    │   │       ├───#
    │   │       │   ├───@@iterator
    │   │       │   ├───code-point-at
    │   │       │   ├───contains
    │   │       │   ├───ends-with
    │   │       │   ├───normalize
    │   │       │   ├───repeat
    │   │       │   └───starts-with
    │   │       ├───from-code-point
    │   │       └───raw
    │   ├───es6-iterator
    │   │   ├───#
    │   │   └───test
    │   │       └───#
    │   ├───es6-symbol
    │   │   ├───.github
    │   │   ├───lib
    │   │   │   └───private
    │   │   │       └───setup
    │   │   └───test
    │   ├───escalade
    │   │   ├───dist
    │   │   └───sync
    │   ├───escape-html
    │   ├───escape-string-regexp
    │   ├───eslint-scope
    │   │   └───lib
    │   ├───esrecurse
    │   │   └───node_modules
    │   │       └───estraverse
    │   ├───estraverse
    │   ├───esutils
    │   │   └───lib
    │   ├───etag
    │   ├───eventemitter3
    │   │   └───umd
    │   ├───events
    │   │   ├───.github
    │   │   └───tests
    │   ├───evp_bytestokey
    │   ├───execa
    │   │   └───lib
    │   ├───express
    │   │   ├───lib
    │   │   │   ├───middleware
    │   │   │   └───router
    │   │   └───node_modules
    │   │       └───safe-buffer
    │   ├───ext
    │   │   ├───.github
    │   │   ├───docs
    │   │   │   ├───function
    │   │   │   ├───math
    │   │   │   ├───object
    │   │   │   ├───promise
    │   │   │   ├───string
    │   │   │   ├───string_
    │   │   │   └───thenable_
    │   │   ├───function
    │   │   ├───global-this
    │   │   ├───lib
    │   │   │   └───private
    │   │   ├───math
    │   │   ├───node_modules
    │   │   │   └───type
    │   │   │       ├───array
    │   │   │       ├───array-length
    │   │   │       ├───array-like
    │   │   │       ├───big-int
    │   │   │       ├───constructor
    │   │   │       ├───date
    │   │   │       ├───docs
    │   │   │       ├───error
    │   │   │       ├───finite
    │   │   │       ├───function
    │   │   │       ├───integer
    │   │   │       ├───iterable
    │   │   │       ├───lib
    │   │   │       │   └───ensure
    │   │   │       ├───map
    │   │   │       ├───natural-number
    │   │   │       ├───number
    │   │   │       ├───object
    │   │   │       ├───plain-function
    │   │   │       ├───plain-object
    │   │   │       ├───promise
    │   │   │       ├───prototype
    │   │   │       ├───reg-exp
    │   │   │       ├───safe-integer
    │   │   │       ├───set
    │   │   │       ├───string
    │   │   │       ├───thenable
    │   │   │       ├───time-value
    │   │   │       ├───ts-types
    │   │   │       │   ├───array
    │   │   │       │   ├───array-length
    │   │   │       │   ├───array-like
    │   │   │       │   ├───big-int
    │   │   │       │   ├───constructor
    │   │   │       │   ├───date
    │   │   │       │   ├───error
    │   │   │       │   ├───finite
    │   │   │       │   ├───function
    │   │   │       │   ├───integer
    │   │   │       │   ├───iterable
    │   │   │       │   ├───map
    │   │   │       │   ├───natural-number
    │   │   │       │   ├───number
    │   │   │       │   ├───object
    │   │   │       │   ├───plain-function
    │   │   │       │   ├───plain-object
    │   │   │       │   ├───promise
    │   │   │       │   ├───prototype
    │   │   │       │   ├───reg-exp
    │   │   │       │   ├───safe-integer
    │   │   │       │   ├───set
    │   │   │       │   ├───string
    │   │   │       │   ├───thenable
    │   │   │       │   ├───time-value
    │   │   │       │   └───value
    │   │   │       └───value
    │   │   ├───object
    │   │   │   └───entries
    │   │   ├───promise
    │   │   ├───string
    │   │   ├───string_
    │   │   │   └───includes
    │   │   ├───test
    │   │   │   ├───function
    │   │   │   ├───global-this
    │   │   │   ├───math
    │   │   │   ├───object
    │   │   │   │   └───entries
    │   │   │   ├───promise
    │   │   │   ├───string
    │   │   │   ├───string_
    │   │   │   │   └───includes
    │   │   │   └───thenable_
    │   │   └───thenable_
    │   ├───fast-deep-equal
    │   │   └───es6
    │   ├───fast-glob
    │   │   └───out
    │   │       ├───managers
    │   │       ├───providers
    │   │       │   ├───filters
    │   │       │   ├───matchers
    │   │       │   └───transformers
    │   │       ├───readers
    │   │       ├───types
    │   │       └───utils
    │   ├───fast-json-stable-stringify
    │   │   ├───.github
    │   │   ├───benchmark
    │   │   ├───example
    │   │   └───test
    │   ├───fastest-levenshtein
    │   │   └───esm
    │   ├───fastq
    │   │   ├───.github
    │   │   │   └───workflows
    │   │   └───test
    │   ├───faye-websocket
    │   │   └───lib
    │   │       └───faye
    │   │           └───websocket
    │   │               └───api
    │   ├───file-loader
    │   │   ├───dist
    │   │   └───node_modules
    │   │       └───.bin
    │   ├───file-type
    │   ├───fill-range
    │   ├───finalhandler
    │   ├───find-cache-dir
    │   ├───find-up
    │   ├───follow-redirects
    │   ├───forwarded
    │   ├───fraction.js
    │   ├───fresh
    │   ├───fs-extra
    │   │   └───lib
    │   │       ├───copy
    │   │       ├───empty
    │   │       ├───ensure
    │   │       ├───fs
    │   │       ├───json
    │   │       ├───mkdirs
    │   │       ├───move
    │   │       ├───output-file
    │   │       ├───path-exists
    │   │       ├───remove
    │   │       └───util
    │   ├───fs-monkey
    │   │   ├───docs
    │   │   │   └───api
    │   │   └───lib
    │   │       └───util
    │   ├───fs.realpath
    │   ├───function-bind
    │   │   └───test
    │   ├───gensync
    │   │   └───test
    │   ├───get-caller-file
    │   ├───get-intrinsic
    │   │   ├───.github
    │   │   └───test
    │   ├───get-stream
    │   ├───glob
    │   ├───glob-parent
    │   ├───glob-to-regexp
    │   ├───globals
    │   ├───globby
    │   ├───graceful-fs
    │   ├───growly
    │   │   ├───example
    │   │   └───lib
    │   ├───handle-thing
    │   │   ├───lib
    │   │   └───test
    │   ├───has
    │   │   ├───src
    │   │   └───test
    │   ├───has-flag
    │   ├───has-property-descriptors
    │   │   ├───.github
    │   │   └───test
    │   ├───has-symbols
    │   │   ├───.github
    │   │   └───test
    │   │       └───shams
    │   ├───hash-base
    │   │   └───node_modules
    │   │       ├───readable-stream
    │   │       │   └───lib
    │   │       │       └───internal
    │   │       │           └───streams
    │   │       └───safe-buffer
    │   ├───hash-sum
    │   ├───hash.js
    │   │   ├───lib
    │   │   │   └───hash
    │   │   │       └───sha
    │   │   └───test
    │   ├───he
    │   │   ├───bin
    │   │   └───man
    │   ├───hmac-drbg
    │   │   ├───lib
    │   │   └───test
    │   │       └───fixtures
    │   ├───hpack.js
    │   │   ├───bin
    │   │   ├───lib
    │   │   │   └───hpack
    │   │   ├───test
    │   │   └───tools
    │   ├───html-entities
    │   │   └───lib
    │   ├───html-loader
    │   │   ├───dist
    │   │   │   ├───plugins
    │   │   │   └───runtime
    │   │   └───node_modules
    │   │       └───.bin
    │   ├───html-minifier-terser
    │   │   ├───node_modules
    │   │   │   ├───.bin
    │   │   │   ├───clean-css
    │   │   │   │   └───lib
    │   │   │   │       ├───optimizer
    │   │   │   │       │   ├───level-0
    │   │   │   │       │   ├───level-1
    │   │   │   │       │   └───level-2
    │   │   │   │       │       └───properties
    │   │   │   │       ├───options
    │   │   │   │       ├───reader
    │   │   │   │       ├───tokenizer
    │   │   │   │       ├───utils
    │   │   │   │       └───writer
    │   │   │   ├───commander
    │   │   │   │   └───typings
    │   │   │   └───terser
    │   │   │       ├───bin
    │   │   │       ├───dist
    │   │   │       ├───node_modules
    │   │   │       │   └───commander
    │   │   │       │       └───typings
    │   │   │       └───tools
    │   │   └───src
    │   ├───htmlparser2
    │   │   ├───lib
    │   │   └───node_modules
    │   │       └───domhandler
    │   │           └───lib
    │   ├───http-deceiver
    │   │   ├───lib
    │   │   └───test
    │   ├───http-errors
    │   ├───http-parser-js
    │   ├───http-proxy
    │   │   └───lib
    │   │       └───http-proxy
    │   │           └───passes
    │   ├───http-proxy-middleware
    │   │   └───dist
    │   │       └───handlers
    │   ├───https-browserify
    │   ├───human-signals
    │   │   └───build
    │   │       └───src
    │   ├───iconv-lite
    │   │   ├───encodings
    │   │   │   └───tables
    │   │   └───lib
    │   ├───icss-utils
    │   │   └───src
    │   ├───ieee754
    │   ├───ignore
    │   ├───imagemin
    │   ├───img-loader
    │   │   ├───.github
    │   │   │   └───workflows
    │   │   ├───node_modules
    │   │   │   └───loader-utils
    │   │   │       ├───lib
    │   │   │       └───node_modules
    │   │   │           └───.bin
    │   │   └───__tests__
    │   ├───immutable
    │   │   └───dist
    │   ├───import-fresh
    │   ├───import-local
    │   │   └───fixtures
    │   ├───inflight
    │   ├───inherits
    │   ├───interpret
    │   ├───ipaddr.js
    │   │   └───lib
    │   ├───is-arrayish
    │   ├───is-binary-path
    │   ├───is-buffer
    │   │   └───test
    │   ├───is-core-module
    │   │   └───test
    │   ├───is-docker
    │   ├───is-extglob
    │   ├───is-fullwidth-code-point
    │   ├───is-glob
    │   ├───is-number
    │   ├───is-plain-obj
    │   ├───is-plain-object
    │   ├───is-stream
    │   ├───is-wsl
    │   │   └───node_modules
    │   │       └───.bin
    │   ├───isarray
    │   ├───isexe
    │   │   └───test
    │   ├───isobject
    │   ├───jest-worker
    │   │   ├───build
    │   │   │   ├───base
    │   │   │   └───workers
    │   │   └───node_modules
    │   │       ├───has-flag
    │   │       └───supports-color
    │   ├───js-tokens
    │   ├───jsesc
    │   │   ├───bin
    │   │   └───man
    │   ├───json-parse-even-better-errors
    │   ├───json-schema-traverse
    │   │   └───spec
    │   │       └───fixtures
    │   ├───json5
    │   │   ├───dist
    │   │   └───lib
    │   ├───jsonfile
    │   ├───junk
    │   ├───kind-of
    │   ├───klona
    │   │   ├───dist
    │   │   ├───full
    │   │   ├───json
    │   │   └───lite
    │   ├───laravel-mix
    │   │   ├───bin
    │   │   ├───icons
    │   │   ├───node_modules
    │   │   │   ├───.bin
    │   │   │   ├───chalk
    │   │   │   │   └───source
    │   │   │   ├───commander
    │   │   │   │   └───typings
    │   │   │   ├───has-flag
    │   │   │   ├───lru-cache
    │   │   │   ├───semver
    │   │   │   │   ├───bin
    │   │   │   │   ├───classes
    │   │   │   │   ├───functions
    │   │   │   │   ├───internal
    │   │   │   │   └───ranges
    │   │   │   ├───supports-color
    │   │   │   └───yallist
    │   │   ├───setup
    │   │   ├───src
    │   │   │   ├───builder
    │   │   │   ├───components
    │   │   │   ├───tasks
    │   │   │   └───webpackPlugins
    │   │   │       └───Css
    │   │   └───types
    │   ├───lilconfig
    │   │   └───dist
    │   ├───lines-and-columns
    │   │   └───build
    │   ├───loader-runner
    │   │   └───lib
    │   ├───loader-utils
    │   │   ├───lib
    │   │   │   └───hash
    │   │   └───node_modules
    │   │       ├───.bin
    │   │       └───json5
    │   │           ├───dist
    │   │           └───lib
    │   ├───locate-path
    │   ├───lodash
    │   │   └───fp
    │   ├───lodash.debounce
    │   ├───lodash.memoize
    │   ├───lodash.uniq
    │   ├───lower-case
    │   │   ├───dist
    │   │   └───dist.es2015
    │   ├───lru-cache
    │   ├───make-dir
    │   │   └───node_modules
    │   │       └───.bin
    │   ├───md5
    │   │   ├───demo
    │   │   └───dist
    │   ├───md5.js
    │   ├───mdn-data
    │   │   ├───api
    │   │   ├───css
    │   │   └───l10n
    │   ├───media-typer
    │   ├───memfs
    │   │   └───lib
    │   │       └───internal
    │   ├───merge-descriptors
    │   ├───merge-source-map
    │   ├───merge-stream
    │   ├───merge2
    │   ├───methods
    │   ├───micromatch
    │   ├───miller-rabin
    │   │   ├───bin
    │   │   ├───lib
    │   │   └───test
    │   ├───mime
    │   │   └───src
    │   ├───mime-db
    │   ├───mime-types
    │   ├───mimic-fn
    │   ├───mini-css-extract-plugin
    │   │   ├───dist
    │   │   │   └───hmr
    │   │   └───node_modules
    │   │       └───.bin
    │   ├───minimalistic-assert
    │   ├───minimalistic-crypto-utils
    │   │   ├───lib
    │   │   └───test
    │   ├───minimatch
    │   ├───minimist
    │   │   ├───example
    │   │   └───test
    │   ├───ms
    │   ├───multicast-dns
    │   ├───nanoid
    │   │   ├───async
    │   │   ├───bin
    │   │   ├───non-secure
    │   │   └───url-alphabet
    │   ├───negotiator
    │   │   └───lib
    │   ├───neo-async
    │   ├───next-tick
    │   │   ├───.github
    │   │   └───test
    │   ├───no-case
    │   │   ├───dist
    │   │   └───dist.es2015
    │   ├───node-forge
    │   │   ├───dist
    │   │   ├───flash
    │   │   │   └───swf
    │   │   └───lib
    │   ├───node-libs-browser
    │   │   └───mock
    │   ├───node-notifier
    │   │   ├───lib
    │   │   ├───node_modules
    │   │   │   ├───.bin
    │   │   │   ├───lru-cache
    │   │   │   ├───semver
    │   │   │   │   ├───bin
    │   │   │   │   ├───classes
    │   │   │   │   ├───functions
    │   │   │   │   ├───internal
    │   │   │   │   └───ranges
    │   │   │   └───yallist
    │   │   ├───notifiers
    │   │   └───vendor
    │   │       ├───mac.noindex
    │   │       │   └───terminal-notifier.app
    │   │       │       └───Contents
    │   │       │           ├───MacOS
    │   │       │           └───Resources
    │   │       │               └───en.lproj
    │   │       ├───notifu
    │   │       └───snoreToast
    │   ├───node-releases
    │   │   └───data
    │   │       ├───processed
    │   │       └───release-schedule
    │   ├───normalize-path
    │   ├───normalize-range
    │   ├───normalize-url
    │   ├───npm-run-path
    │   ├───nth-check
    │   │   └───lib
    │   │       └───esm
    │   ├───object-assign
    │   ├───object-inspect
    │   │   ├───.github
    │   │   ├───example
    │   │   └───test
    │   │       └───browser
    │   ├───object-keys
    │   │   └───test
    │   ├───object.assign
    │   │   ├───.github
    │   │   │   └───workflows
    │   │   ├───dist
    │   │   └───test
    │   ├───obuf
    │   │   └───test
    │   ├───on-finished
    │   ├───on-headers
    │   ├───once
    │   ├───onetime
    │   ├───open
    │   │   └───node_modules
    │   │       └───.bin
    │   ├───os-browserify
    │   ├───p-limit
    │   ├───p-locate
    │   ├───p-pipe
    │   ├───p-retry
    │   ├───p-try
    │   ├───pako
    │   │   ├───dist
    │   │   └───lib
    │   │       ├───utils
    │   │       └───zlib
    │   ├───param-case
    │   │   ├───dist
    │   │   └───dist.es2015
    │   ├───parent-module
    │   ├───parse-asn1
    │   ├───parse-json
    │   ├───parseurl
    │   ├───pascal-case
    │   │   ├───dist
    │   │   └───dist.es2015
    │   ├───path-browserify
    │   │   └───test
    │   ├───path-exists
    │   ├───path-is-absolute
    │   ├───path-key
    │   ├───path-parse
    │   ├───path-to-regexp
    │   ├───path-type
    │   ├───pbkdf2
    │   │   ├───lib
    │   │   └───node_modules
    │   │       └───.bin
    │   ├───picocolors
    │   ├───picomatch
    │   │   └───lib
    │   ├───pkg-dir
    │   ├───postcss
    │   │   ├───lib
    │   │   └───node_modules
    │   │       └───.bin
    │   ├───postcss-calc
    │   │   ├───src
    │   │   │   ├───lib
    │   │   │   └───__tests__
    │   │   └───types
    │   │       └───lib
    │   ├───postcss-colormin
    │   │   ├───node_modules
    │   │   │   └───.bin
    │   │   ├───src
    │   │   └───types
    │   ├───postcss-convert-values
    │   │   ├───node_modules
    │   │   │   └───.bin
    │   │   ├───src
    │   │   │   └───lib
    │   │   └───types
    │   │       └───lib
    │   ├───postcss-discard-comments
    │   │   ├───src
    │   │   │   └───lib
    │   │   └───types
    │   │       └───lib
    │   ├───postcss-discard-duplicates
    │   │   ├───src
    │   │   └───types
    │   ├───postcss-discard-empty
    │   │   ├───src
    │   │   └───types
    │   ├───postcss-discard-overridden
    │   │   └───src
    │   ├───postcss-load-config
    │   │   └───src
    │   ├───postcss-loader
    │   │   ├───dist
    │   │   └───node_modules
    │   │       ├───.bin
    │   │       ├───lru-cache
    │   │       ├───semver
    │   │       │   ├───bin
    │   │       │   ├───classes
    │   │       │   ├───functions
    │   │       │   ├───internal
    │   │       │   └───ranges
    │   │       └───yallist
    │   ├───postcss-merge-longhand
    │   │   ├───src
    │   │   │   └───lib
    │   │   │       └───decl
    │   │   └───types
    │   │       └───lib
    │   │           └───decl
    │   ├───postcss-merge-rules
    │   │   ├───node_modules
    │   │   │   └───.bin
    │   │   ├───src
    │   │   │   └───lib
    │   │   └───types
    │   │       └───lib
    │   ├───postcss-minify-font-values
    │   │   ├───src
    │   │   │   └───lib
    │   │   └───types
    │   │       └───lib
    │   ├───postcss-minify-gradients
    │   │   ├───src
    │   │   └───types
    │   ├───postcss-minify-params
    │   │   ├───node_modules
    │   │   │   └───.bin
    │   │   ├───src
    │   │   └───types
    │   ├───postcss-minify-selectors
    │   │   ├───src
    │   │   │   └───lib
    │   │   └───types
    │   │       └───lib
    │   ├───postcss-modules-extract-imports
    │   │   └───src
    │   ├───postcss-modules-local-by-default
    │   │   └───src
    │   ├───postcss-modules-scope
    │   │   └───src
    │   ├───postcss-modules-values
    │   │   └───src
    │   ├───postcss-normalize-charset
    │   │   ├───src
    │   │   └───types
    │   ├───postcss-normalize-display-values
    │   │   ├───src
    │   │   │   └───lib
    │   │   └───types
    │   │       └───lib
    │   ├───postcss-normalize-positions
    │   │   ├───src
    │   │   └───types
    │   ├───postcss-normalize-repeat-style
    │   │   ├───src
    │   │   │   └───lib
    │   │   └───types
    │   │       └───lib
    │   ├───postcss-normalize-string
    │   │   ├───src
    │   │   └───types
    │   ├───postcss-normalize-timing-functions
    │   │   ├───src
    │   │   └───types
    │   ├───postcss-normalize-unicode
    │   │   ├───node_modules
    │   │   │   └───.bin
    │   │   ├───src
    │   │   └───types
    │   ├───postcss-normalize-url
    │   │   ├───src
    │   │   └───types
    │   ├───postcss-normalize-whitespace
    │   │   ├───src
    │   │   └───types
    │   ├───postcss-ordered-values
    │   │   ├───src
    │   │   │   ├───lib
    │   │   │   └───rules
    │   │   └───types
    │   │       ├───lib
    │   │       └───rules
    │   ├───postcss-reduce-initial
    │   │   ├───node_modules
    │   │   │   └───.bin
    │   │   ├───src
    │   │   │   └───data
    │   │   └───types
    │   ├───postcss-reduce-transforms
    │   │   ├───src
    │   │   └───types
    │   ├───postcss-selector-parser
    │   │   ├───dist
    │   │   │   ├───selectors
    │   │   │   └───util
    │   │   └───node_modules
    │   │       └───.bin
    │   ├───postcss-svgo
    │   │   ├───node_modules
    │   │   │   └───.bin
    │   │   ├───src
    │   │   │   └───lib
    │   │   └───types
    │   │       └───lib
    │   ├───postcss-unique-selectors
    │   │   ├───src
    │   │   └───types
    │   ├───postcss-value-parser
    │   │   └───lib
    │   ├───prettier
    │   │   └───esm
    │   ├───pretty-time
    │   ├───process
    │   ├───process-nextick-args
    │   ├───proxy-addr
    │   │   └───node_modules
    │   │       └───ipaddr.js
    │   │           └───lib
    │   ├───pseudomap
    │   │   └───test
    │   ├───public-encrypt
    │   │   └───test
    │   ├───punycode
    │   ├───qs
    │   │   ├───.github
    │   │   ├───dist
    │   │   ├───lib
    │   │   └───test
    │   ├───querystring
    │   │   └───test
    │   ├───querystring-es3
    │   │   └───test
    │   ├───queue-microtask
    │   ├───randombytes
    │   ├───randomfill
    │   ├───range-parser
    │   ├───raw-body
    │   ├───readable-stream
    │   │   ├───doc
    │   │   │   └───wg-meetings
    │   │   ├───lib
    │   │   │   └───internal
    │   │   │       └───streams
    │   │   └───node_modules
    │   │       └───string_decoder
    │   │           └───lib
    │   ├───readdirp
    │   ├───rechoir
    │   │   ├───lib
    │   │   └───node_modules
    │   │       └───.bin
    │   ├───regenerate
    │   ├───regenerate-unicode-properties
    │   │   ├───Binary_Property
    │   │   ├───General_Category
    │   │   ├───Property_of_Strings
    │   │   ├───Script
    │   │   └───Script_Extensions
    │   ├───regenerator-runtime
    │   ├───regenerator-transform
    │   │   ├───lib
    │   │   └───src
    │   ├───regex-parser
    │   │   └───lib
    │   │       └───typings
    │   ├───regexpu-core
    │   │   ├───data
    │   │   └───node_modules
    │   │       └───.bin
    │   ├───regjsgen
    │   ├───regjsparser
    │   │   ├───bin
    │   │   └───node_modules
    │   │       ├───.bin
    │   │       └───jsesc
    │   │           ├───bin
    │   │           └───man
    │   ├───relateurl
    │   │   └───lib
    │   │       ├───parse
    │   │       ├───relate
    │   │       └───util
    │   ├───replace-ext
    │   ├───require-directory
    │   ├───require-from-string
    │   ├───requires-port
    │   ├───resolve
    │   │   ├───.github
    │   │   ├───bin
    │   │   ├───example
    │   │   ├───lib
    │   │   └───test
    │   │       ├───dotdot
    │   │       │   └───abc
    │   │       ├───module_dir
    │   │       │   ├───xmodules
    │   │       │   │   └───aaa
    │   │       │   ├───ymodules
    │   │       │   │   └───aaa
    │   │       │   └───zmodules
    │   │       │       └───bbb
    │   │       ├───node_path
    │   │       │   ├───x
    │   │       │   │   ├───aaa
    │   │       │   │   └───ccc
    │   │       │   └───y
    │   │       │       ├───bbb
    │   │       │       └───ccc
    │   │       ├───pathfilter
    │   │       │   └───deep_ref
    │   │       ├───precedence
    │   │       │   ├───aaa
    │   │       │   └───bbb
    │   │       ├───resolver
    │   │       │   ├───baz
    │   │       │   ├───browser_field
    │   │       │   ├───dot_main
    │   │       │   ├───dot_slash_main
    │   │       │   ├───false_main
    │   │       │   ├───incorrect_main
    │   │       │   ├───invalid_main
    │   │       │   ├───malformed_package_json
    │   │       │   ├───multirepo
    │   │       │   │   └───packages
    │   │       │   │       ├───package-a
    │   │       │   │       └───package-b
    │   │       │   ├───nested_symlinks
    │   │       │   │   └───mylib
    │   │       │   ├───other_path
    │   │       │   │   └───lib
    │   │       │   ├───quux
    │   │       │   │   └───foo
    │   │       │   ├───same_names
    │   │       │   │   └───foo
    │   │       │   ├───symlinked
    │   │       │   │   ├───package
    │   │       │   │   └───_
    │   │       │   │       ├───node_modules
    │   │       │   │       └───symlink_target
    │   │       │   └───without_basedir
    │   │       └───shadowed_core
    │   │           └───node_modules
    │   │               └───util
    │   ├───resolve-cwd
    │   │   └───node_modules
    │   │       └───resolve-from
    │   ├───resolve-from
    │   ├───resolve-url
    │   │   └───test
    │   ├───resolve-url-loader
    │   │   ├───lib
    │   │   │   └───engine
    │   │   └───node_modules
    │   │       ├───emojis-list
    │   │       ├───loader-utils
    │   │       │   ├───lib
    │   │       │   └───node_modules
    │   │       │       └───.bin
    │   │       ├───postcss
    │   │       │   ├───docs
    │   │       │   │   └───guidelines
    │   │       │   └───lib
    │   │       └───supports-color
    │   ├───retry
    │   │   ├───example
    │   │   └───lib
    │   ├───reusify
    │   │   └───benchmarks
    │   ├───rework
    │   │   └───node_modules
    │   │       └───convert-source-map
    │   │           ├───example
    │   │           └───test
    │   │               └───fixtures
    │   ├───rework-visit
    │   ├───rimraf
    │   ├───ripemd160
    │   ├───run-parallel
    │   ├───safe-buffer
    │   ├───safer-buffer
    │   ├───sass
    │   │   └───types
    │   │       ├───legacy
    │   │       ├───logger
    │   │       ├───util
    │   │       └───value
    │   ├───sass-loader
    │   │   ├───dist
    │   │   └───node_modules
    │   │       └───.bin
    │   ├───schema-utils
    │   │   ├───declarations
    │   │   │   ├───keywords
    │   │   │   └───util
    │   │   └───dist
    │   │       ├───keywords
    │   │       └───util
    │   ├───select-hose
    │   │   ├───lib
    │   │   └───test
    │   ├───selfsigned
    │   │   └───test
    │   ├───semver
    │   │   └───bin
    │   ├───send
    │   │   └───node_modules
    │   │       ├───.bin
    │   │       └───ms
    │   ├───serialize-javascript
    │   ├───serve-index
    │   │   ├───node_modules
    │   │   │   ├───depd
    │   │   │   │   └───lib
    │   │   │   │       ├───browser
    │   │   │   │       └───compat
    │   │   │   ├───http-errors
    │   │   │   ├───inherits
    │   │   │   ├───setprototypeof
    │   │   │   └───statuses
    │   │   └───public
    │   │       └───icons
    │   ├───serve-static
    │   ├───setimmediate
    │   ├───setprototypeof
    │   │   └───test
    │   ├───sha.js
    │   │   └───test
    │   ├───shallow-clone
    │   ├───shebang-command
    │   ├───shebang-regex
    │   ├───shellwords
    │   │   └───lib
    │   ├───side-channel
    │   │   ├───.github
    │   │   └───test
    │   ├───signal-exit
    │   ├───slash
    │   ├───sockjs
    │   │   ├───lib
    │   │   └───node_modules
    │   │       └───.bin
    │   ├───source-list-map
    │   │   └───lib
    │   ├───source-map
    │   │   ├───dist
    │   │   └───lib
    │   ├───source-map-js
    │   │   └───lib
    │   ├───source-map-resolve
    │   │   ├───lib
    │   │   └───node_modules
    │   │       └───.bin
    │   ├───source-map-support
    │   ├───source-map-url
    │   ├───spdy
    │   │   ├───lib
    │   │   │   └───spdy
    │   │   ├───node_modules
    │   │   │   ├───debug
    │   │   │   │   └───src
    │   │   │   └───ms
    │   │   └───test
    │   ├───spdy-transport
    │   │   ├───lib
    │   │   │   └───spdy-transport
    │   │   │       └───protocol
    │   │   │           ├───base
    │   │   │           ├───http2
    │   │   │           └───spdy
    │   │   └───node_modules
    │   │       ├───debug
    │   │       │   └───src
    │   │       ├───ms
    │   │       └───readable-stream
    │   │           └───lib
    │   │               └───internal
    │   │                   └───streams
    │   ├───stable
    │   ├───statuses
    │   ├───std-env
    │   │   └───dist
    │   ├───stream-browserify
    │   │   └───test
    │   ├───stream-http
    │   │   ├───lib
    │   │   └───test
    │   │       ├───browser
    │   │       │   └───lib
    │   │       ├───node
    │   │       └───server
    │   │           └───static
    │   ├───string-width
    │   ├───string_decoder
    │   │   ├───lib
    │   │   └───node_modules
    │   │       └───safe-buffer
    │   ├───strip-ansi
    │   ├───strip-final-newline
    │   ├───style-loader
    │   │   ├───dist
    │   │   │   └───runtime
    │   │   └───node_modules
    │   │       └───.bin
    │   ├───stylehacks
    │   │   ├───node_modules
    │   │   │   └───.bin
    │   │   ├───src
    │   │   │   ├───dictionary
    │   │   │   └───plugins
    │   │   └───types
    │   │       ├───dictionary
    │   │       └───plugins
    │   ├───supports-color
    │   ├───supports-preserve-symlinks-flag
    │   │   ├───.github
    │   │   └───test
    │   ├───svgo
    │   │   ├───bin
    │   │   ├───dist
    │   │   ├───lib
    │   │   │   └───svgo
    │   │   ├───node_modules
    │   │   │   └───commander
    │   │   │       └───typings
    │   │   └───plugins
    │   ├───tapable
    │   │   └───lib
    │   ├───terser
    │   │   ├───bin
    │   │   ├───dist
    │   │   ├───lib
    │   │   │   ├───compress
    │   │   │   └───utils
    │   │   ├───node_modules
    │   │   │   └───.bin
    │   │   └───tools
    │   ├───terser-webpack-plugin
    │   │   ├───dist
    │   │   ├───node_modules
    │   │   │   └───.bin
    │   │   └───types
    │   ├───thunky
    │   ├───timers-browserify
    │   ├───to-arraybuffer
    │   ├───to-fast-properties
    │   ├───to-regex-range
    │   ├───toidentifier
    │   ├───tslib
    │   │   └───modules
    │   ├───tty-browserify
    │   ├───type
    │   │   ├───array
    │   │   ├───array-length
    │   │   ├───array-like
    │   │   ├───date
    │   │   ├───error
    │   │   ├───finite
    │   │   ├───function
    │   │   ├───integer
    │   │   ├───iterable
    │   │   ├───lib
    │   │   ├───natural-number
    │   │   ├───number
    │   │   ├───object
    │   │   ├───plain-function
    │   │   ├───plain-object
    │   │   ├───promise
    │   │   ├───prototype
    │   │   ├───reg-exp
    │   │   ├───safe-integer
    │   │   ├───string
    │   │   ├───test
    │   │   │   ├───array
    │   │   │   ├───array-length
    │   │   │   ├───array-like
    │   │   │   ├───date
    │   │   │   ├───error
    │   │   │   ├───finite
    │   │   │   ├───function
    │   │   │   ├───integer
    │   │   │   ├───iterable
    │   │   │   ├───lib
    │   │   │   ├───natural-number
    │   │   │   ├───number
    │   │   │   ├───object
    │   │   │   ├───plain-function
    │   │   │   ├───plain-object
    │   │   │   ├───promise
    │   │   │   ├───prototype
    │   │   │   ├───reg-exp
    │   │   │   ├───safe-integer
    │   │   │   ├───string
    │   │   │   ├───thenable
    │   │   │   ├───time-value
    │   │   │   ├───value
    │   │   │   └───_lib
    │   │   ├───thenable
    │   │   ├───time-value
    │   │   └───value
    │   ├───type-is
    │   ├───unicode-canonical-property-names-ecmascript
    │   ├───unicode-match-property-ecmascript
    │   ├───unicode-match-property-value-ecmascript
    │   │   └───data
    │   ├───unicode-property-aliases-ecmascript
    │   ├───universalify
    │   ├───unpipe
    │   ├───update-browserslist-db
    │   │   └───node_modules
    │   │       └───.bin
    │   ├───uri-js
    │   │   ├───dist
    │   │   │   ├───es5
    │   │   │   └───esnext
    │   │   │       └───schemes
    │   │   └───node_modules
    │   │       └───punycode
    │   ├───urix
    │   │   └───test
    │   ├───url
    │   │   └───node_modules
    │   │       └───punycode
    │   ├───util
    │   │   ├───node_modules
    │   │   │   └───inherits
    │   │   └───support
    │   ├───util-deprecate
    │   ├───utils-merge
    │   ├───uuid
    │   │   └───dist
    │   │       ├───bin
    │   │       ├───esm-browser
    │   │       ├───esm-node
    │   │       └───umd
    │   ├───vary
    │   ├───vm-browserify
    │   │   ├───.github
    │   │   ├───example
    │   │   │   └───run
    │   │   └───test
    │   ├───vue
    │   │   ├───compiler-sfc
    │   │   ├───dist
    │   │   ├───packages
    │   │   │   └───compiler-sfc
    │   │   │       ├───dist
    │   │   │       ├───node_modules
    │   │   │       │   └───.bin
    │   │   │       ├───src
    │   │   │       │   ├───stylePlugins
    │   │   │       │   └───templateCompilerModules
    │   │   │       └───test
    │   │   │           └───__snapshots__
    │   │   ├───src
    │   │   │   ├───compiler
    │   │   │   │   ├───codegen
    │   │   │   │   ├───directives
    │   │   │   │   └───parser
    │   │   │   ├───core
    │   │   │   │   ├───components
    │   │   │   │   ├───global-api
    │   │   │   │   ├───instance
    │   │   │   │   │   └───render-helpers
    │   │   │   │   ├───observer
    │   │   │   │   ├───util
    │   │   │   │   └───vdom
    │   │   │   │       ├───helpers
    │   │   │   │       └───modules
    │   │   │   ├───platforms
    │   │   │   │   └───web
    │   │   │   │       ├───compiler
    │   │   │   │       │   ├───directives
    │   │   │   │       │   └───modules
    │   │   │   │       ├───runtime
    │   │   │   │       │   ├───components
    │   │   │   │       │   ├───directives
    │   │   │   │       │   └───modules
    │   │   │   │       └───util
    │   │   │   ├───shared
    │   │   │   ├───types
    │   │   │   └───v3
    │   │   │       ├───reactivity
    │   │   │       └───sfc-helpers
    │   │   └───types
    │   ├───vue-hot-reload-api
    │   │   └───dist
    │   ├───vue-loader
    │   │   ├───lib
    │   │   │   ├───codegen
    │   │   │   ├───loaders
    │   │   │   └───runtime
    │   │   └───node_modules
    │   │       └───loader-utils
    │   │           ├───lib
    │   │           └───node_modules
    │   │               └───.bin
    │   ├───vue-style-loader
    │   │   ├───.circleci
    │   │   ├───.github
    │   │   ├───lib
    │   │   ├───node_modules
    │   │   │   └───loader-utils
    │   │   │       ├───lib
    │   │   │       └───node_modules
    │   │   │           └───.bin
    │   │   └───test
    │   ├───vue-template-compiler
    │   │   ├───node_modules
    │   │   │   └───.bin
    │   │   └───types
    │   ├───vue-template-es2015-compiler
    │   ├───watchpack
    │   │   └───lib
    │   ├───wbuf
    │   │   └───test
    │   ├───webpack
    │   │   ├───bin
    │   │   ├───hot
    │   │   ├───lib
    │   │   │   ├───asset
    │   │   │   ├───async-modules
    │   │   │   ├───cache
    │   │   │   ├───config
    │   │   │   ├───container
    │   │   │   ├───css
    │   │   │   ├───debug
    │   │   │   ├───dependencies
    │   │   │   ├───electron
    │   │   │   ├───errors
    │   │   │   ├───esm
    │   │   │   ├───hmr
    │   │   │   ├───ids
    │   │   │   ├───javascript
    │   │   │   ├───json
    │   │   │   ├───library
    │   │   │   ├───logging
    │   │   │   ├───node
    │   │   │   ├───optimize
    │   │   │   ├───performance
    │   │   │   ├───prefetch
    │   │   │   ├───rules
    │   │   │   ├───runtime
    │   │   │   ├───schemes
    │   │   │   ├───serialization
    │   │   │   ├───sharing
    │   │   │   ├───stats
    │   │   │   ├───util
    │   │   │   │   └───hash
    │   │   │   ├───wasm
    │   │   │   ├───wasm-async
    │   │   │   ├───wasm-sync
    │   │   │   ├───web
    │   │   │   └───webworker
    │   │   ├───node_modules
    │   │   │   ├───.bin
    │   │   │   └───webpack-sources
    │   │   │       └───lib
    │   │   │           └───helpers
    │   │   └───schemas
    │   │       └───plugins
    │   │           ├───asset
    │   │           ├───container
    │   │           ├───css
    │   │           ├───debug
    │   │           ├───ids
    │   │           ├───optimize
    │   │           ├───schemes
    │   │           └───sharing
    │   ├───webpack-cli
    │   │   ├───bin
    │   │   ├───lib
    │   │   │   ├───plugins
    │   │   │   └───utils
    │   │   └───node_modules
    │   │       ├───.bin
    │   │       └───commander
    │   │           └───typings
    │   ├───webpack-dev-middleware
    │   │   ├───dist
    │   │   │   └───utils
    │   │   ├───node_modules
    │   │   │   ├───.bin
    │   │   │   ├───ajv
    │   │   │   │   ├───dist
    │   │   │   │   │   ├───compile
    │   │   │   │   │   │   ├───codegen
    │   │   │   │   │   │   ├───jtd
    │   │   │   │   │   │   └───validate
    │   │   │   │   │   ├───refs
    │   │   │   │   │   │   ├───json-schema-2019-09
    │   │   │   │   │   │   │   └───meta
    │   │   │   │   │   │   └───json-schema-2020-12
    │   │   │   │   │   │       └───meta
    │   │   │   │   │   ├───runtime
    │   │   │   │   │   ├───standalone
    │   │   │   │   │   ├───types
    │   │   │   │   │   └───vocabularies
    │   │   │   │   │       ├───applicator
    │   │   │   │   │       ├───core
    │   │   │   │   │       ├───discriminator
    │   │   │   │   │       ├───dynamic
    │   │   │   │   │       ├───format
    │   │   │   │   │       ├───jtd
    │   │   │   │   │       ├───unevaluated
    │   │   │   │   │       └───validation
    │   │   │   │   └───lib
    │   │   │   │       ├───compile
    │   │   │   │       │   ├───codegen
    │   │   │   │       │   ├───jtd
    │   │   │   │       │   └───validate
    │   │   │   │       ├───refs
    │   │   │   │       │   ├───json-schema-2019-09
    │   │   │   │       │   │   └───meta
    │   │   │   │       │   └───json-schema-2020-12
    │   │   │   │       │       └───meta
    │   │   │   │       ├───runtime
    │   │   │   │       ├───standalone
    │   │   │   │       ├───types
    │   │   │   │       └───vocabularies
    │   │   │   │           ├───applicator
    │   │   │   │           ├───core
    │   │   │   │           ├───discriminator
    │   │   │   │           ├───dynamic
    │   │   │   │           ├───format
    │   │   │   │           ├───jtd
    │   │   │   │           ├───unevaluated
    │   │   │   │           └───validation
    │   │   │   ├───ajv-formats
    │   │   │   │   ├───dist
    │   │   │   │   └───src
    │   │   │   ├───ajv-keywords
    │   │   │   │   ├───dist
    │   │   │   │   │   ├───definitions
    │   │   │   │   │   └───keywords
    │   │   │   │   └───src
    │   │   │   │       ├───definitions
    │   │   │   │       └───keywords
    │   │   │   ├───json-schema-traverse
    │   │   │   │   ├───.github
    │   │   │   │   │   └───workflows
    │   │   │   │   └───spec
    │   │   │   │       └───fixtures
    │   │   │   └───schema-utils
    │   │   │       ├───declarations
    │   │   │       │   ├───keywords
    │   │   │       │   └───util
    │   │   │       └───dist
    │   │   │           ├───keywords
    │   │   │           └───util
    │   │   └───types
    │   │       └───utils
    │   ├───webpack-dev-server
    │   │   ├───bin
    │   │   ├───client
    │   │   │   ├───clients
    │   │   │   ├───modules
    │   │   │   │   ├───logger
    │   │   │   │   └───sockjs-client
    │   │   │   └───utils
    │   │   ├───lib
    │   │   │   └───servers
    │   │   ├───node_modules
    │   │   │   ├───.bin
    │   │   │   ├───ajv
    │   │   │   │   ├───dist
    │   │   │   │   │   ├───compile
    │   │   │   │   │   │   ├───codegen
    │   │   │   │   │   │   ├───jtd
    │   │   │   │   │   │   └───validate
    │   │   │   │   │   ├───refs
    │   │   │   │   │   │   ├───json-schema-2019-09
    │   │   │   │   │   │   │   └───meta
    │   │   │   │   │   │   └───json-schema-2020-12
    │   │   │   │   │   │       └───meta
    │   │   │   │   │   ├───runtime
    │   │   │   │   │   ├───standalone
    │   │   │   │   │   ├───types
    │   │   │   │   │   └───vocabularies
    │   │   │   │   │       ├───applicator
    │   │   │   │   │       ├───core
    │   │   │   │   │       ├───discriminator
    │   │   │   │   │       ├───dynamic
    │   │   │   │   │       ├───format
    │   │   │   │   │       ├───jtd
    │   │   │   │   │       ├───unevaluated
    │   │   │   │   │       └───validation
    │   │   │   │   └───lib
    │   │   │   │       ├───compile
    │   │   │   │       │   ├───codegen
    │   │   │   │       │   ├───jtd
    │   │   │   │       │   └───validate
    │   │   │   │       ├───refs
    │   │   │   │       │   ├───json-schema-2019-09
    │   │   │   │       │   │   └───meta
    │   │   │   │       │   └───json-schema-2020-12
    │   │   │   │       │       └───meta
    │   │   │   │       ├───runtime
    │   │   │   │       ├───standalone
    │   │   │   │       ├───types
    │   │   │   │       └───vocabularies
    │   │   │   │           ├───applicator
    │   │   │   │           ├───core
    │   │   │   │           ├───discriminator
    │   │   │   │           ├───dynamic
    │   │   │   │           ├───format
    │   │   │   │           ├───jtd
    │   │   │   │           ├───unevaluated
    │   │   │   │           └───validation
    │   │   │   ├───ajv-formats
    │   │   │   │   ├───dist
    │   │   │   │   └───src
    │   │   │   ├───ajv-keywords
    │   │   │   │   ├───dist
    │   │   │   │   │   ├───definitions
    │   │   │   │   │   └───keywords
    │   │   │   │   └───src
    │   │   │   │       ├───definitions
    │   │   │   │       └───keywords
    │   │   │   ├───json-schema-traverse
    │   │   │   │   ├───.github
    │   │   │   │   │   └───workflows
    │   │   │   │   └───spec
    │   │   │   │       └───fixtures
    │   │   │   └───schema-utils
    │   │   │       ├───declarations
    │   │   │       │   ├───keywords
    │   │   │       │   └───util
    │   │   │       └───dist
    │   │   │           ├───keywords
    │   │   │           └───util
    │   │   └───types
    │   │       ├───bin
    │   │       └───lib
    │   │           └───servers
    │   ├───webpack-merge
    │   │   └───dist
    │   ├───webpack-notifier
    │   ├───webpack-sources
    │   │   └───lib
    │   ├───webpackbar
    │   │   ├───dist
    │   │   └───node_modules
    │   │       ├───.bin
    │   │       ├───chalk
    │   │       │   └───source
    │   │       ├───has-flag
    │   │       └───supports-color
    │   ├───websocket-driver
    │   │   └───lib
    │   │       └───websocket
    │   │           └───driver
    │   │               └───hybi
    │   ├───websocket-extensions
    │   │   └───lib
    │   │       └───pipeline
    │   ├───which
    │   │   └───bin
    │   ├───wildcard
    │   │   ├───examples
    │   │   └───test
    │   ├───wrap-ansi
    │   ├───wrappy
    │   ├───ws
    │   │   └───lib
    │   ├───xtend
    │   ├───y18n
    │   │   └───build
    │   │       └───lib
    │   │           └───platform-shims
    │   ├───yallist
    │   ├───yaml
    │   │   ├───browser
    │   │   │   ├───dist
    │   │   │   └───types
    │   │   ├───dist
    │   │   └───types
    │   ├───yargs
    │   │   ├───build
    │   │   │   └───lib
    │   │   │       ├───typings
    │   │   │       └───utils
    │   │   ├───helpers
    │   │   ├───lib
    │   │   │   └───platform-shims
    │   │   └───locales
    │   └───yargs-parser
    │       └───build
    │           └───lib
    ├───public
    │   ├───css
    │   └───js
    ├───resources
    │   ├───css
    │   ├───js
    │   │   └───components
    │   ├───lang
    │   │   └───en
    │   ├───sass
    │   └───views
    │       ├───auth
    │       │   └───passwords
    │       └───layouts
    ├───routes
    ├───storage
    │   ├───app
    │   │   └───public
    │   ├───framework
    │   │   ├───cache
    │   │   │   └───data
    │   │   │       ├───3e
    │   │   │       │   └───c6
    │   │   │       ├───51
    │   │   │       │   └───00
    │   │   │       ├───76
    │   │   │       │   └───e7
    │   │   │       └───9c
    │   │   │           └───1c
    │   │   ├───sessions
    │   │   ├───testing
    │   │   └───views
    │   └───logs
    ├───tests
    │   ├───Feature
    │   └───Unit
    └───vendor
      ├───asm89
      │   └───stack-cors
      │       └───src
      ├───bin
      ├───brick
      │   └───math
      │       └───src
      │           ├───Exception
      │           └───Internal
      │               └───Calculator
      ├───composer
      ├───dflydev
      │   └───dot-access-data
      │       └───src
      │           └───Exception
      ├───doctrine
      │   ├───inflector
      │   │   ├───docs
      │   │   │   └───en
      │   │   └───lib
      │   │       └───Doctrine
      │   │           └───Inflector
      │   │               └───Rules
      │   │                   ├───English
      │   │                   ├───French
      │   │                   ├───NorwegianBokmal
      │   │                   ├───Portuguese
      │   │                   ├───Spanish
      │   │                   └───Turkish
      │   ├───instantiator
      │   │   ├───docs
      │   │   │   └───en
      │   │   └───src
      │   │       └───Doctrine
      │   │           └───Instantiator
      │   │               └───Exception
      │   └───lexer
      │       └───lib
      │           └───Doctrine
      │               └───Common
      │                   └───Lexer
      ├───dragonmantank
      │   └───cron-expression
      │       └───src
      │           └───Cron
      ├───egulias
      │   └───email-validator
      │       └───src
      │           ├───Exception
      │           ├───Parser
      │           ├───Validation
      │           │   ├───Error
      │           │   └───Exception
      │           └───Warning
      ├───facade
      │   ├───flare-client-php
      │   │   └───src
      │   │       ├───Concerns
      │   │       ├───Context
      │   │       ├───Contracts
      │   │       ├───Enums
      │   │       ├───Glows
      │   │       ├───Http
      │   │       │   └───Exceptions
      │   │       ├───Middleware
      │   │       ├───Solutions
      │   │       ├───Stacktrace
      │   │       ├───Time
      │   │       └───Truncation
      │   ├───ignition
      │   │   ├───config
      │   │   ├───resources
      │   │   │   ├───compiled
      │   │   │   └───views
      │   │   └───src
      │   │       ├───Actions
      │   │       ├───Commands
      │   │       │   └───stubs
      │   │       ├───Context
      │   │       ├───DumpRecorder
      │   │       ├───ErrorPage
      │   │       ├───Exceptions
      │   │       ├───Facades
      │   │       ├───Http
      │   │       │   ├───Controllers
      │   │       │   ├───Middleware
      │   │       │   └───Requests
      │   │       ├───JobRecorder
      │   │       ├───Logger
      │   │       ├───LogRecorder
      │   │       ├───Middleware
      │   │       ├───QueryRecorder
      │   │       ├───SolutionProviders
      │   │       ├───Solutions
      │   │       ├───Support
      │   │       │   └───Packagist
      │   │       ├───Tabs
      │   │       └───Views
      │   │           ├───Compilers
      │   │           ├───Concerns
      │   │           └───Engines
      │   └───ignition-contracts
      │       ├───.github
      │       │   └───workflows
      │       └───src
      ├───fakerphp
      │   └───faker
      │       └───src
      │           └───Faker
      │               ├───Calculator
      │               ├───Container
      │               ├───Core
      │               ├───Extension
      │               ├───Guesser
      │               ├───ORM
      │               │   ├───CakePHP
      │               │   ├───Doctrine
      │               │   ├───Mandango
      │               │   ├───Propel
      │               │   ├───Propel2
      │               │   └───Spot
      │               └───Provider
      │                   ├───ar_EG
      │                   ├───ar_JO
      │                   ├───ar_SA
      │                   ├───at_AT
      │                   ├───bg_BG
      │                   ├───bn_BD
      │                   ├───cs_CZ
      │                   ├───da_DK
      │                   ├───de_AT
      │                   ├───de_CH
      │                   ├───de_DE
      │                   ├───el_CY
      │                   ├───el_GR
      │                   ├───en_AU
      │                   ├───en_CA
      │                   ├───en_GB
      │                   ├───en_HK
      │                   ├───en_IN
      │                   ├───en_NG
      │                   ├───en_NZ
      │                   ├───en_PH
      │                   ├───en_SG
      │                   ├───en_UG
      │                   ├───en_US
      │                   ├───en_ZA
      │                   ├───es_AR
      │                   ├───es_ES
      │                   ├───es_PE
      │                   ├───es_VE
      │                   ├───et_EE
      │                   ├───fa_IR
      │                   ├───fi_FI
      │                   ├───fr_BE
      │                   ├───fr_CA
      │                   ├───fr_CH
      │                   ├───fr_FR
      │                   ├───he_IL
      │                   ├───hr_HR
      │                   ├───hu_HU
      │                   ├───hy_AM
      │                   ├───id_ID
      │                   ├───is_IS
      │                   ├───it_CH
      │                   ├───it_IT
      │                   ├───ja_JP
      │                   ├───ka_GE
      │                   ├───kk_KZ
      │                   ├───ko_KR
      │                   ├───lt_LT
      │                   ├───lv_LV
      │                   ├───me_ME
      │                   ├───mn_MN
      │                   ├───ms_MY
      │                   ├───nb_NO
      │                   ├───ne_NP
      │                   ├───nl_BE
      │                   ├───nl_NL
      │                   ├───pl_PL
      │                   ├───pt_BR
      │                   ├───pt_PT
      │                   ├───ro_MD
      │                   ├───ro_RO
      │                   ├───ru_RU
      │                   ├───sk_SK
      │                   ├───sl_SI
      │                   ├───sr_Cyrl_RS
      │                   ├───sr_Latn_RS
      │                   ├───sr_RS
      │                   ├───sv_SE
      │                   ├───th_TH
      │                   ├───tr_TR
      │                   ├───uk_UA
      │                   ├───vi_VN
      │                   ├───zh_CN
      │                   └───zh_TW
      ├───filp
      │   └───whoops
      │       ├───.github
      │       │   └───workflows
      │       └───src
      │           └───Whoops
      │               ├───Exception
      │               ├───Handler
      │               ├───Resources
      │               │   ├───css
      │               │   ├───js
      │               │   └───views
      │               └───Util
      ├───fruitcake
      │   └───laravel-cors
      │       ├───config
      │       └───src
      ├───graham-campbell
      │   └───result-type
      │       └───src
      ├───guzzlehttp
      │   ├───guzzle
      │   │   └───src
      │   │       ├───Cookie
      │   │       ├───Exception
      │   │       └───Handler
      │   ├───promises
      │   │   └───src
      │   └───psr7
      │       └───src
      │           └───Exception
      ├───hamcrest
      │   └───hamcrest-php
      │       ├───.github
      │       │   └───workflows
      │       ├───generator
      │       │   └───parts
      │       ├───hamcrest
      │       │   └───Hamcrest
      │       │       ├───Arrays
      │       │       ├───Collection
      │       │       ├───Core
      │       │       ├───Internal
      │       │       ├───Number
      │       │       ├───Text
      │       │       ├───Type
      │       │       └───Xml
      │       └───tests
      │           └───Hamcrest
      │               ├───Array
      │               ├───Collection
      │               ├───Core
      │               ├───Number
      │               ├───Text
      │               ├───Type
      │               └───Xml
      ├───laravel
      │   ├───framework
      │   │   └───src
      │   │       └───Illuminate
      │   │           ├───Auth
      │   │           │   ├───Access
      │   │           │   │   └───Events
      │   │           │   ├───Console
      │   │           │   │   └───stubs
      │   │           │   │       └───make
      │   │           │   │           └───views
      │   │           │   │               └───layouts
      │   │           │   ├───Events
      │   │           │   ├───Listeners
      │   │           │   ├───Middleware
      │   │           │   ├───Notifications
      │   │           │   └───Passwords
      │   │           ├───Broadcasting
      │   │           │   └───Broadcasters
      │   │           ├───Bus
      │   │           │   └───Events
      │   │           ├───Cache
      │   │           │   ├───Console
      │   │           │   │   └───stubs
      │   │           │   ├───Events
      │   │           │   └───RateLimiting
      │   │           ├───Collections
      │   │           │   └───Traits
      │   │           ├───Config
      │   │           ├───Console
      │   │           │   ├───Concerns
      │   │           │   ├───Events
      │   │           │   └───Scheduling
      │   │           ├───Container
      │   │           ├───Contracts
      │   │           │   ├───Auth
      │   │           │   │   ├───Access
      │   │           │   │   └───Middleware
      │   │           │   ├───Broadcasting
      │   │           │   ├───Bus
      │   │           │   ├───Cache
      │   │           │   ├───Config
      │   │           │   ├───Console
      │   │           │   ├───Container
      │   │           │   ├───Cookie
      │   │           │   ├───Database
      │   │           │   │   ├───Eloquent
      │   │           │   │   └───Events
      │   │           │   ├───Debug
      │   │           │   ├───Encryption
      │   │           │   ├───Events
      │   │           │   ├───Filesystem
      │   │           │   ├───Foundation
      │   │           │   ├───Hashing
      │   │           │   ├───Http
      │   │           │   ├───Mail
      │   │           │   ├───Notifications
      │   │           │   ├───Pagination
      │   │           │   ├───Pipeline
      │   │           │   ├───Queue
      │   │           │   ├───Redis
      │   │           │   ├───Routing
      │   │           │   ├───Session
      │   │           │   ├───Support
      │   │           │   ├───Translation
      │   │           │   ├───Validation
      │   │           │   └───View
      │   │           ├───Cookie
      │   │           │   └───Middleware
      │   │           ├───Database
      │   │           │   ├───Capsule
      │   │           │   ├───Concerns
      │   │           │   ├───Connectors
      │   │           │   ├───Console
      │   │           │   │   ├───Factories
      │   │           │   │   │   └───stubs
      │   │           │   │   ├───Migrations
      │   │           │   │   └───Seeds
      │   │           │   │       └───stubs
      │   │           │   ├───DBAL
      │   │           │   ├───Eloquent
      │   │           │   │   ├───Casts
      │   │           │   │   ├───Concerns
      │   │           │   │   ├───Factories
      │   │           │   │   └───Relations
      │   │           │   │       └───Concerns
      │   │           │   ├───Events
      │   │           │   ├───Migrations
      │   │           │   │   └───stubs
      │   │           │   ├───PDO
      │   │           │   │   └───Concerns
      │   │           │   ├───Query
      │   │           │   │   ├───Grammars
      │   │           │   │   └───Processors
      │   │           │   └───Schema
      │   │           │       └───Grammars
      │   │           ├───Encryption
      │   │           ├───Events
      │   │           ├───Filesystem
      │   │           ├───Foundation
      │   │           │   ├───Auth
      │   │           │   │   └───Access
      │   │           │   ├───Bootstrap
      │   │           │   ├───Bus
      │   │           │   ├───Console
      │   │           │   │   └───stubs
      │   │           │   ├───Events
      │   │           │   ├───Exceptions
      │   │           │   │   └───views
      │   │           │   ├───Http
      │   │           │   │   ├───Events
      │   │           │   │   ├───Exceptions
      │   │           │   │   └───Middleware
      │   │           │   ├───Providers
      │   │           │   ├───stubs
      │   │           │   ├───Support
      │   │           │   │   └───Providers
      │   │           │   ├───Testing
      │   │           │   │   ├───Concerns
      │   │           │   │   └───Traits
      │   │           │   └───Validation
      │   │           ├───Hashing
      │   │           ├───Http
      │   │           │   ├───Client
      │   │           │   │   └───Events
      │   │           │   ├───Concerns
      │   │           │   ├───Exceptions
      │   │           │   ├───Middleware
      │   │           │   ├───Resources
      │   │           │   │   └───Json
      │   │           │   └───Testing
      │   │           ├───Log
      │   │           │   └───Events
      │   │           ├───Macroable
      │   │           │   └───Traits
      │   │           ├───Mail
      │   │           │   ├───Events
      │   │           │   ├───resources
      │   │           │   │   └───views
      │   │           │   │       ├───html
      │   │           │   │       │   └───themes
      │   │           │   │       └───text
      │   │           │   └───Transport
      │   │           ├───Notifications
      │   │           │   ├───Channels
      │   │           │   ├───Console
      │   │           │   │   └───stubs
      │   │           │   ├───Events
      │   │           │   ├───Messages
      │   │           │   └───resources
      │   │           │       └───views
      │   │           ├───Pagination
      │   │           │   └───resources
      │   │           │       └───views
      │   │           ├───Pipeline
      │   │           ├───Queue
      │   │           │   ├───Capsule
      │   │           │   ├───Connectors
      │   │           │   ├───Console
      │   │           │   │   └───stubs
      │   │           │   ├───Events
      │   │           │   ├───Failed
      │   │           │   ├───Jobs
      │   │           │   └───Middleware
      │   │           ├───Redis
      │   │           │   ├───Connections
      │   │           │   ├───Connectors
      │   │           │   ├───Events
      │   │           │   └───Limiters
      │   │           ├───Routing
      │   │           │   ├───Console
      │   │           │   │   └───stubs
      │   │           │   ├───Contracts
      │   │           │   ├───Events
      │   │           │   ├───Exceptions
      │   │           │   ├───Matching
      │   │           │   └───Middleware
      │   │           ├───Session
      │   │           │   ├───Console
      │   │           │   │   └───stubs
      │   │           │   └───Middleware
      │   │           ├───Support
      │   │           │   ├───Facades
      │   │           │   ├───Testing
      │   │           │   │   └───Fakes
      │   │           │   └───Traits
      │   │           ├───Testing
      │   │           │   ├───Concerns
      │   │           │   ├───Constraints
      │   │           │   └───Fluent
      │   │           │       └───Concerns
      │   │           ├───Translation
      │   │           ├───Validation
      │   │           │   ├───Concerns
      │   │           │   └───Rules
      │   │           └───View
      │   │               ├───Compilers
      │   │               │   └───Concerns
      │   │               ├───Concerns
      │   │               ├───Engines
      │   │               └───Middleware
      │   ├───sail
      │   │   ├───bin
      │   │   ├───database
      │   │   │   ├───mysql
      │   │   │   └───pgsql
      │   │   ├───runtimes
      │   │   │   ├───7.4
      │   │   │   ├───8.0
      │   │   │   └───8.1
      │   │   ├───src
      │   │   │   └───Console
      │   │   └───stubs
      │   ├───sanctum
      │   │   ├───config
      │   │   ├───database
      │   │   │   └───migrations
      │   │   └───src
      │   │       ├───Console
      │   │       │   └───Commands
      │   │       ├───Contracts
      │   │       ├───Events
      │   │       ├───Exceptions
      │   │       └───Http
      │   │           ├───Controllers
      │   │           └───Middleware
      │   ├───serializable-closure
      │   │   └───src
      │   │       ├───Contracts
      │   │       ├───Exceptions
      │   │       ├───Serializers
      │   │       ├───Signers
      │   │       └───Support
      │   ├───tinker
      │   │   ├───config
      │   │   └───src
      │   │       └───Console
      │   └───ui
      │       ├───auth-backend
      │       ├───src
      │       │   ├───Auth
      │       │   │   ├───bootstrap-stubs
      │       │   │   │   ├───auth
      │       │   │   │   │   └───passwords
      │       │   │   │   └───layouts
      │       │   │   └───stubs
      │       │   │       └───controllers
      │       │   └───Presets
      │       │       ├───bootstrap-stubs
      │       │       ├───react-stubs
      │       │       └───vue-stubs
      │       ├───stubs
      │       │   ├───Auth
      │       │   └───migrations
      │       └───tests
      │           └───AuthBackend
      ├───league
      │   ├───commonmark
      │   │   └───src
      │   │       ├───Delimiter
      │   │       │   └───Processor
      │   │       ├───Environment
      │   │       ├───Event
      │   │       ├───Exception
      │   │       ├───Extension
      │   │       │   ├───Attributes
      │   │       │   │   ├───Event
      │   │       │   │   ├───Node
      │   │       │   │   ├───Parser
      │   │       │   │   └───Util
      │   │       │   ├───Autolink
      │   │       │   ├───CommonMark
      │   │       │   │   ├───Delimiter
      │   │       │   │   │   └───Processor
      │   │       │   │   ├───Node
      │   │       │   │   │   ├───Block
      │   │       │   │   │   └───Inline
      │   │       │   │   ├───Parser
      │   │       │   │   │   ├───Block
      │   │       │   │   │   └───Inline
      │   │       │   │   └───Renderer
      │   │       │   │       ├───Block
      │   │       │   │       └───Inline
      │   │       │   ├───DefaultAttributes
      │   │       │   ├───DescriptionList
      │   │       │   │   ├───Event
      │   │       │   │   ├───Node
      │   │       │   │   ├───Parser
      │   │       │   │   └───Renderer
      │   │       │   ├───DisallowedRawHtml
      │   │       │   ├───Embed
      │   │       │   │   └───Bridge
      │   │       │   ├───ExternalLink
      │   │       │   ├───Footnote
      │   │       │   │   ├───Event
      │   │       │   │   ├───Node
      │   │       │   │   ├───Parser
      │   │       │   │   └───Renderer
      │   │       │   ├───FrontMatter
      │   │       │   │   ├───Data
      │   │       │   │   ├───Exception
      │   │       │   │   ├───Input
      │   │       │   │   ├───Listener
      │   │       │   │   └───Output
      │   │       │   ├───HeadingPermalink
      │   │       │   ├───InlinesOnly
      │   │       │   ├───Mention
      │   │       │   │   └───Generator
      │   │       │   ├───SmartPunct
      │   │       │   ├───Strikethrough
      │   │       │   ├───Table
      │   │       │   ├───TableOfContents
      │   │       │   │   ├───Node
      │   │       │   │   └───Normalizer
      │   │       │   └───TaskList
      │   │       ├───Input
      │   │       ├───Node
      │   │       │   ├───Block
      │   │       │   ├───Inline
      │   │       │   └───Query
      │   │       ├───Normalizer
      │   │       ├───Output
      │   │       ├───Parser
      │   │       │   ├───Block
      │   │       │   └───Inline
      │   │       ├───Reference
      │   │       ├───Renderer
      │   │       │   ├───Block
      │   │       │   └───Inline
      │   │       ├───Util
      │   │       └───Xml
      │   ├───config
      │   │   └───src
      │   │       └───Exception
      │   ├───flysystem
      │   │   └───src
      │   │       ├───Adapter
      │   │       │   └───Polyfill
      │   │       ├───Plugin
      │   │       └───Util
      │   └───mime-type-detection
      │       └───src
      ├───mockery
      │   └───mockery
      │       ├───docs
      │       │   ├───cookbook
      │       │   ├───getting_started
      │       │   ├───mockery
      │       │   └───reference
      │       └───library
      │           └───Mockery
      │               ├───Adapter
      │               │   └───Phpunit
      │               ├───CountValidator
      │               ├───Exception
      │               ├───Generator
      │               │   └───StringManipulation
      │               │       └───Pass
      │               ├───Loader
      │               └───Matcher
      ├───monolog
      │   └───monolog
      │       └───src
      │           └───Monolog
      │               ├───Attribute
      │               ├───Formatter
      │               ├───Handler
      │               │   ├───Curl
      │               │   ├───FingersCrossed
      │               │   ├───Slack
      │               │   └───SyslogUdp
      │               ├───Processor
      │               └───Test
      ├───myclabs
      │   └───deep-copy
      │       ├───.github
      │       │   └───workflows
      │       └───src
      │           └───DeepCopy
      │               ├───Exception
      │               ├───Filter
      │               │   └───Doctrine
      │               ├───Matcher
      │               │   └───Doctrine
      │               ├───Reflection
      │               ├───TypeFilter
      │               │   ├───Date
      │               │   └───Spl
      │               └───TypeMatcher
      ├───nesbot
      │   └───carbon
      │       ├───bin
      │       ├───lazy
      │       │   └───Carbon
      │       │       └───PHPStan
      │       └───src
      │           └───Carbon
      │               ├───Cli
      │               ├───Doctrine
      │               ├───Exceptions
      │               ├───Lang
      │               ├───Laravel
      │               ├───List
      │               ├───PHPStan
      │               └───Traits
      ├───nette
      │   ├───schema
      │   │   └───src
      │   │       └───Schema
      │   │           └───Elements
      │   └───utils
      │       └───src
      │           ├───Iterators
      │           └───Utils
      ├───nikic
      │   └───php-parser
      │       ├───bin
      │       ├───grammar
      │       └───lib
      │           └───PhpParser
      │               ├───Builder
      │               ├───Comment
      │               ├───ErrorHandler
      │               ├───Internal
      │               ├───Lexer
      │               │   └───TokenEmulator
      │               ├───Node
      │               │   ├───Expr
      │               │   │   ├───AssignOp
      │               │   │   ├───BinaryOp
      │               │   │   └───Cast
      │               │   ├───Name
      │               │   ├───Scalar
      │               │   │   └───MagicConst
      │               │   └───Stmt
      │               │       └───TraitUseAdaptation
      │               ├───NodeVisitor
      │               ├───Parser
      │               └───PrettyPrinter
      ├───nunomaduro
      │   └───collision
      │       └───src
      │           ├───Adapters
      │           │   ├───Laravel
      │           │   │   ├───Commands
      │           │   │   └───Exceptions
      │           │   └───Phpunit
      │           ├───Contracts
      │           │   └───Adapters
      │           │       └───Phpunit
      │           ├───Exceptions
      │           └───SolutionsRepositories
      ├───opis
      │   └───closure
      │       └───src
      ├───phar-io
      │   ├───manifest
      │   │   └───src
      │   │       ├───exceptions
      │   │       ├───values
      │   │       └───xml
      │   └───version
      │       └───src
      │           ├───constraints
      │           └───exceptions
      ├───phpdocumentor
      │   ├───reflection-common
      │   │   ├───.github
      │   │   │   └───workflows
      │   │   └───src
      │   ├───reflection-docblock
      │   │   └───src
      │   │       ├───DocBlock
      │   │       │   └───Tags
      │   │       │       ├───Factory
      │   │       │       ├───Formatter
      │   │       │       └───Reference
      │   │       └───Exception
      │   └───type-resolver
      │       └───src
      │           ├───PseudoTypes
      │           └───Types
      ├───phpoption
      │   └───phpoption
      │       └───src
      │           └───PhpOption
      ├───phpspec
      │   └───prophecy
      │       └───src
      │           └───Prophecy
      │               ├───Argument
      │               │   └───Token
      │               ├───Call
      │               ├───Comparator
      │               ├───Doubler
      │               │   ├───ClassPatch
      │               │   └───Generator
      │               │       └───Node
      │               ├───Exception
      │               │   ├───Call
      │               │   ├───Doubler
      │               │   ├───Prediction
      │               │   └───Prophecy
      │               ├───PhpDocumentor
      │               ├───Prediction
      │               ├───Promise
      │               ├───Prophecy
      │               └───Util
      ├───phpunit
      │   ├───php-code-coverage
      │   │   └───src
      │   │       ├───Driver
      │   │       ├───Exception
      │   │       ├───Node
      │   │       ├───Report
      │   │       │   ├───Html
      │   │       │   │   └───Renderer
      │   │       │   │       └───Template
      │   │       │   │           ├───css
      │   │       │   │           ├───icons
      │   │       │   │           └───js
      │   │       │   └───Xml
      │   │       ├───StaticAnalysis
      │   │       └───Util
      │   ├───php-file-iterator
      │   │   ├───.psalm
      │   │   └───src
      │   ├───php-invoker
      │   │   └───src
      │   │       └───exceptions
      │   ├───php-text-template
      │   │   ├───.psalm
      │   │   └───src
      │   │       └───exceptions
      │   ├───php-timer
      │   │   ├───.psalm
      │   │   └───src
      │   │       └───exceptions
      │   └───phpunit
      │       ├───schema
      │       └───src
      │           ├───Framework
      │           │   ├───Assert
      │           │   ├───Constraint
      │           │   │   ├───Boolean
      │           │   │   ├───Cardinality
      │           │   │   ├───Equality
      │           │   │   ├───Exception
      │           │   │   ├───Filesystem
      │           │   │   ├───Math
      │           │   │   ├───Object
      │           │   │   ├───Operator
      │           │   │   ├───String
      │           │   │   ├───Traversable
      │           │   │   └───Type
      │           │   ├───Error
      │           │   ├───Exception
      │           │   └───MockObject
      │           │       ├───Api
      │           │       ├───Builder
      │           │       ├───Exception
      │           │       ├───Generator
      │           │       ├───Rule
      │           │       └───Stub
      │           ├───Runner
      │           │   ├───Extension
      │           │   ├───Filter
      │           │   └───Hook
      │           ├───TextUI
      │           │   ├───CliArguments
      │           │   ├───Exception
      │           │   └───XmlConfiguration
      │           │       ├───CodeCoverage
      │           │       │   ├───Filter
      │           │       │   └───Report
      │           │       ├───Filesystem
      │           │       ├───Group
      │           │       ├───Logging
      │           │       │   └───TestDox
      │           │       ├───Migration
      │           │       │   └───Migrations
      │           │       ├───PHP
      │           │       ├───PHPUnit
      │           │       └───TestSuite
      │           └───Util
      │               ├───Annotation
      │               ├───Log
      │               ├───PHP
      │               │   └───Template
      │               ├───TestDox
      │               └───Xml
      ├───psr
      │   ├───container
      │   │   └───src
      │   ├───event-dispatcher
      │   │   └───src
      │   ├───http-client
      │   │   └───src
      │   ├───http-factory
      │   │   └───src
      │   ├───http-message
      │   │   └───src
      │   ├───log
      │   │   └───Psr
      │   │       └───Log
      │   │           └───Test
      │   └───simple-cache
      │       └───src
      ├───psy
      │   └───psysh
      │       ├───bin
      │       └───src
      │           ├───CodeCleaner
      │           ├───Command
      │           │   ├───ListCommand
      │           │   └───TimeitCommand
      │           ├───Exception
      │           ├───ExecutionLoop
      │           ├───Formatter
      │           ├───Input
      │           ├───Output
      │           ├───Readline
      │           │   └───Hoa
      │           │       └───Terminfo
      │           │           ├───77
      │           │           └───78
      │           ├───Reflection
      │           ├───Sudo
      │           ├───TabCompletion
      │           │   └───Matcher
      │           ├───Util
      │           ├───VarDumper
      │           └───VersionUpdater
      ├───ralouphie
      │   └───getallheaders
      │       └───src
      ├───ramsey
      │   ├───collection
      │   │   ├───bin
      │   │   └───src
      │   │       ├───Exception
      │   │       ├───Map
      │   │       └───Tool
      │   └───uuid
      │       └───src
      │           ├───Builder
      │           ├───Codec
      │           ├───Converter
      │           │   ├───Number
      │           │   └───Time
      │           ├───Exception
      │           ├───Fields
      │           ├───Generator
      │           ├───Guid
      │           ├───Lazy
      │           ├───Math
      │           ├───Nonstandard
      │           ├───Provider
      │           │   ├───Dce
      │           │   ├───Node
      │           │   └───Time
      │           ├───Rfc4122
      │           ├───Type
      │           └───Validator
      ├───sebastian
      │   ├───cli-parser
      │   │   └───src
      │   │       └───exceptions
      │   ├───code-unit
      │   │   ├───.psalm
      │   │   └───src
      │   │       └───exceptions
      │   ├───code-unit-reverse-lookup
      │   │   └───src
      │   ├───comparator
      │   │   └───src
      │   │       └───exceptions
      │   ├───complexity
      │   │   ├───.psalm
      │   │   └───src
      │   │       ├───Complexity
      │   │       ├───Exception
      │   │       └───Visitor
      │   ├───diff
      │   │   └───src
      │   │       ├───Exception
      │   │       └───Output
      │   ├───environment
      │   │   └───src
      │   ├───exporter
      │   │   └───src
      │   ├───global-state
      │   │   └───src
      │   │       └───exceptions
      │   ├───lines-of-code
      │   │   ├───.psalm
      │   │   └───src
      │   │       └───Exception
      │   ├───object-enumerator
      │   │   ├───.psalm
      │   │   └───src
      │   ├───object-reflector
      │   │   ├───.psalm
      │   │   └───src
      │   ├───recursion-context
      │   │   ├───.psalm
      │   │   └───src
      │   ├───resource-operations
      │   │   ├───build
      │   │   └───src
      │   ├───type
      │   │   └───src
      │   │       ├───exception
      │   │       └───type
      │   └───version
      │       └───src
      ├───swiftmailer
      │   └───swiftmailer
      │       ├───.github
      │       │   └───workflows
      │       ├───doc
      │       └───lib
      │           ├───classes
      │           │   └───Swift
      │           │       ├───AddressEncoder
      │           │       ├───ByteStream
      │           │       ├───CharacterReader
      │           │       ├───CharacterReaderFactory
      │           │       ├───CharacterStream
      │           │       ├───Encoder
      │           │       ├───Events
      │           │       ├───KeyCache
      │           │       ├───Mailer
      │           │       ├───Mime
      │           │       │   ├───ContentEncoder
      │           │       │   ├───HeaderEncoder
      │           │       │   └───Headers
      │           │       ├───Plugins
      │           │       │   ├───Decorator
      │           │       │   ├───Loggers
      │           │       │   ├───Pop
      │           │       │   └───Reporters
      │           │       ├───Signers
      │           │       ├───StreamFilters
      │           │       └───Transport
      │           │           └───Esmtp
      │           │               └───Auth
      │           └───dependency_maps
      ├───symfony
      │   ├───console
      │   │   ├───Attribute
      │   │   ├───CI
      │   │   ├───Command
      │   │   ├───CommandLoader
      │   │   ├───Completion
      │   │   │   └───Output
      │   │   ├───DependencyInjection
      │   │   ├───Descriptor
      │   │   ├───Event
      │   │   ├───EventListener
      │   │   ├───Exception
      │   │   ├───Formatter
      │   │   ├───Helper
      │   │   ├───Input
      │   │   ├───Logger
      │   │   ├───Output
      │   │   ├───Question
      │   │   ├───Resources
      │   │   │   └───bin
      │   │   ├───SignalRegistry
      │   │   ├───Style
      │   │   └───Tester
      │   │       └───Constraint
      │   ├───css-selector
      │   │   ├───Exception
      │   │   ├───Node
      │   │   ├───Parser
      │   │   │   ├───Handler
      │   │   │   ├───Shortcut
      │   │   │   └───Tokenizer
      │   │   └───XPath
      │   │       └───Extension
      │   ├───deprecation-contracts
      │   ├───error-handler
      │   │   ├───Error
      │   │   ├───ErrorEnhancer
      │   │   ├───ErrorRenderer
      │   │   ├───Exception
      │   │   ├───Internal
      │   │   └───Resources
      │   │       ├───assets
      │   │       │   ├───css
      │   │       │   ├───images
      │   │       │   └───js
      │   │       ├───bin
      │   │       └───views
      │   ├───event-dispatcher
      │   │   ├───Attribute
      │   │   ├───Debug
      │   │   └───DependencyInjection
      │   ├───event-dispatcher-contracts
      │   ├───finder
      │   │   ├───Comparator
      │   │   ├───Exception
      │   │   └───Iterator
      │   ├───http-foundation
      │   │   ├───Exception
      │   │   ├───File
      │   │   │   └───Exception
      │   │   ├───RateLimiter
      │   │   ├───Session
      │   │   │   ├───Attribute
      │   │   │   ├───Flash
      │   │   │   └───Storage
      │   │   │       ├───Handler
      │   │   │       └───Proxy
      │   │   └───Test
      │   │       └───Constraint
      │   ├───http-kernel
      │   │   ├───Attribute
      │   │   ├───Bundle
      │   │   ├───CacheClearer
      │   │   ├───CacheWarmer
      │   │   ├───Config
      │   │   ├───Controller
      │   │   │   └───ArgumentResolver
      │   │   ├───ControllerMetadata
      │   │   ├───DataCollector
      │   │   ├───Debug
      │   │   ├───DependencyInjection
      │   │   ├───Event
      │   │   ├───EventListener
      │   │   ├───Exception
      │   │   ├───Fragment
      │   │   ├───HttpCache
      │   │   ├───Log
      │   │   ├───Profiler
      │   │   └───Resources
      │   ├───mime
      │   │   ├───Crypto
      │   │   ├───DependencyInjection
      │   │   ├───Encoder
      │   │   ├───Exception
      │   │   ├───Header
      │   │   ├───Part
      │   │   │   └───Multipart
      │   │   ├───Resources
      │   │   │   └───bin
      │   │   └───Test
      │   │       └───Constraint
      │   ├───polyfill-ctype
      │   ├───polyfill-iconv
      │   │   └───Resources
      │   │       └───charset
      │   ├───polyfill-intl-grapheme
      │   ├───polyfill-intl-idn
      │   │   └───Resources
      │   │       └───unidata
      │   ├───polyfill-intl-normalizer
      │   │   └───Resources
      │   │       ├───stubs
      │   │       └───unidata
      │   ├───polyfill-mbstring
      │   │   └───Resources
      │   │       └───unidata
      │   ├───polyfill-php72
      │   ├───polyfill-php73
      │   │   └───Resources
      │   │       └───stubs
      │   ├───polyfill-php80
      │   │   └───Resources
      │   │       └───stubs
      │   ├───polyfill-php81
      │   │   └───Resources
      │   │       └───stubs
      │   ├───process
      │   │   ├───Exception
      │   │   └───Pipes
      │   ├───routing
      │   │   ├───Annotation
      │   │   ├───DependencyInjection
      │   │   ├───Exception
      │   │   ├───Generator
      │   │   │   └───Dumper
      │   │   ├───Loader
      │   │   │   ├───Configurator
      │   │   │   │   └───Traits
      │   │   │   └───schema
      │   │   │       └───routing
      │   │   └───Matcher
      │   │       └───Dumper
      │   ├───service-contracts
      │   │   ├───Attribute
      │   │   └───Test
      │   ├───string
      │   │   ├───Exception
      │   │   ├───Inflector
      │   │   ├───Resources
      │   │   │   ├───bin
      │   │   │   └───data
      │   │   └───Slugger
      │   ├───translation
      │   │   ├───Catalogue
      │   │   ├───Command
      │   │   ├───DataCollector
      │   │   ├───DependencyInjection
      │   │   ├───Dumper
      │   │   ├───Exception
      │   │   ├───Extractor
      │   │   ├───Formatter
      │   │   ├───Loader
      │   │   ├───Provider
      │   │   ├───Reader
      │   │   ├───Resources
      │   │   │   ├───bin
      │   │   │   ├───data
      │   │   │   └───schemas
      │   │   ├───Test
      │   │   ├───Util
      │   │   └───Writer
      │   ├───translation-contracts
      │   │   └───Test
      │   └───var-dumper
      │       ├───Caster
      │       ├───Cloner
      │       ├───Command
      │       │   └───Descriptor
      │       ├───Dumper
      │       │   └───ContextProvider
      │       ├───Exception
      │       ├───Resources
      │       │   ├───bin
      │       │   ├───css
      │       │   ├───functions
      │       │   └───js
      │       ├───Server
      │       └───Test
      ├───theseer
      │   └───tokenizer
      │       └───src
      ├───tijsverkoyen
      │   └───css-to-inline-styles
      │       ├───.github
      │       │   └───workflows
      │       └───src
      │           └───Css
      │               ├───Property
      │               └───Rule
      ├───vlucas
      │   └───phpdotenv
      │       └───src
      │           ├───Exception
      │           ├───Loader
      │           ├───Parser
      │           ├───Repository
      │           │   └───Adapter
      │           ├───Store
      │           │   └───File
      │           └───Util
      ├───voku
      │   └───portable-ascii
      │       ├───build
      │       │   └───docs
      │       └───src
      │           └───voku
      │               └───helper
      │                   └───data
      └───webmozart
          └───assert
              └───src
    ```

## Getting Started

Download or clone the repo and open in VS Code.

### Prerequisites

Install php or xampp

-   Install xampp
    ```sh
    https://www.apachefriends.org/
    ```

### Installation

_Copy the repo & import the database file in phpmyadmin. No need to create database. Just import it. It will make database and table automatically. Then run the project._

1. Clone repo
    ```sh
    git clone https://github.com/Coding-Err0r/url-shortner.git
    ```
2. Install Node modules
    ```sh
    php artisan serve
    ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage

Read the official Next JS docs for more information.

_For more examples, please refer to the [Documentation](https://laravel.com/)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Your Name - [@ErrorrCoding](https://twitter.com/ErrorrCoding) - rhine.cse@gmail.com

Project Link: [Porject Link](https://github.com/Coding-Err0r/url-shortner.git)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

-   [Choose an Open Source License](https://choosealicense.com)
-   [GitHub badges](https://github.com/Ileriayo/markdown-badges)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[next-url]: https://nextjs.org/
[react.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[react-url]: https://reactjs.org/
[vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[vue-url]: https://vuejs.org/
[angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[angular-url]: https://angular.io/
[svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[svelte-url]: https://svelte.dev/
[laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[laravel-url]: https://laravel.com
[bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[bootstrap-url]: https://getbootstrap.com
[jquery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[jquery-url]: https://jquery.com

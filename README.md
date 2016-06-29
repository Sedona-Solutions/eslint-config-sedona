eslint-config-sedona
====================

Set of eslint rules by Sedona.

This project gather all the different eslint rules we may use in our different javascript projects (node.js, angularjs, etc...).

how to use it
-------------

Install eslint and eslint-config-sedona as a development dependency on your javascript project :
 ```
 npm i --save-dev eslint eslint-config-sedona
 ```

 Create an .eslintrc file at your project's root.

 Use `extends` with "sedona/set" in .eslintrc to specify that one of our rules sets apply to it.

 For example, in an angularjs project, your .eslintrc could be the following one :
 ```json
 {
   "parser": "babel-eslint",
   "extends": "sedona/angular-es6"
 }
 ```

### about eslint shareable config

 To learn more about eslint shareable configs, see the [eslint documentation](http://eslint.org/docs/developer-guide/shareable-configs).

Credits
-----------

Eslint-config-sedona is created and maintained by [Sedona](http://www.sedona.fr).

It is available under the MIT Licence, more details in the LICENCE file.

We would like to thanks the authors of the excellent eslint tool, and all the people who contributes to its rules and their documentations.
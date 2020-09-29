# ## [1.7.0](https://gitlab.com/roomle/web/roomle-pdc/compare/v1.6.1...v1.7.0) (2020-09-29)


### Features

* add configurator loading screen wen some assets in progress ([1f722c6](https://gitlab.com/roomle/web/roomle-pdc/commit/1f722c62319c51653e7e4d5510eb36c46dae0fef))
* add confirmation dialog before delete additional-contents in item page ([3631ce0](https://gitlab.com/roomle/web/roomle-pdc/commit/3631ce0d2c2fdb85acfa89ddb4544c498f46a57a))
* Add Render variations to easily render variations of a product without creating an item ([317da73](https://gitlab.com/roomle/web/roomle-pdc/commit/317da739f291f04cca40f71f2b588d0a34e91941))
* add rendering resolutions selection ([5ae3127](https://gitlab.com/roomle/web/roomle-pdc/commit/5ae31277eb397f63d534615fd649efda70059dba))
* create stripe billing form ([6cfaa04](https://gitlab.com/roomle/web/roomle-pdc/commit/6cfaa04b6c3ede79cdc9a86a5340e9fe0c4084d2))
* upload asset after item creation in free/starter ([7f99ce4](https://gitlab.com/roomle/web/roomle-pdc/commit/7f99ce47b71016fd700f47c56769682b080db005))
* upload assets automatically when create item in starter and free packages ([9aeb96b](https://gitlab.com/roomle/web/roomle-pdc/commit/9aeb96b04cce9561d53f95c49d9657d591b32f44))


### Bug Fixes

* access to user management for starter/free package ([98a01c7](https://gitlab.com/roomle/web/roomle-pdc/commit/98a01c7dd708294cdf4db708c3fc23ef4f354a4d))
* adding new content if there is opening content ([88274fe](https://gitlab.com/roomle/web/roomle-pdc/commit/88274fe067bb62b4fba727985df77f4462e39f78))
* change password ([b4b8b35](https://gitlab.com/roomle/web/roomle-pdc/commit/b4b8b35227e4b9a7a2b1af2d69e43a1ad069d9ec))
* delete and cancel textures/additional content deletion with popup ([7045693](https://gitlab.com/roomle/web/roomle-pdc/commit/7045693450cb253d6d71fd2ee4cbe295aefb16c1))
* dialog after add or change user role ([c98eb12](https://gitlab.com/roomle/web/roomle-pdc/commit/c98eb124c0d20670a6a187d1230deaf5820d9ade))
* hiding active state from products list in free and starter packages ([6d7a9f6](https://gitlab.com/roomle/web/roomle-pdc/commit/6d7a9f693afb98ad14db0fbd48e206c6317a1b3f))
* make the view in users list is list view ([ee65ac1](https://gitlab.com/roomle/web/roomle-pdc/commit/ee65ac10d61afc616425e05f6c368de509bbf1da))
* remove auto-generated string from product label ([615d2a5](https://gitlab.com/roomle/web/roomle-pdc/commit/615d2a501e8706c5e8989d3b9463046626086ca2))
* remove unused import ([c3951b4](https://gitlab.com/roomle/web/roomle-pdc/commit/c3951b4e5f905ee10ab006398d3aaa98596952c1))
* solve ember concurrency warning ([c31e689](https://gitlab.com/roomle/web/roomle-pdc/commit/c31e6893ef1e24a4b768e00700c5d35f54e97226))
* typescript lint errors ([9eb4ddb](https://gitlab.com/roomle/web/roomle-pdc/commit/9eb4ddbe24ab21858b420930bb5d347d4fad07e6))
* typo in intl translations files ([613562e](https://gitlab.com/roomle/web/roomle-pdc/commit/613562efdceec7dec2ed9401d92bb1ec26372d71))

### [1.6.1](https://gitlab.com/roomle/web/roomle-pdc/compare/v1.6.0...v1.6.1) (2020-09-16)


### Bug Fixes

* resolves RML-160 so that the problematic item can be loaded ([641ce2c](https://gitlab.com/roomle/web/roomle-pdc/commit/641ce2c7ea3d7c85c27843fce682edafcf3bcc48))

## [1.6.0](https://gitlab.com/roomle/web/roomle-pdc/compare/v1.5.0...v1.6.0) (2020-09-15)


### Features

* Add differant type of geometry for object display in material viewer ([f7ec7c7](https://gitlab.com/roomle/web/roomle-pdc/commit/f7ec7c77af41aa6597fb355f227f30c3c941be05))
* add glb preview in free/starter package ([2f5ccb2](https://gitlab.com/roomle/web/roomle-pdc/commit/2f5ccb20174b0bb4f7a4af35922e3c199181b333))
* Add grid view as default view and store it in localstorage ([9b74a30](https://gitlab.com/roomle/web/roomle-pdc/commit/9b74a306eadbeeae5919cd5dda68b06bb6deabf4))
* add helper function to detect if we are on gitlab.io server ([714e212](https://gitlab.com/roomle/web/roomle-pdc/commit/714e21286194f3c79902bd96aaf59d876a8abfa6))
* Add live preview in material viewer in every update ([8b23e22](https://gitlab.com/roomle/web/roomle-pdc/commit/8b23e22139a012092aaebc9e275d0c9e32895e43))
* create a bottom banner for creation [product-component-material-catalog] ([36e9a08](https://gitlab.com/roomle/web/roomle-pdc/commit/36e9a0852b45bff41afef9c85f988a56dd31ca6e))
* Move material viewer to be beside the sliders ([1194420](https://gitlab.com/roomle/web/roomle-pdc/commit/11944209ee5540e87b21c5c1806b547af430951c))
* send promo code after tenant registration to know what the current package type you need to register ([a885973](https://gitlab.com/roomle/web/roomle-pdc/commit/a885973702e2c4a81b1cddae52b1914c1119cb2c))


### Bug Fixes

* add redirecting to add cases in free/starter ([8f6c06b](https://gitlab.com/roomle/web/roomle-pdc/commit/8f6c06bdb4d51693a157c8b00290f22a1dcb7477))
* apply `m-header__content-lang-custom` if user have only one tenant ([c070d0f](https://gitlab.com/roomle/web/roomle-pdc/commit/c070d0f386adf9cfdc30d31a1fe367f37632772b))
* change the check for rendering and export rights from catalog module to product module ([0efcc9c](https://gitlab.com/roomle/web/roomle-pdc/commit/0efcc9cc4df01bc3e7418647960ec176365a3d28))
* change tooltip for product name in starter/free package ([9ed72a1](https://gitlab.com/roomle/web/roomle-pdc/commit/9ed72a10dc22ed9bb436cd36cf7018f39e0a3bd5))
* fix image validation check for nested image object ([e24f2a1](https://gitlab.com/roomle/web/roomle-pdc/commit/e24f2a187382a01659e645d9d5931cdbdd713ecd))
* handle null catalog id exception and move create catalog to global service ([953cf6f](https://gitlab.com/roomle/web/roomle-pdc/commit/953cf6fdda1243bdf214e99fdc0f79e7d28751c1))
* hide number of changeset changes in free/starter packages ([d883e28](https://gitlab.com/roomle/web/roomle-pdc/commit/d883e287956dc3cc6783c281b2763a3032f725e0))
* make shortId call if the item have id ([ca595ce](https://gitlab.com/roomle/web/roomle-pdc/commit/ca595ce49d5e3aa1414de7b9285e57a6c8714d75))
* material image delete icon ([1354e1e](https://gitlab.com/roomle/web/roomle-pdc/commit/1354e1e8b084caafd39507f3bf48af854630f673))
* redirect to first tenant if we are on gitlab.io and index.html ([e10e9f6](https://gitlab.com/roomle/web/roomle-pdc/commit/e10e9f6a63e5694a2f5fe0c16bab7481009a3570))
* remove change email callback if this is not passed ([b205c01](https://gitlab.com/roomle/web/roomle-pdc/commit/b205c01c824926aa7aa804cce07ee7f16c627163))
* remove Diacritics and replace any non printable ascii ([281b92a](https://gitlab.com/roomle/web/roomle-pdc/commit/281b92ab89cc1fbc07377803f81e8bf794298383))
* remove unused computed decorator ([7f9a3dc](https://gitlab.com/roomle/web/roomle-pdc/commit/7f9a3dcdbc33e62c4f9cd3503ef05962bf620615))
* transition between free and enterprise tenant ([dd9a001](https://gitlab.com/roomle/web/roomle-pdc/commit/dd9a001986cfc78bdc3e1f4395b631cbef875dcb))

## [1.5.0](https://gitlab.com/roomle/web/roomle-pdc/compare/v1.4.0...v1.5.0) (2020-09-01)


### Features

* add 3d Export and rendering modifications rights ([0236cdb](https://gitlab.com/roomle/web/roomle-pdc/commit/0236cdbae445b60ca0464177f20f99d31acfe657))
* Add 3d model samples file to docs ([ea45ef5](https://gitlab.com/roomle/web/roomle-pdc/commit/ea45ef5b736587bffedd933a13d3663c83095825))
* add smple 3d model upload in docs ([cee0d40](https://gitlab.com/roomle/web/roomle-pdc/commit/cee0d4032119e86fcd93cc308e747656dcae857b))
* added first version of pdc help for use in roomle docu project ([6079170](https://gitlab.com/roomle/web/roomle-pdc/commit/607917074dd3c07ba7255f625ce28303c78da3cb))
* Create a product from uploading content in a simple way in case of starter package ([4f34afc](https://gitlab.com/roomle/web/roomle-pdc/commit/4f34afcef2385c06c444d1ee0ac6b98de32de687))
* move activate email logic to be in PDC not planner ([e329e3e](https://gitlab.com/roomle/web/roomle-pdc/commit/e329e3e1ec6bee3210656b6d522588a33f91e8d3))


### Bug Fixes

* change hidden flag for item hidden functionality with visibilityStatus: 1 ([094918b](https://gitlab.com/roomle/web/roomle-pdc/commit/094918bdb8832d966d4264e77ff290425125af20))
* change placeholder word for label to auto-generated instead of  autogenerated ([b4ff44f](https://gitlab.com/roomle/web/roomle-pdc/commit/b4ff44fc871695dde0ff376713fb28762b791682))
* fix redirecting problem after roles edit ([bef3cb4](https://gitlab.com/roomle/web/roomle-pdc/commit/bef3cb4f13c926340f0ab201d2fb12eb8791370f))
* hide the connection tenant from the tenant list ([d90ecdb](https://gitlab.com/roomle/web/roomle-pdc/commit/d90ecdb36db0772f2bf3344af6e5c7264e6139ec))
* remove debugger ([805d671](https://gitlab.com/roomle/web/roomle-pdc/commit/805d67194aedcffebe1d0f6db4ae2b7f36862a60))
* remove unused markup ([45d411b](https://gitlab.com/roomle/web/roomle-pdc/commit/45d411b2c13b153a9e7f683978a1e9b5fe6dba55))
* solve tenant 9 problem ([8e9e023](https://gitlab.com/roomle/web/roomle-pdc/commit/8e9e02303ccc6eac0f548b94da8bfbdcd1c93ed1))
* User settings after registration shows unsaved changes ([89cad32](https://gitlab.com/roomle/web/roomle-pdc/commit/89cad32e2b6cfd36ab657c00b96781fb16460cf1))

## [1.4.0](https://gitlab.com/roomle/web/roomle-pdc/compare/v1.3.0...v1.4.0) (2020-08-18)


### Features

* Add change email form ([fe8588d](https://gitlab.com/roomle/web/roomle-pdc/commit/fe8588de46f37f876198a688fe0f7d02a28dd4e2))
* add current tenant info ([8c0c012](https://gitlab.com/roomle/web/roomle-pdc/commit/8c0c01202da821b9120e6d7d285001e09e4631ad))
* Add packages in PDC ([6ce65c4](https://gitlab.com/roomle/web/roomle-pdc/commit/6ce65c4406978e8b26cc3c3c125efdb1c6ca1bb7))
* Add resend email ([8678e7d](https://gitlab.com/roomle/web/roomle-pdc/commit/8678e7d61ba04851a7ebb22c6cef9df82472d57e))
* Create a try-out  page so we can test 3d content and see it without login ([8dbd4f8](https://gitlab.com/roomle/web/roomle-pdc/commit/8dbd4f815619facf1ffa02b6a61a061933c62989))
* Create an automatic tenant for register user ([8a3e37f](https://gitlab.com/roomle/web/roomle-pdc/commit/8a3e37fc1047a16c3d08f8b1292fb8aa01c7c1ed))
* create card for upgrading packages ([fe6e4b7](https://gitlab.com/roomle/web/roomle-pdc/commit/fe6e4b7bef3b2f87a68d5af3d7c2ab94cec90d57))
* Create pre-step process before tenant creation ([2960ad8](https://gitlab.com/roomle/web/roomle-pdc/commit/2960ad8cba56a438cad288275680ded9808d0043))
* hide tenant context menu if the user have only one tenant ([f2b5e75](https://gitlab.com/roomle/web/roomle-pdc/commit/f2b5e750e4f52d7323368c582cb7fd2643d7cea7))
* make router redirect to tryout page ([0e07e71](https://gitlab.com/roomle/web/roomle-pdc/commit/0e07e7166ade6c79af862de4fdd0a58b5c2c64dc))


### Bug Fixes

* change default texture mapping to be RBG instead of RBGA as RGBA causes artefacts, when you rotate the model and I also believe RGBA texture takes more resources than a RGB ([16290a3](https://gitlab.com/roomle/web/roomle-pdc/commit/16290a3187d2863b4a09a320b6ba0a34daabd8b3))
* remove debugger ([ba68252](https://gitlab.com/roomle/web/roomle-pdc/commit/ba68252c4a359c593b1e3b7839089daa89e5cf0e))
* remove unused import ([5278592](https://gitlab.com/roomle/web/roomle-pdc/commit/5278592ec6fac5a2d2683a0aa0faad107c569a30))

## [1.3.0](https://gitlab.com/roomle/web/roomle-pdc/compare/v1.2.1...v1.3.0) (2020-07-08)


### Features

* add `.releaserc.json` file for configure `@semantic-release/changelog` package ([362b165](https://gitlab.com/roomle/web/roomle-pdc/commit/362b16559f7bbb7a66d444a7956d39e2285cafbe))
* add `@semantic-release/changelog` plugin to create or update a changelog file ([e58ac74](https://gitlab.com/roomle/web/roomle-pdc/commit/e58ac74a3ce1802886b14f4747395abc464a8952))
* add `conventionalcommits` package for adding human and machine readable meaning to commit messages ([d61f64f](https://gitlab.com/roomle/web/roomle-pdc/commit/d61f64fdfd2f73a64b9dc2367afa36c2924070e6))
* add default value for shading params ([567ca32](https://gitlab.com/roomle/web/roomle-pdc/commit/567ca32d4947769931b1a8554954d5b003430248))
* add new error code ([026d5d6](https://gitlab.com/roomle/web/roomle-pdc/commit/026d5d652a4f293242914b0ea93b4a30e88a01f7))
* show the material viewer for the new created material ([ab410b9](https://gitlab.com/roomle/web/roomle-pdc/commit/ab410b972b10a0e2fbcb3d6d09f31566776fdc79))
* Use loadMaterial method instead of loadMaterialId ([0c0cfcb](https://gitlab.com/roomle/web/roomle-pdc/commit/0c0cfcb498f1f64e8e6eddd884ce0a013c7f3087))


### Bug Fixes

* color picker rgb if it is bigger than 1 ([bbd4f77](https://gitlab.com/roomle/web/roomle-pdc/commit/bbd4f77a844abc1df16d90c3c18509b009ce972b))
* fix archive material so it update model after archive operation ([12d2e5c](https://gitlab.com/roomle/web/roomle-pdc/commit/12d2e5cfe3e531d1fc247727ade3d9610ff8dd8b))
* Skip power of two validations for texture images and accept that the configurator has bad performance because of this ([104fcc5](https://gitlab.com/roomle/web/roomle-pdc/commit/104fcc550201329268b6ebc84a079f9ee033e86e))

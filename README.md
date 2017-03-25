# api documentation for  [firebase (v3.7.3)](https://firebase.google.com/)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-firebase.svg)](https://travis-ci.org/npmdoc/node-npmdoc-firebase)
#### Firebase JavaScript library for web and Node.js

[![NPM](https://nodei.co/npm/firebase.png?downloads=true)](https://www.npmjs.com/package/firebase)

[![apidoc](https://npmdoc.github.io/node-npmdoc-firebase/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-firebase_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-firebase/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-firebase/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Firebase",
        "email": "firebase-support@google.com",
        "url": "https://firebase.google.com/"
    },
    "browser": "firebase-browser.js",
    "dependencies": {
        "dom-storage": "2.0.2",
        "faye-websocket": "0.9.3",
        "jsonwebtoken": "7.1.9",
        "rsvp": "3.2.1",
        "xmlhttprequest": "1.8.0"
    },
    "description": "Firebase JavaScript library for web and Node.js",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "5f143638a84874095a7faf411589e059ac419ccc",
        "tarball": "https://registry.npmjs.org/firebase/-/firebase-3.7.3.tgz"
    },
    "homepage": "https://firebase.google.com/",
    "keywords": [
        "Firebase",
        "realtime",
        "database",
        "storage",
        "authentication"
    ],
    "license": "SEE LICENSE IN https://firebase.google.com/terms/",
    "main": "firebase-node.js",
    "maintainers": [
        {
            "name": "firebase",
            "email": "operations@firebase.com"
        }
    ],
    "name": "firebase",
    "optionalDependencies": {},
    "react-native": "firebase-react-native.js",
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "none",
        "url": "https://firebase.google.com/"
    },
    "scripts": {},
    "types": "firebase.d.ts",
    "version": "3.7.3"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module firebase](#apidoc.module.firebase)
1.  boolean <span class="apidocSignatureSpan">firebase.</span>__esModule
1.  [function <span class="apidocSignatureSpan">firebase.</span>INTERNAL.ErrorFactory (a, b, c)](#apidoc.element.firebase.INTERNAL.ErrorFactory)
1.  [function <span class="apidocSignatureSpan">firebase.</span>Promise ()](#apidoc.element.firebase.Promise)
1.  [function <span class="apidocSignatureSpan">firebase.</span>User (a, b, c)](#apidoc.element.firebase.User)
1.  [function <span class="apidocSignatureSpan">firebase.</span>app (a)](#apidoc.element.firebase.app)
1.  [function <span class="apidocSignatureSpan">firebase.</span>app.App (a, b, c)](#apidoc.element.firebase.app.App)
1.  [function <span class="apidocSignatureSpan">firebase.</span>auth (c)](#apidoc.element.firebase.auth)
1.  [function <span class="apidocSignatureSpan">firebase.</span>auth.Auth (a)](#apidoc.element.firebase.auth.Auth)
1.  [function <span class="apidocSignatureSpan">firebase.</span>auth.EmailAuthProvider ()](#apidoc.element.firebase.auth.EmailAuthProvider)
1.  [function <span class="apidocSignatureSpan">firebase.</span>auth.Error (a, b)](#apidoc.element.firebase.auth.Error)
1.  [function <span class="apidocSignatureSpan">firebase.</span>auth.FacebookAuthProvider ()](#apidoc.element.firebase.auth.FacebookAuthProvider)
1.  [function <span class="apidocSignatureSpan">firebase.</span>auth.GithubAuthProvider ()](#apidoc.element.firebase.auth.GithubAuthProvider)
1.  [function <span class="apidocSignatureSpan">firebase.</span>auth.GoogleAuthProvider ()](#apidoc.element.firebase.auth.GoogleAuthProvider)
1.  [function <span class="apidocSignatureSpan">firebase.</span>auth.TwitterAuthProvider ()](#apidoc.element.firebase.auth.TwitterAuthProvider)
1.  [function <span class="apidocSignatureSpan">firebase.</span>database (c)](#apidoc.element.firebase.database)
1.  [function <span class="apidocSignatureSpan">firebase.</span>database.Database (a)](#apidoc.element.firebase.database.Database)
1.  [function <span class="apidocSignatureSpan">firebase.</span>database.Query (a, b, c, d)](#apidoc.element.firebase.database.Query)
1.  [function <span class="apidocSignatureSpan">firebase.</span>database.Reference (a, b)](#apidoc.element.firebase.database.Reference)
1.  [function <span class="apidocSignatureSpan">firebase.</span>initializeApp (a, c)](#apidoc.element.firebase.initializeApp)
1.  [function <span class="apidocSignatureSpan">firebase.</span>serverAuth (c)](#apidoc.element.firebase.serverAuth)
1.  object <span class="apidocSignatureSpan">firebase.</span>INTERNAL
1.  object <span class="apidocSignatureSpan">firebase.</span>INTERNAL.ErrorFactory.prototype
1.  object <span class="apidocSignatureSpan">firebase.</span>INTERNAL.factories
1.  object <span class="apidocSignatureSpan">firebase.</span>INTERNAL.node
1.  object <span class="apidocSignatureSpan">firebase.</span>User.prototype
1.  object <span class="apidocSignatureSpan">firebase.</span>User.ud
1.  object <span class="apidocSignatureSpan">firebase.</span>app.App.prototype
1.  object <span class="apidocSignatureSpan">firebase.</span>apps
1.  object <span class="apidocSignatureSpan">firebase.</span>auth.Auth.prototype
1.  object <span class="apidocSignatureSpan">firebase.</span>auth.Error.prototype
1.  object <span class="apidocSignatureSpan">firebase.</span>auth.FacebookAuthProvider.prototype
1.  object <span class="apidocSignatureSpan">firebase.</span>auth.GithubAuthProvider.prototype
1.  object <span class="apidocSignatureSpan">firebase.</span>auth.GoogleAuthProvider.prototype
1.  object <span class="apidocSignatureSpan">firebase.</span>auth.TwitterAuthProvider.prototype
1.  object <span class="apidocSignatureSpan">firebase.</span>database.Database.prototype
1.  object <span class="apidocSignatureSpan">firebase.</span>database.INTERNAL
1.  object <span class="apidocSignatureSpan">firebase.</span>database.Query.prototype
1.  object <span class="apidocSignatureSpan">firebase.</span>database.Reference.prototype
1.  object <span class="apidocSignatureSpan">firebase.</span>database.TEST_ACCESS
1.  object <span class="apidocSignatureSpan">firebase.</span>database.TEST_ACCESS.Context.prototype
1.  object <span class="apidocSignatureSpan">firebase.</span>database.TEST_ACCESS.kc.prototype
1.  object <span class="apidocSignatureSpan">firebase.</span>database.TEST_ACCESS.xf.prototype
1.  object <span class="apidocSignatureSpan">firebase.</span>database.TEST_ACCESS.yf.prototype
1.  object <span class="apidocSignatureSpan">firebase.</span>default
1.  string <span class="apidocSignatureSpan">firebase.</span>SDK_VERSION

#### [module firebase.INTERNAL](#apidoc.module.firebase.INTERNAL)
1.  [function <span class="apidocSignatureSpan">firebase.INTERNAL.</span>ErrorFactory (a, b, c)](#apidoc.element.firebase.INTERNAL.ErrorFactory)
1.  [function <span class="apidocSignatureSpan">firebase.INTERNAL.</span>createFirebaseNamespace ()](#apidoc.element.firebase.INTERNAL.createFirebaseNamespace)
1.  [function <span class="apidocSignatureSpan">firebase.INTERNAL.</span>createSubscribe (a, b)](#apidoc.element.firebase.INTERNAL.createSubscribe)
1.  [function <span class="apidocSignatureSpan">firebase.INTERNAL.</span>deepExtend (a, b)](#apidoc.element.firebase.INTERNAL.deepExtend)
1.  [function <span class="apidocSignatureSpan">firebase.INTERNAL.</span>extendNamespace (a)](#apidoc.element.firebase.INTERNAL.extendNamespace)
1.  [function <span class="apidocSignatureSpan">firebase.INTERNAL.</span>registerService (b, c, d, n, Q)](#apidoc.element.firebase.INTERNAL.registerService)
1.  [function <span class="apidocSignatureSpan">firebase.INTERNAL.</span>removeApp (a)](#apidoc.element.firebase.INTERNAL.removeApp)
1.  [function <span class="apidocSignatureSpan">firebase.INTERNAL.</span>useAsService (a, b)](#apidoc.element.firebase.INTERNAL.useAsService)
1.  object <span class="apidocSignatureSpan">firebase.INTERNAL.</span>factories
1.  object <span class="apidocSignatureSpan">firebase.INTERNAL.</span>node

#### [module firebase.INTERNAL.ErrorFactory](#apidoc.module.firebase.INTERNAL.ErrorFactory)
1.  [function <span class="apidocSignatureSpan">firebase.INTERNAL.</span>ErrorFactory (a, b, c)](#apidoc.element.firebase.INTERNAL.ErrorFactory.ErrorFactory)

#### [module firebase.INTERNAL.ErrorFactory.prototype](#apidoc.module.firebase.INTERNAL.ErrorFactory.prototype)
1.  [function <span class="apidocSignatureSpan">firebase.INTERNAL.ErrorFactory.prototype.</span>create (a, b)](#apidoc.element.firebase.INTERNAL.ErrorFactory.prototype.create)

#### [module firebase.INTERNAL.factories](#apidoc.module.firebase.INTERNAL.factories)
1.  [function <span class="apidocSignatureSpan">firebase.INTERNAL.factories.</span>auth (a, b)](#apidoc.element.firebase.INTERNAL.factories.auth)
1.  [function <span class="apidocSignatureSpan">firebase.INTERNAL.factories.</span>database (a, b)](#apidoc.element.firebase.INTERNAL.factories.database)
1.  [function <span class="apidocSignatureSpan">firebase.INTERNAL.factories.</span>serverAuth (a, b)](#apidoc.element.firebase.INTERNAL.factories.serverAuth)

#### [module firebase.INTERNAL.node](#apidoc.module.firebase.INTERNAL.node)
1.  [function <span class="apidocSignatureSpan">firebase.INTERNAL.node.</span>XMLHttpRequest ()](#apidoc.element.firebase.INTERNAL.node.XMLHttpRequest)
1.  object <span class="apidocSignatureSpan">firebase.INTERNAL.node.</span>localStorage
1.  object <span class="apidocSignatureSpan">firebase.INTERNAL.node.</span>sessionStorage

#### [module firebase.User](#apidoc.module.firebase.User)
1.  [function <span class="apidocSignatureSpan">firebase.</span>User (a, b, c)](#apidoc.element.firebase.User.User)
1.  [function <span class="apidocSignatureSpan">firebase.User.</span>ag (a, c, f)](#apidoc.element.firebase.User.ag)
1.  object <span class="apidocSignatureSpan">firebase.User.</span>ud

#### [module firebase.User.prototype](#apidoc.module.firebase.User.prototype)
1.  [function <span class="apidocSignatureSpan">firebase.User.prototype.</span>Cd (a, b)](#apidoc.element.firebase.User.prototype.Cd)
1.  [function <span class="apidocSignatureSpan">firebase.User.prototype.</span>D ()](#apidoc.element.firebase.User.prototype.D)
1.  [function <span class="apidocSignatureSpan">firebase.User.prototype.</span>Jd (a, b)](#apidoc.element.firebase.User.prototype.Jd)
1.  [function <span class="apidocSignatureSpan">firebase.User.prototype.</span>Kd (a, b)](#apidoc.element.firebase.User.prototype.Kd)
1.  [function <span class="apidocSignatureSpan">firebase.User.prototype.</span>La ()](#apidoc.element.firebase.User.prototype.La)
1.  [function <span class="apidocSignatureSpan">firebase.User.prototype.</span>Sa (a, b, c, d)](#apidoc.element.firebase.User.prototype.Sa)
1.  [function <span class="apidocSignatureSpan">firebase.User.prototype.</span>Vc ()](#apidoc.element.firebase.User.prototype.Vc)
1.  [function <span class="apidocSignatureSpan">firebase.User.prototype.</span>c (a, b)](#apidoc.element.firebase.User.prototype.c)
1.  [function <span class="apidocSignatureSpan">firebase.User.prototype.</span>cc ()](#apidoc.element.firebase.User.prototype.cc)
1.  [function <span class="apidocSignatureSpan">firebase.User.prototype.</span>constructor (a, b, c)](#apidoc.element.firebase.User.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">firebase.User.prototype.</span>copy (a)](#apidoc.element.firebase.User.prototype.copy)
1.  [function <span class="apidocSignatureSpan">firebase.User.prototype.</span>delete ()](#apidoc.element.firebase.User.prototype.delete)
1.  [function <span class="apidocSignatureSpan">firebase.User.prototype.</span>getToken ()](#apidoc.element.firebase.User.prototype.getToken)
1.  [function <span class="apidocSignatureSpan">firebase.User.prototype.</span>link ()](#apidoc.element.firebase.User.prototype.link)
1.  [function <span class="apidocSignatureSpan">firebase.User.prototype.</span>linkWithPopup ()](#apidoc.element.firebase.User.prototype.linkWithPopup)
1.  [function <span class="apidocSignatureSpan">firebase.User.prototype.</span>linkWithRedirect ()](#apidoc.element.firebase.User.prototype.linkWithRedirect)
1.  [function <span class="apidocSignatureSpan">firebase.User.prototype.</span>reauthenticate ()](#apidoc.element.firebase.User.prototype.reauthenticate)
1.  [function <span class="apidocSignatureSpan">firebase.User.prototype.</span>reload ()](#apidoc.element.firebase.User.prototype.reload)
1.  [function <span class="apidocSignatureSpan">firebase.User.prototype.</span>sendEmailVerification ()](#apidoc.element.firebase.User.prototype.sendEmailVerification)
1.  [function <span class="apidocSignatureSpan">firebase.User.prototype.</span>sf (a)](#apidoc.element.firebase.User.prototype.sf)
1.  [function <span class="apidocSignatureSpan">firebase.User.prototype.</span>toJSON ()](#apidoc.element.firebase.User.prototype.toJSON)
1.  [function <span class="apidocSignatureSpan">firebase.User.prototype.</span>unlink ()](#apidoc.element.firebase.User.prototype.unlink)
1.  [function <span class="apidocSignatureSpan">firebase.User.prototype.</span>updateEmail ()](#apidoc.element.firebase.User.prototype.updateEmail)
1.  [function <span class="apidocSignatureSpan">firebase.User.prototype.</span>updatePassword ()](#apidoc.element.firebase.User.prototype.updatePassword)
1.  [function <span class="apidocSignatureSpan">firebase.User.prototype.</span>updateProfile ()](#apidoc.element.firebase.User.prototype.updateProfile)
1.  [function <span class="apidocSignatureSpan">firebase.User.prototype.</span>xb (a, b)](#apidoc.element.firebase.User.prototype.xb)
1.  string <span class="apidocSignatureSpan">firebase.User.prototype.</span>providerId

#### [module firebase.User.ud](#apidoc.module.firebase.User.ud)
1.  boolean <span class="apidocSignatureSpan">firebase.User.ud.</span>closure_listenable_158650
1.  [function <span class="apidocSignatureSpan">firebase.User.ud.</span>Sc (a, b, c, d)](#apidoc.element.firebase.User.ud.Sc)
1.  [function <span class="apidocSignatureSpan">firebase.User.ud.</span>addEventListener (a, b, c, d)](#apidoc.element.firebase.User.ud.addEventListener)
1.  [function <span class="apidocSignatureSpan">firebase.User.ud.</span>constructor ()](#apidoc.element.firebase.User.ud.constructor)
1.  [function <span class="apidocSignatureSpan">firebase.User.ud.</span>dispatchEvent (a)](#apidoc.element.firebase.User.ud.dispatchEvent)
1.  [function <span class="apidocSignatureSpan">firebase.User.ud.</span>listen (a, b, c, d)](#apidoc.element.firebase.User.ud.listen)
1.  [function <span class="apidocSignatureSpan">firebase.User.ud.</span>removeEventListener (a, b, c, d)](#apidoc.element.firebase.User.ud.removeEventListener)

#### [module firebase.app](#apidoc.module.firebase.app)
1.  [function <span class="apidocSignatureSpan">firebase.</span>app (a)](#apidoc.element.firebase.app.app)
1.  [function <span class="apidocSignatureSpan">firebase.app.</span>App (a, b, c)](#apidoc.element.firebase.app.App)

#### [module firebase.app.App](#apidoc.module.firebase.app.App)
1.  [function <span class="apidocSignatureSpan">firebase.app.</span>App (a, b, c)](#apidoc.element.firebase.app.App.App)

#### [module firebase.app.App.prototype](#apidoc.module.firebase.app.App.prototype)
1.  [function <span class="apidocSignatureSpan">firebase.app.App.prototype.</span>T (a)](#apidoc.element.firebase.app.App.prototype.T)
1.  [function <span class="apidocSignatureSpan">firebase.app.App.prototype.</span>U (a, b)](#apidoc.element.firebase.app.App.prototype.U)
1.  [function <span class="apidocSignatureSpan">firebase.app.App.prototype.</span>delete ()](#apidoc.element.firebase.app.App.prototype.delete)

#### [module firebase.auth](#apidoc.module.firebase.auth)
1.  [function <span class="apidocSignatureSpan">firebase.</span>auth (c)](#apidoc.element.firebase.auth.auth)
1.  [function <span class="apidocSignatureSpan">firebase.auth.</span>Auth (a)](#apidoc.element.firebase.auth.Auth)
1.  [function <span class="apidocSignatureSpan">firebase.auth.</span>EmailAuthProvider ()](#apidoc.element.firebase.auth.EmailAuthProvider)
1.  [function <span class="apidocSignatureSpan">firebase.auth.</span>Error (a, b)](#apidoc.element.firebase.auth.Error)
1.  [function <span class="apidocSignatureSpan">firebase.auth.</span>FacebookAuthProvider ()](#apidoc.element.firebase.auth.FacebookAuthProvider)
1.  [function <span class="apidocSignatureSpan">firebase.auth.</span>GithubAuthProvider ()](#apidoc.element.firebase.auth.GithubAuthProvider)
1.  [function <span class="apidocSignatureSpan">firebase.auth.</span>GoogleAuthProvider ()](#apidoc.element.firebase.auth.GoogleAuthProvider)
1.  [function <span class="apidocSignatureSpan">firebase.auth.</span>TwitterAuthProvider ()](#apidoc.element.firebase.auth.TwitterAuthProvider)

#### [module firebase.auth.Auth](#apidoc.module.firebase.auth.Auth)
1.  [function <span class="apidocSignatureSpan">firebase.auth.</span>Auth (a)](#apidoc.element.firebase.auth.Auth.Auth)

#### [module firebase.auth.Auth.prototype](#apidoc.module.firebase.auth.Auth.prototype)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>Cd (a, b)](#apidoc.element.firebase.auth.Auth.prototype.Cd)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>De (a)](#apidoc.element.firebase.auth.Auth.prototype.De)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>La ()](#apidoc.element.firebase.auth.Auth.prototype.La)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>Ne (a, b)](#apidoc.element.firebase.auth.Auth.prototype.Ne)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>Of ()](#apidoc.element.firebase.auth.Auth.prototype.Of)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>Sa (a, b, c, d)](#apidoc.element.firebase.auth.Auth.prototype.Sa)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>Vc ()](#apidoc.element.firebase.auth.Auth.prototype.Vc)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>Ye ()](#apidoc.element.firebase.auth.Auth.prototype.Ye)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>Ze ()](#apidoc.element.firebase.auth.Auth.prototype.Ze)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>addAuthTokenListener (a)](#apidoc.element.firebase.auth.Auth.prototype.addAuthTokenListener)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>applyActionCode ()](#apidoc.element.firebase.auth.Auth.prototype.applyActionCode)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>c (a)](#apidoc.element.firebase.auth.Auth.prototype.c)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>cb (a)](#apidoc.element.firebase.auth.Auth.prototype.cb)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>cc ()](#apidoc.element.firebase.auth.Auth.prototype.cc)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>cf (a)](#apidoc.element.firebase.auth.Auth.prototype.cf)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>checkActionCode ()](#apidoc.element.firebase.auth.Auth.prototype.checkActionCode)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>confirmPasswordReset ()](#apidoc.element.firebase.auth.Auth.prototype.confirmPasswordReset)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>createUserWithEmailAndPassword ()](#apidoc.element.firebase.auth.Auth.prototype.createUserWithEmailAndPassword)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>delete ()](#apidoc.element.firebase.auth.Auth.prototype.delete)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>fetchProvidersForEmail ()](#apidoc.element.firebase.auth.Auth.prototype.fetchProvidersForEmail)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>getRedirectResult ()](#apidoc.element.firebase.auth.Auth.prototype.getRedirectResult)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>getToken (a)](#apidoc.element.firebase.auth.Auth.prototype.getToken)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>getUid ()](#apidoc.element.firebase.auth.Auth.prototype.getUid)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>onAuthStateChanged ()](#apidoc.element.firebase.auth.Auth.prototype.onAuthStateChanged)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>removeAuthTokenListener (a)](#apidoc.element.firebase.auth.Auth.prototype.removeAuthTokenListener)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>sendPasswordResetEmail ()](#apidoc.element.firebase.auth.Auth.prototype.sendPasswordResetEmail)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>signInAnonymously ()](#apidoc.element.firebase.auth.Auth.prototype.signInAnonymously)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>signInWithCredential ()](#apidoc.element.firebase.auth.Auth.prototype.signInWithCredential)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>signInWithCustomToken ()](#apidoc.element.firebase.auth.Auth.prototype.signInWithCustomToken)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>signInWithEmailAndPassword ()](#apidoc.element.firebase.auth.Auth.prototype.signInWithEmailAndPassword)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>signInWithPopup ()](#apidoc.element.firebase.auth.Auth.prototype.signInWithPopup)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>signInWithRedirect ()](#apidoc.element.firebase.auth.Auth.prototype.signInWithRedirect)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>signOut ()](#apidoc.element.firebase.auth.Auth.prototype.signOut)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>toJSON ()](#apidoc.element.firebase.auth.Auth.prototype.toJSON)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>verifyPasswordResetCode ()](#apidoc.element.firebase.auth.Auth.prototype.verifyPasswordResetCode)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>xb (a, b)](#apidoc.element.firebase.auth.Auth.prototype.xb)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>yf (a)](#apidoc.element.firebase.auth.Auth.prototype.yf)

#### [module firebase.auth.EmailAuthProvider](#apidoc.module.firebase.auth.EmailAuthProvider)
1.  [function <span class="apidocSignatureSpan">firebase.auth.</span>EmailAuthProvider ()](#apidoc.element.firebase.auth.EmailAuthProvider.EmailAuthProvider)
1.  [function <span class="apidocSignatureSpan">firebase.auth.EmailAuthProvider.</span>credential ()](#apidoc.element.firebase.auth.EmailAuthProvider.credential)
1.  string <span class="apidocSignatureSpan">firebase.auth.EmailAuthProvider.</span>PROVIDER_ID

#### [module firebase.auth.Error](#apidoc.module.firebase.auth.Error)
1.  [function <span class="apidocSignatureSpan">firebase.auth.</span>Error (a, b)](#apidoc.element.firebase.auth.Error.Error)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Error.</span>ag (a, c, f)](#apidoc.element.firebase.auth.Error.ag)
1.  object <span class="apidocSignatureSpan">firebase.auth.Error.</span>ud

#### [module firebase.auth.Error.prototype](#apidoc.module.firebase.auth.Error.prototype)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Error.prototype.</span>D ()](#apidoc.element.firebase.auth.Error.prototype.D)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Error.prototype.</span>constructor (a, b)](#apidoc.element.firebase.auth.Error.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">firebase.auth.Error.prototype.</span>toJSON ()](#apidoc.element.firebase.auth.Error.prototype.toJSON)

#### [module firebase.auth.FacebookAuthProvider](#apidoc.module.firebase.auth.FacebookAuthProvider)
1.  [function <span class="apidocSignatureSpan">firebase.auth.</span>FacebookAuthProvider ()](#apidoc.element.firebase.auth.FacebookAuthProvider.FacebookAuthProvider)
1.  [function <span class="apidocSignatureSpan">firebase.auth.FacebookAuthProvider.</span>ag (a, c, f)](#apidoc.element.firebase.auth.FacebookAuthProvider.ag)
1.  [function <span class="apidocSignatureSpan">firebase.auth.FacebookAuthProvider.</span>credential ()](#apidoc.element.firebase.auth.FacebookAuthProvider.credential)
1.  object <span class="apidocSignatureSpan">firebase.auth.FacebookAuthProvider.</span>ud
1.  string <span class="apidocSignatureSpan">firebase.auth.FacebookAuthProvider.</span>PROVIDER_ID

#### [module firebase.auth.FacebookAuthProvider.prototype](#apidoc.module.firebase.auth.FacebookAuthProvider.prototype)
1.  [function <span class="apidocSignatureSpan">firebase.auth.FacebookAuthProvider.prototype.</span>Nd ()](#apidoc.element.firebase.auth.FacebookAuthProvider.prototype.Nd)
1.  [function <span class="apidocSignatureSpan">firebase.auth.FacebookAuthProvider.prototype.</span>addScope ()](#apidoc.element.firebase.auth.FacebookAuthProvider.prototype.addScope)
1.  [function <span class="apidocSignatureSpan">firebase.auth.FacebookAuthProvider.prototype.</span>credential (a, b)](#apidoc.element.firebase.auth.FacebookAuthProvider.prototype.credential)
1.  [function <span class="apidocSignatureSpan">firebase.auth.FacebookAuthProvider.prototype.</span>setCustomParameters ()](#apidoc.element.firebase.auth.FacebookAuthProvider.prototype.setCustomParameters)

#### [module firebase.auth.GithubAuthProvider](#apidoc.module.firebase.auth.GithubAuthProvider)
1.  [function <span class="apidocSignatureSpan">firebase.auth.</span>GithubAuthProvider ()](#apidoc.element.firebase.auth.GithubAuthProvider.GithubAuthProvider)
1.  [function <span class="apidocSignatureSpan">firebase.auth.GithubAuthProvider.</span>ag (a, c, f)](#apidoc.element.firebase.auth.GithubAuthProvider.ag)
1.  [function <span class="apidocSignatureSpan">firebase.auth.GithubAuthProvider.</span>credential ()](#apidoc.element.firebase.auth.GithubAuthProvider.credential)
1.  object <span class="apidocSignatureSpan">firebase.auth.GithubAuthProvider.</span>ud
1.  string <span class="apidocSignatureSpan">firebase.auth.GithubAuthProvider.</span>PROVIDER_ID

#### [module firebase.auth.GithubAuthProvider.prototype](#apidoc.module.firebase.auth.GithubAuthProvider.prototype)
1.  [function <span class="apidocSignatureSpan">firebase.auth.GithubAuthProvider.prototype.</span>Nd ()](#apidoc.element.firebase.auth.GithubAuthProvider.prototype.Nd)
1.  [function <span class="apidocSignatureSpan">firebase.auth.GithubAuthProvider.prototype.</span>addScope ()](#apidoc.element.firebase.auth.GithubAuthProvider.prototype.addScope)
1.  [function <span class="apidocSignatureSpan">firebase.auth.GithubAuthProvider.prototype.</span>credential (a, b)](#apidoc.element.firebase.auth.GithubAuthProvider.prototype.credential)
1.  [function <span class="apidocSignatureSpan">firebase.auth.GithubAuthProvider.prototype.</span>setCustomParameters ()](#apidoc.element.firebase.auth.GithubAuthProvider.prototype.setCustomParameters)

#### [module firebase.auth.GoogleAuthProvider](#apidoc.module.firebase.auth.GoogleAuthProvider)
1.  [function <span class="apidocSignatureSpan">firebase.auth.</span>GoogleAuthProvider ()](#apidoc.element.firebase.auth.GoogleAuthProvider.GoogleAuthProvider)
1.  [function <span class="apidocSignatureSpan">firebase.auth.GoogleAuthProvider.</span>ag (a, c, f)](#apidoc.element.firebase.auth.GoogleAuthProvider.ag)
1.  [function <span class="apidocSignatureSpan">firebase.auth.GoogleAuthProvider.</span>credential ()](#apidoc.element.firebase.auth.GoogleAuthProvider.credential)
1.  object <span class="apidocSignatureSpan">firebase.auth.GoogleAuthProvider.</span>ud
1.  string <span class="apidocSignatureSpan">firebase.auth.GoogleAuthProvider.</span>PROVIDER_ID

#### [module firebase.auth.GoogleAuthProvider.prototype](#apidoc.module.firebase.auth.GoogleAuthProvider.prototype)
1.  [function <span class="apidocSignatureSpan">firebase.auth.GoogleAuthProvider.prototype.</span>Nd ()](#apidoc.element.firebase.auth.GoogleAuthProvider.prototype.Nd)
1.  [function <span class="apidocSignatureSpan">firebase.auth.GoogleAuthProvider.prototype.</span>addScope ()](#apidoc.element.firebase.auth.GoogleAuthProvider.prototype.addScope)
1.  [function <span class="apidocSignatureSpan">firebase.auth.GoogleAuthProvider.prototype.</span>credential (a, b)](#apidoc.element.firebase.auth.GoogleAuthProvider.prototype.credential)
1.  [function <span class="apidocSignatureSpan">firebase.auth.GoogleAuthProvider.prototype.</span>setCustomParameters ()](#apidoc.element.firebase.auth.GoogleAuthProvider.prototype.setCustomParameters)

#### [module firebase.auth.TwitterAuthProvider](#apidoc.module.firebase.auth.TwitterAuthProvider)
1.  [function <span class="apidocSignatureSpan">firebase.auth.</span>TwitterAuthProvider ()](#apidoc.element.firebase.auth.TwitterAuthProvider.TwitterAuthProvider)
1.  [function <span class="apidocSignatureSpan">firebase.auth.TwitterAuthProvider.</span>ag (a, c, f)](#apidoc.element.firebase.auth.TwitterAuthProvider.ag)
1.  [function <span class="apidocSignatureSpan">firebase.auth.TwitterAuthProvider.</span>credential ()](#apidoc.element.firebase.auth.TwitterAuthProvider.credential)
1.  object <span class="apidocSignatureSpan">firebase.auth.TwitterAuthProvider.</span>ud
1.  string <span class="apidocSignatureSpan">firebase.auth.TwitterAuthProvider.</span>PROVIDER_ID

#### [module firebase.auth.TwitterAuthProvider.prototype](#apidoc.module.firebase.auth.TwitterAuthProvider.prototype)
1.  [function <span class="apidocSignatureSpan">firebase.auth.TwitterAuthProvider.prototype.</span>setCustomParameters ()](#apidoc.element.firebase.auth.TwitterAuthProvider.prototype.setCustomParameters)

#### [module firebase.database](#apidoc.module.firebase.database)
1.  [function <span class="apidocSignatureSpan">firebase.</span>database (c)](#apidoc.element.firebase.database.database)
1.  [function <span class="apidocSignatureSpan">firebase.database.</span>Database (a)](#apidoc.element.firebase.database.Database)
1.  [function <span class="apidocSignatureSpan">firebase.database.</span>Query (a, b, c, d)](#apidoc.element.firebase.database.Query)
1.  [function <span class="apidocSignatureSpan">firebase.database.</span>Reference (a, b)](#apidoc.element.firebase.database.Reference)
1.  [function <span class="apidocSignatureSpan">firebase.database.</span>enableLogging (a, b)](#apidoc.element.firebase.database.enableLogging)
1.  object <span class="apidocSignatureSpan">firebase.database.</span>INTERNAL
1.  object <span class="apidocSignatureSpan">firebase.database.</span>ServerValue
1.  object <span class="apidocSignatureSpan">firebase.database.</span>TEST_ACCESS

#### [module firebase.database.Database](#apidoc.module.firebase.database.Database)
1.  [function <span class="apidocSignatureSpan">firebase.database.</span>Database (a)](#apidoc.element.firebase.database.Database.Database)

#### [module firebase.database.Database.prototype](#apidoc.module.firebase.database.Database.prototype)
1.  [function <span class="apidocSignatureSpan">firebase.database.Database.prototype.</span>Rf ()](#apidoc.element.firebase.database.Database.prototype.Rf)
1.  [function <span class="apidocSignatureSpan">firebase.database.Database.prototype.</span>Sf ()](#apidoc.element.firebase.database.Database.prototype.Sf)
1.  [function <span class="apidocSignatureSpan">firebase.database.Database.prototype.</span>gf (a)](#apidoc.element.firebase.database.Database.prototype.gf)
1.  [function <span class="apidocSignatureSpan">firebase.database.Database.prototype.</span>goOffline ()](#apidoc.element.firebase.database.Database.prototype.goOffline)
1.  [function <span class="apidocSignatureSpan">firebase.database.Database.prototype.</span>goOnline ()](#apidoc.element.firebase.database.Database.prototype.goOnline)
1.  [function <span class="apidocSignatureSpan">firebase.database.Database.prototype.</span>ig (a)](#apidoc.element.firebase.database.Database.prototype.ig)
1.  [function <span class="apidocSignatureSpan">firebase.database.Database.prototype.</span>ref (a)](#apidoc.element.firebase.database.Database.prototype.ref)
1.  [function <span class="apidocSignatureSpan">firebase.database.Database.prototype.</span>refFromURL (a)](#apidoc.element.firebase.database.Database.prototype.refFromURL)

#### [module firebase.database.INTERNAL](#apidoc.module.firebase.database.INTERNAL)
1.  [function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>Ae (a, b)](#apidoc.element.firebase.database.INTERNAL.Ae)
1.  [function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>Of ()](#apidoc.element.firebase.database.INTERNAL.Of)
1.  [function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>Pf ()](#apidoc.element.firebase.database.INTERNAL.Pf)
1.  [function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>Uf (a, b)](#apidoc.element.firebase.database.INTERNAL.Uf)
1.  [function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>Vf ()](#apidoc.element.firebase.database.INTERNAL.Vf)
1.  [function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>cd (a)](#apidoc.element.firebase.database.INTERNAL.cd)
1.  [function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>dataUpdateCount (a)](#apidoc.element.firebase.database.INTERNAL.dataUpdateCount)
1.  [function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>forceLongPolling ()](#apidoc.element.firebase.database.INTERNAL.forceLongPolling)
1.  [function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>forceWebSockets ()](#apidoc.element.firebase.database.INTERNAL.forceWebSockets)
1.  [function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>interceptServerData (a, b)](#apidoc.element.firebase.database.INTERNAL.interceptServerData)
1.  [function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>isWebSocketsAvailable ()](#apidoc.element.firebase.database.INTERNAL.isWebSocketsAvailable)
1.  [function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>ng (a, b)](#apidoc.element.firebase.database.INTERNAL.ng)
1.  [function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>setSecurityDebugCallback (a, b)](#apidoc.element.firebase.database.INTERNAL.setSecurityDebugCallback)
1.  [function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>stats (a, b)](#apidoc.element.firebase.database.INTERNAL.stats)
1.  [function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>statsIncrementCounter (a, b)](#apidoc.element.firebase.database.INTERNAL.statsIncrementCounter)
1.  [function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>ze (a, b)](#apidoc.element.firebase.database.INTERNAL.ze)

#### [module firebase.database.Query](#apidoc.module.firebase.database.Query)
1.  [function <span class="apidocSignatureSpan">firebase.database.</span>Query (a, b, c, d)](#apidoc.element.firebase.database.Query.Query)

#### [module firebase.database.Query.prototype](#apidoc.module.firebase.database.Query.prototype)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>Fc (a, b, c)](#apidoc.element.firebase.database.Query.prototype.Fc)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>Jf (a, b)](#apidoc.element.firebase.database.Query.prototype.Jf)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>Kd (a, b)](#apidoc.element.firebase.database.Query.prototype.Kd)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>ag (a, b)](#apidoc.element.firebase.database.Query.prototype.ag)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>bg (a)](#apidoc.element.firebase.database.Query.prototype.bg)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>cg ()](#apidoc.element.firebase.database.Query.prototype.cg)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>dc (a, b, c, d)](#apidoc.element.firebase.database.Query.prototype.dc)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>dd (a, b)](#apidoc.element.firebase.database.Query.prototype.dd)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>dg ()](#apidoc.element.firebase.database.Query.prototype.dg)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>eg ()](#apidoc.element.firebase.database.Query.prototype.eg)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>endAt (a, b)](#apidoc.element.firebase.database.Query.prototype.endAt)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>equalTo (a, b)](#apidoc.element.firebase.database.Query.prototype.equalTo)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>isEqual (a)](#apidoc.element.firebase.database.Query.prototype.isEqual)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>ja ()](#apidoc.element.firebase.database.Query.prototype.ja)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>ke (a)](#apidoc.element.firebase.database.Query.prototype.ke)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>le (a)](#apidoc.element.firebase.database.Query.prototype.le)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>limitToFirst (a)](#apidoc.element.firebase.database.Query.prototype.limitToFirst)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>limitToLast (a)](#apidoc.element.firebase.database.Query.prototype.limitToLast)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>off (a, b, c)](#apidoc.element.firebase.database.Query.prototype.off)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>on (a, b, c, d)](#apidoc.element.firebase.database.Query.prototype.on)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>once (a, b)](#apidoc.element.firebase.database.Query.prototype.once)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>orderByChild (a)](#apidoc.element.firebase.database.Query.prototype.orderByChild)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>orderByKey ()](#apidoc.element.firebase.database.Query.prototype.orderByKey)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>orderByPriority ()](#apidoc.element.firebase.database.Query.prototype.orderByPriority)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>orderByValue ()](#apidoc.element.firebase.database.Query.prototype.orderByValue)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>startAt (a, b)](#apidoc.element.firebase.database.Query.prototype.startAt)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>toJSON ()](#apidoc.element.firebase.database.Query.prototype.toJSON)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>toString ()](#apidoc.element.firebase.database.Query.prototype.toString)
1.  [function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>ub ()](#apidoc.element.firebase.database.Query.prototype.ub)

#### [module firebase.database.Reference](#apidoc.module.firebase.database.Reference)
1.  [function <span class="apidocSignatureSpan">firebase.database.</span>Reference (a, b)](#apidoc.element.firebase.database.Reference.Reference)
1.  [function <span class="apidocSignatureSpan">firebase.database.Reference.</span>vg (a, c, f)](#apidoc.element.firebase.database.Reference.vg)
1.  object <span class="apidocSignatureSpan">firebase.database.Reference.</span>Bg

#### [module firebase.database.Reference.prototype](#apidoc.module.firebase.database.Reference.prototype)
1.  [function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>Gf ()](#apidoc.element.firebase.database.Reference.prototype.Gf)
1.  [function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>Hb (a, b, c)](#apidoc.element.firebase.database.Reference.prototype.Hb)
1.  [function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>Qf ()](#apidoc.element.firebase.database.Reference.prototype.Qf)
1.  [function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>child (a)](#apidoc.element.firebase.database.Reference.prototype.child)
1.  [function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>constructor (a, b)](#apidoc.element.firebase.database.Reference.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>gb ()](#apidoc.element.firebase.database.Reference.prototype.gb)
1.  [function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>getKey ()](#apidoc.element.firebase.database.Reference.prototype.getKey)
1.  [function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>getParent ()](#apidoc.element.firebase.database.Reference.prototype.getParent)
1.  [function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>mg (a, b)](#apidoc.element.firebase.database.Reference.prototype.mg)
1.  [function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>n (a)](#apidoc.element.firebase.database.Reference.prototype.n)
1.  [function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>onDisconnect ()](#apidoc.element.firebase.database.Reference.prototype.onDisconnect)
1.  [function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>push (a, b)](#apidoc.element.firebase.database.Reference.prototype.push)
1.  [function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>remove (a)](#apidoc.element.firebase.database.Reference.prototype.remove)
1.  [function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>set (a, b)](#apidoc.element.firebase.database.Reference.prototype.set)
1.  [function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>setPriority (a, b)](#apidoc.element.firebase.database.Reference.prototype.setPriority)
1.  [function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>setWithPriority (a, b, c)](#apidoc.element.firebase.database.Reference.prototype.setWithPriority)
1.  [function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>transaction (a, b, c)](#apidoc.element.firebase.database.Reference.prototype.transaction)
1.  [function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>update (a, b)](#apidoc.element.firebase.database.Reference.prototype.update)

#### [module firebase.database.TEST_ACCESS](#apidoc.module.firebase.database.TEST_ACCESS)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>ConnectionTarget (a, b, c, d, e)](#apidoc.element.firebase.database.TEST_ACCESS.ConnectionTarget)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>Context ()](#apidoc.element.firebase.database.TEST_ACCESS.Context)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>DataConnection (a, b, c, d, e, f)](#apidoc.element.firebase.database.TEST_ACCESS.DataConnection)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>RealTimeConnection (a, b, c, d, e, f, g)](#apidoc.element.firebase.database.TEST_ACCESS.RealTimeConnection)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>Tf (a)](#apidoc.element.firebase.database.TEST_ACCESS.Tf)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>Wf (a)](#apidoc.element.firebase.database.TEST_ACCESS.Wf)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>forceRestClient (a)](#apidoc.element.firebase.database.TEST_ACCESS.forceRestClient)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>hijackHash (a)](#apidoc.element.firebase.database.TEST_ACCESS.hijackHash)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>ja (a)](#apidoc.element.firebase.database.TEST_ACCESS.ja)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>kc (a, b, c, d, e, f)](#apidoc.element.firebase.database.TEST_ACCESS.kc)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>listens (a)](#apidoc.element.firebase.database.TEST_ACCESS.listens)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>queryIdentifier (a)](#apidoc.element.firebase.database.TEST_ACCESS.queryIdentifier)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>xf (a, b, c, d, e)](#apidoc.element.firebase.database.TEST_ACCESS.xf)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>yf (a, b, c, d, e, f, g)](#apidoc.element.firebase.database.TEST_ACCESS.yf)

#### [module firebase.database.TEST_ACCESS.Context.prototype](#apidoc.module.firebase.database.TEST_ACCESS.Context.prototype)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.Context.prototype.</span>hc ()](#apidoc.element.firebase.database.TEST_ACCESS.Context.prototype.hc)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.Context.prototype.</span>interrupt ()](#apidoc.element.firebase.database.TEST_ACCESS.Context.prototype.interrupt)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.Context.prototype.</span>resume ()](#apidoc.element.firebase.database.TEST_ACCESS.Context.prototype.resume)

#### [module firebase.database.TEST_ACCESS.kc.prototype](#apidoc.module.firebase.database.TEST_ACCESS.kc.prototype)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>Ic (a, b)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.Ic)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>If (a, b)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.If)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>Xe (a, b, c, d)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.Xe)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>Ye (a, b, c, d)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.Ye)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>Zf (a)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.Zf)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>bf (a, b, c)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.bf)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>cf ()](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.cf)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>echo (a, b)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.echo)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>hc (a)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.hc)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>hf (a)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.hf)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>interrupt (a)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.interrupt)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>pe (a, b, c)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.pe)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>pg (a, b)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.pg)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>put (a, b, c, d)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.put)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>simpleListen (a, b)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.simpleListen)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>tf (a, b)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.tf)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>ua (a, b, c)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.ua)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>ud (a)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.ud)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>vd (a, b)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.vd)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>we (a)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.we)

#### [module firebase.database.TEST_ACCESS.xf.prototype](#apidoc.module.firebase.database.TEST_ACCESS.xf.prototype)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.xf.prototype.</span>toString ()](#apidoc.element.firebase.database.TEST_ACCESS.xf.prototype.toString)

#### [module firebase.database.TEST_ACCESS.yf.prototype](#apidoc.module.firebase.database.TEST_ACCESS.yf.prototype)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.yf.prototype.</span>close ()](#apidoc.element.firebase.database.TEST_ACCESS.yf.prototype.close)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.yf.prototype.</span>sendRequest (a)](#apidoc.element.firebase.database.TEST_ACCESS.yf.prototype.sendRequest)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.yf.prototype.</span>ua (a)](#apidoc.element.firebase.database.TEST_ACCESS.yf.prototype.ua)
1.  [function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.yf.prototype.</span>ud (a)](#apidoc.element.firebase.database.TEST_ACCESS.yf.prototype.ud)

#### [module firebase.serverAuth](#apidoc.module.firebase.serverAuth)
1.  [function <span class="apidocSignatureSpan">firebase.</span>serverAuth (c)](#apidoc.element.firebase.serverAuth.serverAuth)
1.  [function <span class="apidocSignatureSpan">firebase.serverAuth.</span>Auth (app_)](#apidoc.element.firebase.serverAuth.Auth)



# <a name="apidoc.module.firebase"></a>[module firebase](#apidoc.module.firebase)

#### <a name="apidoc.element.firebase.INTERNAL.ErrorFactory"></a>[function <span class="apidocSignatureSpan">firebase.</span>INTERNAL.ErrorFactory (a, b, c)](#apidoc.element.firebase.INTERNAL.ErrorFactory)
- description and source-code
```javascript
INTERNAL.ErrorFactory = function (a, b, c){this.X=a;this.Y=b;this.P=c;this.pattern=/\{\$([^}]+)}/g}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.Promise"></a>[function <span class="apidocSignatureSpan">firebase.</span>Promise ()](#apidoc.element.firebase.Promise)
- description and source-code
```javascript
function Promise() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User"></a>[function <span class="apidocSignatureSpan">firebase.</span>User (a, b, c)](#apidoc.element.firebase.User)
- description and source-code
```javascript
User = function (a, b, c){this.$=[];this.j=a.apiKey;this.B=a.appName;this.v=a.authDomain||null;a=firebase.SDK_VERSION?yf(firebase.SDK_VERSION
):null;this.g=new R(this.j,null,a);this.ga=new Xi(this.g);cj(this,b.idToken);Zi(this.ga,b);M(this,"refreshToken",this.ga.W);dj(this
,c||{});te.call(this);this.tc=!1;this.v&&Bf()&&(this.m=Si(this.v,this.j,this.B));this.yc=[];this.ia=null;this.jb=ej(this);this.tb
=q(this.Vc,this)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.app"></a>[function <span class="apidocSignatureSpan">firebase.</span>app (a)](#apidoc.element.firebase.app)
- description and source-code
```javascript
function a(a){a=a||"[DEFAULT]";var b=d[a];void 0===b&&M("no-app",{name:a});return b}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.app.App"></a>[function <span class="apidocSignatureSpan">firebase.</span>app.App (a, b, c)](#apidoc.element.firebase.app.App)
- description and source-code
```javascript
app.App = function (a, b, c){var d=this;this.F=c;this.H=!1;this.b={};this.l=b;this.s=z(void 0,a);a="serviceAccount"in this.s;("credential"in
 this.s||a)&&"undefined"!==typeof console&&console.log("The '"+(a?"serviceAccount":"credential")+"' property specified in the first
 argument to initializeApp() is deprecated and will be removed in the next major version. You should instead use the 'firebase-admin
' package. See https://firebase.google.com/docs/admin/setup for details on how to get started.");Object.keys(c.INTERNAL.factories
).forEach(function(a){var b=
c.INTERNAL.useAsService(d,a);null!==b&&(b=d.U.bind(d,b),d[a]=b)})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth"></a>[function <span class="apidocSignatureSpan">firebase.</span>auth (c)](#apidoc.element.firebase.auth)
- description and source-code
```javascript
auth = function (c){void 0===c&&(c=a());"function"!==typeof c[b]&&M("invalid-app-argument",{name:b});return c[b]()}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth"></a>[function <span class="apidocSignatureSpan">firebase.</span>auth.Auth (a)](#apidoc.element.firebase.auth.Auth)
- description and source-code
```javascript
auth.Auth = function (a){this.Za=!1;M(this,"app",a);if(X(this).options&&X(this).options.apiKey)a=firebase.SDK_VERSION?yf(firebase.SDK_VERSION
):null,this.g=new R(X(this).options&&X(this).options.apiKey,null,a);else throw new N("invalid-api-key");this.$=[];this.Aa=[];this
.pf=firebase.INTERNAL.createSubscribe(q(this.cf,this));Oj(this,null);this.pa=new Jj(X(this).options.apiKey+":"+X(this).name);this
.mb=new Hj(X(this).options.apiKey+":"+X(this).name);this.Xb=this.c(Pj(this));this.va=this.c(Qj(this));this.ad=
!1;this.Tc=q(this.Of,this);this.ue=q(this.cb,this);this.tb=q(this.Vc,this);this.se=q(this.Ye,this);this.te=q(this.Ze,this);Rj(this
);this.INTERNAL={};this.INTERNAL["delete"]=q(this["delete"],this);this.Fa=0}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.EmailAuthProvider"></a>[function <span class="apidocSignatureSpan">firebase.</span>auth.EmailAuthProvider ()](#apidoc.element.firebase.auth.EmailAuthProvider)
- description and source-code
```javascript
auth.EmailAuthProvider = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Error"></a>[function <span class="apidocSignatureSpan">firebase.</span>auth.Error (a, b)](#apidoc.element.firebase.auth.Error)
- description and source-code
```javascript
auth.Error = function (a, b){this.code="auth/"+a;this.message=b||Zf[a]||""}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.FacebookAuthProvider"></a>[function <span class="apidocSignatureSpan">firebase.</span>auth.FacebookAuthProvider ()](#apidoc.element.firebase.auth.FacebookAuthProvider)
- description and source-code
```javascript
auth.FacebookAuthProvider = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.GithubAuthProvider"></a>[function <span class="apidocSignatureSpan">firebase.</span>auth.GithubAuthProvider ()](#apidoc.element.firebase.auth.GithubAuthProvider)
- description and source-code
```javascript
auth.GithubAuthProvider = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.GoogleAuthProvider"></a>[function <span class="apidocSignatureSpan">firebase.</span>auth.GoogleAuthProvider ()](#apidoc.element.firebase.auth.GoogleAuthProvider)
- description and source-code
```javascript
auth.GoogleAuthProvider = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.TwitterAuthProvider"></a>[function <span class="apidocSignatureSpan">firebase.</span>auth.TwitterAuthProvider ()](#apidoc.element.firebase.auth.TwitterAuthProvider)
- description and source-code
```javascript
auth.TwitterAuthProvider = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database"></a>[function <span class="apidocSignatureSpan">firebase.</span>database (c)](#apidoc.element.firebase.database)
- description and source-code
```javascript
database = function (c){void 0===c&&(c=a());"function"!==typeof c[b]&&M("invalid-app-argument",{name:b});return c[b]()}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Database"></a>[function <span class="apidocSignatureSpan">firebase.</span>database.Database (a)](#apidoc.element.firebase.database.Database)
- description and source-code
```javascript
function Og(a){a instanceof Pg||Sb("Don't call new Database() directly - please use firebase.database().");this.ta=a;this.ba=new
 U(a,Q);this.INTERNAL=new Qg(this)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query"></a>[function <span class="apidocSignatureSpan">firebase.</span>database.Query (a, b, c, d)](#apidoc.element.firebase.database.Query)
- description and source-code
```javascript
function X(a, b, c, d){this.u=a;this.path=b;this.m=c;this.Kc=d}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Reference"></a>[function <span class="apidocSignatureSpan">firebase.</span>database.Reference (a, b)](#apidoc.element.firebase.database.Reference)
- description and source-code
```javascript
function U(a, b){if(!(a instanceof Pg))throw Error("new Firebase() no longer supported - use app.database().");X.call(this,a,b,jf
,!1);this.then=void 0;this["catch"]=void 0}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.initializeApp"></a>[function <span class="apidocSignatureSpan">firebase.</span>initializeApp (a, c)](#apidoc.element.firebase.initializeApp)
- description and source-code
```javascript
initializeApp = function (a, c){void 0===c?c="[DEFAULT]":"string"===typeof c&&""!==c||M("bad-app-name",
{name:c+""});void 0!==d[c]&&M("duplicate-app",{name:c});a=new K(a,c,h);d[c]=a;b(a,"create");void 0!=a.INTERNAL&&void 0!=a.INTERNAL
.getToken||z(a,{INTERNAL:{getUid:function(){return null},getToken:function(){return A.resolve(null)},addAuthTokenListener:function
(){},removeAuthTokenListener:function(){}}});return a}
```
- example usage
```shell
...

Include Firebase in your web application via a '<script>' tag:

'''
<script src="https://www.gstatic.com/firebasejs/3.7.3/firebase.js"></script>

<script>
var app = firebase.initializeApp({
  apiKey: '<your-api-key>',
  authDomain: '<your-auth-domain>',
  databaseURL: '<your-database-url>',
  storageBucket: '<your-storage-bucket>',
  messagingSenderId: '<your-sender-id>'
});
// ...
...
```

#### <a name="apidoc.element.firebase.serverAuth"></a>[function <span class="apidocSignatureSpan">firebase.</span>serverAuth (c)](#apidoc.element.firebase.serverAuth)
- description and source-code
```javascript
serverAuth = function (c){void 0===c&&(c=a());"function"!==typeof c[b]&&M("invalid-app-argument",{name:b});return c[b]()}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.INTERNAL"></a>[module firebase.INTERNAL](#apidoc.module.firebase.INTERNAL)

#### <a name="apidoc.element.firebase.INTERNAL.ErrorFactory"></a>[function <span class="apidocSignatureSpan">firebase.INTERNAL.</span>ErrorFactory (a, b, c)](#apidoc.element.firebase.INTERNAL.ErrorFactory)
- description and source-code
```javascript
ErrorFactory = function (a, b, c){this.X=a;this.Y=b;this.P=c;this.pattern=/\{\$([^}]+)}/g}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.INTERNAL.createFirebaseNamespace"></a>[function <span class="apidocSignatureSpan">firebase.INTERNAL.</span>createFirebaseNamespace ()](#apidoc.element.firebase.INTERNAL.createFirebaseNamespace)
- description and source-code
```javascript
function N(){function a(a){a=a||"[DEFAULT]";var b=d[a];void 0===b&&M("no-app",{name:a});return b}function b(a,b){Object.keys(e).
forEach(function(d){d=c(a,d);if(null!==d&&g[d])g[d](b,a)})}function c(a,b){if("serverAuth"===b)return null;var c=b;a=a.options;"
auth"===b&&(a.serviceAccount||a.credential)&&(c="serverAuth","serverAuth"in e||M("sa-not-supported"));return c}var d={},e={},g={},
h={__esModule:!0,initializeApp:function(a,c){void 0===c?c="[DEFAULT]":"string"===typeof c&&""!==c||M("bad-app-name",
{name:c+""});void 0!==d[c]&&M("duplicate-app",{name:c});a=new K(a,c,h);d[c]=a;b(a,"create");void 0!=a.INTERNAL&&void 0!=a.INTERNAL
.getToken||z(a,{INTERNAL:{getUid:function(){return null},getToken:function(){return A.resolve(null)},addAuthTokenListener:function
(){},removeAuthTokenListener:function(){}}});return a},app:a,apps:null,Promise:A,SDK_VERSION:"0.0.0",INTERNAL:{registerService:function
(b,c,d,n,Q){e[b]&&M("duplicate-service",{name:b});e[b]=Q?c:function(a,b){return c(a,b,"[DEFAULT]")};n&&(g[b]=
n);n=function(c){void 0===c&&(c=a());"function"!==typeof c[b]&&M("invalid-app-argument",{name:b});return c[b]()};void 0!==d&&z(n
,d);return h[b]=n},createFirebaseNamespace:N,extendNamespace:function(a){z(h,a)},createSubscribe:B,ErrorFactory:I,removeApp:function
(a){b(d[a],"delete");delete d[a]},factories:e,useAsService:c,Promise:void 0,deepExtend:z}};h["default"]=h;Object.defineProperty(
h,"apps",{get:function(){return Object.keys(d).map(function(a){return d[a]})}});a.App=K;return h}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.INTERNAL.createSubscribe"></a>[function <span class="apidocSignatureSpan">firebase.INTERNAL.</span>createSubscribe (a, b)](#apidoc.element.firebase.INTERNAL.createSubscribe)
- description and source-code
```javascript
function B(a, b){a=new C(a,b);return a.subscribe.bind(a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.INTERNAL.deepExtend"></a>[function <span class="apidocSignatureSpan">firebase.INTERNAL.</span>deepExtend (a, b)](#apidoc.element.firebase.INTERNAL.deepExtend)
- description and source-code
```javascript
function z(a, b){if(!(b instanceof Object))return b;switch(b.constructor){case Date:return new Date(b.getTime());case Object:void
 0===a&&(a={});break;case Array:a=[];break;default:return b}for(var c in b)b.hasOwnProperty(c)&&(a[c]=z(a[c],b[c]));return a}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.INTERNAL.extendNamespace"></a>[function <span class="apidocSignatureSpan">firebase.INTERNAL.</span>extendNamespace (a)](#apidoc.element.firebase.INTERNAL.extendNamespace)
- description and source-code
```javascript
extendNamespace = function (a){z(h,a)}
```
- example usage
```shell
...
 *
 *   firebase = require('firebase');
 */
var firebase = require('./app-node');
var Storage = require('dom-storage');
var XMLHttpRequest = require("xmlhttprequest").XMLHttpRequest;

firebase.INTERNAL.extendNamespace({
'INTERNAL': {
  'node': {
    'localStorage': new Storage(null, { strict: true }),
    'sessionStorage': new Storage(null, { strict: true }),
    'XMLHttpRequest': XMLHttpRequest
  }
}
...
```

#### <a name="apidoc.element.firebase.INTERNAL.registerService"></a>[function <span class="apidocSignatureSpan">firebase.INTERNAL.</span>registerService (b, c, d, n, Q)](#apidoc.element.firebase.INTERNAL.registerService)
- description and source-code
```javascript
registerService = function (b, c, d, n, Q){e[b]&&M("duplicate-service",{name:b});e[b]=Q?c:function(a,b){return c(a,b,"[DEFAULT]")};n&&(g[b]=
n);n=function(c){void 0===c&&(c=a());"function"!==typeof c[b]&&M("invalid-app-argument",{name:b});return c[b]()};void 0!==d&&z(n
,d);return h[b]=n}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.INTERNAL.removeApp"></a>[function <span class="apidocSignatureSpan">firebase.INTERNAL.</span>removeApp (a)](#apidoc.element.firebase.INTERNAL.removeApp)
- description and source-code
```javascript
removeApp = function (a){b(d[a],"delete");delete d[a]}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.INTERNAL.useAsService"></a>[function <span class="apidocSignatureSpan">firebase.INTERNAL.</span>useAsService (a, b)](#apidoc.element.firebase.INTERNAL.useAsService)
- description and source-code
```javascript
function c(a, b){if("serverAuth"===b)return null;var c=b;a=a.options;"auth"===b&&(a.serviceAccount||a.credential)&&(c="serverAuth
","serverAuth"in e||M("sa-not-supported"));return c}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.INTERNAL.ErrorFactory"></a>[module firebase.INTERNAL.ErrorFactory](#apidoc.module.firebase.INTERNAL.ErrorFactory)

#### <a name="apidoc.element.firebase.INTERNAL.ErrorFactory.ErrorFactory"></a>[function <span class="apidocSignatureSpan">firebase.INTERNAL.</span>ErrorFactory (a, b, c)](#apidoc.element.firebase.INTERNAL.ErrorFactory.ErrorFactory)
- description and source-code
```javascript
ErrorFactory = function (a, b, c){this.X=a;this.Y=b;this.P=c;this.pattern=/\{\$([^}]+)}/g}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.INTERNAL.ErrorFactory.prototype"></a>[module firebase.INTERNAL.ErrorFactory.prototype](#apidoc.module.firebase.INTERNAL.ErrorFactory.prototype)

#### <a name="apidoc.element.firebase.INTERNAL.ErrorFactory.prototype.create"></a>[function <span class="apidocSignatureSpan">firebase.INTERNAL.ErrorFactory.prototype.</span>create (a, b)](#apidoc.element.firebase.INTERNAL.ErrorFactory.prototype.create)
- description and source-code
```javascript
create = function (a, b){void 0===b&&(b={});var c=this.P[a];a=this.X+"/"+a;var c=void 0===c?"Error":c.replace(this.pattern,function(a,c){a
=b[c];return void 0!==a?a.toString():"<"+c+"?>"}),c=this.Y+": "+c+" ("+a+").",c=new J(a,c),d;for(d in b)b.hasOwnProperty(d)&&"_"!==
d.slice(-1)&&(c[d]=b[d]);return c}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.INTERNAL.factories"></a>[module firebase.INTERNAL.factories](#apidoc.module.firebase.INTERNAL.factories)

#### <a name="apidoc.element.firebase.INTERNAL.factories.auth"></a>[function <span class="apidocSignatureSpan">firebase.INTERNAL.factories.</span>auth (a, b)](#apidoc.element.firebase.INTERNAL.factories.auth)
- description and source-code
```javascript
auth = function (a, b){return c(a,b,"[DEFAULT]")}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.INTERNAL.factories.database"></a>[function <span class="apidocSignatureSpan">firebase.INTERNAL.factories.</span>database (a, b)](#apidoc.element.firebase.INTERNAL.factories.database)
- description and source-code
```javascript
database = function (a, b){return c(a,b,"[DEFAULT]")}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.INTERNAL.factories.serverAuth"></a>[function <span class="apidocSignatureSpan">firebase.INTERNAL.factories.</span>serverAuth (a, b)](#apidoc.element.firebase.INTERNAL.factories.serverAuth)
- description and source-code
```javascript
serverAuth = function (a, b){return c(a,b,"[DEFAULT]")}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.INTERNAL.node"></a>[module firebase.INTERNAL.node](#apidoc.module.firebase.INTERNAL.node)

#### <a name="apidoc.element.firebase.INTERNAL.node.XMLHttpRequest"></a>[function <span class="apidocSignatureSpan">firebase.INTERNAL.node.</span>XMLHttpRequest ()](#apidoc.element.firebase.INTERNAL.node.XMLHttpRequest)
- description and source-code
```javascript
XMLHttpRequest = function () {
  "use strict";

<span class="apidocCodeCommentSpan">  /**
   * Private variables
   */
</span>  var self = this;
  var http = require("http");
  var https = require("https");

  // Holds http.js objects
  var request;
  var response;

  // Request settings
  var settings = {};

  // Disable header blacklist.
  // Not part of XHR specs.
  var disableHeaderCheck = false;

  // Set some default headers
  var defaultHeaders = {
    "User-Agent": "node-XMLHttpRequest",
    "Accept": "*/*",
  };

  var headers = {};
  var headersCase = {};

  // These headers are not user setable.
  // The following are allowed but banned in the spec:
  // * user-agent
  var forbiddenRequestHeaders = [
    "accept-charset",
    "accept-encoding",
    "access-control-request-headers",
    "access-control-request-method",
    "connection",
    "content-length",
    "content-transfer-encoding",
    "cookie",
    "cookie2",
    "date",
    "expect",
    "host",
    "keep-alive",
    "origin",
    "referer",
    "te",
    "trailer",
    "transfer-encoding",
    "upgrade",
    "via"
  ];

  // These request methods are not allowed
  var forbiddenRequestMethods = [
    "TRACE",
    "TRACK",
    "CONNECT"
  ];

  // Send flag
  var sendFlag = false;
  // Error flag, used when errors occur or abort is called
  var errorFlag = false;

  // Event listeners
  var listeners = {};

  /**
   * Constants
   */

  this.UNSENT = 0;
  this.OPENED = 1;
  this.HEADERS_RECEIVED = 2;
  this.LOADING = 3;
  this.DONE = 4;

  /**
   * Public vars
   */

  // Current state
  this.readyState = this.UNSENT;

  // default ready state change handler in case one is not set or is set late
  this.onreadystatechange = null;

  // Result & response
  this.responseText = "";
  this.responseXML = "";
  this.status = null;
  this.statusText = null;

  // Whether cross-site Access-Control requests should be made using
  // credentials such as cookies or authorization headers
  this.withCredentials = false;

  /**
   * Private methods
   */

  /**
   * Check if the specified header is allowed.
   *
   * @param string header Header to validate
   * @return boolean False if not allowed, otherwise true
   */
  var isAllowedHttpHeader = function(header) {
    return disableHeaderCheck || (header && forbiddenRequestHeaders.indexOf(header.toLowerCase()) === -1);
  };

  /**
   * Check if the specified method is allowed.
   *
   * @param string method Request method to validate
   * @return boolean False if not allowed, otherwise true
   */
  var isAllowedHttpMethod = function(method) {
    return (method && forbiddenRequestMethods.indexOf(method) === -1);
  };

  /**
   * Public methods
   */

  /**
   * Open the connection. Currently supports local server requests.
   *
   * @param string method Connection method (eg GET, POST)
   * @param string url URL for the connection.
   * @param boolean async Asynchronous connection. Default is true.
   * @param string user Username for basic authentication (optional)
   * @param string password Password for basic authentication (optional)
   */
  this.open = function(method, url, async, user, password) {
    this.abort();
    errorFlag = false;

    // Check for valid request method
    if (!isAllowedHttpMethod(method)) {
      throw new Error("SecurityError: Request method not allowed");
    }

    settings = {
      "method": method,
      "url": url.toString(),
      "async": (typeof async !== "boolean" ? true : async),
      "user": user || null,
      "password": password || null
    };

    setState(this.OPENED);
  };

  /**
   * Disables or enables isAllowedHttpHeader() check the request. Enabled by default.
   * This does not conform to the W3C spec.
   *
   * @param boolean state Enable or disable header checking.
   */
  this.setDisableHeaderCheck = function(state) {
    disableHeaderCheck = state;
  };

  /**
   * Sets a header for the request or appends the value if one is already set.
   *
   * @param string header Header name
   * @param string value Header value
   */
  this.setRequestHeader = function(header, value) {
    if (this.readyState !== this.OPENED ...
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.User"></a>[module firebase.User](#apidoc.module.firebase.User)

#### <a name="apidoc.element.firebase.User.User"></a>[function <span class="apidocSignatureSpan">firebase.</span>User (a, b, c)](#apidoc.element.firebase.User.User)
- description and source-code
```javascript
User = function (a, b, c){this.$=[];this.j=a.apiKey;this.B=a.appName;this.v=a.authDomain||null;a=firebase.SDK_VERSION?yf(firebase.SDK_VERSION
):null;this.g=new R(this.j,null,a);this.ga=new Xi(this.g);cj(this,b.idToken);Zi(this.ga,b);M(this,"refreshToken",this.ga.W);dj(this
,c||{});te.call(this);this.tc=!1;this.v&&Bf()&&(this.m=Si(this.v,this.j,this.B));this.yc=[];this.ia=null;this.jb=ej(this);this.tb
=q(this.Vc,this)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.ag"></a>[function <span class="apidocSignatureSpan">firebase.User.</span>ag (a, c, f)](#apidoc.element.firebase.User.ag)
- description and source-code
```javascript
ag = function (a, c, f){for(var d=Array(arguments.length-2),e=2;e<arguments.length;e++)d[e-2]=arguments[e];return b.prototype[c].apply(
a,d)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.User.prototype"></a>[module firebase.User.prototype](#apidoc.module.firebase.User.prototype)

#### <a name="apidoc.element.firebase.User.prototype.Cd"></a>[function <span class="apidocSignatureSpan">firebase.User.prototype.</span>Cd (a, b)](#apidoc.element.firebase.User.prototype.Cd)
- description and source-code
```javascript
Cd = function (a, b){return"linkViaPopup"==a&&(this.aa||null)==b&&this.Z||"reauthViaPopup"==a&&(this.aa||null)==b&&this.Z||"linkViaRedirect
"==a&&(this.ua||null)==b||"reauthViaRedirect"==a&&(this.ua||null)==b?!0:!1}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.prototype.D"></a>[function <span class="apidocSignatureSpan">firebase.User.prototype.</span>D ()](#apidoc.element.firebase.User.prototype.D)
- description and source-code
```javascript
D = function (){var a={uid:this.uid,displayName:this.displayName,photoURL:this.photoURL,email:this.email,emailVerified:this.emailVerified
,isAnonymous:this.isAnonymous,providerData:[],apiKey:this.j,appName:this.B,authDomain:this.v,stsTokenManager:this.ga.D(),redirectEventId
:this.ua||null};w(this.providerData,function(b){a.providerData.push(Sf(b))});return a}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.prototype.Jd"></a>[function <span class="apidocSignatureSpan">firebase.User.prototype.</span>Jd (a, b)](#apidoc.element.firebase.User.prototype.Jd)
- description and source-code
```javascript
Jd = function (a, b){var c=this;this.C&&(this.C.cancel(),this.C=null);var d=null,e=this.getToken().then(function(d){return hg(c.g,{requestUri
:a,sessionId:b,idToken:d})}).then(function(a){d=vg(a);return xj(c,a)}).then(function(a){return{user:a,credential:d}});return this
.c(e)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.prototype.Kd"></a>[function <span class="apidocSignatureSpan">firebase.User.prototype.</span>Kd (a, b)](#apidoc.element.firebase.User.prototype.Kd)
- description and source-code
```javascript
Kd = function (a, b){var c=this;this.C&&(this.C.cancel(),this.C=null);var d=null,e=C().then(function(){return fg(c.g,{requestUri:a,sessionId
:b})}).then(function(a){d=vg(a);var b=dg(a.idToken);if(!b||c.uid!=b.Xd)throw new N("user-mismatch");sj(c,a);c.ia=null;return c.reload
()}).then(function(){return{user:c,credential:d}});return this.c(e,!0)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.prototype.La"></a>[function <span class="apidocSignatureSpan">firebase.User.prototype.</span>La ()](#apidoc.element.firebase.User.prototype.La)
- description and source-code
```javascript
La = function (){this.dispatchEvent(new bj("tokenChanged"))}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.prototype.Sa"></a>[function <span class="apidocSignatureSpan">firebase.User.prototype.</span>Sa (a, b, c, d)](#apidoc.element.firebase.User.prototype.Sa)
- description and source-code
```javascript
Sa = function (a, b, c, d){"linkViaPopup"!=a&&"reauthViaPopup"!=a||d!=(this.aa||null)||(c&&this.Na?this.Na(c):b&&!c&&this.Z&&this.Z(b),this
.C&&(this.C.cancel(),this.C=null),delete this.Z,delete this.Na)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.prototype.Vc"></a>[function <span class="apidocSignatureSpan">firebase.User.prototype.</span>Vc ()](#apidoc.element.firebase.User.prototype.Vc)
- description and source-code
```javascript
Vc = function (){this.jb.hb&&(this.jb.stop(),this.jb.start())}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.prototype.c"></a>[function <span class="apidocSignatureSpan">firebase.User.prototype.</span>c (a, b)](#apidoc.element.firebase.User.prototype.c)
- description and source-code
```javascript
c = function (a, b){var c=this,d=Ej(this,a,b);this.$.push(d);Rd(d,function(){Ka(c.$,d)});return d}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.prototype.cc"></a>[function <span class="apidocSignatureSpan">firebase.User.prototype.</span>cc ()](#apidoc.element.firebase.User.prototype.cc)
- description and source-code
```javascript
cc = function (){return Af(this.uid+":::")}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.prototype.constructor"></a>[function <span class="apidocSignatureSpan">firebase.User.prototype.</span>constructor (a, b, c)](#apidoc.element.firebase.User.prototype.constructor)
- description and source-code
```javascript
constructor = function (a, b, c){this.$=[];this.j=a.apiKey;this.B=a.appName;this.v=a.authDomain||null;a=firebase.SDK_VERSION?yf(firebase.SDK_VERSION
):null;this.g=new R(this.j,null,a);this.ga=new Xi(this.g);cj(this,b.idToken);Zi(this.ga,b);M(this,"refreshToken",this.ga.W);dj(this
,c||{});te.call(this);this.tc=!1;this.v&&Bf()&&(this.m=Si(this.v,this.j,this.B));this.yc=[];this.ia=null;this.jb=ej(this);this.tb
=q(this.Vc,this)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.prototype.copy"></a>[function <span class="apidocSignatureSpan">firebase.User.prototype.</span>copy (a)](#apidoc.element.firebase.User.prototype.copy)
- description and source-code
```javascript
copy = function (a){var b=this;b!=a&&(Rf(this,{uid:a.uid,displayName:a.displayName,photoURL:a.photoURL,email:a.email,emailVerified:a.emailVerified
,isAnonymous:a.isAnonymous,providerData:[]}),w(a.providerData,function(a){oj(b,a)}),this.ga=a.ga,M(this,"refreshToken",this.ga.W
))}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.prototype.delete"></a>[function <span class="apidocSignatureSpan">firebase.User.prototype.</span>delete ()](#apidoc.element.firebase.User.prototype.delete)
- description and source-code
```javascript
delete = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.prototype.getToken"></a>[function <span class="apidocSignatureSpan">firebase.User.prototype.</span>getToken ()](#apidoc.element.firebase.User.prototype.getToken)
- description and source-code
```javascript
getToken = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.prototype.link"></a>[function <span class="apidocSignatureSpan">firebase.User.prototype.</span>link ()](#apidoc.element.firebase.User.prototype.link)
- description and source-code
```javascript
link = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.prototype.linkWithPopup"></a>[function <span class="apidocSignatureSpan">firebase.User.prototype.</span>linkWithPopup ()](#apidoc.element.firebase.User.prototype.linkWithPopup)
- description and source-code
```javascript
linkWithPopup = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.prototype.linkWithRedirect"></a>[function <span class="apidocSignatureSpan">firebase.User.prototype.</span>linkWithRedirect ()](#apidoc.element.firebase.User.prototype.linkWithRedirect)
- description and source-code
```javascript
linkWithRedirect = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.prototype.reauthenticate"></a>[function <span class="apidocSignatureSpan">firebase.User.prototype.</span>reauthenticate ()](#apidoc.element.firebase.User.prototype.reauthenticate)
- description and source-code
```javascript
reauthenticate = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.prototype.reload"></a>[function <span class="apidocSignatureSpan">firebase.User.prototype.</span>reload ()](#apidoc.element.firebase.User.prototype.reload)
- description and source-code
```javascript
reload = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.prototype.sendEmailVerification"></a>[function <span class="apidocSignatureSpan">firebase.User.prototype.</span>sendEmailVerification ()](#apidoc.element.firebase.User.prototype.sendEmailVerification)
- description and source-code
```javascript
sendEmailVerification = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.prototype.sf"></a>[function <span class="apidocSignatureSpan">firebase.User.prototype.</span>sf (a)](#apidoc.element.firebase.User.prototype.sf)
- description and source-code
```javascript
sf = function (a){a=a.users;if(!a||!a.length)throw new N("internal-error");a=a[0];dj(this,{uid:a.localId,displayName:a.displayName,photoURL
:a.photoUrl,email:a.email,emailVerified:!!a.emailVerified});for(var b=tj(a),c=0;c<b.length;c++)oj(this,b[c]);pj(this,"isAnonymous
",!(this.email&&a.passwordHash)&&!(this.providerData&&this.providerData.length))}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">firebase.User.prototype.</span>toJSON ()](#apidoc.element.firebase.User.prototype.toJSON)
- description and source-code
```javascript
toJSON = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.prototype.unlink"></a>[function <span class="apidocSignatureSpan">firebase.User.prototype.</span>unlink ()](#apidoc.element.firebase.User.prototype.unlink)
- description and source-code
```javascript
unlink = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.prototype.updateEmail"></a>[function <span class="apidocSignatureSpan">firebase.User.prototype.</span>updateEmail ()](#apidoc.element.firebase.User.prototype.updateEmail)
- description and source-code
```javascript
updateEmail = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.prototype.updatePassword"></a>[function <span class="apidocSignatureSpan">firebase.User.prototype.</span>updatePassword ()](#apidoc.element.firebase.User.prototype.updatePassword)
- description and source-code
```javascript
updatePassword = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.prototype.updateProfile"></a>[function <span class="apidocSignatureSpan">firebase.User.prototype.</span>updateProfile ()](#apidoc.element.firebase.User.prototype.updateProfile)
- description and source-code
```javascript
updateProfile = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.prototype.xb"></a>[function <span class="apidocSignatureSpan">firebase.User.prototype.</span>xb (a, b)](#apidoc.element.firebase.User.prototype.xb)
- description and source-code
```javascript
xb = function (a, b){return"linkViaPopup"==a&&b==(this.aa||null)?q(this.Jd,this):"reauthViaPopup"==a&&b==(this.aa||null)?q(this.Kd,this
):"linkViaRedirect"==a&&(this.ua||null)==b?q(this.Jd,this):"reauthViaRedirect"==a&&(this.ua||null)==b?q(this.Kd,this):null}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.User.ud"></a>[module firebase.User.ud](#apidoc.module.firebase.User.ud)

#### <a name="apidoc.element.firebase.User.ud.Sc"></a>[function <span class="apidocSignatureSpan">firebase.User.ud.</span>Sc (a, b, c, d)](#apidoc.element.firebase.User.ud.Sc)
- description and source-code
```javascript
Sc = function (a, b, c, d){return this.da.Sc(String(a),b,c,d)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.ud.addEventListener"></a>[function <span class="apidocSignatureSpan">firebase.User.ud.</span>addEventListener (a, b, c, d)](#apidoc.element.firebase.User.ud.addEventListener)
- description and source-code
```javascript
addEventListener = function (a, b, c, d){Oc(this,a,b,c,d)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.ud.constructor"></a>[function <span class="apidocSignatureSpan">firebase.User.ud.</span>constructor ()](#apidoc.element.firebase.User.ud.constructor)
- description and source-code
```javascript
constructor = function (){Bc.call(this);this.da=new Ic(this);this.Ce=this;this.ed=null}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.ud.dispatchEvent"></a>[function <span class="apidocSignatureSpan">firebase.User.ud.</span>dispatchEvent (a)](#apidoc.element.firebase.User.ud.dispatchEvent)
- description and source-code
```javascript
dispatchEvent = function (a){ue(this);var b,c=this.ed;if(c){b=[];for(var d=1;c;c=c.ed)b.push(c),v(1E3>++d,"infinite loop")}c=this.Ce;d=a.type||a
;if(m(a))a=new Cc(a,c);else if(a instanceof Cc)a.target=a.target||c;else{var e=a;a=new Cc(d,c);Va(a,e)}var e=!0,f;if(b)for(var g
=b.length-1;!a.kb&&0<=g;g--)f=a.currentTarget=b[g],e=ve(f,d,!0,a)&&e;a.kb||(f=a.currentTarget=c,e=ve(f,d,!0,a)&&e,a.kb||(e=ve(f,
d,!1,a)&&e));if(b)for(g=0;!a.kb&&g<b.length;g++)f=a.currentTarget=b[g],e=ve(f,d,!1,a)&&e;return e}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.ud.listen"></a>[function <span class="apidocSignatureSpan">firebase.User.ud.</span>listen (a, b, c, d)](#apidoc.element.firebase.User.ud.listen)
- description and source-code
```javascript
listen = function (a, b, c, d){ue(this);return this.da.add(String(a),b,!1,c,d)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.User.ud.removeEventListener"></a>[function <span class="apidocSignatureSpan">firebase.User.ud.</span>removeEventListener (a, b, c, d)](#apidoc.element.firebase.User.ud.removeEventListener)
- description and source-code
```javascript
removeEventListener = function (a, b, c, d){Xc(this,a,b,c,d)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.app"></a>[module firebase.app](#apidoc.module.firebase.app)

#### <a name="apidoc.element.firebase.app.app"></a>[function <span class="apidocSignatureSpan">firebase.</span>app (a)](#apidoc.element.firebase.app.app)
- description and source-code
```javascript
function a(a){a=a||"[DEFAULT]";var b=d[a];void 0===b&&M("no-app",{name:a});return b}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.app.App"></a>[function <span class="apidocSignatureSpan">firebase.app.</span>App (a, b, c)](#apidoc.element.firebase.app.App)
- description and source-code
```javascript
App = function (a, b, c){var d=this;this.F=c;this.H=!1;this.b={};this.l=b;this.s=z(void 0,a);a="serviceAccount"in this.s;("credential"in
 this.s||a)&&"undefined"!==typeof console&&console.log("The '"+(a?"serviceAccount":"credential")+"' property specified in the first
 argument to initializeApp() is deprecated and will be removed in the next major version. You should instead use the 'firebase-admin
' package. See https://firebase.google.com/docs/admin/setup for details on how to get started.");Object.keys(c.INTERNAL.factories
).forEach(function(a){var b=
c.INTERNAL.useAsService(d,a);null!==b&&(b=d.U.bind(d,b),d[a]=b)})}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.app.App"></a>[module firebase.app.App](#apidoc.module.firebase.app.App)

#### <a name="apidoc.element.firebase.app.App.App"></a>[function <span class="apidocSignatureSpan">firebase.app.</span>App (a, b, c)](#apidoc.element.firebase.app.App.App)
- description and source-code
```javascript
App = function (a, b, c){var d=this;this.F=c;this.H=!1;this.b={};this.l=b;this.s=z(void 0,a);a="serviceAccount"in this.s;("credential"in
 this.s||a)&&"undefined"!==typeof console&&console.log("The '"+(a?"serviceAccount":"credential")+"' property specified in the first
 argument to initializeApp() is deprecated and will be removed in the next major version. You should instead use the 'firebase-admin
' package. See https://firebase.google.com/docs/admin/setup for details on how to get started.");Object.keys(c.INTERNAL.factories
).forEach(function(a){var b=
c.INTERNAL.useAsService(d,a);null!==b&&(b=d.U.bind(d,b),d[a]=b)})}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.app.App.prototype"></a>[module firebase.app.App.prototype](#apidoc.module.firebase.app.App.prototype)

#### <a name="apidoc.element.firebase.app.App.prototype.T"></a>[function <span class="apidocSignatureSpan">firebase.app.App.prototype.</span>T (a)](#apidoc.element.firebase.app.App.prototype.T)
- description and source-code
```javascript
T = function (a){z(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.app.App.prototype.U"></a>[function <span class="apidocSignatureSpan">firebase.app.App.prototype.</span>U (a, b)](#apidoc.element.firebase.app.App.prototype.U)
- description and source-code
```javascript
U = function (a, b){L(this);"undefined"===typeof this.b[a]&&(this.b[a]={});var c=b||"[DEFAULT]";return"undefined"===typeof this.b[a][
c]?(b=this.F.INTERNAL.factories[a](this,this.T.bind(this),b),this.b[a][c]=b):this.b[a][c]}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.app.App.prototype.delete"></a>[function <span class="apidocSignatureSpan">firebase.app.App.prototype.</span>delete ()](#apidoc.element.firebase.app.App.prototype.delete)
- description and source-code
```javascript
delete = function (){var a=this;return(new A(function(b){L(a);b()})).then(function(){a.F.INTERNAL.removeApp(a.l);var b=[];Object.keys(a.b
).forEach(function(c){Object.keys(a.b[c]).forEach(function(d){b.push(a.b[c][d])})});return A.all(b.map(function(a){return a.INTERNAL
.delete()}))}).then(function(){a.H=!0;a.b={}})}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.auth"></a>[module firebase.auth](#apidoc.module.firebase.auth)

#### <a name="apidoc.element.firebase.auth.auth"></a>[function <span class="apidocSignatureSpan">firebase.</span>auth (c)](#apidoc.element.firebase.auth.auth)
- description and source-code
```javascript
auth = function (c){void 0===c&&(c=a());"function"!==typeof c[b]&&M("invalid-app-argument",{name:b});return c[b]()}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth"></a>[function <span class="apidocSignatureSpan">firebase.auth.</span>Auth (a)](#apidoc.element.firebase.auth.Auth)
- description and source-code
```javascript
Auth = function (a){this.Za=!1;M(this,"app",a);if(X(this).options&&X(this).options.apiKey)a=firebase.SDK_VERSION?yf(firebase.SDK_VERSION
):null,this.g=new R(X(this).options&&X(this).options.apiKey,null,a);else throw new N("invalid-api-key");this.$=[];this.Aa=[];this
.pf=firebase.INTERNAL.createSubscribe(q(this.cf,this));Oj(this,null);this.pa=new Jj(X(this).options.apiKey+":"+X(this).name);this
.mb=new Hj(X(this).options.apiKey+":"+X(this).name);this.Xb=this.c(Pj(this));this.va=this.c(Qj(this));this.ad=
!1;this.Tc=q(this.Of,this);this.ue=q(this.cb,this);this.tb=q(this.Vc,this);this.se=q(this.Ye,this);this.te=q(this.Ze,this);Rj(this
);this.INTERNAL={};this.INTERNAL["delete"]=q(this["delete"],this);this.Fa=0}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.EmailAuthProvider"></a>[function <span class="apidocSignatureSpan">firebase.auth.</span>EmailAuthProvider ()](#apidoc.element.firebase.auth.EmailAuthProvider)
- description and source-code
```javascript
EmailAuthProvider = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Error"></a>[function <span class="apidocSignatureSpan">firebase.auth.</span>Error (a, b)](#apidoc.element.firebase.auth.Error)
- description and source-code
```javascript
Error = function (a, b){this.code="auth/"+a;this.message=b||Zf[a]||""}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.FacebookAuthProvider"></a>[function <span class="apidocSignatureSpan">firebase.auth.</span>FacebookAuthProvider ()](#apidoc.element.firebase.auth.FacebookAuthProvider)
- description and source-code
```javascript
FacebookAuthProvider = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.GithubAuthProvider"></a>[function <span class="apidocSignatureSpan">firebase.auth.</span>GithubAuthProvider ()](#apidoc.element.firebase.auth.GithubAuthProvider)
- description and source-code
```javascript
GithubAuthProvider = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.GoogleAuthProvider"></a>[function <span class="apidocSignatureSpan">firebase.auth.</span>GoogleAuthProvider ()](#apidoc.element.firebase.auth.GoogleAuthProvider)
- description and source-code
```javascript
GoogleAuthProvider = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.TwitterAuthProvider"></a>[function <span class="apidocSignatureSpan">firebase.auth.</span>TwitterAuthProvider ()](#apidoc.element.firebase.auth.TwitterAuthProvider)
- description and source-code
```javascript
TwitterAuthProvider = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.auth.Auth"></a>[module firebase.auth.Auth](#apidoc.module.firebase.auth.Auth)

#### <a name="apidoc.element.firebase.auth.Auth.Auth"></a>[function <span class="apidocSignatureSpan">firebase.auth.</span>Auth (a)](#apidoc.element.firebase.auth.Auth.Auth)
- description and source-code
```javascript
Auth = function (a){this.Za=!1;M(this,"app",a);if(X(this).options&&X(this).options.apiKey)a=firebase.SDK_VERSION?yf(firebase.SDK_VERSION
):null,this.g=new R(X(this).options&&X(this).options.apiKey,null,a);else throw new N("invalid-api-key");this.$=[];this.Aa=[];this
.pf=firebase.INTERNAL.createSubscribe(q(this.cf,this));Oj(this,null);this.pa=new Jj(X(this).options.apiKey+":"+X(this).name);this
.mb=new Hj(X(this).options.apiKey+":"+X(this).name);this.Xb=this.c(Pj(this));this.va=this.c(Qj(this));this.ad=
!1;this.Tc=q(this.Of,this);this.ue=q(this.cb,this);this.tb=q(this.Vc,this);this.se=q(this.Ye,this);this.te=q(this.Ze,this);Rj(this
);this.INTERNAL={};this.INTERNAL["delete"]=q(this["delete"],this);this.Fa=0}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.auth.Auth.prototype"></a>[module firebase.auth.Auth.prototype](#apidoc.module.firebase.auth.Auth.prototype)

#### <a name="apidoc.element.firebase.auth.Auth.prototype.Cd"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>Cd (a, b)](#apidoc.element.firebase.auth.Auth.prototype.Cd)
- description and source-code
```javascript
Cd = function (a, b){switch(a){case "unknown":case "signInViaRedirect":return!0;case "signInViaPopup":return this.aa==b&&!!this.Z;default
:return!1}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.De"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>De (a)](#apidoc.element.firebase.auth.Auth.prototype.De)
- description and source-code
```javascript
De = function (a){this.addAuthTokenListener(a);this.Fa++;0<this.Fa&&Z(this)&&fj(Z(this))}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.La"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>La ()](#apidoc.element.firebase.auth.Auth.prototype.La)
- description and source-code
```javascript
La = function (){if(this.ad)for(var a=0;a<this.Aa.length;a++)if(this.Aa[a])this.Aa[a](Z(this)&&Z(this)._lat||null)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.Ne"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>Ne (a, b)](#apidoc.element.firebase.auth.Auth.prototype.Ne)
- description and source-code
```javascript
Ne = function (a, b){var c=this;a={requestUri:a,sessionId:b};this.C&&(this.C.cancel(),this.C=null);var d=null,e=fg(c.g,a).then(function
(a){d=vg(a);return a});a=c.Xb.then(function(){return e}).then(function(a){return Tj(c,a)}).then(function(){return{user:Z(c),credential
:d}});return this.c(a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.Of"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>Of ()](#apidoc.element.firebase.auth.Auth.prototype.Of)
- description and source-code
```javascript
Of = function (){var a=this;return Nj(this.pa,X(this).options.authDomain).then(function(b){if(!a.Za){var c;if(c=Z(a)&&b){c=Z(a).uid;var
 d=b.uid;c=void 0===c||null===c||""===c||void 0===d||null===d||""===d?!1:c==d}if(c)return Z(a).copy(b),Z(a).getToken();if(Z(a)||
b)Oj(a,b),b&&(jj(b),b.Qa=a.mb),a.m&&a.m.subscribe(a),a.La()}})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.Sa"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>Sa (a, b, c, d)](#apidoc.element.firebase.auth.Auth.prototype.Sa)
- description and source-code
```javascript
Sa = function (a, b, c, d){"signInViaPopup"==a&&this.aa==d&&(c&&this.Na?this.Na(c):b&&!c&&this.Z&&this.Z(b),this.C&&(this.C.cancel(),this
.C=null),delete this.Z,delete this.Na)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.Vc"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>Vc ()](#apidoc.element.firebase.auth.Auth.prototype.Vc)
- description and source-code
```javascript
Vc = function (){this.La();this.cb(Z(this))}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.Ye"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>Ye ()](#apidoc.element.firebase.auth.Auth.prototype.Ye)
- description and source-code
```javascript
Ye = function (){this.signOut()}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.Ze"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>Ze ()](#apidoc.element.firebase.auth.Auth.prototype.Ze)
- description and source-code
```javascript
Ze = function (){this.signOut()}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.addAuthTokenListener"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>addAuthTokenListener (a)](#apidoc.element.firebase.auth.Auth.prototype.addAuthTokenListener)
- description and source-code
```javascript
addAuthTokenListener = function (a){var b=this;this.Aa.push(a);this.c(this.va.then(function(){b.Za||Ia(b.Aa,a)&&a(Z(b)&&Z(b)._lat||null)}))}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.applyActionCode"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>applyActionCode ()](#apidoc.element.firebase.auth.Auth.prototype.applyActionCode)
- description and source-code
```javascript
applyActionCode = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.c"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>c (a)](#apidoc.element.firebase.auth.Auth.prototype.c)
- description and source-code
```javascript
c = function (a){var b=this;this.$.push(a);Rd(a,function(){Ka(b.$,a)});return a}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.cb"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>cb (a)](#apidoc.element.firebase.auth.Auth.prototype.cb)
- description and source-code
```javascript
cb = function (a){return Lj(this.pa,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.cc"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>cc ()](#apidoc.element.firebase.auth.Auth.prototype.cc)
- description and source-code
```javascript
cc = function (){return Af()}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.cf"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>cf (a)](#apidoc.element.firebase.auth.Auth.prototype.cf)
- description and source-code
```javascript
cf = function (a){var b=this;this.addAuthTokenListener(function(){a.next(Z(b))})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.checkActionCode"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>checkActionCode ()](#apidoc.element.firebase.auth.Auth.prototype.checkActionCode)
- description and source-code
```javascript
checkActionCode = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.confirmPasswordReset"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>confirmPasswordReset ()](#apidoc.element.firebase.auth.Auth.prototype.confirmPasswordReset)
- description and source-code
```javascript
confirmPasswordReset = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.createUserWithEmailAndPassword"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>createUserWithEmailAndPassword ()](#apidoc.element.firebase.auth.Auth.prototype.createUserWithEmailAndPassword)
- description and source-code
```javascript
createUserWithEmailAndPassword = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.delete"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>delete ()](#apidoc.element.firebase.auth.Auth.prototype.delete)
- description and source-code
```javascript
delete = function (){this.Za=!0;for(var a=0;a<this.$.length;a++)this.$[a].cancel("app-deleted");this.$=[];this.pa&&(a=this.pa,a.i.removeListener
(Kj,a.u,this.Tc));this.m&&this.m.unsubscribe(this);return firebase.Promise.resolve()}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.fetchProvidersForEmail"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>fetchProvidersForEmail ()](#apidoc.element.firebase.auth.Auth.prototype.fetchProvidersForEmail)
- description and source-code
```javascript
fetchProvidersForEmail = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.getRedirectResult"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>getRedirectResult ()](#apidoc.element.firebase.auth.Auth.prototype.getRedirectResult)
- description and source-code
```javascript
getRedirectResult = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.getToken"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>getToken (a)](#apidoc.element.firebase.auth.Auth.prototype.getToken)
- description and source-code
```javascript
getToken = function (a){var b=this,c=this.va.then(function(){return Z(b)?Z(b).getToken(a).then(function(a){return{accessToken:a}}):null});return
 this.c(c)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.getUid"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>getUid ()](#apidoc.element.firebase.auth.Auth.prototype.getUid)
- description and source-code
```javascript
getUid = function (){return Z(this)&&Z(this).uid||null}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.onAuthStateChanged"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>onAuthStateChanged ()](#apidoc.element.firebase.auth.Auth.prototype.onAuthStateChanged)
- description and source-code
```javascript
onAuthStateChanged = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.removeAuthTokenListener"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>removeAuthTokenListener (a)](#apidoc.element.firebase.auth.Auth.prototype.removeAuthTokenListener)
- description and source-code
```javascript
removeAuthTokenListener = function (a){La(this.Aa,function(b){return b==a})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.sendPasswordResetEmail"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>sendPasswordResetEmail ()](#apidoc.element.firebase.auth.Auth.prototype.sendPasswordResetEmail)
- description and source-code
```javascript
sendPasswordResetEmail = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.signInAnonymously"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>signInAnonymously ()](#apidoc.element.firebase.auth.Auth.prototype.signInAnonymously)
- description and source-code
```javascript
signInAnonymously = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.signInWithCredential"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>signInWithCredential ()](#apidoc.element.firebase.auth.Auth.prototype.signInWithCredential)
- description and source-code
```javascript
signInWithCredential = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.signInWithCustomToken"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>signInWithCustomToken ()](#apidoc.element.firebase.auth.Auth.prototype.signInWithCustomToken)
- description and source-code
```javascript
signInWithCustomToken = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.signInWithEmailAndPassword"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>signInWithEmailAndPassword ()](#apidoc.element.firebase.auth.Auth.prototype.signInWithEmailAndPassword)
- description and source-code
```javascript
signInWithEmailAndPassword = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.signInWithPopup"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>signInWithPopup ()](#apidoc.element.firebase.auth.Auth.prototype.signInWithPopup)
- description and source-code
```javascript
signInWithPopup = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.signInWithRedirect"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>signInWithRedirect ()](#apidoc.element.firebase.auth.Auth.prototype.signInWithRedirect)
- description and source-code
```javascript
signInWithRedirect = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.signOut"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>signOut ()](#apidoc.element.firebase.auth.Auth.prototype.signOut)
- description and source-code
```javascript
signOut = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>toJSON ()](#apidoc.element.firebase.auth.Auth.prototype.toJSON)
- description and source-code
```javascript
toJSON = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.verifyPasswordResetCode"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>verifyPasswordResetCode ()](#apidoc.element.firebase.auth.Auth.prototype.verifyPasswordResetCode)
- description and source-code
```javascript
verifyPasswordResetCode = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.xb"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>xb (a, b)](#apidoc.element.firebase.auth.Auth.prototype.xb)
- description and source-code
```javascript
xb = function (a, b){return"signInViaRedirect"==a||"signInViaPopup"==a&&this.aa==b&&this.Z?q(this.Ne,this):null}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Auth.prototype.yf"></a>[function <span class="apidocSignatureSpan">firebase.auth.Auth.prototype.</span>yf (a)](#apidoc.element.firebase.auth.Auth.prototype.yf)
- description and source-code
```javascript
yf = function (a){var b=this;w(this.Aa,function(c){c==a&&b.Fa--});0>this.Fa&&(this.Fa=0);0==this.Fa&&Z(this)&&gj(Z(this));this.removeAuthTokenListener
(a)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.auth.EmailAuthProvider"></a>[module firebase.auth.EmailAuthProvider](#apidoc.module.firebase.auth.EmailAuthProvider)

#### <a name="apidoc.element.firebase.auth.EmailAuthProvider.EmailAuthProvider"></a>[function <span class="apidocSignatureSpan">firebase.auth.</span>EmailAuthProvider ()](#apidoc.element.firebase.auth.EmailAuthProvider.EmailAuthProvider)
- description and source-code
```javascript
EmailAuthProvider = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.EmailAuthProvider.credential"></a>[function <span class="apidocSignatureSpan">firebase.auth.EmailAuthProvider.</span>credential ()](#apidoc.element.firebase.auth.EmailAuthProvider.credential)
- description and source-code
```javascript
credential = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.auth.Error"></a>[module firebase.auth.Error](#apidoc.module.firebase.auth.Error)

#### <a name="apidoc.element.firebase.auth.Error.Error"></a>[function <span class="apidocSignatureSpan">firebase.auth.</span>Error (a, b)](#apidoc.element.firebase.auth.Error.Error)
- description and source-code
```javascript
Error = function (a, b){this.code="auth/"+a;this.message=b||Zf[a]||""}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Error.ag"></a>[function <span class="apidocSignatureSpan">firebase.auth.Error.</span>ag (a, c, f)](#apidoc.element.firebase.auth.Error.ag)
- description and source-code
```javascript
ag = function (a, c, f){for(var d=Array(arguments.length-2),e=2;e<arguments.length;e++)d[e-2]=arguments[e];return b.prototype[c].apply(
a,d)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.auth.Error.prototype"></a>[module firebase.auth.Error.prototype](#apidoc.module.firebase.auth.Error.prototype)

#### <a name="apidoc.element.firebase.auth.Error.prototype.D"></a>[function <span class="apidocSignatureSpan">firebase.auth.Error.prototype.</span>D ()](#apidoc.element.firebase.auth.Error.prototype.D)
- description and source-code
```javascript
D = function (){return{code:this.code,message:this.message}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Error.prototype.constructor"></a>[function <span class="apidocSignatureSpan">firebase.auth.Error.prototype.</span>constructor (a, b)](#apidoc.element.firebase.auth.Error.prototype.constructor)
- description and source-code
```javascript
constructor = function (a, b){this.code="auth/"+a;this.message=b||Zf[a]||""}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.Error.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">firebase.auth.Error.prototype.</span>toJSON ()](#apidoc.element.firebase.auth.Error.prototype.toJSON)
- description and source-code
```javascript
toJSON = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.auth.FacebookAuthProvider"></a>[module firebase.auth.FacebookAuthProvider](#apidoc.module.firebase.auth.FacebookAuthProvider)

#### <a name="apidoc.element.firebase.auth.FacebookAuthProvider.FacebookAuthProvider"></a>[function <span class="apidocSignatureSpan">firebase.auth.</span>FacebookAuthProvider ()](#apidoc.element.firebase.auth.FacebookAuthProvider.FacebookAuthProvider)
- description and source-code
```javascript
FacebookAuthProvider = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.FacebookAuthProvider.ag"></a>[function <span class="apidocSignatureSpan">firebase.auth.FacebookAuthProvider.</span>ag (a, c, f)](#apidoc.element.firebase.auth.FacebookAuthProvider.ag)
- description and source-code
```javascript
ag = function (a, c, f){for(var d=Array(arguments.length-2),e=2;e<arguments.length;e++)d[e-2]=arguments[e];return b.prototype[c].apply(
a,d)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.FacebookAuthProvider.credential"></a>[function <span class="apidocSignatureSpan">firebase.auth.FacebookAuthProvider.</span>credential ()](#apidoc.element.firebase.auth.FacebookAuthProvider.credential)
- description and source-code
```javascript
credential = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.auth.FacebookAuthProvider.prototype"></a>[module firebase.auth.FacebookAuthProvider.prototype](#apidoc.module.firebase.auth.FacebookAuthProvider.prototype)

#### <a name="apidoc.element.firebase.auth.FacebookAuthProvider.prototype.Nd"></a>[function <span class="apidocSignatureSpan">firebase.auth.FacebookAuthProvider.prototype.</span>Nd ()](#apidoc.element.firebase.auth.FacebookAuthProvider.prototype.Nd)
- description and source-code
```javascript
Nd = function (){return Na(this.od)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.FacebookAuthProvider.prototype.addScope"></a>[function <span class="apidocSignatureSpan">firebase.auth.FacebookAuthProvider.prototype.</span>addScope ()](#apidoc.element.firebase.auth.FacebookAuthProvider.prototype.addScope)
- description and source-code
```javascript
addScope = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.FacebookAuthProvider.prototype.credential"></a>[function <span class="apidocSignatureSpan">firebase.auth.FacebookAuthProvider.prototype.</span>credential (a, b)](#apidoc.element.firebase.auth.FacebookAuthProvider.prototype.credential)
- description and source-code
```javascript
credential = function (a, b){if(!a&&!b)throw new N("argument-error","credential failed: must provide the ID token and/or the access token.");return
 new eg(this.providerId,{idToken:a||null,accessToken:b||null})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.FacebookAuthProvider.prototype.setCustomParameters"></a>[function <span class="apidocSignatureSpan">firebase.auth.FacebookAuthProvider.prototype.</span>setCustomParameters ()](#apidoc.element.firebase.auth.FacebookAuthProvider.prototype.setCustomParameters)
- description and source-code
```javascript
setCustomParameters = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.auth.GithubAuthProvider"></a>[module firebase.auth.GithubAuthProvider](#apidoc.module.firebase.auth.GithubAuthProvider)

#### <a name="apidoc.element.firebase.auth.GithubAuthProvider.GithubAuthProvider"></a>[function <span class="apidocSignatureSpan">firebase.auth.</span>GithubAuthProvider ()](#apidoc.element.firebase.auth.GithubAuthProvider.GithubAuthProvider)
- description and source-code
```javascript
GithubAuthProvider = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.GithubAuthProvider.ag"></a>[function <span class="apidocSignatureSpan">firebase.auth.GithubAuthProvider.</span>ag (a, c, f)](#apidoc.element.firebase.auth.GithubAuthProvider.ag)
- description and source-code
```javascript
ag = function (a, c, f){for(var d=Array(arguments.length-2),e=2;e<arguments.length;e++)d[e-2]=arguments[e];return b.prototype[c].apply(
a,d)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.GithubAuthProvider.credential"></a>[function <span class="apidocSignatureSpan">firebase.auth.GithubAuthProvider.</span>credential ()](#apidoc.element.firebase.auth.GithubAuthProvider.credential)
- description and source-code
```javascript
credential = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.auth.GithubAuthProvider.prototype"></a>[module firebase.auth.GithubAuthProvider.prototype](#apidoc.module.firebase.auth.GithubAuthProvider.prototype)

#### <a name="apidoc.element.firebase.auth.GithubAuthProvider.prototype.Nd"></a>[function <span class="apidocSignatureSpan">firebase.auth.GithubAuthProvider.prototype.</span>Nd ()](#apidoc.element.firebase.auth.GithubAuthProvider.prototype.Nd)
- description and source-code
```javascript
Nd = function (){return Na(this.od)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.GithubAuthProvider.prototype.addScope"></a>[function <span class="apidocSignatureSpan">firebase.auth.GithubAuthProvider.prototype.</span>addScope ()](#apidoc.element.firebase.auth.GithubAuthProvider.prototype.addScope)
- description and source-code
```javascript
addScope = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.GithubAuthProvider.prototype.credential"></a>[function <span class="apidocSignatureSpan">firebase.auth.GithubAuthProvider.prototype.</span>credential (a, b)](#apidoc.element.firebase.auth.GithubAuthProvider.prototype.credential)
- description and source-code
```javascript
credential = function (a, b){if(!a&&!b)throw new N("argument-error","credential failed: must provide the ID token and/or the access token.");return
 new eg(this.providerId,{idToken:a||null,accessToken:b||null})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.GithubAuthProvider.prototype.setCustomParameters"></a>[function <span class="apidocSignatureSpan">firebase.auth.GithubAuthProvider.prototype.</span>setCustomParameters ()](#apidoc.element.firebase.auth.GithubAuthProvider.prototype.setCustomParameters)
- description and source-code
```javascript
setCustomParameters = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.auth.GoogleAuthProvider"></a>[module firebase.auth.GoogleAuthProvider](#apidoc.module.firebase.auth.GoogleAuthProvider)

#### <a name="apidoc.element.firebase.auth.GoogleAuthProvider.GoogleAuthProvider"></a>[function <span class="apidocSignatureSpan">firebase.auth.</span>GoogleAuthProvider ()](#apidoc.element.firebase.auth.GoogleAuthProvider.GoogleAuthProvider)
- description and source-code
```javascript
GoogleAuthProvider = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.GoogleAuthProvider.ag"></a>[function <span class="apidocSignatureSpan">firebase.auth.GoogleAuthProvider.</span>ag (a, c, f)](#apidoc.element.firebase.auth.GoogleAuthProvider.ag)
- description and source-code
```javascript
ag = function (a, c, f){for(var d=Array(arguments.length-2),e=2;e<arguments.length;e++)d[e-2]=arguments[e];return b.prototype[c].apply(
a,d)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.GoogleAuthProvider.credential"></a>[function <span class="apidocSignatureSpan">firebase.auth.GoogleAuthProvider.</span>credential ()](#apidoc.element.firebase.auth.GoogleAuthProvider.credential)
- description and source-code
```javascript
credential = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.auth.GoogleAuthProvider.prototype"></a>[module firebase.auth.GoogleAuthProvider.prototype](#apidoc.module.firebase.auth.GoogleAuthProvider.prototype)

#### <a name="apidoc.element.firebase.auth.GoogleAuthProvider.prototype.Nd"></a>[function <span class="apidocSignatureSpan">firebase.auth.GoogleAuthProvider.prototype.</span>Nd ()](#apidoc.element.firebase.auth.GoogleAuthProvider.prototype.Nd)
- description and source-code
```javascript
Nd = function (){return Na(this.od)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.GoogleAuthProvider.prototype.addScope"></a>[function <span class="apidocSignatureSpan">firebase.auth.GoogleAuthProvider.prototype.</span>addScope ()](#apidoc.element.firebase.auth.GoogleAuthProvider.prototype.addScope)
- description and source-code
```javascript
addScope = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.GoogleAuthProvider.prototype.credential"></a>[function <span class="apidocSignatureSpan">firebase.auth.GoogleAuthProvider.prototype.</span>credential (a, b)](#apidoc.element.firebase.auth.GoogleAuthProvider.prototype.credential)
- description and source-code
```javascript
credential = function (a, b){if(!a&&!b)throw new N("argument-error","credential failed: must provide the ID token and/or the access token.");return
 new eg(this.providerId,{idToken:a||null,accessToken:b||null})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.GoogleAuthProvider.prototype.setCustomParameters"></a>[function <span class="apidocSignatureSpan">firebase.auth.GoogleAuthProvider.prototype.</span>setCustomParameters ()](#apidoc.element.firebase.auth.GoogleAuthProvider.prototype.setCustomParameters)
- description and source-code
```javascript
setCustomParameters = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.auth.TwitterAuthProvider"></a>[module firebase.auth.TwitterAuthProvider](#apidoc.module.firebase.auth.TwitterAuthProvider)

#### <a name="apidoc.element.firebase.auth.TwitterAuthProvider.TwitterAuthProvider"></a>[function <span class="apidocSignatureSpan">firebase.auth.</span>TwitterAuthProvider ()](#apidoc.element.firebase.auth.TwitterAuthProvider.TwitterAuthProvider)
- description and source-code
```javascript
TwitterAuthProvider = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.TwitterAuthProvider.ag"></a>[function <span class="apidocSignatureSpan">firebase.auth.TwitterAuthProvider.</span>ag (a, c, f)](#apidoc.element.firebase.auth.TwitterAuthProvider.ag)
- description and source-code
```javascript
ag = function (a, c, f){for(var d=Array(arguments.length-2),e=2;e<arguments.length;e++)d[e-2]=arguments[e];return b.prototype[c].apply(
a,d)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.auth.TwitterAuthProvider.credential"></a>[function <span class="apidocSignatureSpan">firebase.auth.TwitterAuthProvider.</span>credential ()](#apidoc.element.firebase.auth.TwitterAuthProvider.credential)
- description and source-code
```javascript
credential = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.auth.TwitterAuthProvider.prototype"></a>[module firebase.auth.TwitterAuthProvider.prototype](#apidoc.module.firebase.auth.TwitterAuthProvider.prototype)

#### <a name="apidoc.element.firebase.auth.TwitterAuthProvider.prototype.setCustomParameters"></a>[function <span class="apidocSignatureSpan">firebase.auth.TwitterAuthProvider.prototype.</span>setCustomParameters ()](#apidoc.element.firebase.auth.TwitterAuthProvider.prototype.setCustomParameters)
- description and source-code
```javascript
setCustomParameters = function (){var a=Array.prototype.slice.call(arguments),e;a:{e=Array.prototype.slice.call(a);var k;k=0;for(var n=!1,A=0;A<c.length
;A++)if(c[A].optional)n=!0;else{if(n)throw new N("internal-error","Argument validator encountered a required argument after an optional
 argument.");k++}n=c.length;if(e.length<k||n<e.length)e="Expected "+(k==n?1==
k?"1 argument":k+" arguments":k+"-"+n+" arguments")+" but got "+e.length+".";else{for(k=0;k<e.length;k++)if(n=c[k].optional&&void
 0===e[k],!c[k].ja(e[k])&&!n){e=c[k];if(0>k||k>=Uh.length)throw new N("internal-error","Argument validator received an unsupported
 number of arguments.");e=Uh[k]+" argument "+(e.name?'"'+e.name+'" ':"")+"must be "+e.ha+".";break a}e=null}}if(e)throw new N("argument
-error",d+" failed: "+e);return b.apply(this,a)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.database"></a>[module firebase.database](#apidoc.module.firebase.database)

#### <a name="apidoc.element.firebase.database.database"></a>[function <span class="apidocSignatureSpan">firebase.</span>database (c)](#apidoc.element.firebase.database.database)
- description and source-code
```javascript
database = function (c){void 0===c&&(c=a());"function"!==typeof c[b]&&M("invalid-app-argument",{name:b});return c[b]()}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Database"></a>[function <span class="apidocSignatureSpan">firebase.database.</span>Database (a)](#apidoc.element.firebase.database.Database)
- description and source-code
```javascript
function Og(a){a instanceof Pg||Sb("Don't call new Database() directly - please use firebase.database().");this.ta=a;this.ba=new
 U(a,Q);this.INTERNAL=new Qg(this)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query"></a>[function <span class="apidocSignatureSpan">firebase.database.</span>Query (a, b, c, d)](#apidoc.element.firebase.database.Query)
- description and source-code
```javascript
function X(a, b, c, d){this.u=a;this.path=b;this.m=c;this.Kc=d}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Reference"></a>[function <span class="apidocSignatureSpan">firebase.database.</span>Reference (a, b)](#apidoc.element.firebase.database.Reference)
- description and source-code
```javascript
function U(a, b){if(!(a instanceof Pg))throw Error("new Firebase() no longer supported - use app.database().");X.call(this,a,b,jf
,!1);this.then=void 0;this["catch"]=void 0}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.enableLogging"></a>[function <span class="apidocSignatureSpan">firebase.database.</span>enableLogging (a, b)](#apidoc.element.firebase.database.enableLogging)
- description and source-code
```javascript
function Pb(a, b){$a(!b||!0===a||!1===a,"Can't turn on custom loggers persistently.");!0===a?("undefined"!==typeof console&&("function
"===typeof console.log?Nb=q(console.log,console):"object"===typeof console.log&&(Nb=function(a){console.log(a)})),b&&vb.set("logging_enabled
",!0)):ha(a)?Nb=a:(Nb=null,vb.remove("logging_enabled"))}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.database.Database"></a>[module firebase.database.Database](#apidoc.module.firebase.database.Database)

#### <a name="apidoc.element.firebase.database.Database.Database"></a>[function <span class="apidocSignatureSpan">firebase.database.</span>Database (a)](#apidoc.element.firebase.database.Database.Database)
- description and source-code
```javascript
function Og(a){a instanceof Pg||Sb("Don't call new Database() directly - please use firebase.database().");this.ta=a;this.ba=new
 U(a,Q);this.INTERNAL=new Qg(this)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.database.Database.prototype"></a>[module firebase.database.Database.prototype](#apidoc.module.firebase.database.Database.prototype)

#### <a name="apidoc.element.firebase.database.Database.prototype.Rf"></a>[function <span class="apidocSignatureSpan">firebase.database.Database.prototype.</span>Rf ()](#apidoc.element.firebase.database.Database.prototype.Rf)
- description and source-code
```javascript
Rf = function (){z("database.goOffline",0,0,arguments.length);Sg(this,"goOffline");this.ta.$a()}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Database.prototype.Sf"></a>[function <span class="apidocSignatureSpan">firebase.database.Database.prototype.</span>Sf ()](#apidoc.element.firebase.database.Database.prototype.Sf)
- description and source-code
```javascript
Sf = function (){z("database.goOnline",0,0,arguments.length);Sg(this,"goOnline");this.ta.hc()}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Database.prototype.gf"></a>[function <span class="apidocSignatureSpan">firebase.database.Database.prototype.</span>gf (a)](#apidoc.element.firebase.database.Database.prototype.gf)
- description and source-code
```javascript
gf = function (a){Sg(this,"ref");z("database.ref",0,1,arguments.length);return n(a)?this.ba.n(a):this.ba}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Database.prototype.goOffline"></a>[function <span class="apidocSignatureSpan">firebase.database.Database.prototype.</span>goOffline ()](#apidoc.element.firebase.database.Database.prototype.goOffline)
- description and source-code
```javascript
goOffline = function (){z("database.goOffline",0,0,arguments.length);Sg(this,"goOffline");this.ta.$a()}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Database.prototype.goOnline"></a>[function <span class="apidocSignatureSpan">firebase.database.Database.prototype.</span>goOnline ()](#apidoc.element.firebase.database.Database.prototype.goOnline)
- description and source-code
```javascript
goOnline = function (){z("database.goOnline",0,0,arguments.length);Sg(this,"goOnline");this.ta.hc()}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Database.prototype.ig"></a>[function <span class="apidocSignatureSpan">firebase.database.Database.prototype.</span>ig (a)](#apidoc.element.firebase.database.Database.prototype.ig)
- description and source-code
```javascript
ig = function (a){Sg(this,"database.refFromURL");z("database.refFromURL",1,1,arguments.length);var b=Tb(a);Ud("database.refFromURL",b
);var c=b.gc;c.host!==this.ta.L.host&&Sb("database.refFromURL: Host name does not match the current database: (found "+c.host+"
but expected "+this.ta.L.host+")");return this.gf(b.path.toString())}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Database.prototype.ref"></a>[function <span class="apidocSignatureSpan">firebase.database.Database.prototype.</span>ref (a)](#apidoc.element.firebase.database.Database.prototype.ref)
- description and source-code
```javascript
ref = function (a){Sg(this,"ref");z("database.ref",0,1,arguments.length);return n(a)?this.ba.n(a):this.ba}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Database.prototype.refFromURL"></a>[function <span class="apidocSignatureSpan">firebase.database.Database.prototype.</span>refFromURL (a)](#apidoc.element.firebase.database.Database.prototype.refFromURL)
- description and source-code
```javascript
refFromURL = function (a){Sg(this,"database.refFromURL");z("database.refFromURL",1,1,arguments.length);var b=Tb(a);Ud("database.refFromURL",b
);var c=b.gc;c.host!==this.ta.L.host&&Sb("database.refFromURL: Host name does not match the current database: (found "+c.host+"
but expected "+this.ta.L.host+")");return this.gf(b.path.toString())}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.database.INTERNAL"></a>[module firebase.database.INTERNAL](#apidoc.module.firebase.database.INTERNAL)

#### <a name="apidoc.element.firebase.database.INTERNAL.Ae"></a>[function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>Ae (a, b)](#apidoc.element.firebase.database.INTERNAL.Ae)
- description and source-code
```javascript
Ae = function (a, b){a.u.Ae(b)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.INTERNAL.Of"></a>[function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>Of ()](#apidoc.element.firebase.database.INTERNAL.Of)
- description and source-code
```javascript
Of = function (){ag=Wf=!0}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.INTERNAL.Pf"></a>[function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>Pf ()](#apidoc.element.firebase.database.INTERNAL.Pf)
- description and source-code
```javascript
Pf = function (){bg=!0}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.INTERNAL.Uf"></a>[function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>Uf (a, b)](#apidoc.element.firebase.database.INTERNAL.Uf)
- description and source-code
```javascript
Uf = function (a, b){a.u.ge=b}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.INTERNAL.Vf"></a>[function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>Vf ()](#apidoc.element.firebase.database.INTERNAL.Vf)
- description and source-code
```javascript
Vf = function (){return Vf.isAvailable()}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.INTERNAL.cd"></a>[function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>cd (a)](#apidoc.element.firebase.database.INTERNAL.cd)
- description and source-code
```javascript
cd = function (a){return a.u.cd}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.INTERNAL.dataUpdateCount"></a>[function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>dataUpdateCount (a)](#apidoc.element.firebase.database.INTERNAL.dataUpdateCount)
- description and source-code
```javascript
dataUpdateCount = function (a){return a.u.cd}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.INTERNAL.forceLongPolling"></a>[function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>forceLongPolling ()](#apidoc.element.firebase.database.INTERNAL.forceLongPolling)
- description and source-code
```javascript
forceLongPolling = function (){ag=Wf=!0}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.INTERNAL.forceWebSockets"></a>[function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>forceWebSockets ()](#apidoc.element.firebase.database.INTERNAL.forceWebSockets)
- description and source-code
```javascript
forceWebSockets = function (){bg=!0}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.INTERNAL.interceptServerData"></a>[function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>interceptServerData (a, b)](#apidoc.element.firebase.database.INTERNAL.interceptServerData)
- description and source-code
```javascript
interceptServerData = function (a, b){a.u.ge=b}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.INTERNAL.isWebSocketsAvailable"></a>[function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>isWebSocketsAvailable ()](#apidoc.element.firebase.database.INTERNAL.isWebSocketsAvailable)
- description and source-code
```javascript
isWebSocketsAvailable = function (){return Vf.isAvailable()}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.INTERNAL.ng"></a>[function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>ng (a, b)](#apidoc.element.firebase.database.INTERNAL.ng)
- description and source-code
```javascript
ng = function (a, b){a.u.Qa.xe=b}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.INTERNAL.setSecurityDebugCallback"></a>[function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>setSecurityDebugCallback (a, b)](#apidoc.element.firebase.database.INTERNAL.setSecurityDebugCallback)
- description and source-code
```javascript
setSecurityDebugCallback = function (a, b){a.u.Qa.xe=b}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.INTERNAL.stats"></a>[function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>stats (a, b)](#apidoc.element.firebase.database.INTERNAL.stats)
- description and source-code
```javascript
stats = function (a, b){a.u.ze(b)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.INTERNAL.statsIncrementCounter"></a>[function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>statsIncrementCounter (a, b)](#apidoc.element.firebase.database.INTERNAL.statsIncrementCounter)
- description and source-code
```javascript
statsIncrementCounter = function (a, b){a.u.Ae(b)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.INTERNAL.ze"></a>[function <span class="apidocSignatureSpan">firebase.database.INTERNAL.</span>ze (a, b)](#apidoc.element.firebase.database.INTERNAL.ze)
- description and source-code
```javascript
ze = function (a, b){a.u.ze(b)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.database.Query"></a>[module firebase.database.Query](#apidoc.module.firebase.database.Query)

#### <a name="apidoc.element.firebase.database.Query.Query"></a>[function <span class="apidocSignatureSpan">firebase.database.</span>Query (a, b, c, d)](#apidoc.element.firebase.database.Query.Query)
- description and source-code
```javascript
function X(a, b, c, d){this.u=a;this.path=b;this.m=c;this.Kc=d}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.database.Query.prototype"></a>[module firebase.database.Query.prototype](#apidoc.module.firebase.database.Query.prototype)

#### <a name="apidoc.element.firebase.database.Query.prototype.Fc"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>Fc (a, b, c)](#apidoc.element.firebase.database.Query.prototype.Fc)
- description and source-code
```javascript
Fc = function (a, b, c){z("Query.off",0,3,arguments.length);Qd("Query.off",a,!0);B("Query.off",2,b,!0);lb("Query.off",3,c);var d=null,e
=null;"value"===a?d=new Ug(b||null,null,c||null):a&&(b&&(e={},e[a]=b),d=new Vg(e,null,c||null));e=this.u;d=".info"===K(this.path
)?e.md.ib(this,d):e.K.ib(this,d);Ye(e.ca,this.path,d)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.Jf"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>Jf (a, b)](#apidoc.element.firebase.database.Query.prototype.Jf)
- description and source-code
```javascript
Jf = function (a, b){z("Query.equalTo",1,2,arguments.length);Ld("Query.equalTo",a,this.path,!1);Rd("Query.equalTo",b);if(this.m.ka)throw
 Error("Query.equalTo: Starting point was already set (by another call to startAt or equalTo).");if(this.m.na)throw Error("Query
.equalTo: Ending point was already set (by another call to endAt or equalTo).");return this.Kd(a,b).dd(a,b)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.Kd"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>Kd (a, b)](#apidoc.element.firebase.database.Query.prototype.Kd)
- description and source-code
```javascript
Kd = function (a, b){z("Query.startAt",0,2,arguments.length);Ld("Query.startAt",a,this.path,!0);Rd("Query.startAt",b);var c=this.m.Kd(
a,b);Qh(c);Ph(c);if(this.m.ka)throw Error("Query.startAt: Starting point was already set (by another call to startAt or equalTo).");
n(a)||(b=a=null);return new X(this.u,this.path,c,this.Kc)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.ag"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>ag (a, b)](#apidoc.element.firebase.database.Query.prototype.ag)
- description and source-code
```javascript
ag = function (a, b){function c(k){f&&(f=!1,e.Fc(a,c),b&&b.call(d.La,k),g.resolve(k))}z("Query.once",1,4,arguments.length);Qd("Query.once
",a,!1);B("Query.once",2,b,!0);var d=Sh("Query.once",arguments[2],arguments[3]),e=this,f=!0,g=new fb;hb(g.ra);this.dc(a,c,function
(b){e.Fc(a,c);d.cancel&&d.cancel.call(d.La,b);g.reject(b)});return g.ra}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.bg"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>bg (a)](#apidoc.element.firebase.database.Query.prototype.bg)
- description and source-code
```javascript
bg = function (a){z("Query.orderByChild",1,1,arguments.length);if("$key"===a)throw Error('Query.orderByChild: "$key" is invalid.  Use
 Query.orderByKey() instead.');if("$priority"===a)throw Error('Query.orderByChild: "$priority" is invalid.  Use Query.orderByPriority
() instead.');if("$value"===a)throw Error('Query.orderByChild: "$value" is invalid.  Use Query.orderByValue() instead.');Sd("Query
.orderByChild",a);Rh(this,"Query.orderByChild");var b=new E(a);if(b.e())throw Error("Query.orderByChild: cannot pass in empty path
.  Use Query.orderByValue() instead.");
b=new mc(b);b=lf(this.m,b);Ph(b);return new X(this.u,this.path,b,!0)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.cg"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>cg ()](#apidoc.element.firebase.database.Query.prototype.cg)
- description and source-code
```javascript
cg = function (){z("Query.orderByKey",0,0,arguments.length);Rh(this,"Query.orderByKey");var a=lf(this.m,qc);Ph(a);return new X(this.u
,this.path,a,!0)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.dc"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>dc (a, b, c, d)](#apidoc.element.firebase.database.Query.prototype.dc)
- description and source-code
```javascript
dc = function (a, b, c, d){z("Query.on",2,4,arguments.length);Qd("Query.on",a,!1);B("Query.on",2,b,!1);var e=Sh("Query.on",c,d);if("value
"===a)Eh(this.u,this,new Ug(b,e.cancel||null,e.La||null));else{var f={};f[a]=b;Eh(this.u,this,new Vg(f,e.cancel,e.La))}return b}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.dd"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>dd (a, b)](#apidoc.element.firebase.database.Query.prototype.dd)
- description and source-code
```javascript
dd = function (a, b){z("Query.endAt",0,2,arguments.length);Ld("Query.endAt",a,this.path,!0);Rd("Query.endAt",b);var c=this.m.dd(a,b);Qh
(c);Ph(c);if(this.m.na)throw Error("Query.endAt: Ending point was already set (by another call to endAt or equalTo).");return new
 X(this.u,this.path,c,this.Kc)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.dg"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>dg ()](#apidoc.element.firebase.database.Query.prototype.dg)
- description and source-code
```javascript
dg = function (){z("Query.orderByPriority",0,0,arguments.length);Rh(this,"Query.orderByPriority");var a=lf(this.m,H);Ph(a);return new
 X(this.u,this.path,a,!0)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.eg"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>eg ()](#apidoc.element.firebase.database.Query.prototype.eg)
- description and source-code
```javascript
eg = function (){z("Query.orderByValue",0,0,arguments.length);Rh(this,"Query.orderByValue");var a=lf(this.m,tc);Ph(a);return new X(this
.u,this.path,a,!0)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.endAt"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>endAt (a, b)](#apidoc.element.firebase.database.Query.prototype.endAt)
- description and source-code
```javascript
endAt = function (a, b){z("Query.endAt",0,2,arguments.length);Ld("Query.endAt",a,this.path,!0);Rd("Query.endAt",b);var c=this.m.dd(a,b);Qh
(c);Ph(c);if(this.m.na)throw Error("Query.endAt: Ending point was already set (by another call to endAt or equalTo).");return new
 X(this.u,this.path,c,this.Kc)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.equalTo"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>equalTo (a, b)](#apidoc.element.firebase.database.Query.prototype.equalTo)
- description and source-code
```javascript
equalTo = function (a, b){z("Query.equalTo",1,2,arguments.length);Ld("Query.equalTo",a,this.path,!1);Rd("Query.equalTo",b);if(this.m.ka)throw
 Error("Query.equalTo: Starting point was already set (by another call to startAt or equalTo).");if(this.m.na)throw Error("Query
.equalTo: Ending point was already set (by another call to endAt or equalTo).");return this.Kd(a,b).dd(a,b)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.isEqual"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>isEqual (a)](#apidoc.element.firebase.database.Query.prototype.isEqual)
- description and source-code
```javascript
isEqual = function (a){z("Query.isEqual",1,1,arguments.length);if(!(a instanceof X))throw Error("Query.isEqual failed: First argument must
 be an instance of firebase.database.Query.");var b=this.u===a.u,c=this.path.Z(a.path),d=this.ja()===a.ja();return b&&c&&d}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.ja"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>ja ()](#apidoc.element.firebase.database.Query.prototype.ja)
- description and source-code
```javascript
ja = function (){var a=Yb(mf(this.m));return"{}"===a?"default":a}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.ke"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>ke (a)](#apidoc.element.firebase.database.Query.prototype.ke)
- description and source-code
```javascript
ke = function (a){z("Query.limitToFirst",1,1,arguments.length);if(!ga(a)||Math.floor(a)!==a||0>=a)throw Error("Query.limitToFirst: First
 argument must be a positive integer.");if(this.m.xa)throw Error("Query.limitToFirst: Limit was already set (by another call to
limit, limitToFirst, or limitToLast).");return new X(this.u,this.path,this.m.ke(a),this.Kc)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.le"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>le (a)](#apidoc.element.firebase.database.Query.prototype.le)
- description and source-code
```javascript
le = function (a){z("Query.limitToLast",1,1,arguments.length);if(!ga(a)||Math.floor(a)!==a||0>=a)throw Error("Query.limitToLast: First
 argument must be a positive integer.");if(this.m.xa)throw Error("Query.limitToLast: Limit was already set (by another call to limit
, limitToFirst, or limitToLast).");return new X(this.u,this.path,this.m.le(a),this.Kc)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.limitToFirst"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>limitToFirst (a)](#apidoc.element.firebase.database.Query.prototype.limitToFirst)
- description and source-code
```javascript
limitToFirst = function (a){z("Query.limitToFirst",1,1,arguments.length);if(!ga(a)||Math.floor(a)!==a||0>=a)throw Error("Query.limitToFirst: First
 argument must be a positive integer.");if(this.m.xa)throw Error("Query.limitToFirst: Limit was already set (by another call to
limit, limitToFirst, or limitToLast).");return new X(this.u,this.path,this.m.ke(a),this.Kc)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.limitToLast"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>limitToLast (a)](#apidoc.element.firebase.database.Query.prototype.limitToLast)
- description and source-code
```javascript
limitToLast = function (a){z("Query.limitToLast",1,1,arguments.length);if(!ga(a)||Math.floor(a)!==a||0>=a)throw Error("Query.limitToLast: First
 argument must be a positive integer.");if(this.m.xa)throw Error("Query.limitToLast: Limit was already set (by another call to limit
, limitToFirst, or limitToLast).");return new X(this.u,this.path,this.m.le(a),this.Kc)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.off"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>off (a, b, c)](#apidoc.element.firebase.database.Query.prototype.off)
- description and source-code
```javascript
off = function (a, b, c){z("Query.off",0,3,arguments.length);Qd("Query.off",a,!0);B("Query.off",2,b,!0);lb("Query.off",3,c);var d=null,e
=null;"value"===a?d=new Ug(b||null,null,c||null):a&&(b&&(e={},e[a]=b),d=new Vg(e,null,c||null));e=this.u;d=".info"===K(this.path
)?e.md.ib(this,d):e.K.ib(this,d);Ye(e.ca,this.path,d)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.on"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>on (a, b, c, d)](#apidoc.element.firebase.database.Query.prototype.on)
- description and source-code
```javascript
on = function (a, b, c, d){z("Query.on",2,4,arguments.length);Qd("Query.on",a,!1);B("Query.on",2,b,!1);var e=Sh("Query.on",c,d);if("value
"===a)Eh(this.u,this,new Ug(b,e.cancel||null,e.La||null));else{var f={};f[a]=b;Eh(this.u,this,new Vg(f,e.cancel,e.La))}return b}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.once"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>once (a, b)](#apidoc.element.firebase.database.Query.prototype.once)
- description and source-code
```javascript
once = function (a, b){function c(k){f&&(f=!1,e.Fc(a,c),b&&b.call(d.La,k),g.resolve(k))}z("Query.once",1,4,arguments.length);Qd("Query.once
",a,!1);B("Query.once",2,b,!0);var d=Sh("Query.once",arguments[2],arguments[3]),e=this,f=!0,g=new fb;hb(g.ra);this.dc(a,c,function
(b){e.Fc(a,c);d.cancel&&d.cancel.call(d.La,b);g.reject(b)});return g.ra}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.orderByChild"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>orderByChild (a)](#apidoc.element.firebase.database.Query.prototype.orderByChild)
- description and source-code
```javascript
orderByChild = function (a){z("Query.orderByChild",1,1,arguments.length);if("$key"===a)throw Error('Query.orderByChild: "$key" is invalid.  Use
 Query.orderByKey() instead.');if("$priority"===a)throw Error('Query.orderByChild: "$priority" is invalid.  Use Query.orderByPriority
() instead.');if("$value"===a)throw Error('Query.orderByChild: "$value" is invalid.  Use Query.orderByValue() instead.');Sd("Query
.orderByChild",a);Rh(this,"Query.orderByChild");var b=new E(a);if(b.e())throw Error("Query.orderByChild: cannot pass in empty path
.  Use Query.orderByValue() instead.");
b=new mc(b);b=lf(this.m,b);Ph(b);return new X(this.u,this.path,b,!0)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.orderByKey"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>orderByKey ()](#apidoc.element.firebase.database.Query.prototype.orderByKey)
- description and source-code
```javascript
orderByKey = function (){z("Query.orderByKey",0,0,arguments.length);Rh(this,"Query.orderByKey");var a=lf(this.m,qc);Ph(a);return new X(this.u
,this.path,a,!0)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.orderByPriority"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>orderByPriority ()](#apidoc.element.firebase.database.Query.prototype.orderByPriority)
- description and source-code
```javascript
orderByPriority = function (){z("Query.orderByPriority",0,0,arguments.length);Rh(this,"Query.orderByPriority");var a=lf(this.m,H);Ph(a);return new
 X(this.u,this.path,a,!0)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.orderByValue"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>orderByValue ()](#apidoc.element.firebase.database.Query.prototype.orderByValue)
- description and source-code
```javascript
orderByValue = function (){z("Query.orderByValue",0,0,arguments.length);Rh(this,"Query.orderByValue");var a=lf(this.m,tc);Ph(a);return new X(this
.u,this.path,a,!0)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.startAt"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>startAt (a, b)](#apidoc.element.firebase.database.Query.prototype.startAt)
- description and source-code
```javascript
startAt = function (a, b){z("Query.startAt",0,2,arguments.length);Ld("Query.startAt",a,this.path,!0);Rd("Query.startAt",b);var c=this.m.Kd(
a,b);Qh(c);Ph(c);if(this.m.ka)throw Error("Query.startAt: Starting point was already set (by another call to startAt or equalTo).");
n(a)||(b=a=null);return new X(this.u,this.path,c,this.Kc)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.toJSON"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>toJSON ()](#apidoc.element.firebase.database.Query.prototype.toJSON)
- description and source-code
```javascript
toJSON = function (){z("Query.toJSON",0,1,arguments.length);return this.toString()}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.toString"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>toString ()](#apidoc.element.firebase.database.Query.prototype.toString)
- description and source-code
```javascript
toString = function (){z("Query.toString",0,0,arguments.length);for(var a=this.path,b="",c=a.Y;c<a.o.length;c++)""!==a.o[c]&&(b+="/"+encodeURIComponent
(String(a.o[c])));return this.u.toString()+(b||"/")}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Query.prototype.ub"></a>[function <span class="apidocSignatureSpan">firebase.database.Query.prototype.</span>ub ()](#apidoc.element.firebase.database.Query.prototype.ub)
- description and source-code
```javascript
ub = function (){z("Query.ref",0,0,arguments.length);return new U(this.u,this.path)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.database.Reference"></a>[module firebase.database.Reference](#apidoc.module.firebase.database.Reference)

#### <a name="apidoc.element.firebase.database.Reference.Reference"></a>[function <span class="apidocSignatureSpan">firebase.database.</span>Reference (a, b)](#apidoc.element.firebase.database.Reference.Reference)
- description and source-code
```javascript
function U(a, b){if(!(a instanceof Pg))throw Error("new Firebase() no longer supported - use app.database().");X.call(this,a,b,jf
,!1);this.then=void 0;this["catch"]=void 0}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Reference.vg"></a>[function <span class="apidocSignatureSpan">firebase.database.Reference.</span>vg (a, c, f)](#apidoc.element.firebase.database.Reference.vg)
- description and source-code
```javascript
vg = function (a, c, f){for(var g=Array(arguments.length-2),k=2;k<arguments.length;k++)g[k-2]=arguments[k];return b.prototype[c].apply(
a,g)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.database.Reference.prototype"></a>[module firebase.database.Reference.prototype](#apidoc.module.firebase.database.Reference.prototype)

#### <a name="apidoc.element.firebase.database.Reference.prototype.Gf"></a>[function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>Gf ()](#apidoc.element.firebase.database.Reference.prototype.Gf)
- description and source-code
```javascript
Gf = function (){return this.u.Xa}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Reference.prototype.Hb"></a>[function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>Hb (a, b, c)](#apidoc.element.firebase.database.Reference.prototype.Hb)
- description and source-code
```javascript
Hb = function (a, b, c){z("Firebase.setWithPriority",2,3,arguments.length);Td("Firebase.setWithPriority",this.path);Ld("Firebase.setWithPriority
",a,this.path,!1);Pd("Firebase.setWithPriority",2,b);B("Firebase.setWithPriority",3,c,!0);if(".length"===this.getKey()||".keys"===
this.getKey())throw"Firebase.setWithPriority failed: "+this.getKey()+" is a read-only object.";var d=new fb;this.u.Hb(this.path,
a,b,gb(d,c));return d.ra}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Reference.prototype.Qf"></a>[function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>Qf ()](#apidoc.element.firebase.database.Reference.prototype.Qf)
- description and source-code
```javascript
Qf = function (){z("Firebase.ref",0,0,arguments.length);for(var a=this;null!==a.getParent();)a=a.getParent();return a}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Reference.prototype.child"></a>[function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>child (a)](#apidoc.element.firebase.database.Reference.prototype.child)
- description and source-code
```javascript
child = function (a){z("Firebase.child",1,1,arguments.length);if(ga(a))a=String(a);else if(!(a instanceof E))if(null===K(this.path)){var
 b=a;b&&(b=b.replace(/^\/*\.info(\/|$)/,"/"));Sd("Firebase.child",b)}else Sd("Firebase.child",a);return new U(this.u,this.path.n(a))}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Reference.prototype.constructor"></a>[function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>constructor (a, b)](#apidoc.element.firebase.database.Reference.prototype.constructor)
- description and source-code
```javascript
function U(a, b){if(!(a instanceof Pg))throw Error("new Firebase() no longer supported - use app.database().");X.call(this,a,b,jf
,!1);this.then=void 0;this["catch"]=void 0}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Reference.prototype.gb"></a>[function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>gb ()](#apidoc.element.firebase.database.Reference.prototype.gb)
- description and source-code
```javascript
gb = function (){Td("Firebase.onDisconnect",this.path);return new Y(this.u,this.path)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Reference.prototype.getKey"></a>[function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>getKey ()](#apidoc.element.firebase.database.Reference.prototype.getKey)
- description and source-code
```javascript
getKey = function (){z("Firebase.key",0,0,arguments.length);return this.path.e()?null:Lc(this.path)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Reference.prototype.getParent"></a>[function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>getParent ()](#apidoc.element.firebase.database.Reference.prototype.getParent)
- description and source-code
```javascript
getParent = function (){z("Firebase.parent",0,0,arguments.length);var a=this.path.parent();return null===a?null:new U(this.u,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Reference.prototype.mg"></a>[function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>mg (a, b)](#apidoc.element.firebase.database.Reference.prototype.mg)
- description and source-code
```javascript
mg = function (a, b){z("Firebase.setPriority",1,2,arguments.length);Td("Firebase.setPriority",this.path);Pd("Firebase.setPriority",1,a
);B("Firebase.setPriority",2,b,!0);var c=new fb;this.u.Hb(this.path.n(".priority"),a,null,gb(c,b));return c.ra}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Reference.prototype.n"></a>[function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>n (a)](#apidoc.element.firebase.database.Reference.prototype.n)
- description and source-code
```javascript
n = function (a){z("Firebase.child",1,1,arguments.length);if(ga(a))a=String(a);else if(!(a instanceof E))if(null===K(this.path)){var
 b=a;b&&(b=b.replace(/^\/*\.info(\/|$)/,"/"));Sd("Firebase.child",b)}else Sd("Firebase.child",a);return new U(this.u,this.path.n(a))}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Reference.prototype.onDisconnect"></a>[function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>onDisconnect ()](#apidoc.element.firebase.database.Reference.prototype.onDisconnect)
- description and source-code
```javascript
onDisconnect = function (){Td("Firebase.onDisconnect",this.path);return new Y(this.u,this.path)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Reference.prototype.push"></a>[function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>push (a, b)](#apidoc.element.firebase.database.Reference.prototype.push)
- description and source-code
```javascript
push = function (a, b){z("Firebase.push",0,2,arguments.length);Td("Firebase.push",this.path);Ld("Firebase.push",a,this.path,!0);B("Firebase
.push",2,b,!0);var c=vh(this.u),d=Hc(c),c=this.n(d),e;if(null!=a){var f=this;e=c.set(a,b).then(function(){return f.n(d)})}else e
=eb.resolve(c);c.then=q(e.then,e);c["catch"]=q(e.then,e,void 0);ha(b)&&hb(e);return c}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Reference.prototype.remove"></a>[function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>remove (a)](#apidoc.element.firebase.database.Reference.prototype.remove)
- description and source-code
```javascript
remove = function (a){z("Firebase.remove",0,1,arguments.length);Td("Firebase.remove",this.path);B("Firebase.remove",1,a,!0);return this.set
(null,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Reference.prototype.set"></a>[function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>set (a, b)](#apidoc.element.firebase.database.Reference.prototype.set)
- description and source-code
```javascript
set = function (a, b){z("Firebase.set",1,2,arguments.length);Td("Firebase.set",this.path);Ld("Firebase.set",a,this.path,!1);B("Firebase
.set",2,b,!0);var c=new fb;this.u.Hb(this.path,a,null,gb(c,b));return c.ra}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Reference.prototype.setPriority"></a>[function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>setPriority (a, b)](#apidoc.element.firebase.database.Reference.prototype.setPriority)
- description and source-code
```javascript
setPriority = function (a, b){z("Firebase.setPriority",1,2,arguments.length);Td("Firebase.setPriority",this.path);Pd("Firebase.setPriority",1,a
);B("Firebase.setPriority",2,b,!0);var c=new fb;this.u.Hb(this.path.n(".priority"),a,null,gb(c,b));return c.ra}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Reference.prototype.setWithPriority"></a>[function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>setWithPriority (a, b, c)](#apidoc.element.firebase.database.Reference.prototype.setWithPriority)
- description and source-code
```javascript
setWithPriority = function (a, b, c){z("Firebase.setWithPriority",2,3,arguments.length);Td("Firebase.setWithPriority",this.path);Ld("Firebase.setWithPriority
",a,this.path,!1);Pd("Firebase.setWithPriority",2,b);B("Firebase.setWithPriority",3,c,!0);if(".length"===this.getKey()||".keys"===
this.getKey())throw"Firebase.setWithPriority failed: "+this.getKey()+" is a read-only object.";var d=new fb;this.u.Hb(this.path,
a,b,gb(d,c));return d.ra}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Reference.prototype.transaction"></a>[function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>transaction (a, b, c)](#apidoc.element.firebase.database.Reference.prototype.transaction)
- description and source-code
```javascript
transaction = function (a, b, c){z("Firebase.transaction",1,3,arguments.length);Td("Firebase.transaction",this.path);B("Firebase.transaction",1,
a,!1);B("Firebase.transaction",2,b,!0);if(n(c)&&"boolean"!=typeof c)throw Error(A("Firebase.transaction",3,!0)+"must be a boolean
.");if(".length"===this.getKey()||".keys"===this.getKey())throw"Firebase.transaction failed: "+this.getKey()+" is a read-only object
.";"undefined"===typeof c&&(c=!0);var d=new fb;ha(b)&&hb(d.ra);Fh(this.u,this.path,a,function(a,c,g){a?
d.reject(a):d.resolve(new Oh(c,g));ha(b)&&b(a,c,g)},c);return d.ra}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.Reference.prototype.update"></a>[function <span class="apidocSignatureSpan">firebase.database.Reference.prototype.</span>update (a, b)](#apidoc.element.firebase.database.Reference.prototype.update)
- description and source-code
```javascript
update = function (a, b){z("Firebase.update",1,2,arguments.length);Td("Firebase.update",this.path);if(ea(a)){for(var c={},d=0;d<a.length;++
d)c[""+d]=a[d];a=c;J("Passing an Array to Firebase.update() is deprecated. Use set() if you want to overwrite the existing data,
or an Object with integer keys if you really do want to only update some of the children.")}Od("Firebase.update",a,this.path);B("
Firebase.update",2,b,!0);c=new fb;this.u.update(this.path,a,gb(c,b));return c.ra}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.database.TEST_ACCESS"></a>[module firebase.database.TEST_ACCESS](#apidoc.module.firebase.database.TEST_ACCESS)

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.ConnectionTarget"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>ConnectionTarget (a, b, c, d, e)](#apidoc.element.firebase.database.TEST_ACCESS.ConnectionTarget)
- description and source-code
```javascript
function wb(a, b, c, d, e){this.host=a.toLowerCase();this.domain=this.host.substr(this.host.indexOf(".")+1);this.Pc=b;this.ne=c;this
.tg=d;this.ef=e||"";this.Za=ub.get("host:"+a)||this.host}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.Context"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>Context ()](#apidoc.element.firebase.database.TEST_ACCESS.Context)
- description and source-code
```javascript
function Tg(){this.jb={};this.uf=!1}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.DataConnection"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>DataConnection (a, b, c, d, e, f)](#apidoc.element.firebase.database.TEST_ACCESS.DataConnection)
- description and source-code
```javascript
function zg(a, b, c, d, e, f){this.id=Ag++;this.f=Qb("p:"+this.id+":");this.nd={};this.$={};this.pa=[];this.Lc=0;this.Hc=[];this.ma=!
1;this.Ra=1E3;this.qd=3E5;this.Eb=b;this.Gc=c;this.se=d;this.L=a;this.mb=this.Ea=this.Ab=this.xe=null;this.Xc=e;this.ae=!1;this.
he=0;this.Rd=f;this.sb=null;this.Kb=!1;this.Ed={};this.kg=0;this.Oe=!0;this.xc=this.je=null;Bg(this,0);Jc.Tb().dc("visible",this
.$f,this);-1===a.host.indexOf("fblocal")&&Ic.Tb().dc("online",this.Zf,this)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.RealTimeConnection"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>RealTimeConnection (a, b, c, d, e, f, g)](#apidoc.element.firebase.database.TEST_ACCESS.RealTimeConnection)
- description and source-code
```javascript
function ng(a, b, c, d, e, f, g){this.id=a;this.f=Qb("c:"+this.id+":");this.re=c;this.Ic=d;this.ia=e;this.qe=f;this.L=b;this.yd=[];this
.Ie=0;this.rf=new jg(b);this.Ta=0;this.Ab=g;this.f("Connection created");og(this)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.Tf"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>Tf (a)](#apidoc.element.firebase.database.TEST_ACCESS.Tf)
- description and source-code
```javascript
Tf = function (a){var b=zg.prototype.put;zg.prototype.put=function(c,d,e,f){n(f)&&(f=a());b.call(this,c,d,e,f)};return function(){zg.
prototype.put=b}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.Wf"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>Wf (a)](#apidoc.element.firebase.database.TEST_ACCESS.Wf)
- description and source-code
```javascript
Wf = function (a){return a.u.Qa.$}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.forceRestClient"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>forceRestClient (a)](#apidoc.element.firebase.database.TEST_ACCESS.forceRestClient)
- description and source-code
```javascript
forceRestClient = function (a){Tg.Tb().$d(a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.hijackHash"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>hijackHash (a)](#apidoc.element.firebase.database.TEST_ACCESS.hijackHash)
- description and source-code
```javascript
hijackHash = function (a){var b=zg.prototype.put;zg.prototype.put=function(c,d,e,f){n(f)&&(f=a());b.call(this,c,d,e,f)};return function(){zg.
prototype.put=b}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.ja"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>ja (a)](#apidoc.element.firebase.database.TEST_ACCESS.ja)
- description and source-code
```javascript
ja = function (a){return a.ja()}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.kc"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>kc (a, b, c, d, e, f)](#apidoc.element.firebase.database.TEST_ACCESS.kc)
- description and source-code
```javascript
function zg(a, b, c, d, e, f){this.id=Ag++;this.f=Qb("p:"+this.id+":");this.nd={};this.$={};this.pa=[];this.Lc=0;this.Hc=[];this.ma=!
1;this.Ra=1E3;this.qd=3E5;this.Eb=b;this.Gc=c;this.se=d;this.L=a;this.mb=this.Ea=this.Ab=this.xe=null;this.Xc=e;this.ae=!1;this.
he=0;this.Rd=f;this.sb=null;this.Kb=!1;this.Ed={};this.kg=0;this.Oe=!0;this.xc=this.je=null;Bg(this,0);Jc.Tb().dc("visible",this
.$f,this);-1===a.host.indexOf("fblocal")&&Ic.Tb().dc("online",this.Zf,this)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.listens"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>listens (a)](#apidoc.element.firebase.database.TEST_ACCESS.listens)
- description and source-code
```javascript
listens = function (a){return a.u.Qa.$}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.queryIdentifier"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>queryIdentifier (a)](#apidoc.element.firebase.database.TEST_ACCESS.queryIdentifier)
- description and source-code
```javascript
queryIdentifier = function (a){return a.ja()}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.xf"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>xf (a, b, c, d, e)](#apidoc.element.firebase.database.TEST_ACCESS.xf)
- description and source-code
```javascript
function wb(a, b, c, d, e){this.host=a.toLowerCase();this.domain=this.host.substr(this.host.indexOf(".")+1);this.Pc=b;this.ne=c;this
.tg=d;this.ef=e||"";this.Za=ub.get("host:"+a)||this.host}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.yf"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.</span>yf (a, b, c, d, e, f, g)](#apidoc.element.firebase.database.TEST_ACCESS.yf)
- description and source-code
```javascript
function ng(a, b, c, d, e, f, g){this.id=a;this.f=Qb("c:"+this.id+":");this.re=c;this.Ic=d;this.ia=e;this.qe=f;this.L=b;this.yd=[];this
.Ie=0;this.rf=new jg(b);this.Ta=0;this.Ab=g;this.f("Connection created");og(this)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.database.TEST_ACCESS.Context.prototype"></a>[module firebase.database.TEST_ACCESS.Context.prototype](#apidoc.module.firebase.database.TEST_ACCESS.Context.prototype)

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.Context.prototype.hc"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.Context.prototype.</span>hc ()](#apidoc.element.firebase.database.TEST_ACCESS.Context.prototype.hc)
- description and source-code
```javascript
hc = function (){for(var a in this.jb)this.jb[a].hc()}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.Context.prototype.interrupt"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.Context.prototype.</span>interrupt ()](#apidoc.element.firebase.database.TEST_ACCESS.Context.prototype.interrupt)
- description and source-code
```javascript
interrupt = function (){for(var a in this.jb)this.jb[a].$a()}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.Context.prototype.resume"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.Context.prototype.</span>resume ()](#apidoc.element.firebase.database.TEST_ACCESS.Context.prototype.resume)
- description and source-code
```javascript
resume = function (){for(var a in this.jb)this.jb[a].hc()}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.database.TEST_ACCESS.kc.prototype"></a>[module firebase.database.TEST_ACCESS.kc.prototype](#apidoc.module.firebase.database.TEST_ACCESS.kc.prototype)

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.Ic"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>Ic (a, b)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.Ic)
- description and source-code
```javascript
Ic = function (a, b){this.f("connection ready");this.ma=!0;this.xc=(new Date).getTime();this.se({serverTimeOffset:a-(new Date).getTime
()});this.Ab=b;if(this.Oe){var c={};c["sdk.node."+firebase.SDK_VERSION.replace(/\./g,"-")]=1;mb()?c["framework.cordova"]=1:"object"===typeof navigator&&"ReactNative"===navigator.product&&(c["framework.reactnative"]=1);this.we(c)}Lg(this);this.Oe=!1;this.Gc(!0)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.If"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>If (a, b)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.If)
- description and source-code
```javascript
If = function (a, b){this.ua("echo",{d:a},b)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.Xe"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>Xe (a, b, c, d)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.Xe)
- description and source-code
```javascript
Xe = function (a, b, c, d){var e=a.ja(),f=a.path.toString();this.f("Listen called for "+f+" "+e);this.$[f]=this.$[f]||{};D(nf(a.m)||!T(a
.m),"listen() called for non-default but complete query");D(!this.$[f][e],"listen() called twice for same path/queryId.");a={G:d
,hd:b,gg:a,tag:c};this.$[f][e]=a;this.ma&&Dg(this,a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.Ye"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>Ye (a, b, c, d)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.Ye)
- description and source-code
```javascript
Ye = function (a, b, c, d){Ig(this,"m",a,b,c,d)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.Zf"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>Zf (a)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.Zf)
- description and source-code
```javascript
Zf = function (a){a?(this.f("Browser went online."),this.Ra=1E3,this.Ea||Bg(this,0)):(this.f("Browser went offline.  Killing connection
."),this.Ea&&this.Ea.close())}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.bf"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>bf (a, b, c)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.bf)
- description and source-code
```javascript
bf = function (a, b, c){this.ma?Hg(this,"om",a,b,c):this.Hc.push({ue:a,action:"om",data:b,G:c})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.cf"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>cf ()](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.cf)
- description and source-code
```javascript
cf = function (){this.f("data client disconnected");this.ma=!1;this.Ea=null;for(var a=0;a<this.pa.length;a++){var b=this.pa[a];b&&"h"
in b.kf&&b.hg&&(b.G&&b.G("disconnect"),delete this.pa[a],this.Lc--)}0===this.Lc&&(this.pa=[]);this.Ed={};Ng(this)&&(this.Kb?this
.xc&&(3E4<(new Date).getTime()-this.xc&&(this.Ra=1E3),this.xc=null):(this.f("Window isn't visible.  Delaying reconnect."),this.Ra
=this.qd,this.je=(new Date).getTime()),a=Math.max(0,this.Ra-((new Date).getTime()-this.je)),a*=Math.random(),this.f("Trying to reconnect
 in "+
a+"ms"),Bg(this,a),this.Ra=Math.min(this.qd,1.3*this.Ra));this.Gc(!1)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.echo"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>echo (a, b)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.echo)
- description and source-code
```javascript
echo = function (a, b){this.ua("echo",{d:a},b)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.hc"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>hc (a)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.hc)
- description and source-code
```javascript
hc = function (a){I("Resuming connection for reason: "+a);delete this.nd[a];Ra(this.nd)&&(this.Ra=1E3,this.Ea||Bg(this,0))}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.hf"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>hf (a)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.hf)
- description and source-code
```javascript
hf = function (a){this.mb=a;this.f("Auth token refreshed");this.mb?Fg(this):this.ma&&this.ua("unauth",{},function(){});if(a&&40===a.length
||hc(a))this.f("Admin auth credential detected.  Reducing max reconnect time."),this.qd=3E4}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.interrupt"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>interrupt (a)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.interrupt)
- description and source-code
```javascript
interrupt = function (a){I("Interrupting connection for reason: "+a);this.nd[a]=!0;this.Ea?this.Ea.close():(this.sb&&(clearTimeout(this.sb),
this.sb=null),this.ma&&this.cf())}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.pe"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>pe (a, b, c)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.pe)
- description and source-code
```javascript
pe = function (a, b, c){this.ma?Hg(this,"o",a,b,c):this.Hc.push({ue:a,action:"o",data:b,G:c})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.pg"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>pg (a, b)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.pg)
- description and source-code
```javascript
pg = function (a, b){this.ua("q",{p:a},b)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.put"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>put (a, b, c, d)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.put)
- description and source-code
```javascript
put = function (a, b, c, d){Ig(this,"p",a,b,c,d)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.simpleListen"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>simpleListen (a, b)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.simpleListen)
- description and source-code
```javascript
simpleListen = function (a, b){this.ua("q",{p:a},b)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.tf"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>tf (a, b)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.tf)
- description and source-code
```javascript
tf = function (a, b){var c=a.path.toString(),d=a.ja();this.f("Unlisten called for "+c+" "+d);D(nf(a.m)||!T(a.m),"unlisten() called for
 non-default but complete query");if(Eg(this,c,d)&&this.ma){var e=mf(a.m);this.f("Unlisten on "+c+" for "+d);c={p:c};b&&(c.q=e,c
.t=b);this.ua("n",c)}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.ua"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>ua (a, b, c)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.ua)
- description and source-code
```javascript
ua = function (a, b, c){var d=++this.kg;a={r:d,a:a,b:b};this.f(x(a));D(this.ma,"sendRequest call when we're not connected not allowed.");
this.Ea.ua(a);c&&(this.Ed[d]=c)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.ud"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>ud (a)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.ud)
- description and source-code
```javascript
ud = function (a){if("r"in a){this.f("from server: "+x(a));var b=a.r,c=this.Ed[b];c&&(delete this.Ed[b],c(a.b))}else{if("error"in a)throw
"A server-side error has occurred: "+a.error;"a"in a&&(b=a.a,a=a.b,this.f("handleServerMessage",b,a),"d"===b?this.Eb(a.p,a.d,!1,
a.t):"m"===b?this.Eb(a.p,a.d,!0,a.t):"c"===b?Kg(this,a.p,a.q):"ac"===b?Gg(this,a.s,a.d):"sd"===b?this.xe?this.xe(a):"msg"in a&&"
undefined"!==typeof console&&console.log("FIREBASE: "+a.msg.replace("\n","\nFIREBASE: ")):Rb("Unrecognized action received from server: "+
x(b)+"\nAre you using the latest client?"))}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.vd"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>vd (a, b)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.vd)
- description and source-code
```javascript
vd = function (a, b){this.ma?Hg(this,"oc",a,null,b):this.Hc.push({ue:a,action:"oc",data:null,G:b})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.we"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.kc.prototype.</span>we (a)](#apidoc.element.firebase.database.TEST_ACCESS.kc.prototype.we)
- description and source-code
```javascript
we = function (a){this.ma&&(a={c:a},this.f("reportStats",a),this.ua("s",a,function(a){"ok"!==a.s&&this.f("reportStats","Error sending
 stats: "+a.d)}))}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.database.TEST_ACCESS.xf.prototype"></a>[module firebase.database.TEST_ACCESS.xf.prototype](#apidoc.module.firebase.database.TEST_ACCESS.xf.prototype)

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.xf.prototype.toString"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.xf.prototype.</span>toString ()](#apidoc.element.firebase.database.TEST_ACCESS.xf.prototype.toString)
- description and source-code
```javascript
toString = function (){var a=(this.Pc?"https://":"http://")+this.host;this.ef&&(a+="<"+this.ef+">");return a}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.database.TEST_ACCESS.yf.prototype"></a>[module firebase.database.TEST_ACCESS.yf.prototype](#apidoc.module.firebase.database.TEST_ACCESS.yf.prototype)

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.yf.prototype.close"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.yf.prototype.</span>close ()](#apidoc.element.firebase.database.TEST_ACCESS.yf.prototype.close)
- description and source-code
```javascript
close = function (){2!==this.Ta&&(this.f("Closing realtime connection."),this.Ta=2,ug(this),this.ia&&(this.ia(),this.ia=null))}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.yf.prototype.sendRequest"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.yf.prototype.</span>sendRequest (a)](#apidoc.element.firebase.database.TEST_ACCESS.yf.prototype.sendRequest)
- description and source-code
```javascript
sendRequest = function (a){yg(this,{t:"d",d:a})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.yf.prototype.ua"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.yf.prototype.</span>ua (a)](#apidoc.element.firebase.database.TEST_ACCESS.yf.prototype.ua)
- description and source-code
```javascript
ua = function (a){yg(this,{t:"d",d:a})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.database.TEST_ACCESS.yf.prototype.ud"></a>[function <span class="apidocSignatureSpan">firebase.database.TEST_ACCESS.yf.prototype.</span>ud (a)](#apidoc.element.firebase.database.TEST_ACCESS.yf.prototype.ud)
- description and source-code
```javascript
ud = function (a){vg(this);this.re(a)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.firebase.serverAuth"></a>[module firebase.serverAuth](#apidoc.module.firebase.serverAuth)

#### <a name="apidoc.element.firebase.serverAuth.serverAuth"></a>[function <span class="apidocSignatureSpan">firebase.</span>serverAuth (c)](#apidoc.element.firebase.serverAuth.serverAuth)
- description and source-code
```javascript
serverAuth = function (c){void 0===c&&(c=a());"function"!==typeof c[b]&&M("invalid-app-argument",{name:b});return c[b]()}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.firebase.serverAuth.Auth"></a>[function <span class="apidocSignatureSpan">firebase.serverAuth.</span>Auth (app_)](#apidoc.element.firebase.serverAuth.Auth)
- description and source-code
```javascript
Auth = function (app_) {
  if (!('options' in app_)) {
    throw new Error('First parameter to Auth constructor must be an instance of firebase.App');
  }

  var cachedToken_ = null;
  var tokenListeners_ = [];

  var credential_ = app_.options.credential;
  var serviceAccount_ = getServiceAccount(app_);
  var tokenGenerator_;

  if (credential_ && typeof credential_.getAccessToken !== 'function') {
    throw new Error('Called firebase.initializeApp with an invalid credential parameter');
  }
  if (serviceAccount_) {
    credential_ = credential_ || new credential.CertCredential(serviceAccount_);
    tokenGenerator_ = new FirebaseTokenGenerator(serviceAccount_);
  } else {
    credential_ = credential_ || new credential.UnauthenticatedCredential();
  }

<span class="apidocCodeCommentSpan">  /**
   * Defines the app property with a getter but no setter.
   */
</span>  Object.defineProperty(this, 'app', {
    get: function() { return app_; }
  });

  /**
   * Creates a new custom token that can be sent back to a client to use with
   * signInWithCustomToken.
   *
   * @param {string} uid The uid to use as the subject
   * @param {Object=} developerClaims Optional additional claims to include
   *                                  in the payload of the JWT
   *
   * @return {string} The JWT for the provided payload.
   */
  this.createCustomToken = function(uid, developerClaims) {
    /* eslint-disable no-console */
    console.log(
      'createCustomToken() is deprecated and will be removed in the next major version. You ' +
      'should instead use the same method in the 'firebase-admin' package. See ' +
      'https://firebase.google.com/docs/admin/setup for details on how to get started.'
    );
    /* eslint-enable no-console */

    if (typeof tokenGenerator_ === 'undefined') {
      throw new Error('Must initialize FirebaseApp with a service account to call auth().createCustomToken()');
    }
    return tokenGenerator_.createCustomToken(uid, developerClaims);
  };

  /**
   * Verifies a JWT auth token. Returns a Promise with the tokens claims. Rejects
   * the promise if the token could not be verified.
   *
   * @param {string} idToken The JWT to verify
   * @return {Object} The Promise that will be fulfilled after a successful
   *                  verification.
   */
  this.verifyIdToken = function(idToken) {
    /* eslint-disable no-console */
    console.log(
      'verifyIdToken() is deprecated and will be removed in the next major version. You ' +
      'should instead use the same method in the 'firebase-admin' package. See ' +
      'https://firebase.google.com/docs/admin/setup for details on how to get started.'
    );
    /* eslint-enable no-console */

    if (typeof tokenGenerator_ === 'undefined') {
      throw new Error('Must initialize FirebaseApp with a service account to call auth().verifyIdToken()');
    }
    return tokenGenerator_.verifyIdToken(idToken);
  };

  this.INTERNAL = {};

  /**
   * Deletes the service and it's associated resources
   */
  this.INTERNAL.delete = function() {
    // There are no resources to clean up
    return firebase.Promise.resolve();
  };

  /**
   * Internal method: Gets an auth token for the associated app.
   * @param {boolean} forceRefresh Forces a token refresh
   * @return {Object} The Promise that will be fulfilled with the current or new
   *                  token
   */
  this.INTERNAL.getToken = function(forceRefresh) {
    var expired = cachedToken_ && cachedToken_.expirationTime < Date.now();
    if (cachedToken_ && !forceRefresh && !expired) {
      return firebase.Promise.resolve(cachedToken_);
    } else {
      // credential_ may be an external class; resolving it in a promise helps us
      // protect against exceptions and upgrades the result to a promise in all cases.
      return firebase.Promise.resolve().then(function() {
        return credential_.getAccessToken();
      }).then(function(result) {
        if (result === null) {
          return null;
        }
        if (typeof result !== 'object' ||
            typeof result.expires_in !== 'number' ||
            typeof result.access_toke ...
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

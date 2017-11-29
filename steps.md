in ext-angular-generator

npm i
node all.js modern
node all.js classic

cd ext-angular-modern
npm i
gulp lib
gulp exp
npm version patch
npm publish

cd ..

cd ext-angular-classic
npm i
gulp lib
gulp exp
npm version patch
npm publish

cd ..

cd ext-angular-demos
npm i
npm version patch
npm publish

## This workspace was made for the [Kiwi Bundle](https://github.com/theblueforest/kiwi-bundle)

```console
# Step 1 : clone this repo
git clone git@github.com:theblueforest/kiwi-workspace.git kiwi
cd kiwi

# Step 2 : clone the bundle
git clone git@github.com:theblueforest/kiwi-bundle.git bundle
cd bundle

# Step 3 : install bundle dependencies and create a link module
yarn && yarn link # If you use Yarn
npm install && npm link # Otherwise with npm

# Step 4 : clone the demo
cd -
git clone git@github.com:theblueforest/kiwi-demo.git demo
cd demo

# Step 5 : make a local link to the bundle module
yarn link kiwi-bundle # If you use Yarn
npm link kiwi-bundle # Otherwise with npm

# Step 6 : if you use VSCode, here we go !
cd -
code kiwi.code-workspace # Open in VSCode
```

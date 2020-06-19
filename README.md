### Github Packages
---
https://github.com/takagotch?tab=packages




```docker
cat ~/GH_TOKEN.txt | docker login docker.pkg.github.com -u takagotch --password-stdin
docker tag IMAGE_ID docker.pkg.github.com/takagotch/repository-name/IMAGE_NAME:VERSION
docker push docker.pkg.github.com/takagotch/repository-name/IMAGE_NAME:VERSION


```

```npm
"publishConfig": { "registry": "https://npm.pkg.github.com/"}

npm login --registry=https://npm.pkg.github.com/
npm publish


```

```ruby
echo ":github: Bearer GH_TOKEN" >> ~/.gem/credentials
gem build repository-name.gmespec
gem push -key github --host https://rubygems.pkg.github.com/takagotch repository-name-1.0.0.gem


```


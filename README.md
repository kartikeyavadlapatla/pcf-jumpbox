# pcf-jumpbox

https://github.com/cloudfoundry-community/jumpbox-boshrelease

https://bosh.io/releases/github.com/cloudfoundry/os-conf-release?all=1

Replace yaml in manifest folder and run the bosh command

bosh -e <env> -d jumpbox deploy \
  -o manifests/jumpbox_options.yml \
  manifests/jumpbox.yml

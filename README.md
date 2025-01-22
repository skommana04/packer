updated the packer-vars.json with the AWS credentials before building or validating

after updating the packer.json just run these 2 steps. No need of packer init

packer validate -var-file=packer-vars.json packer.json
packer build -var-file=packer-vars.json packer.json

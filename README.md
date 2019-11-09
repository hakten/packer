1. Clone Repo 
2. cd tools 
3. packer validate -var-file=../configurations/regions/eu-west-1/eu-west-1.json golden_image.json
4. packer build    -var-file=../configurations/regions/eu-west-1/eu-west-1.json golden_image.json



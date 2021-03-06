# EPIC: Hello World locally

## USs

### To have application as a container

* Clone the repo
* Create branch
* Create docker file
* Create service.yml
* Build and Push into docker hub 
`docker build --tag helloworld-kotlin:x.0.0 .`
`docker run -p 8080:8080 helloworld-kotlin:4.0.0`

### To have container deployed on k8 env

* Create helm chart skeleton
`helm3 create  helloworld*kotlin`
* Set up value.yaml
* Set up template.yaml
* Deploy on k8
`helm3 install helloworld-kotlin`
`helm3 install helloworld-kotlin ./helloworld-kotlin/`

### To have a pipeline (gitlaci)

* Create stages

# EPIC: Hello World on AWS :rocket:

## USs

### To have an infrastructure provisioned on AWS capable to support containers

* Create EC2
* Create ASG
* Creat SG
* Creat sg ELB
* Create ELB
* Create var
* Create bootstrap

### To have a pipeline coded (gitlaci)

* Create stages with env vars

### References

[knativeDev](https://knative.dev/v0.13-docs/serving/samples/hello-world/helloworld-kotlin/)
[bitnami](https://docs.bitnami.com/tutorials/deploy-go-application-kubernetes-helm)
[labGetNinja](https://labs.getninjas.com.br/construa-um-c%C3%B3digo-reutiliz%C3%A1vel-no-terraform-com-a-ajuda-de-m%C3%B3dulos-6894a507735b)
[nanoShots](https://www.nanoshots.com.br/2017/12/realizando-deploys-em-auto-scaling.html)
[wikiCentos](https://wiki.centos.org/Cloud/AWS)
[docsGitLab](https://docs.gitlab.com/ee/user/markdown.html#url-auto-linking)
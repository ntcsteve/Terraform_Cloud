## Observability as Code with Terraform and New Relic

### Technical Overview

This is the demonstration Github repository I used together with [Terraform Cloud](https://app.terraform.io) to encrypt senstive data in the UI. 
It’s possible to treat configurations as code with New Relic, called “**Observability as code**”, adopting infrastructure as code for your monitoring and alerting environment.

These materials were prepared as part of my technical talk at DevOps Days 2019 (Taiwan). Further details about implementating Terraform with New Relic can be found in the **Terraform and New Relic Best Practice Guide** and the **Additional Links** section. 

### Notes

The provided tf files **WILL NOT** work out of the box. 

Please replace the following: 
- <'ADMIN_KEY'> with your New Relic admin API key
- <'APM_APPNAME'> with your designated application name
- <'EMAIL'> with your preferred email address

Many [Terraform recommeded practices](https://www.terraform.io/docs/cloud/guides/recommended-practices/index.html) are applicable especially when it comes to encrypting [New Relic Admin API keys](https://www.terraform.io/docs/state/sensitive-data.html). 

### Addtional Links

[Original Github Link](https://github.com/ntcsteve/Terraform_NewRelic)

[DevOps Days 2019 (Taiwan) Presentation - Mandarin](https://www.dropbox.com/s/iqbm5qo363rzp89/Observability%20as%20Code%20%28DevOps%20Days%20TW%202019%29%20Traditional%20Mandarin.pdf?dl=0)

[DevOps Days 2019 (Taiwan) Presentation - English](https://www.dropbox.com/s/hahglmuilx3ov2g/Observability%20as%20Code%20%28DevOps%20Days%20TW%202019%29%20English.pdf?dl=0)

[Terraform and New Relic Best Practice Guide](https://www.dropbox.com/s/yp2tq72et0rrf7n/Terraform%20with%20New%20Relic%20Best%20Practices.pdf?dl=0)

[Modular Infrastructure Deployments at New Relic with Terraform](https://www.hashicorp.com/resources/modular-infrastructure-deployments-new-relic-terraform)
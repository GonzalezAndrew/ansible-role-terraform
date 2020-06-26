Role Name
=========

Installs Terraform a infrastructure as code software tool.

Requirements
------------

None.

Role Variables
--------------

Below are the role variables and their default values.
```
terraform_version: 0.12.6
```
The Terraform version to install.
```
terraform_bin_path: /usr/local/bin
```
The location where the Teraform binary will be installed. Hashicorp recommends to install the Terraform binary to be included by your system `$PATH`.
```
terraform_os: "linux"
terraform_arch: "amd64"
```
The system operating system and architecture to use.
``` 
terraform_download_url: " https://releases.hashicorp.com/terraform/{{ terraform_version }}/terraform_{{ terraform_version }}_{{ terraform_os }}_{{ terraform_arch }}.zip"
```
The Teraform download url.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - gonzalezandrew.terraform

License
-------

MIT

Author Information
------------------

- [GitHub](https://github.com/GonzalezAndrew)
- [LinkedIn](https://www.linkedin.com/in/-andrew-gonzalez/)
- [Twitter](https://twitter.com/_GonzalezAndrew)
# Terraform is an infrastructure provisioning tools. It allows automation and management of infrastructure.

Terraform is open source.

Terraform uses declarative language.

Terraform is also simple to learn.

Idempotence -- Meaning it runs once and remembers if the code has been run before. This will not be run again

It can be used with multiple cloud vendors.

Ansible vs Terraform

Similarities
They are both infrastructure as a code.
They both provision, configure and manage the infrastructure.

Differences
Terraform - it is mainly an infrastructure provisioning tools. It can also deploy apps. It is relatively new and more advanced in orchestration.

Ansible - It is maninly a configuration tool. It can also configure infrastructure, deploy apps, install/update software. It is more mature.

---

Terraform can be used to replicate infrastructure on multiple servers.

## TERRAFORM ARCHITECTURE

_Terraform Cor_

It uses 2 input sources. **Terraform config which is the code that is written and**
**Terraform state which stores the current state of the setup**

_Terraform provider_
The providers checks the platform that is been communicated with.

Different stages of Terraform

1. Init
2. plan
3. apply

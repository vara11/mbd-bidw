# Business Intelligence and Data Warehouse Course

## Session 2

The topic of this session is the components of **Business Intelligence**. This repository includes the extra content discuss in class.

## FAQ

### Do we have different environment in DW/BI?

Yes. We can have four environments:

 - **Production Environment (PROD)**: DW/BI system production-ready
 - **Developer Environment (Developer Sandbox)**: DW/BI system’s development environment
 - **Quality Assurance Environment (QA)**: all developers’ changes are integrated in this environment and the DW/BI system quality controls are performed
 - **Pre-production environment (PRE-PROD)**: is a production-like environment, tests and end-user demonstrations run on this environment
 
 A DW/BI must have, at least, the first two.
 
 ### Is it recommended to use Control Version System in DW/BI?
 
Yes. It is recommended to use a version control system (SCM) to version all artifacts created during the project: (schema, sql scripts, data, etls, reports,...). Some options: [git](https://git-scm.com), [SVN](https://subversion.apache.org/), [CVS](http://www.nongnu.org/cvs/).

### How we can provision the different environments?

This usually is called **IaC** (Infrastructure as Code). Infrastructure as Code is the approach to defining computing and network infrastructure through source code that can then be treated just like any software system. We can use, for example, [Ansible](https://www.ansible.com/), a platform that allows you to create YAML code for provisioning environments, and works together with [Vagrant](https://www.vagrantup.com/) which is a virtual environment manager.

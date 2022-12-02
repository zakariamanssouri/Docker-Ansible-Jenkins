# Docker-Ansible-Jenkins

<h3 align="center">Devops Project using  Jenkins , Ansible , Docker  for creating a CI-CD pipeline for automatically building and deploying a spring boot application as a docker container </h3>

---

## 📝 Table of Contents
- [About](#about)
- [Architecture](#Architecture)
- [Github WebHook](#github-webhook)
- [Ansible Plugin](#ansible-plugin)
- [Jenkins-pipeline](#jenkins-pipeline)
- [⛏️ Built Using](#build_using)



## 🧐 About <a name = "about"></a>
a devops project that uses Github - Jenkins - Ansible for creating a complete CI-CD pipeline for automating the build & deployment of a java micro service in a container 
## 🏁 Architecture <a name = "Architecture"></a>
This is the architecture of our Application

<div align="center">

![image](https://user-images.githubusercontent.com/80859231/205272482-1d1fed34-950b-47d8-b48e-b34335671021.png)


</div>



##  Github WebHook <a name = "github-webhook"></a>
Rather than using the traditional method for pulling the code from a git repository in a jenkins job which is pulling the code periodically at a configured 
interval, we will use the Jenkins GitHub Webhook which is used to trigger the action whenever Developers commit something into the repository.

<div align="center">

![image](https://user-images.githubusercontent.com/80859231/205273670-25caa2a9-9c47-4eeb-86aa-861e3f11fc22.png)

</div>

##  ⛏️ Built Using <a name = "built_using"></a>
- [Jenkins](https://spring.io/projects/spring-boot)
- [Docker](https://www.docker.com/) 
- [Ansible](https://www.ansible.com/)

## ✍️ Authors <a name = "authors"></a>
- [@zakariamanssouri](https://github.com/zakariamanssouri) 

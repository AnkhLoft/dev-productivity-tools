# 🚀dev-productivity-tools🚀

List of development productivity tools that help streamline and speed up our daily workflow

# Table of contents
1. [Monorepo projects](#monorepo-projects)<br>
    1.1. [Tools](#monorepo-project-tools)

## 1. Monorepo projects <a name="monorepo-projects"></a>

* **Q:** What is a monorepo?
* **A:** A monorepo is a software strategy that consists of having more than one project within the same repository. [Read more here](https://en.wikipedia.org/wiki/Monorepo)

<br>

* **Q:** Why do we need tools for this kind of projects?
* **A:** As our projects start to scale up the complexity of mantaining them starts to grow as well, so imagine having to maintain more than one project... :boom::boom::boom: Yeap, if you have been there, you know what I'm talking about, right?
That's why we need a good set of tools to help us reduce this complexity and workload.

### 1.1 Tools <a name="monorepo-project-tools"></a>
* **Yarn Workspaces** 
Yarn workspaces It's a Yarn built-in feature. It allows to setup multiple packages on the same repository and run a single command to start the installation dependencies for each of them. For me the biggest advantage of this feature is the way yarn manage all the project dependencies, because they will be all installed together giving the power to yarn to best optimize them.

<br>

* [Read more about Yarn Workspaces](https://classic.yarnpkg.com/lang/en/docs/workspaces/)
---
* **Volta** 
It is a tool manager, which helps you to install and run any js tool easily. One particular feature I really like about Volta is switching between multiple projects and not having to manually switch to a specific version of the tool(s) that particular project uses, Volta does that automatically for us!! **How cool is that!**

<br>

* **Install Volta** | [Homepage](https://volta.sh/)
`$ curl https://get.volta.sh | bash`

---

* **Lerna** 
Is a tool for managing projects with multiple packages. One feature that I really like within lerna is the possibility to run a single command and trigger one npm script for each package that we have in our project.:heartpulse: :heartpulse:

<br>

* **Install Lerna** | [Homepage](https://lerna.js.org/)
`$ npm install --global lerna`

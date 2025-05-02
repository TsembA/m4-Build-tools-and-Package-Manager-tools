# 🛠️ Build & Package Manager Tools Cheat Sheet

## 📦 What are Build and Package Manager Tools?

When deploying an application to a **production server**, we need to **package the code** into a **single, portable file** (called an **artifact**).  
This process is called **building the code**, and it is handled by **build tools** or **package manager tools**.

🔧 These tools also manage project dependencies, ensuring the correct versions of libraries are used.

---

## 📁 What is an Artifact?

* A **portable file** that contains your **application code + all dependencies**  
* Can be easily shared, moved, or deployed across different environments  
* Examples: `.jar`, `.zip`, `.tar.gz`, `.whl`, Docker images

---

## 🏗️ What Does "Building the Code" Mean?

* **Compiling** source code into binaries or bytecode 🧱  
* **Compressing** or bundling code into one file 📦  
* **Packaging** hundreds of files, configs, and dependencies into a single deployable unit 🎯

---

## 🗃️ What is an Artifact Repository?

* A **storage system for built artifacts and dependencies**  
* Useful for:
  - **Multiple deployments**
  - **Backup and version control**
  - **Sharing artifacts** across teams or environments
* Examples:
  - **Docker images** → DockerHub, Amazon ECR, Google Artifact Registry  
  - **General artifacts** → JFrog Artifactory, Sonatype Nexus

---

## 🧰 Build Tools by Language

| Language     | Tools Used                          |
|--------------|-------------------------------------|
| Java         | `Maven`, `Gradle` ☕                |
| JavaScript   | `npm`, `yarn`, `webpack` 🟨         |
| Python       | `pip` 🐍                           |
| C/C++        | `conan` 🧩                          |
| C# (.NET)    | `NuGet` 🧰                          |
| Go (Golang)  | `dep` 🐹                            |
| Ruby         | `RubyGems` 💎                       |

🔁 The **concepts** of build and dependency management are similar across languages!

---

## 🐳 Why Docker?

Docker is a **universal packaging solution** that replaces many traditional artifact types.

✅ Docker image = Your **app + OS-level dependencies**  
✅ Run the same image across **development**, **testing**, and **production**  
✅ Reduces complexity in managing multiple types of artifacts  
✅ Portable across all environments — "it works on my machine" becomes reality 💯

---

💡 With Docker, instead of dealing with `.jar`, `.zip`, `.whl`, `.tar.gz`, etc., you just manage a **Docker image**. One format, all use cases.

---

✒️ *Use this guide as a handy reference when working with build tools and artifact management in DevOps workflows.*


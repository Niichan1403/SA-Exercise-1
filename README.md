### 1. What is Docker? What is Docker Compose?

1.1. `Docker`

<details open>
  <summary></summary>
Docker is an open platform for developing, shipping, and running applications.

Docker allows you to separate your applications from your infrastructure so you can deliver software quickly. With Docker, you can manage your infrastructure in the same ways you manage your applications.

By taking advantage of Docker’s methodologies for shipping, testing, and deploying code quickly, you can significantly reduce the delay between writing code and running it in production.

  > Source: [Docker](https://docs.docker.com/get-docker/)
</details>


1.2. `Docker Compose`

Docker Compose is a tool for defining and running multi-container applications. It is the key to unlocking a streamlined and efficient development and deployment experience.

Compose simplifies the control of your entire application stack, making it easy to manage services, networks, and volumes in a single, comprehensible YAML configuration file. Then, with a single command, you create and start all the services from your configuration file.

Compose works in all environments; production, staging, development, testing, as well as CI workflows. It also has commands for managing the whole lifecycle of your application.

  > Source: [Docker Compose](https://docs.docker.com/compose/)

### 2. What is the difference between Unix, Linux, BSD and *nix

Source: [What is the difference between Unix, Linux, BSD and GNU?](https://unix.stackexchange.com/questions/104714/what-is-the-difference-between-unix-linux-bsd-and-gnu)

### 3. Alpine vs Ubuntu
3.1. `Alpine`

  Alpine is a lightweight Linux distribution that only occupies about 5 MB of disk space. It is designed to be simple, fast, and secure, with minimal dependencies and features. Alpine is ideal for creating small and efficient Docker images, which can reduce the build time, the storage space, and the network bandwidth. Alpine also has a built-in package manager called apk, which allows you to install additional software as needed. However, Alpine also has some drawbacks. For example, it uses a different C library than most Linux distributions, which can cause compatibility issues with some applications or libraries. Alpine also has fewer packages and documentation available than Ubuntu, which can make it harder to troubleshoot or customize.

  > Source: [Alpine](https://www.linkedin.com/advice/0/how-do-you-scale-deploy-docker-alpine-ubuntu-containers)

3.2. `Ubuntu`

  Ubuntu is a popular and widely used Linux distribution that offers a large and diverse collection of packages, tools, and documentation. Ubuntu is well-supported and updated regularly, which can make it easier to find and fix bugs, security issues, or dependencies. Ubuntu also has a familiar and user-friendly interface, which can make it more comfortable and convenient for developers and users. However, Ubuntu also has some disadvantages. For example, it is much larger and heavier than Alpine, which can increase the build time, the storage space, and the network bandwidth. Ubuntu also has more features and services running in the background, which can consume more resources and introduce more complexity and vulnerability.

  > Source: [Ubuntu](https://www.linkedin.com/advice/0/how-do-you-scale-deploy-docker-alpine-ubuntu-containers)

### 4. VNC

VNC stands for Virtual Network Computing. It is a cross-platform screen sharing system that was created to remotely control another computer. This means that a computer’s screen, keyboard, and mouse can be used from a distance by a remote user from a secondary device as though they were sitting right in front of it.   

VNC works on a client/server model. A server component is installed on the remote computer (the one you want to control), and a VNC viewer, or client, is installed on the device you want to control from. This can include another computer, a tablet, or a mobile phone. When the server and viewer are connected, the server transmits a copy of the remote computer’s screen to the viewer.  

Not only can the remote user see everything on the remote computer’s screen, but the program also allows for keyboard and mouse commands to work on the remote computer from afar, so the connected user has full control (after being granted permission from the remote computer).

  > Source: [VNC](https://discover.realvnc.com/what-is-vnc-remote-access-technology)


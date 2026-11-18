# L


Windows PowerShell 5.1
Copyright (C) Microsoft Corporation. All rights reserved.

PS C:\WINDOWS\System32> docker --version
Docker version 29.8.0, build 88096ef
PS C:\WINDOWS\System32> docker compose version
Docker Compose version v5.5.1
PS C:\WINDOWS\System32> docker info
Client:
 Version:    29.8.0
 Context:    desktop-linux
 Debug Mode: false
 Plugins:
  agent: Docker AI Agent Runner (Docker Inc.)
    Version:  v1.140.0
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-agent.exe
  ai: Docker AI Agent - Ask Gordon (Docker Inc.)
    Version:  v1.31.0
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-ai.exe
  buildx: Docker Buildx (Docker Inc.)
    Version:  v0.37.1
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-buildx.exe
  compose: Docker Compose (Docker Inc.)
    Version:  v5.5.1
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-compose.exe
  debug: Get a shell into any image or container (Docker Inc.)
    Version:  0.0.47
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-debug.exe
  desktop: Docker Desktop commands (Docker Inc.)
    Version:  v0.4.4
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-desktop.exe
  dhi: CLI for managing Docker Hardened Images (Docker Inc.)
    Version:  v0.0.7
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-dhi.exe
  extension: Manages Docker extensions (Docker Inc.)
    Version:  v0.2.31
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-extension.exe
  init: Creates Docker-related starter files for your project (Docker Inc.)
    Version:  v1.4.0
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-init.exe
  mcp: Docker MCP Plugin (Docker Inc.)
    Version:  v0.43.3
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-mcp.exe
  model: Docker Model Runner (Docker Inc.)
    Version:  v1.2.6
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-model.exe
  offload: Docker Offload (Docker Inc.)
    Version:  v0.6.27
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-offload.exe
  pass: Docker Pass Secrets Manager Plugin (beta) (Docker Inc.)
    Version:  v0.2.2
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-pass.exe
  sandbox: "docker sandbox" is deprecated, use Docker Sandboxes instead (Docker Inc.)
    Version:  v0.13.0
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-sandbox.exe
  scout: Docker Scout (Docker Inc.)
    Version:  v1.24.0
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-scout.exe

Server:
failed to connect to the docker API at npipe:////./pipe/dockerDesktopLinuxEngine; check if the path is correct and if the daemon is running: open //./pipe/dockerDesktopLinuxEngine: The system cannot find the file specified.
PS C:\WINDOWS\System32> docker info
Client:
 Version:    29.8.0
 Context:    desktop-linux
 Debug Mode: false
 Plugins:
  agent: Docker AI Agent Runner (Docker Inc.)
    Version:  v1.140.0
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-agent.exe
  ai: Docker AI Agent - Ask Gordon (Docker Inc.)
    Version:  v1.31.0
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-ai.exe
  buildx: Docker Buildx (Docker Inc.)
    Version:  v0.37.1
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-buildx.exe
  compose: Docker Compose (Docker Inc.)
    Version:  v5.5.1
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-compose.exe
  debug: Get a shell into any image or container (Docker Inc.)
    Version:  0.0.47
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-debug.exe
  desktop: Docker Desktop commands (Docker Inc.)
    Version:  v0.4.4
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-desktop.exe
  dhi: CLI for managing Docker Hardened Images (Docker Inc.)
    Version:  v0.0.7
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-dhi.exe
  extension: Manages Docker extensions (Docker Inc.)
    Version:  v0.2.31
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-extension.exe
  init: Creates Docker-related starter files for your project (Docker Inc.)
    Version:  v1.4.0
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-init.exe
  mcp: Docker MCP Plugin (Docker Inc.)
    Version:  v0.43.3
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-mcp.exe
  model: Docker Model Runner (Docker Inc.)
    Version:  v1.2.6
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-model.exe
  offload: Docker Offload (Docker Inc.)
    Version:  v0.6.27
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-offload.exe
  pass: Docker Pass Secrets Manager Plugin (beta) (Docker Inc.)
    Version:  v0.2.2
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-pass.exe
  sandbox: "docker sandbox" is deprecated, use Docker Sandboxes instead (Docker Inc.)
    Version:  v0.13.0
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-sandbox.exe
  scout: Docker Scout (Docker Inc.)
    Version:  v1.24.0
    Path:     C:\Users\APURVA-LAP\.docker\cli-plugins\docker-scout.exe

Server:
 Containers: 0
  Running: 0
  Paused: 0
  Stopped: 0
 Images: 1
 Server Version: 29.8.0
 Storage Driver: overlayfs
  driver-type: io.containerd.snapshotter.v1
 Logging Driver: json-file
 Cgroup Driver: cgroupfs
 Cgroup Version: 2
 Plugins:
  Volume: local
  Network: bridge host ipvlan macvlan null overlay
  Log: awslogs fluentd gcplogs gelf journald json-file local splunk syslog
 CDI spec directories:
  /etc/cdi
  /var/run/cdi
 Discovered Devices:
  cdi: docker.com/gpu=webgpu
 Swarm: inactive
 Runtimes: runc io.containerd.runc.v2 nvidia
 Default Runtime: runc
 Init Binary: docker-init
 containerd version: 1294c24a7da8e5a793ed378161673abe94118892
 runc version: v1.5.1-0-g8f2685a4
 init version: de40ad0
 Security Options:
  seccomp
   Profile: builtin
  cgroupns
 Kernel Version: 6.18.33.2-microsoft-standard-WSL2
 Operating System: Docker Desktop
 OSType: linux
 Architecture: x86_64
 CPUs: 16
 Total Memory: 7.572GiB
 Name: docker-desktop
 ID: 3abdedc9-acd2-4dac-9710-f0a5c057c23f
 Docker Root Dir: /var/lib/docker
 Debug Mode: false
 HTTP Proxy: http.docker.internal:3128
 HTTPS Proxy: http.docker.internal:3128
 No Proxy: hubproxy.docker.internal
 Labels:
  com.docker.desktop.address=npipe://\\.\pipe\docker_cli
 Experimental: false
 Insecure Registries:
  hubproxy.docker.internal:5555
  127.0.0.0/8
  ::1/128
 Live Restore Enabled: false
 Firewall Backend: iptables

PS C:\WINDOWS\System32> docker run hello-world
Unable to find image 'hello-world:latest' locally
latest: Pulling from library/hello-world
4f55086f7dd0: Pull complete
d5e71e642bf5: Download complete
Digest: sha256:1e4c05b897a751332ce85c7e9449da2d93514ea2dea6dbb0e2753c9e949b2bfa
Status: Downloaded newer image for hello-world:latest

Hello from Docker!
This message shows that your installation appears to be working correctly.

To generate this message, Docker took the following steps:
 1. The Docker client contacted the Docker daemon.
 2. The Docker daemon pulled the "hello-world" image from the Docker Hub.
    (amd64)
 3. The Docker daemon created a new container from that image which runs the
    executable that produces the output you are currently reading.
 4. The Docker daemon streamed that output to the Docker client, which sent it
    to your terminal.

To try something more ambitious, you can run an Ubuntu container with:
 $ docker run -it ubuntu bash

Share images, automate workflows, and more with a free Docker ID:
 https://hub.docker.com/

For more examples and ideas, visit:
 https://docs.docker.com/get-started/

PS C:\WINDOWS\System32> docker ps -a
CONTAINER ID   IMAGE         COMMAND    CREATED          STATUS                      PORTS     NAMES
1127bbb560ea   hello-world   "/hello"   41 seconds ago   Exited (0) 40 seconds ago             modest_benz
PS C:\WINDOWS\System32>










Windows PowerShell 5.1
Copyright (C) Microsoft Corporation. All rights reserved.

PS C:\WINDOWS\System32> mkdir DockerJavaDemo
mkdir : Access to the path 'DockerJavaDemo' is denied.
At line:1 char:1
+ mkdir DockerJavaDemo
+ ~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : PermissionDenied: (C:\WINDOWS\System32\Docke
   rJavaDemo:String) [New-Item], UnauthorizedAccessException
    + FullyQualifiedErrorId : CreateDirectoryUnauthorizedAccessError,Micro
   soft.PowerShell.Commands.NewItemCommand

PS C:\WINDOWS\System32> cd $HOME\Documents
PS C:\Users\APURVA-LAP\Documents> mkdir DockerJavaDemo


    Directory: C:\Users\APURVA-LAP\Documents


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        11/18/2026   7:22 AM                DockerJavaDemo


PS C:\Users\APURVA-LAP\Documents> cd DockerJavaDemo
PS C:\Users\APURVA-LAP\Documents\DockerJavaDemo> notepad App.java
PS C:\Users\APURVA-LAP\Documents\DockerJavaDemo> notepad Dockerfile
PS C:\Users\APURVA-LAP\Documents\DockerJavaDemo> dir


    Directory: C:\Users\APURVA-LAP\Documents\DockerJavaDemo


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        11/18/2026   7:23 AM            140 App.java
-a----        11/18/2026   7:26 AM            107 Dockerfile.txt


PS C:\Users\APURVA-LAP\Documents\DockerJavaDemo> notepad Dockerfile
PS C:\Users\APURVA-LAP\Documents\DockerJavaDemo> dir


    Directory: C:\Users\APURVA-LAP\Documents\DockerJavaDemo


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        11/18/2026   7:23 AM            140 App.java
-a----        11/18/2026   7:29 AM            107 Dockerfile.txt


PS C:\Users\APURVA-LAP\Documents\DockerJavaDemo> Rename-Item Dockerfile.txt Dockerfile
PS C:\Users\APURVA-LAP\Documents\DockerJavaDemo> dir


    Directory: C:\Users\APURVA-LAP\Documents\DockerJavaDemo


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        11/18/2026   7:23 AM            140 App.java
-a----        11/18/2026   7:29 AM            107 Dockerfile


PS C:\Users\APURVA-LAP\Documents\DockerJavaDemo> docker build -t my-java-app .
Failed to initialize: unable to resolve docker endpoint: context "desktop-linux": open C:\Users\APURVA-LAP\.docker\contexts\meta\fe9c6bd7a66301f49ca9b6a70b217107cd1284598bfc254700c989b916da791e\meta.json: The process cannot access the file because it is being used by another process.

What's next:
    Debug this build failure with Gordon → docker ai "help me fix this build failure"
PS C:\Users\APURVA-LAP\Documents\DockerJavaDemo> docker build -t my-java-app .
[+] Building 74.4s (10/10) FINISHED                    docker:desktop-linux
 => [internal] load build definition from Dockerfile                   0.1s
 => => transferring dockerfile: 144B                                   0.0s
 => [internal] load metadata for docker.io/library/eclipse-temurin:21  5.0s
 => [auth] library/eclipse-temurin:pull token for registry-1.docker.i  0.0s
 => [internal] load .dockerignore                                      0.1s
 => => transferring context: 2B                                        0.0s
 => [1/4] FROM docker.io/library/eclipse-temurin:21-jdk@sha256:db5cc  66.9s
 => => resolve docker.io/library/eclipse-temurin:21-jdk@sha256:db5cc6  0.0s
 => => sha256:1a4d3ce8dc865f660b6d5fddfd7a71eeac21d4e 2.46kB / 2.46kB  0.4s
 => => sha256:56b30dcd928e09edc41b3d531da0f889509adc9b3c4 160B / 160B  0.8s
 => => sha256:68397b0ee36ada913324abbd10f763c03c 158.42MB / 158.42MB  64.5s
 => => sha256:a252cd0b56603e67d824736bff2f014f1518 24.06MB / 24.06MB  15.3s
 => => sha256:96aae9022e0e1b310a415e7c2ff1b435d853e8eabb2 389B / 389B  0.9s
 => => sha256:517b871c26eac1b24d47992388bcc20e2afb 42.17MB / 42.17MB  30.4s
 => => extracting sha256:517b871c26eac1b24d47992388bcc20e2afba3643a89  1.7s
 => => extracting sha256:96aae9022e0e1b310a415e7c2ff1b435d853e8eabb27  0.1s
 => => extracting sha256:a252cd0b56603e67d824736bff2f014f15182b108ab8  0.8s
 => => extracting sha256:68397b0ee36ada913324abbd10f763c03cb2998a271a  2.0s
 => => extracting sha256:56b30dcd928e09edc41b3d531da0f889509adc9b3c49  0.0s
 => => extracting sha256:1a4d3ce8dc865f660b6d5fddfd7a71eeac21d4e16be9  0.0s
 => [internal] load build context                                      0.1s
 => => transferring context: 177B                                      0.0s
 => [2/4] WORKDIR /app                                                 0.3s
 => [3/4] COPY App.java .                                              0.1s
 => [4/4] RUN javac App.java                                           1.0s
 => exporting to image                                                 0.7s
 => => exporting layers                                                0.4s
 => => exporting manifest sha256:3e3d67ce200d5de6bd0d6f835ee8cda03107  0.0s
 => => exporting config sha256:98985ccd844ae526114f9615d7c7294640d064  0.0s
 => => exporting attestation manifest sha256:5e1a2a058b541c52314a7dab  0.0s
 => => exporting manifest list sha256:a0b18a1cec74de1e7a829c15a2a93a4  0.0s
 => => naming to docker.io/library/my-java-app:latest                  0.0s
 => => unpacking to docker.io/library/my-java-app:latest               0.1s

View build details: docker-desktop://dashboard/build/desktop-linux/desktop-linux/jsj1blx9wu72v092frfft9of8
PS C:\Users\APURVA-LAP\Documents\DockerJavaDemo> docker image
Usage:  docker image COMMAND

Manage images

Commands:
  build       Build an image from a Dockerfile
  history     Show the history of an image
  import      Import the contents from a tarball to create a filesystem image
  inspect     Display detailed information on one or more images
  load        Load an image from a tar archive or STDIN
  ls          List images
  prune       Remove unused images
  pull        Download an image from a registry
  push        Upload an image to a registry
  rm          Remove one or more images
  save        Save one or more images to a tar archive (streamed to STDOUT by default)
  tag         Create a tag TARGET_IMAGE that refers to SOURCE_IMAGE

Run 'docker image COMMAND --help' for more information on a command.
PS C:\Users\APURVA-LAP\Documents\DockerJavaDemo> docker image ls
                                                        i Info →   U  In Use
IMAGE                 ID             DISK USAGE   CONTENT SIZE   EXTRA
crud-backend:latest   935460bc3f3d        510MB          149MB
hello-world:latest    1e4c05b897a7       25.9kB         9.49kB    U
my-java-app:latest    a0b18a1cec74        724MB          225MB
PS C:\Users\APURVA-LAP\Documents\DockerJavaDemo> done
done : The term 'done' is not recognized as the name of a cmdlet,
function, script file, or operable program. Check the spelling of the
name, or if a path was included, verify that the path is correct and try
again.
At line:1 char:1
+ done
+ ~~~~
    + CategoryInfo          : ObjectNotFound: (done:String) [], CommandNot
   FoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\APURVA-LAP\Documents\DockerJavaDemo> docker run --name my-java-container my-java-app
Hello from Java Docker Container!
PS C:\Users\APURVA-LAP\Documents\DockerJavaDemo> docker ps -a
CONTAINER ID   IMAGE         COMMAND                  CREATED              STATUS                      PORTS     NAMES
07acd91fccc3   my-java-app   "/__cacert_entrypoin…"   About a minute ago   Exited (0) 58 seconds ago             my-java-container
1127bbb560ea   hello-world   "/hello"                 27 minutes ago       Exited (0) 27 minutes ago             modest_benz
PS C:\Users\APURVA-LAP\Documents\DockerJavaDemo>


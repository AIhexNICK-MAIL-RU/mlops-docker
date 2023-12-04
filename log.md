Last login: Sun Dec  3 12:06:20 on ttys000

The default interactive shell is now zsh.
To update your account to use zsh, please run `chsh -s /bin/zsh`.
For more details, please visit https://support.apple.com/kb/HT208050.
(base) MacBook-Pro-ivan:~ ivan$ cd devops-mlops
(base) MacBook-Pro-ivan:devops-mlops ivan$ cd practic
(base) MacBook-Pro-ivan:practic ivan$ cd docker
(base) MacBook-Pro-ivan:docker ivan$ vim Dockerfile
(base) MacBook-Pro-ivan:docker ivan$ docker build -t nginx-php-fpm:php80 . # PHP8
Cannot connect to the Docker daemon at unix:///var/run/docker.sock. Is the docker daemon running?
ERRO[0000] Can't add file /Users/ivan/devops-mlops/practic/docker/html/css/skeleton.min.css to tar: io: read/write on closed pipe 
(base) MacBook-Pro-ivan:docker ivan$ docker build -t nginx-php-fpm:php80 . # PHP80
Cannot connect to the Docker daemon at unix:///var/run/docker.sock. Is the docker daemon running?
(base) MacBook-Pro-ivan:docker ivan$ -y
-bash: -y: command not found
(base) MacBook-Pro-ivan:docker ivan$ y
-bash: y: command not found
(base) MacBook-Pro-ivan:docker ivan$ docker build -t nginx-php-fpm:php80 . # PHP80
Cannot connect to the Docker daemon at unix:///var/run/docker.sock. Is the docker daemon running?
(base) MacBook-Pro-ivan:docker ivan$ 
(base) MacBook-Pro-ivan:docker ivan$ y
-bash: y: command not found
(base) MacBook-Pro-ivan:docker ivan$ docker build -t nginx-php-fpm:php80 . # PHP80
ERRO[0000] Can't add file /Users/ivan/devops-mlops/practic/docker/html/css/skeleton.min.css to tar: io: read/write on closed pipe 
ERRO[0000] Can't close tar writer: io: read/write on closed pipe 
Cannot connect to the Docker daemon at unix:///var/run/docker.sock. Is the docker daemon running?
(base) MacBook-Pro-ivan:docker ivan$ y
-bash: y: command not found
(base) MacBook-Pro-ivan:docker ivan$ docker build -t nginx-php-fpm:php80 . # PHP80 -y
Cannot connect to the Docker daemon at unix:///var/run/docker.sock. Is the docker daemon running?
ERRO[0000] Can't add file /Users/ivan/devops-mlops/practic/docker/html/css/skeleton.min.css to tar: io: read/write on closed pipe 
ERRO[0000] Can't close tar writer: io: read/write on closed pipe 
(base) MacBook-Pro-ivan:docker ivan$ docker build -t nginx-php-fpm:php80 . # PHP
Cannot connect to the Docker daemon at unix:///var/run/docker.sock. Is the docker daemon running?
ERRO[0000] Can't add file /Users/ivan/devops-mlops/practic/docker/html/css/skeleton.min.css to tar: io: read/write on closed pipe 
(base) MacBook-Pro-ivan:docker ivan$ docker images | grep
usage: grep [-abcdDEFGHhIiJLlMmnOopqRSsUVvwXxZz] [-A num] [-B num] [-C[num]]
	[-e pattern] [-f file] [--binary-files=value] [--color=when]
	[--context[=num]] [--directories=action] [--label] [--line-buffered]
	[--null] [pattern] [file ...]
Cannot connect to the Docker daemon at unix:///var/run/docker.sock. Is the docker daemon running?
(base) MacBook-Pro-ivan:docker ivan$ systemctl start docker
-bash: systemctl: command not found
(base) MacBook-Pro-ivan:docker ivan$ gpasswd -a $USER docker
-bash: gpasswd: command not found
(base) MacBook-Pro-ivan:docker ivan$ sudo dockerd
Password:
sudo: dockerd: command not found
(base) MacBook-Pro-ivan:docker ivan$ sudo dockerd
sudo: dockerd: command not found
(base) MacBook-Pro-ivan:docker ivan$ sudo dockerd
sudo: dockerd: command not found
(base) MacBook-Pro-ivan:docker ivan$ gpasswd -a $USER docker
-bash: gpasswd: command not found
(base) MacBook-Pro-ivan:docker ivan$ systemctl start docker
-bash: systemctl: command not found
(base) MacBook-Pro-ivan:docker ivan$ docker images | grep
usage: grep [-abcdDEFGHhIiJLlMmnOopqRSsUVvwXxZz] [-A num] [-B num] [-C[num]]
	[-e pattern] [-f file] [--binary-files=value] [--color=when]
	[--context[=num]] [--directories=action] [--label] [--line-buffered]
	[--null] [pattern] [file ...]
Cannot connect to the Docker daemon at unix:///var/run/docker.sock. Is the docker daemon running?
(base) MacBook-Pro-ivan:docker ivan$ docker build -t nginx-php-fpm:php80 . # PHP
Cannot connect to the Docker daemon at unix:///var/run/docker.sock. Is the docker daemon running?
ERRO[0000] Can't add file /Users/ivan/devops-mlops/practic/docker/html/css/skeleton.min.css to tar: io: read/write on closed pipe 
(base) MacBook-Pro-ivan:docker ivan$ docker build -t nginx-php-fpm:php80 . # PHP8
ERRO[0000] Can't add file /Users/ivan/devops-mlops/practic/docker/html/css/skeleton.min.css to tar: io: read/write on closed pipe 
Cannot connect to the Docker daemon at unix:///var/run/docker.sock. Is the docker daemon running?
ERRO[0000] Can't close tar writer: io: read/write on closed pipe 
(base) MacBook-Pro-ivan:docker ivan$ sudo service --status-all
sudo: service: command not found
(base) MacBook-Pro-ivan:docker ivan$ sudo service docker start
sudo: service: command not found
(base) MacBook-Pro-ivan:docker ivan$ sudo service docker start
sudo: service: command not found
(base) MacBook-Pro-ivan:docker ivan$ snap start docker
-bash: snap: command not found
(base) MacBook-Pro-ivan:docker ivan$ sudo su
sh-3.2# docker-compose --version
docker: 'compose' is not a docker command.
See 'docker --help'
sh-3.2# docker ps
Cannot connect to the Docker daemon at unix:///var/run/docker.sock. Is the docker daemon running?
sh-3.2# chmod +x /usr/local/bin/docker-compose
sh-3.2# q
sh: q: command not found
sh-3.2# q
sh: q: command not found
sh-3.2# qq
sh: qq: command not found
sh-3.2# :q
sh: :q: command not found
sh-3.2# sudo
usage: sudo -h | -K | -k | -V
usage: sudo -v [-AknS] [-g group] [-h host] [-p prompt] [-u user]
usage: sudo -l [-AknS] [-g group] [-h host] [-p prompt] [-U user] [-u user] [command]
usage: sudo [-AbEHknPS] [-C num] [-D directory] [-g group] [-h host] [-p prompt] [-R directory]
            [-T timeout] [-u user] [VAR=value] [-i|-s] [<command>]
usage: sudo -e [-AknS] [-C num] [-D directory] [-g group] [-h host] [-p prompt] [-R directory]
            [-T timeout] [-u user] file ...
sh-3.2# sudo -h
sudo - execute a command as another user

usage: sudo -h | -K | -k | -V
usage: sudo -v [-AknS] [-g group] [-h host] [-p prompt] [-u user]
usage: sudo -l [-AknS] [-g group] [-h host] [-p prompt] [-U user] [-u user] [command]
usage: sudo [-AbEHknPS] [-C num] [-D directory] [-g group] [-h host] [-p prompt] [-R directory]
            [-T timeout] [-u user] [VAR=value] [-i|-s] [<command>]
usage: sudo -e [-AknS] [-C num] [-D directory] [-g group] [-h host] [-p prompt] [-R directory]
            [-T timeout] [-u user] file ...

Options:
  -A, --askpass                 use a helper program for password prompting
  -b, --background              run command in the background
  -B, --bell                    ring bell when prompting
  -C, --close-from=num          close all file descriptors >= num
  -D, --chdir=directory         change the working directory before running command
  -E, --preserve-env            preserve user environment when running command
      --preserve-env=list       preserve specific environment variables
  -e, --edit                    edit files instead of running a command
  -g, --group=group             run command as the specified group name or ID
  -H, --set-home                set HOME variable to target user's home dir
  -h, --help                    display help message and exit
  -h, --host=host               run command on host (if supported by plugin)
  -i, --login                   run login shell as the target user; a command may also be
                                specified
  -K, --remove-timestamp        remove timestamp file completely
  -k, --reset-timestamp         invalidate timestamp file
  -l, --list                    list user's privileges or check a specific command; use twice for
                                longer format
  -n, --non-interactive         non-interactive mode, no prompts are used
  -P, --preserve-groups         preserve group vector instead of setting to target's
  -p, --prompt=prompt           use the specified password prompt
  -R, --chroot=directory        change the root directory before running command
  -S, --stdin                   read password from standard input
  -s, --shell                   run shell as the target user; a command may also be specified
  -T, --command-timeout=timeout terminate command after the specified time limit
  -U, --other-user=user         in list mode, display privileges for user
  -u, --user=user               run command (or edit file) as specified user name or ID
  -V, --version                 display version information and exit
  -v, --validate                update user's timestamp without running a command
  --                            stop processing command line arguments
sh-3.2# sudo -v
sh-3.2# sudo exit
sudo: exit: command not found
sh-3.2# sudo -q
sudo: invalid option -- q
usage: sudo -h | -K | -k | -V
usage: sudo -v [-AknS] [-g group] [-h host] [-p prompt] [-u user]
usage: sudo -l [-AknS] [-g group] [-h host] [-p prompt] [-U user] [-u user] [command]
usage: sudo [-AbEHknPS] [-C num] [-D directory] [-g group] [-h host] [-p prompt] [-R directory]
            [-T timeout] [-u user] [VAR=value] [-i|-s] [<command>]
usage: sudo -e [-AknS] [-C num] [-D directory] [-g group] [-h host] [-p prompt] [-R directory]
            [-T timeout] [-u user] file ...
sh-3.2# sudo --q
sudo: unrecognized option `--q'
usage: sudo -h | -K | -k | -V
usage: sudo -v [-AknS] [-g group] [-h host] [-p prompt] [-u user]
usage: sudo -l [-AknS] [-g group] [-h host] [-p prompt] [-U user] [-u user] [command]
usage: sudo [-AbEHknPS] [-C num] [-D directory] [-g group] [-h host] [-p prompt] [-R directory]
            [-T timeout] [-u user] [VAR=value] [-i|-s] [<command>]
usage: sudo -e [-AknS] [-C num] [-D directory] [-g group] [-h host] [-p prompt] [-R directory]
            [-T timeout] [-u user] file ...
sh-3.2# sudo quit
sudo: quit: command not found
sh-3.2# systemctl start docker
sh: systemctl: command not found
sh-3.2# docker context ls 
NAME                TYPE                DESCRIPTION                               DOCKER ENDPOINT               KUBERNETES ENDPOINT   ORCHESTRATOR
default *           moby                Current DOCKER_HOST based configuration   unix:///var/run/docker.sock                         swarm
sh-3.2# docker context use default
default
Current context is now "default"
sh-3.2# docker context ls 
NAME                TYPE                DESCRIPTION                               DOCKER ENDPOINT               KUBERNETES ENDPOINT   ORCHESTRATOR
default *           moby                Current DOCKER_HOST based configuration   unix:///var/run/docker.sock                         swarm
sh-3.2# sudo service docker stop
sudo: service: command not found
sh-3.2# sudo nohup docker daemon -H tcp://0.0.0.0:2375 -H unix:///var/run/docker.sock
appending output to nohup.out
sh-3.2# sudo /etc/init.d/docker start
sudo: /etc/init.d/docker: command not found
sh-3.2# sudo usermod -aG docker $USER
sudo: usermod: command not found
sh-3.2# ExecStart=/usr/bin/dockerd fd://
sh: fd://: No such file or directory
sh-3.2# ExecStart=/usr/bin/dockerd -H tcp://0.0.0.0:2375
sh: -H: command not found
sh-3.2# DOCKER_OPTS="-H tcp://0.0.0.0:2375"
sh-3.2# service docker start
sh: service: command not found
sh-3.2# rm -rf containerd/*
sh-3.2# rm -f docker-containerd.pid
sh-3.2# service docker start
sh: service: command not found
sh-3.2# sudo /etc/init.d/docker star
sudo: /etc/init.d/docker: command not found
sh-3.2# docker images
Cannot connect to the Docker daemon at unix:///var/run/docker.sock. Is the docker daemon running?
sh-3.2# systemctl start docker
sh: systemctl: command not found
sh-3.2# gpasswd -a $USER docker
sh: gpasswd: command not found
sh-3.2# exit
(base) MacBook-Pro-ivan:docker ivan$ systemctl start docker
-bash: systemctl: command not found
(base) MacBook-Pro-ivan:docker ivan$ gpasswd -a $USER docker
-bash: gpasswd: command not found
(base) MacBook-Pro-ivan:docker ivan$ sudo systemctl restart docker
Password:
Sorry, try again.
Password:
sudo: systemctl: command not found
(base) MacBook-Pro-ivan:docker ivan$ sudo systemctl restart docker
sudo: systemctl: command not found
(base) MacBook-Pro-ivan:docker ivan$ sudo systemctl restart docker
sudo: systemctl: command not found
(base) MacBook-Pro-ivan:docker ivan$ docker system info
Client:
 Context:    desktop-linux
 Debug Mode: false
 Plugins:
  buildx: Docker Buildx (Docker Inc., v0.10.4)
  compose: Docker Compose (Docker Inc., v2.17.2)
  dev: Docker Dev Environments (Docker Inc., v0.1.0)
  extension: Manages Docker extensions (Docker Inc., v0.2.19)
  init: Creates Docker-related starter files for your project (Docker Inc., v0.1.0-beta.2)
  sbom: View the packaged-based Software Bill Of Materials (SBOM) for an image (Anchore Inc., 0.6.0)
  scan: Docker Scan (Docker Inc., v0.25.0)
  scout: Command line tool for Docker Scout (Docker Inc., v0.9.0)

Server:
 Containers: 0
  Running: 0
  Paused: 0
  Stopped: 0
 Images: 2
 Server Version: 20.10.24
 Storage Driver: overlay2
  Backing Filesystem: extfs
  Supports d_type: true
  Native Overlay Diff: true
  userxattr: false
 Logging Driver: json-file
 Cgroup Driver: cgroupfs
 Cgroup Version: 2
 Plugins:
  Volume: local
  Network: bridge host ipvlan macvlan null overlay
  Log: awslogs fluentd gcplogs gelf journald json-file local logentries splunk syslog
 Swarm: inactive
 Runtimes: io.containerd.runtime.v1.linux runc io.containerd.runc.v2
 Default Runtime: runc
 Init Binary: docker-init
 containerd version: 2456e983eb9e37e47538f59ea18f2043c9a73640
 runc version: v1.1.4-0-g5fd4c4d
 init version: de40ad0
 Security Options:
  seccomp
   Profile: default
  cgroupns
 Kernel Version: 5.15.49-linuxkit
 Operating System: Docker Desktop
 OSType: linux
 Architecture: x86_64
 CPUs: 2
 Total Memory: 3.842GiB
 Name: docker-desktop
 ID: V6WM:IJ6P:UT67:IFYM:5YUY:WMFT:G2D5:QKSI:QGGD:YUTU:BOCS:AUGP
 Docker Root Dir: /var/lib/docker
 Debug Mode: false
 HTTP Proxy: http.docker.internal:3128
 HTTPS Proxy: http.docker.internal:3128
 No Proxy: hubproxy.docker.internal
 Registry: https://index.docker.io/v1/
 Labels:
 Experimental: false
 Insecure Registries:
  hubproxy.docker.internal:5555
  127.0.0.0/8
 Live Restore Enabled: false

(base) MacBook-Pro-ivan:docker ivan$ docker login [ARTIFACTORY-REGISTRY-URL]
Username: ainick
Password: 
Error response from daemon: Get "https://[ARTIFACTORY-REGISTRY-URL]/v2/": dialing ARTIFACTORY-REGISTRY-URL:443 with direct connection: resolving host ARTIFACTORY-REGISTRY-URL: lookup ARTIFACTORY-REGISTRY-URL: no such host
(base) MacBook-Pro-ivan:docker ivan$ docker ps
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES
(base) MacBook-Pro-ivan:docker ivan$ cd..
-bash: cd..: command not found
(base) MacBook-Pro-ivan:docker ivan$ cd ..
(base) MacBook-Pro-ivan:practic ivan$ docker ps
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES
(base) MacBook-Pro-ivan:practic ivan$ cd ..
(base) MacBook-Pro-ivan:devops-mlops ivan$ cd ..
(base) MacBook-Pro-ivan:~ ivan$ docker ps
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES
(base) MacBook-Pro-ivan:~ ivan$ cd devops-mlops/Docker
(base) MacBook-Pro-ivan:Docker ivan$ cd ..
(base) MacBook-Pro-ivan:devops-mlops ivan$ cd practic/docker
(base) MacBook-Pro-ivan:docker ivan$ docker ps
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES
(base) MacBook-Pro-ivan:docker ivan$ sudo service docker start
Password:
Sorry, try again.
Password:
sudo: service: command not found
(base) MacBook-Pro-ivan:docker ivan$ apt-get update && \
>       apt-get -y install sudo
-bash: apt-get: command not found
(base) MacBook-Pro-ivan:docker ivan$ apt-get update && \
> apt-get -y install sudo
-bash: apt-get: command not found
(base) MacBook-Pro-ivan:docker ivan$ apt-get -y install sudo
-bash: apt-get: command not found
(base) MacBook-Pro-ivan:docker ivan$ apt-get update
-bash: apt-get: command not found
(base) MacBook-Pro-ivan:docker ivan$ export PATH=$PATH:/usr/local/bin/
(base) MacBook-Pro-ivan:docker ivan$ sudo systemctl status docker
sudo: systemctl: command not found
(base) MacBook-Pro-ivan:docker ivan$ sudo systemctl start docker
sudo: systemctl: command not found
(base) MacBook-Pro-ivan:docker ivan$ docker run -d -p 80:80 nginx-php-fpm:php80
Unable to find image 'nginx-php-fpm:php80' locally
docker: Error response from daemon: pull access denied for nginx-php-fpm, repository does not exist or may require 'docker login': denied: requested access to the resource is denied.
See 'docker run --help'.
(base) MacBook-Pro-ivan:docker ivan$ docker ps
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES
(base) MacBook-Pro-ivan:docker ivan$ docker build -t nginx-php-fpm:php80 . # PHP8
[+] Building 222.3s (12/12) FINISHED                                                                                                                            
 => [internal] load build definition from Dockerfile                                                                                                       0.2s
 => => transferring dockerfile: 5.57kB                                                                                                                     0.0s
 => [internal] load .dockerignore                                                                                                                          0.1s
 => => transferring context: 2B                                                                                                                            0.0s
 => [internal] load metadata for docker.io/library/debian:buster                                                                                           2.8s
 => [auth] library/debian:pull token for registry-1.docker.io                                                                                              0.0s
 => [1/6] FROM docker.io/library/debian:buster@sha256:46ca02d33c65ab188d6e56f26c323bf1aa9a99074f2f54176fdc3884304f58b8                                    18.0s
 => => resolve docker.io/library/debian:buster@sha256:46ca02d33c65ab188d6e56f26c323bf1aa9a99074f2f54176fdc3884304f58b8                                     0.0s
 => => sha256:46ca02d33c65ab188d6e56f26c323bf1aa9a99074f2f54176fdc3884304f58b8 984B / 984B                                                                 0.0s
 => => sha256:0875310d6794fc24c5c966f41c071285b0d381e7f6a0534e03dbce8452e2afc7 529B / 529B                                                                 0.0s
 => => sha256:d20e99fdc4dca6f853c234fbacb3402fc77653110b37717e4a61c7b233932975 1.46kB / 1.46kB                                                             0.0s
 => => sha256:b32028968d56a86ac35eac062e7abba276c547ab175fb057973c469eb41db55b 50.50MB / 50.50MB                                                          10.0s
 => => extracting sha256:b32028968d56a86ac35eac062e7abba276c547ab175fb057973c469eb41db55b                                                                  6.5s
 => [internal] load build context                                                                                                                          0.1s
 => => transferring context: 17.27kB                                                                                                                       0.0s
 => [2/6] RUN buildDeps='curl gcc make autoconf libc-dev zlib1g-dev pkg-config'     && set -x     && apt-get update     && apt-get install --no-install  196.1s
 => [3/6] COPY ./supervisord.conf /etc/supervisord.conf                                                                                                    0.1s
 => [4/6] COPY ./default.conf /etc/nginx/conf.d/default.conf                                                                                               0.0s
 => [5/6] COPY html /usr/share/nginx/html                                                                                                                  0.0s 
 => [6/6] COPY ./start.sh /start.sh                                                                                                                        0.0s 
 => exporting to image                                                                                                                                     4.7s 
 => => exporting layers                                                                                                                                    4.7s 
 => => writing image sha256:e7cf4c41705ad048bad13ebc4984d18d1d8d8035c2f8362cf60ea77aebf297aa                                                               0.0s
 => => naming to docker.io/library/nginx-php-fpm:php80                                                                                                     0.0s
(base) MacBook-Pro-ivan:docker ivan$ docker images | grep
usage: grep [-abcdDEFGHhIiJLlMmnOopqRSsUVvwXxZz] [-A num] [-B num] [-C[num]]
	[-e pattern] [-f file] [--binary-files=value] [--color=when]
	[--context[=num]] [--directories=action] [--label] [--line-buffered]
	[--null] [pattern] [file ...]
(base) MacBook-Pro-ivan:docker ivan$ docker images | grep nginx-php-fpm
nginx-php-fpm   php80     e7cf4c41705a   4 minutes ago   482MB
(base) MacBook-Pro-ivan:docker ivan$ docker run -d -p 80:80 nginx-php-fpm:php80
858aafec5d18b356c0dae50fca83eef72e2372decc401395f50721c7dcffc44a
(base) MacBook-Pro-ivan:docker ivan$ docker ps
CONTAINER ID   IMAGE                 COMMAND       CREATED          STATUS          PORTS                NAMES
858aafec5d18   nginx-php-fpm:php80   "/start.sh"   28 seconds ago   Up 26 seconds   0.0.0.0:80->80/tcp   quirky_noyce
(base) MacBook-Pro-ivan:docker ivan$ netstat -ntlp
netstat: option requires an argument -- p
Usage:	netstat [-AaLlnW] [-f address_family | -p protocol]
	netstat [-gilns] [-f address_family]
	netstat -i | -I interface [-w wait] [-abdgRtS]
	netstat -s [-s] [-f address_family | -p protocol] [-w wait]
	netstat -i | -I interface -s [-f address_family | -p protocol]
	netstat -m [-m]
	netstat -r [-Aaln] [-f address_family]
	netstat -rs [-s]

(base) MacBook-Pro-ivan:docker ivan$ netstat -ntlp -- p
netstat: --: unknown or uninstrumented protocol
(base) MacBook-Pro-ivan:docker ivan$ netstat -ntlp -i
netstat: -i: unknown or uninstrumented protocol
(base) MacBook-Pro-ivan:docker ivan$ netstat -ntlp -s
netstat: -s: unknown or uninstrumented protocol
(base) MacBook-Pro-ivan:docker ivan$ netstat -ntlp -m
netstat: -m: unknown or uninstrumented protocol
(base) MacBook-Pro-ivan:docker ivan$ netstat -ntlp -s
netstat: -s: unknown or uninstrumented protocol
(base) MacBook-Pro-ivan:docker ivan$ 

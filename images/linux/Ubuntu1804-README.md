| Announcements |
|-|
| [[all OS versions] Android SDK tools will be changed to Command line tools on July, 12](https://github.com/actions/virtual-environments/issues/3638) |
| [Ubuntu 16.04 environment will be removed on September 20, 2021](https://github.com/actions/virtual-environments/issues/3287) |
***
# Ubuntu 18.04.5 LTS
- Linux kernel version: 5.4.0-1051-azure
- Image Version: 20210628.1

## Installed Software
### Language and Runtime
- Bash 4.4.20(1)-release
- Clang 9.0.0
- Clang-format 9.0.0
- Erlang 24.0.2 (Eshell 12.0.2)
- Erlang rebar3 3.16.1
- GNU C++ 7.5.0, 9.4.0, 10.3.0
- GNU Fortran 7.5.0, 9.4.0, 10.3.0
- Julia 1.6.1
- Mono 6.12.0.122 (apt source repository: https://download.mono-project.com/repo/ubuntu stable-bionic main)
- MSBuild 16.6.0.15201 (from /usr/lib/mono/msbuild/15.0/bin/MSBuild.dll)
- Node 14.17.1
- Perl 5.26.1
- Python 2.7.17
- Python3 3.6.9
- Ruby 2.5.1p57
- Swift 5.4.1

### Package Management
- cpan 1.64
- Helm 3.6.1
- Homebrew 3.2.0
- Miniconda 4.9.2
- Npm 6.14.13
- Pip 9.0.1
- Pip3 9.0.1
- Pipx 0.16.3
- RubyGems 2.7.6
- Vcpkg  (build from master \<bb002cd>)
- Yarn 1.22.10

#### Environment variables
| Name                    | Value                  |
| ----------------------- | ---------------------- |
| CONDA                   | /usr/share/miniconda   |
| VCPKG_INSTALLATION_ROOT | /usr/local/share/vcpkg |

### Project Management
- Ant 1.10.5
- Gradle 7.1
- Maven 3.8.1
- Sbt 1.5.4

### Tools
- Ansible 2.10.11
- apt-fast 1.9.11
- AzCopy 10.11.0 (available by `azcopy` and `azcopy10` aliases)
- Bazel 4.1.0
- Bazelisk 1.9.0
- Bicep 0.4.63
- Buildah 1.19.6 (apt source repository: https://download.opensuse.org/repositories/devel:/kubic:/libcontainers:/stable)
- CMake 3.20.5
- CodeQL Action Bundle 2.5.6
- Docker Compose 1.29.2
- Docker-Buildx 0.5.1
- Docker-Moby Client 20.10.6+azure
- Docker-Moby Server 20.10.6+azure
- Git 2.32.0 (apt source repository: ppa:git-core/ppa)
- Git LFS 2.13.3 (apt source repository: https://packagecloud.io/install/repositories/github/git-lfs)
- Git-ftp 1.3.1
- Haveged 1.9.1
- Heroku 7.54.1
- HHVM (HipHop VM) 4.115.0
- jq 1.5
- Kind 0.11.1
- Kubectl 1.20.1-5-g76a04fc
- Kustomize 4.1.3
- Leiningen 2.9.6
- MediaInfo 17.12
- Mercurial 4.5.3
- Minikube 1.21.0
- Newman 5.2.4
- nvm 0.38.0
- OpenSSL 1.1.1  11 Sep 2018
- Packer 1.7.3
- PhantomJS 2.1.1
- Podman 3.0.1 (apt source repository: https://download.opensuse.org/repositories/devel:/kubic:/libcontainers:/stable)
- Pulumi 3.5.1
- R 4.1.0
- Skopeo 1.2.2 (apt source repository: https://download.opensuse.org/repositories/devel:/kubic:/libcontainers:/stable)
- Sphinx Open Source Search Server 2.2.11
- SVN 1.9.7
- Terraform 1.0.1
- yamllint 1.26.1
- zstd 1.5.0 (homebrew)

### CLI Tools
- Alibaba Cloud CLI 3.0.80
- AWS CLI 1.19.101
- AWS CLI Session manager plugin 1.2.205.0
- AWS SAM CLI 1.24.1
- Azure CLI (azure-cli) 2.25.0 (installation method: https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-linux?pivots=apt)
- Azure CLI (azure-devops) 0.18.0
- GitHub CLI 1.11.0
- Google Cloud SDK 346.0.0 (apt source repository: https://packages.cloud.google.com/apt)
- Hub CLI 2.14.2
- Netlify CLI 3.39.0
- OpenShift CLI 4.7.16
- ORAS CLI 0.12.0
- Vercel CLI 23.0.1

### Java
| Version             | Vendor        | Environment Variable |
| ------------------- | ------------- | -------------------- |
| 8.0.292+1 (default) | Adopt OpenJDK | JAVA_HOME_8_X64      |
| 11.0.11+9           | Adopt OpenJDK | JAVA_HOME_11_X64     |
| 12.0.2+10           | Adopt OpenJDK | JAVA_HOME_12_X64     |

### PHP
| Tool     | Version                           |
| -------- | --------------------------------- |
| PHP      | 7.1.33 7.2.34 7.3.28 7.4.20 8.0.7 |
| Composer | 2.1.3                             |
| PHPUnit  | 8.5.17                            |
```
    Both Xdebug and PCOV extensions are installed, but only Xdebug is enabled.
```
### Haskell
- Cabal 3.4.0.0
- GHC 9.0.1 (apt source repository: ppa:hvr/ghc)
- GHCup 0.1.15.2
- Stack 2.7.1

### Rust Tools
- Cargo 1.53.0
- Rust 1.53.0
- Rustdoc 1.53.0
- Rustup 1.24.3

#### Packages
- Bindgen 0.58.1
- Cargo audit 0.14.1
- Cargo clippy 0.1.53
- Cargo outdated 0.9.16
- Cbindgen 0.19.0
- Rustfmt 1.4.37

### Browsers and Drivers
- Google Chrome 91.0.4472.114
- ChromeDriver 91.0.4472.101
- Mozilla Firefox 89.0.1
- Geckodriver 0.29.1
- Chromium 91.0.4472.0

#### Environment variables
| Name            | Value                          |
| --------------- | ------------------------------ |
| CHROMEWEBDRIVER | /usr/local/share/chrome_driver |
| GECKOWEBDRIVER  | /usr/local/share/gecko_driver  |

### .NET Core SDK
- 2.1.302 2.1.403 2.1.524 2.1.617 2.1.701 2.1.816 3.1.116 3.1.202 3.1.302 3.1.410 5.0.104 5.0.204 5.0.301

### Databases
- MongoDB 4.4.6 (apt source repository: https://repo.mongodb.org/apt/ubuntu)
- Postgre SQL 13.3 (apt source repository: https://apt.postgresql.org/pub/repos/apt/)
- sqlite3 3.22.0

#### MySQL
- MySQL 5.7.34
- MySQL Server (user:root password:root)

```
    MySQL service is disabled by default. Use the following command as a part of your job to start the service: 'sudo systemctl start mysql.service'
```
#### MS SQL Server Client Tools
- sqlcmd 17.7.0001.1

### Cached Tools
#### Go
- 1.13.15
- 1.14.15
- 1.15.14

#### Node.js
- 10.24.1
- 12.22.1
- 14.17.1

#### PyPy
- 2.7.18 [PyPy 7.3.5]
- 3.6.12 [PyPy 7.3.3]

#### Python
- 2.7.18
- 3.5.10
- 3.6.13
- 3.7.10
- 3.8.10
- 3.9.5

#### Ruby
- 2.4.10
- 2.5.9
- 2.6.7
- 2.7.3
- 3.0.1

#### Environment variables
| Name            | Value                               | Architecture |
| --------------- | ----------------------------------- | ------------ |
| GOROOT_1_13_X64 | /opt/hostedtoolcache/go/1.13.15/x64 | x64          |
| GOROOT_1_14_X64 | /opt/hostedtoolcache/go/1.14.15/x64 | x64          |
| GOROOT_1_15_X64 | /opt/hostedtoolcache/go/1.15.14/x64 | x64          |

### PowerShell Tools
- PowerShell 7.1.3

#### PowerShell Modules
| Module     | Version |
| ---------- | ------- |
| MarkdownPS | 1.9     |
| Pester     | 5.2.2   |

#### Az PowerShell Modules
- 5.9.0 3.1.0.zip 4.4.0.zip

### Web Servers
| Name    | Version | ConfigFile                | ServiceStatus | ListenPort |
| ------- | ------- | ------------------------- | ------------- | ---------- |
| apache2 | 2.4.29  | /etc/apache2/apache2.conf | inactive      | 80         |
| nginx   | 1.14.0  | /etc/nginx/nginx.conf     | inactive      | 80         |

### Android
| Package Name               | Version                                                                                                                                                                                                                                       |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Android Command Line Tools | 4.0                                                                                                                                                                                                                                           |
| Android SDK Build-tools    | 30.0.0 30.0.1 30.0.2 30.0.3<br>29.0.0 29.0.1 29.0.2 29.0.3<br>28.0.0 28.0.1 28.0.2 28.0.3<br>27.0.0 27.0.1 27.0.2 27.0.3<br>26.0.0 26.0.1 26.0.2 26.0.3<br>25.0.0 25.0.1 25.0.2 25.0.3<br>24.0.0 24.0.1 24.0.2 24.0.3<br>23.0.1 23.0.2 23.0.3 |
| Android SDK Platform-Tools | 31.0.2                                                                                                                                                                                                                                        |
| Android SDK Platforms      | android-S (rev 5)<br>android-30 (rev 3)<br>android-29 (rev 5)<br>android-28 (rev 6)<br>android-27 (rev 3)<br>android-26 (rev 2)<br>android-25 (rev 3)<br>android-24 (rev 2)<br>android-23 (rev 3)                                             |
| Android SDK Tools          | 26.1.1                                                                                                                                                                                                                                        |
| Android Support Repository | 47.0.0                                                                                                                                                                                                                                        |
| CMake                      | 3.10.2<br>3.18.1                                                                                                                                                                                                                              |
| Google APIs                | addon-google_apis-google-21<br>addon-google_apis-google-22<br>addon-google_apis-google-23<br>addon-google_apis-google-24                                                                                                                      |
| Google Play services       | 49                                                                                                                                                                                                                                            |
| Google Repository          | 58                                                                                                                                                                                                                                            |
| NDK                        | 21.4.7075529                                                                                                                                                                                                                                  |
| SDK Patch Applier v4       | 1                                                                                                                                                                                                                                             |

#### Environment variables
| Name             | Value                                                                                |
| ---------------- | ------------------------------------------------------------------------------------ |
| ANDROID_HOME     | /usr/local/lib/android/sdk                                                           |
| ANDROID_NDK_HOME | /usr/local/lib/android/sdk/ndk-bundle -> /usr/local/lib/android/sdk/ndk/21.4.7075529 |
| ANDROID_NDK_ROOT | /usr/local/lib/android/sdk/ndk-bundle -> /usr/local/lib/android/sdk/ndk/21.4.7075529 |
| ANDROID_SDK_ROOT | /usr/local/lib/android/sdk                                                           |

### Cached Docker images
| Repository:Tag         | Digest                                                                   | Created    |
| ---------------------- | ------------------------------------------------------------------------ | ---------- |
| alpine:3.11            | sha256:20117524da64d995fd769f0aa3d7cfe2040518426f4b238f43e8373f4aa56c06  | 2021-04-14 |
| alpine:3.12            | sha256:87703314048c40236c6d674424159ee862e2b96ce1c37c62d877e21ed27a387e  | 2021-04-14 |
| alpine:3.13            | sha256:f51ff2d96627690d62fee79e6eecd9fa87429a38142b5df8a3bfbb26061df7fc  | 2021-04-14 |
| buildpack-deps:buster  | sha256:3e2554a4168887038da647f8d22f94348fadd67f753a7287e1e8193000fb4b3a  | 2021-06-23 |
| buildpack-deps:stretch | sha256:04f933352c6a3e46933907f5a7fb6f37134e027207f5de2d3c234bfec43d0d72  | 2021-06-23 |
| debian:10              | sha256:33a8231b1ec668c044b583971eea94fff37151de3a1d5a3737b08665300c8a0b  | 2021-06-23 |
| debian:9               | sha256:8afcdd92f29e1706625631df94ecdfe3bdeb919bb2c6ee685803d245b75ee45a  | 2021-06-23 |
| node:10                | sha256:59531d2835edd5161c8f9512f9e095b1836f7a1fcb0ab73e005ec46047384911  | 2021-04-10 |
| node:10-alpine         | sha256:dc98dac24efd4254f75976c40bce46944697a110d06ce7fa47e7268470cf2e28  | 2021-04-14 |
| node:12                | sha256:07ca77017dff8fccf0e333bd1fc7026844eb1e4e6677cc1f98e59843406cec29  | 2021-06-23 |
| node:12-alpine         | sha256:be24b4fe27c92231c051a06e717b67e2a4dfc70d8edb0281285762292b854c03  | 2021-04-14 |
| node:14                | sha256:d8f90b676efb1260957a4170a9a0843fc003b673ae164f22df07eaee9bbc6223  | 2021-06-23 |
| node:14-alpine         | sha256:21b87afa5f267e50b806f696f754b15b37b4118bb0ef722192f27ddff78d8d67  | 2021-06-15 |
| ubuntu:16.04           | sha256:6aab78d1825b4c15c159fecc62b8eef4fdf0c693a15aace3a605ad44e5e2df0c  | 2021-06-17 |
| ubuntu:18.04           | sha256:139b3846cee2e63de9ced83cee7023a2d95763ee2573e5b0ab6dea9dfbd4db8f  | 2021-06-17 |
| ubuntu:20.04           | sha256:aba80b77e27148d99c034a987e7da3a287ed455390352663418c0f2ed40417fe  | 2021-06-17 |

### Installed apt packages
| Name              | Version                           |
| ----------------- | --------------------------------- |
| binutils          | 2.30-21ubuntu1~18.04.5            |
| bison             | 2:3.0.4.dfsg-1build1              |
| brotli            | 1.0.3-1ubuntu1.3                  |
| build-essential   | 12.4ubuntu1                       |
| bzip2             | 1.0.6-8.1ubuntu0.2                |
| coreutils         | 8.28-1ubuntu1                     |
| curl              | 7.58.0-2ubuntu3.13                |
| dbus              | 1.12.2-1ubuntu1.2                 |
| dnsutils          | 1:9.11.3+dfsg-1ubuntu1.15         |
| dpkg              | 1.19.0.5ubuntu2.3                 |
| fakeroot          | 1.22-2ubuntu1                     |
| file              | 1:5.32-2ubuntu0.4                 |
| flex              | 2.6.4-6                           |
| ftp               | 0.17-34                           |
| gnupg2            | 2.2.4-1ubuntu1.4                  |
| haveged           | 1.9.1-6                           |
| imagemagick       | 8:6.9.7.4+dfsg-16ubuntu6.11       |
| iproute2          | 4.15.0-2ubuntu1.3                 |
| iputils-ping      | 3:20161105-1ubuntu3               |
| jq                | 1.5+dfsg-2                        |
| lib32z1           | 1:1.2.11.dfsg-0ubuntu2            |
| libc++-dev        | 6.0-2                             |
| libc++abi-dev     | 6.0-2                             |
| libcurl3          | 7.58.0-2ubuntu3.13                |
| libgbm-dev        | 20.0.8-0ubuntu1~18.04.1           |
| libgconf-2-4      | 3.2.6-4ubuntu1                    |
| libgsl-dev        | 2.4+dfsg-6                        |
| libgtk-3-0        | 3.22.30-1ubuntu4                  |
| libmagic-dev      | 1:5.32-2ubuntu0.4                 |
| libmagickcore-dev | 8:6.9.7.4+dfsg-16ubuntu6.11       |
| libmagickwand-dev | 8:6.9.7.4+dfsg-16ubuntu6.11       |
| libsecret-1-dev   | 0.18.6-1                          |
| libsqlite3-dev    | 3.22.0-1ubuntu0.4                 |
| libunwind8        | 1.2.1-8                           |
| libxkbfile-dev    | 1:1.0.9-2                         |
| libxss1           | 1:1.2.2-1                         |
| locales           | 2.27-3ubuntu1.4                   |
| m4                | 1.4.18-1                          |
| mediainfo         | 17.12-1                           |
| net-tools         | 1.60+git20161116.90da8a0-1ubuntu1 |
| netcat            | 1.10-41.1                         |
| openssh-client    | 1:7.6p1-4ubuntu0.3                |
| p7zip-full        | 16.02+dfsg-6                      |
| p7zip-rar         | 16.02-2                           |
| parallel          | 20161222-1                        |
| pass              | 1.7.1-3                           |
| patchelf          | 0.9-1                             |
| pkg-config        | 0.29.1-0ubuntu2                   |
| pollinate         | 4.33-0ubuntu1~18.04.2             |
| python-setuptools | 39.0.1-2                          |
| rpm               | 4.14.1+dfsg1-2                    |
| rsync             | 3.1.2-2.1ubuntu1.1                |
| shellcheck        | 0.4.6-1                           |
| sphinxsearch      | 2.2.11-2                          |
| sqlite3           | 3.22.0-1ubuntu0.4                 |
| ssh               | 1:7.6p1-4ubuntu0.3                |
| sshpass           | 1.06-1                            |
| subversion        | 1.9.7-4ubuntu1                    |
| sudo              | 1.8.21p2-3ubuntu1.4               |
| swig              | 3.0.12-1                          |
| telnet            | 0.17-41                           |
| texinfo           | 6.5.0.dfsg.1-2                    |
| time              | 1.7-25.1build1                    |
| tk                | 8.6.0+9                           |
| tzdata            | 2021a-0ubuntu0.18.04              |
| unzip             | 6.0-21ubuntu1.1                   |
| upx               | 3.94-4                            |
| wget              | 1.19.4-1ubuntu2.2                 |
| xorriso           | 1.4.8-3                           |
| xvfb              | 2:1.19.6-1ubuntu4.9               |
| xz-utils          | 5.2.2-1.3                         |
| zip               | 3.0-11build1                      |
| zsync             | 0.6.2-3ubuntu1                    |



# maya-bifrost
## Install
### 1. Clone this source.
`cd /tmp`
#### Choose one:
#### A. Git HTTPS 
`git clone https://github.com/aaronrancsik/maya-bifrost-arch.git`
#### B. Git SSH 
`git clone git@github.com:aaronrancsik/maya-bifrost-arch.git`
### 2. Get the source zip.
`cd /tmp/maya-bifrost-arch`

`cp /tmp/maya20221_BIG/Packages/Bifrost2022-2.2.1.2-2.2.1.2-1.x86_64.rpm ./`
### 3. Create & install the package.
`makepkg -s`

`sudo pacman -U maya-bifrost-2.2.1.2-1-x86_64.pkg.tar.zst`

### 4. It's done.

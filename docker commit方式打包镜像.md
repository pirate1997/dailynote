
### 1. 启动基础镜像
run -ti reg.docker.alibaba-inc.com/aone-base/blink-runtime-test-application_blink_pipeline:20180529171902  /bin/bash

### 2. 容器内安装所需要的包
yum .....

### 3. commit
docker commit 30afdbaea73c  reg.docker.alibaba-inc.com/aisqa/afeds:0.1

### 4. push
docker pushreg.docker.alibaba-inc.com/aisqa/afeds:0.1

     docker run -itd -p 80:80 -p 443:443 \
        --restart=unless-stopped \
        -e CATTLE_AGENT_IMAGE="registry.cn-hangzhou.aliyuncs.com/rancher/rancher-agent:v2.4.2" \
        registry.cn-hangzhou.aliyuncs.com/rancher/rancher:v2.4.2
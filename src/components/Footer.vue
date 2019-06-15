<template>
    <div class="footer">
        <p>RSS | 源码地址</p>
        <p>CNode 社区为国内最专业的 Node.js 开源技术社区，致力于 Node.js 的技术研究。</p>
        <p>新手搭建 Node.js 服务器，推荐使用无需备案的 DigitalOcean(https://www.digitalocean.com/)</p>
    </div>
</template>


<script>
    export default {
        name: 'Footer'
    }

</script>

<style scoped>
    .footer {
        background: #FFFFFF;
        margin-top: 15px;
        padding: 20px 100px;
        color: #ABABAB;
        font-size: 14px;
        height: 140px;
    }
    .footer p {
        padding: 10px 0;
    }
    .footer p:first-child {
        color: #666666;
    }
</style>
## docker-dbfen  
多备份，数据库备份工具docker版


##运行命令示例  
    docker run -idt --name mysql-dbfen --restart=always --link mysql-main:should.be.domain frankzhang/docker-dbfen    

如果不通过docker内部的代理，直接从公网访问，请自行加入-P命令暴露外网端口

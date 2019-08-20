# base image
FROM microsoft/dotnet:2.1-aspnetcore-runtime AS base


# 容器里暴露的端口,由于我的Dotnetcore程序使用5000,这里也暴露5000
EXPOSE 80

# 设置工作目录
WORKDIR /home

# 把当前目录内容拷贝到容器的home目录
COPY . /home



# 启动程序
ENTRYPOINT ["dotnet", "Jenkins2Docker.dll"]
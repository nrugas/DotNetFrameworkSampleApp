FROM microsoft/wcf:4.7.1-windowsservercore-ltsc2016
RUN windows\system32\inetsrv\appcmd.exe set app 'Default Web Site/' /enabledProtocols:"http,net.tcp"
EXPOSE 808
WORKDIR /inetpub/wwwroot
COPY . .

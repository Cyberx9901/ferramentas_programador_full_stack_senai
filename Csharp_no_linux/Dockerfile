FROM debian
LABEL maintainer="cyberx9901@gmail.com"
RUN apt update ; apt install wget -y ; wget https://packages.microsoft.com/config/debian/12/packages-microsoft-prod.deb -O packages-microsoft-prod.deb ; apt install -f ./packages-microsoft-prod.deb ; rm packages-microsoft-prod.deb ; apt update ; apt install dotnet-sdk-7.0 aspnetcore-runtime-7.0 -y

ENTRYPOINT [ "bash" ]

FROM microsoft/dotnet:latest

COPY . /app

WORKDIR /app

EXPOSE 5100/tcp

ENTRYPOINT ["dotnet", "myweb.dll"]

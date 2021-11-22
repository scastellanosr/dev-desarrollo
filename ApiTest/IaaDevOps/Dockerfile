FROM mcr.microsoft.com/dotnet/core/aspnet:3.1.0
WORKDIR /app    
COPY ./out .
ENV TZ=America/Tegucigalpa
ENTRYPOINT ["dotnet", "IaaDevOpsApi.dll"]
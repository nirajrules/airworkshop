FROM mcr.microsoft.com/dotnet/core/sdk:3.1

WORKDIR /app
COPY src/ .

RUN dotnet restore && dotnet build
CMD ["dotnet", "run"]

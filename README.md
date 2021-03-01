# CursoMVC
Usando Entity Framework e Migrations


projeto criado com o comando

    dotnet new mvc

Usando o modelo Code First do Enntity Framework

    [X] code first
    [ ] model first
    [ ] database first



### .CSPROJ do tutorial:

<Project Sdk="Microsoft.NET.Sdk.Web">

  <PropertyGroup>
    <TargetFramework>netcoreapp3.0</TargetFramework>
    <AutoGenerateBindingRedirects>true</AutoGenerateBindingRedirects>
  </PropertyGroup>

  <ItemGroup>
    <PackageReference Include="Microsoft.EntityFrameworkCore.Design" Version="3.1.0">
      <PrivateAssets>all</PrivateAssets>
      <IncludeAssets>runtime; build; native; contentfiles; analyzers; buildtransitive</IncludeAssets>
    </PackageReference>
    <PackageReference Include="Microsoft.EntityFrameworkCore.SqlServer" Version="3.1.0" />
    <PackageReference Include="Microsoft.EntityFrameworkCore.Tools" Version="3.1.0">
      <PrivateAssets>all</PrivateAssets>
      <IncludeAssets>runtime; build; native; contentfiles; analyzers; buildtransitive</IncludeAssets>
    </PackageReference>
    <PackageReference Include="Microsoft.Extensions.Logging.Debug" Version="3.1.0" />
    <PackageReference Include="Microsoft.VisualStudio.Web.CodeGeneration.Design" Version="3.1.0" />
  </ItemGroup>

</Project>

### END/.CSPROJ do tutorial:




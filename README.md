# mooware.showassemblyinfo

Dotnet global tool to display .NET assembly metadata

## Install

    dotnet tool install --global mooware.showassemblyinfo

## Usage

    dotnet assemblyinfo <assemblypath>

## Example Output

    Assembly metadata of file 'C:\Users\foo\Downloads\newtonsoft.json.13.0.1\lib\netstandard2.0\Newtonsoft.Json.dll'

    System.Runtime.CompilerServices.Extension
    System.Runtime.CompilerServices.CompilationRelaxations: 8
    System.Runtime.CompilerServices.RuntimeCompatibility
      WrapNonExceptionThrows: True
    System.Diagnostics.Debuggable: 2
    System.Security.AllowPartiallyTrustedCallers
    System.Runtime.CompilerServices.InternalsVisibleTo: Newtonsoft.Json.Schema, PublicKey=0024000004800000940000000602000000240000525341310004000001000100f561df277c6c0b497d629032b410cdcf286e537c054724f7ffa0164345f62b3e642029d7a80cc351918955328c4adc8a048823ef90b0cf38ea7db0d729caf2b633c3babe08b0310198c1081995c19029bc675193744eab9d7345b8a67258ec17d112cebdbbb2a281487dceeafb9d83aa930f32103fbe1d2911425bc5744002c7
    System.Runtime.CompilerServices.InternalsVisibleTo: Newtonsoft.Json.Tests, PublicKey=0024000004800000940000000602000000240000525341310004000001000100f561df277c6c0b497d629032b410cdcf286e537c054724f7ffa0164345f62b3e642029d7a80cc351918955328c4adc8a048823ef90b0cf38ea7db0d729caf2b633c3babe08b0310198c1081995c19029bc675193744eab9d7345b8a67258ec17d112cebdbbb2a281487dceeafb9d83aa930f32103fbe1d2911425bc5744002c7
    System.Runtime.CompilerServices.InternalsVisibleTo: Newtonsoft.Json.Dynamic, PublicKey=0024000004800000940000000602000000240000525341310004000001000100cbd8d53b9d7de30f1f1278f636ec462cf9c254991291e66ebb157a885638a517887633b898ccbcf0d5c5ff7be85a6abe9e765d0ac7cd33c68dac67e7e64530e8222101109f154ab14a941c490ac155cd1d4fcba0fabb49016b4ef28593b015cab5937da31172f03f67d09edda404b88a60023f062ae71d0b2e4438b74cc11dc9
    System.Reflection.AssemblyTrademark:
    System.Runtime.InteropServices.ComVisible: False
    System.Runtime.InteropServices.Guid: 9ca358aa-317b-4925-8ada-4a29e943a363
    System.CLSCompliant: True
    System.Runtime.Versioning.TargetFramework: .NETStandard,Version=v2.0
      FrameworkDisplayName:
    System.Reflection.AssemblyCompany: Newtonsoft
    System.Reflection.AssemblyConfiguration: Release
    System.Reflection.AssemblyCopyright: Copyright © James Newton-King 2008
    System.Reflection.AssemblyDescription: Json.NET is a popular high-performance JSON framework for .NET
    System.Reflection.AssemblyFileVersion: 13.0.1.25517
    System.Reflection.AssemblyInformationalVersion: 13.0.1+ae9fe44e1323e91bcbd185ca1a14099fba7c021f
    System.Reflection.AssemblyProduct: Json.NET
    System.Reflection.AssemblyTitle: Json.NET .NET Standard 2.0
    System.Reflection.AssemblyMetadata: RepositoryUrl, https://github.com/JamesNK/Newtonsoft.Json
    System.Resources.NeutralResourcesLanguage: en-US

    Referenced assemblies

    netstandard, Version=2.0.0.0, Culture=neutral, PublicKeyToken=cc7b13ffcd2ddd51
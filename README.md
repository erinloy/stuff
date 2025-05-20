# Awesome Microsoft Ecosystem [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License: CC0](https://img.shields.io/badge/License-CC0-lightgrey.svg)](LICENSE)

A curated list of interesting, useful, and sometimes obscure open-source projects, tools, and resources within the .NET, C#, Azure, and larger Microsoft ecosystem. This list focuses on highlighting both popular and specialized solutions that advanced developers might find valuable.

## Table of Contents

- [.NET Core & Framework](#net-core--framework)
- [C# Libraries & Tools](#c-libraries--tools)
- [Data & Storage](#data--storage)
- [Reactive Programming](#reactive-programming)
- [Web Development](#web-development)
- [Azure & Cloud Resources](#azure--cloud-resources)
- [Unity & Game Development](#unity--game-development)
- [Cloud & Distributed Systems](#cloud--distributed-systems)
- [UI & Visualization](#ui--visualization)
- [Console Applications](#console-applications)
- [AI & Machine Learning](#ai--machine-learning)
- [Code Analysis & Compilation](#code-analysis--compilation)
- [Utilities & Helpers](#utilities--helpers)
- [Data Science & Algorithms](#data-science--algorithms)
- [DevOps & Version Control](#devops--version-control)
- [Package Managers](#package-managers)
- [Notable People & Organizations](#notable-people--organizations)
- [Learning Resources](#learning-resources)
- [Contributing](#contributing)
- [Changelog](#changelog)
- [License](#license)

## .NET Core & Framework

### Core Libraries & Extensions
- [Awesome .NET Core](https://github.com/awesomedotnetcore) - A collection of awesome .NET core libraries, tools, frameworks and software.
- [Nerdbank.GitVersioning](https://github.com/dotnet/Nerdbank.GitVersioning) - Stamp your assemblies with semver 2.0 compliant git commit specific version information.
- [Command Line API](https://github.com/dotnet/command-line-api) - Command line parsing, invocation, and rendering of terminal output.
- [.NEXT](https://github.com/sakno/dotNext) - A set of powerful high-performance extensions for .NET. [Documentation](https://sakno.github.io/dotNext/)
- [PolySharp](https://github.com/Sergio0694/PolySharp) - Provides polyfills for newer C# language features to older target frameworks.

### Runtime & Compilation
- [Natasha](https://github.com/dotnetcore/Natasha) - Dynamic compilation framework for C#.
- [CoreRT](https://github.com/dotnet/corert) - .NET Core runtime optimized for AOT compilation scenarios.
- [NativeAOT](https://github.com/dotnet/runtimelab/tree/feature/NativeAOT) - Compiles .NET applications to native code.

### Dependency Injection & IoC
- [ZeroIoC](https://github.com/byme8/ZeroIoC) - A dependency injection container with zero runtime overhead.
- [DryIoc](https://github.com/dadhi/DryIoc) - Fast, small, full-featured IoC container for .NET.
- [Dazinator.Extensions.DependencyInjection](https://github.com/dazinator/Dazinator.Extensions.DependencyInjection) - Child containers for Microsoft.Extensions.DependencyInjection.

### Performance
- [SimdJsonSharp](https://github.com/EgorBo/SimdJsonSharp) - C# port of the SimdJson high-performance JSON parser.
- [BenchmarkDotNet](https://github.com/dotnet/BenchmarkDotNet) - Powerful .NET library for benchmarking.
- [MemoryPack](https://github.com/Cysharp/MemoryPack) - Zero-allocation binary serializer for C#.

## C# Libraries & Tools

- [language-ext](https://github.com/louthy/language-ext) - C# functional language extensions that provide a base set of functional programming features.
- [CppAst.NET](https://github.com/xoofx/CppAst.NET) - A .NET library for parsing C/C++ code into a C# object model.
- [Sawmill](https://github.com/benjamin-hodgson/Sawmill) - Tools for working with immutable trees, based on Uniform Boilerplate and List Processing.
- [Pidgin](https://github.com/benjamin-hodgson/Pidgin) - A lightweight, fast, and flexible parsing library for C#.
- [dotnet-repl](https://github.com/jonsequitur/dotnet-repl) - A polyglot REPL built on .NET Interactive.
- [Time Period Library](https://www.codeproject.com/Articles/168662/Time-Period-Library-for-NET) - A .NET library for working with time periods.
- [Universal Type Converter](https://www.codeproject.com/Articles/248440/Universal-Type-Converter) - A utility class to convert between data types.
- [MessagePack-CSharp](https://github.com/neuecc/MessagePack-CSharp) - Extremely fast MessagePack serializer for C#.
- [Scientist.NET](https://github.com/scientistproject/Scientist.net) - A .NET library for carefully refactoring critical paths, ported from GitHub's Ruby library.
- [Coyote](https://github.com/microsoft/coyote) - Libraries and tools for building reliable asynchronous software.
- [CliWrap](https://github.com/Tyrrrz/CliWrap) - Library for executing and piping shell commands.
- [Sqids](https://github.com/sqids/sqids-dotnet) - Generate YouTube-like IDs from numbers.
- [Friflo.Json.Fliox](https://github.com/friflo/Friflo.Json.Fliox) - High-performance JSON serializer.
- [Rope](https://github.com/FlatlinerDOA/Rope) - Rope (immutable string) implementation for C#.
- [EnumerableAsyncProcessor](https://github.com/thomhurst/EnumerableAsyncProcessor) - Process collections asynchronously.
- [Morton Encoding](https://github.com/tedd/Tedd.MortonEncoding) - Implementation of Morton encoding (Z-order curve) in C#.
- [nanoid-net](https://github.com/codeyu/nanoid-net) - Alternative to UUID, tiny, secure, URL-friendly unique strings.

## Data & Storage

- [FASTER](https://microsoft.github.io/FASTER/) - Fast, thread-safe key-value store and cache from Microsoft Research. [Basic concepts](https://microsoft.github.io/FASTER/docs/fasterkv-basics/)
- [SimpleStore](https://www.microsoft.com/en-us/research/project/simplestore/) - A research storage system for client-cloud applications.
- [Memstate](https://github.com/DevrexLabs/memstate) - In-memory event-sourced ACID-transactional distributed object graph engine for .NET.
- [Rebus](https://github.com/rebus-org/Rebus) - Simple and lean service bus implementation for .NET.
- [AMBROSIA](https://github.com/microsoft/AMBROSIA) - A platform for distributed applications that provides virtually perfect fault tolerance and seamless upgrades.
- [Trill](https://github.com/Microsoft/Trill) - A high-performance single-node in-memory streaming analytics engine.
- [GraphQL.RepoDb](https://github.com/cajuncoding/GraphQL.RepoDb) - GraphQL integration for RepoDb ORM.
- [dotmim.sync](https://github.com/mimetis/dotmim.sync) - A .NET cross-platform data sync library.
- [Octodiff](https://github.com/OctopusDeploy/Octodiff) - Implementation of remote differential compression for efficient file transfer.

## Reactive Programming

- [ReactiveUI](https://github.com/reactiveui/ReactiveUI) - A reactive functional MVVM framework for .NET platforms.
- [DynamicData](https://github.com/reactiveui/DynamicData) - Reactive collections based on Rx.Net. [Website](http://dynamic-data.org)
- [ReactiveProperty](https://github.com/runceel/ReactiveProperty) - MVVM and asynchronous support library for Reactive Extensions.
- [Reaqtor](https://github.com/reaqtive/reaqtor) - A reactive framework for reliable data processing. [Website](https://reaqtive.net/)
- [echo-process](https://github.com/louthy/echo-process) - Actor framework for C# with additional support for AWS Lambda.
- [Pharmacist](https://github.com/reactiveui/pharmacist) - Generate Reactive Observables from Events in C#.
- [Alternative to .NET TPL](https://www.codeproject.com/Articles/5383493/Powerful-Alternative-to-NET-TPL) - A task parallel library alternative.

## Web Development

- [Blazor Web Worker](https://github.com/Tewr/BlazorWorker) - Invoke .NET methods in web workers from Blazor.
- [Blazor Switching](https://itnext.io/blazor-switching-server-and-webassembly-at-runtime-d65c25fd4d8) - Switch between Blazor server and WebAssembly at runtime.
- [AngleSharp](https://github.com/AngleSharp/AngleSharp) - The ultimate angle brackets parser library for HTML, SVG, MathML, and CSS.
- [Azure Functions OpenAPI Extension](https://github.com/Azure/azure-functions-openapi-extension) - OpenAPI extensions for Azure Functions.

## Azure & Cloud Resources

### Azure SDKs & Tools
- [Azure SDK for .NET](https://github.com/Azure/azure-sdk-for-net) - Official Azure SDK for .NET development.
- [Azure CLI](https://github.com/Azure/azure-cli) - Command-line interface for Azure.
- [Azurite](https://github.com/Azure/Azurite) - Azure Storage Emulator for local development.
- [Azure Functions .NET Worker](https://github.com/Azure/azure-functions-dotnet-worker) - .NET Worker implementation for Azure Functions.
- [Azure Dev CLI](https://github.com/Azure/azure-dev) - CLI tool for developer productivity on Azure.

### Azure Integration & Patterns
- [Azure Functions OpenAPI](https://github.com/Azure/azure-functions-openapi-extension) - OpenAPI extensions for Azure Functions.
- [Durable Functions ETL](https://github.com/microsoft/durabletask-netherite) - Netherite backend for Durable Task Framework.
- [Azure Service Bus Explorer](https://github.com/paolosalvatori/ServiceBusExplorer) - Windows application to manage Azure Service Bus resources.
- [CAF Terraform](https://github.com/aztfmod/terraform-azurerm-caf) - Cloud Adoption Framework for Terraform.
- [Azure Key Vault Explorer](https://github.com/microsoft/AzureKeyVaultExplorer) - GUI tool for managing Azure Key Vault secrets.

## Unity & Game Development

- [Awesome Unity3D](https://github.com/insthync/awesome-unity3d) - A categorized collection of awesome Unity3D resources.
- [SlnMerge](https://github.com/Cysharp/SlnMerge) - Merge Visual Studio and Unity solutions on the fly.
- [NuGetForUnity](https://github.com/GlitchEnzo/NuGetForUnity) - NuGet package manager for Unity.
- [Extenject](https://github.com/svermeulen/Extenject) - Dependency injection framework for Unity (successor to Zenject).
- [MLAPI.Cryptography](https://github.com/MidLevel/MLAPI.Cryptography) - Cryptography library for Unity networking.
- [Marvelous](https://adamramberg.github.io/marvelous/) - State management system for Unity.
- [Unity Atoms](https://adamramberg.github.io/unity-atoms/) - Tiny modular pieces utilizing the power of Scriptable Objects.
- [ScriptableObject-Architecture](https://github.com/DanielEverland/ScriptableObject-Architecture) - Framework utilizing ScriptableObjects for object references.
- [Stride 3D](https://www.stride3d.net/) - Open-source C# game engine.
- [RVO2-CS](https://github.com/snape/RVO2-CS) - Optimal Reciprocal Collision Avoidance for C#.

## Cloud & Distributed Systems

- [Orleans](https://github.com/dotnet/orleans) - Cross-platform framework for building distributed applications. [Awesome Orleans](https://github.com/OrleansContrib/Awesome-Orleans)
- [Dasync](https://github.com/Dasync/Dasync) - Distributed programming framework for .NET.
- [Miscreant.NET](https://github.com/miscreant/miscreant.net) - C# implementation of Miscreant misuse-resistant encryption library with AES-SIV and AES-PMAC-SIV. [Website](https://miscreant.io)
- [Noise.NET](https://github.com/Metalnem/noise) - .NET Standard implementation of the Noise Protocol Framework.
- [ProcessX](https://github.com/Cysharp/ProcessX) - Improved Process and shell scripting library for .NET.

## UI & Visualization

- [Terminal.Gui](https://github.com/migueldeicaza/gui.cs) - Console-based user interface toolkit for .NET applications.
- [ImGui](https://github.com/ocornut/imgui) - Immediate Mode Graphical User interface (with numerous C# bindings).
- [Tooll.io](http://www.tooll.io/) - Open source tool for creating interactive 3D content and animations.

### Graphing & Charts
- [LiveCharts2](https://github.com/beto-rodriguez/LiveCharts2) - Simple, flexible, interactive & powerful charts for .NET. [Website](https://livecharts.dev/)
- [Plotly.NET](https://github.com/plotly/Plotly.NET) - Data visualization library for F# and C#.
- [GLGraph](https://github.com/varon/GLGraph) - Scientific visualization using OpenGL.
- [SciChart](https://www.scichart.com/) - High performance chart library (commercial).
- [Image-Charts](https://github.com/image-charts/c-sharp) - Official C# client for the Image-Charts API.

## Console Applications

- [C# Console GUI Framework](https://github.com/TomaszRewak/C-sharp-console-gui-framework) - A simple GUI framework for console applications.
- [FluentColorConsole](https://github.com/developer82/FluentColorConsole) - Fluent API for colored console output.
- [Terminal.Gui](https://github.com/migueldeicaza/gui.cs) - Console-based user interface toolkit for .NET applications.

## AI & Machine Learning

- [RyskampLearningMachine](https://github.com/useaible/RyskampLearningMachine) - Neural network machine learning library for .NET. [Website](http://useaible.com/)
- [GeneticSharp](https://github.com/giacomelli/GeneticSharp) - Genetic algorithm library for .NET Core and .NET Framework.
- [Textc](https://github.com/takenet/textc-csharp) - C# NLP command parser.

### ChatGPT & LLM Tools
- [ChatGPT-Next-Web](https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web) - Cross-platform ChatGPT UI using Next.js.
- [copilot-gpt4-service](https://github.com/aaamoon/copilot-gpt4-service) - Convert GitHub Copilot requests to GPT-4 requests.

## Code Analysis & Compilation

- [CompilerExplorer](https://godbolt.org/) - Tool to explore compiler output. [GitHub](https://github.com/compiler-explorer/compiler-explorer)
- [flattened.net](https://flattened.net/) - Native C# compiler.
- [Essence Pattern in C#](https://www.codeproject.com/Articles/7349/The-Essence-Pattern-in-C) - Pattern for building type-safe APIs.
- [EssenceSharp](https://github.com/EssenceSharp/cSharp) - Modern metaprogramming for .NET. [Archive](https://archive.codeplex.com/?p=essencesharp)
- [MetaLinq](https://github.com/mcintyre321/MetaLinq) - LINQ but for expressions.

## Utilities & Helpers

- [ISO Recorder](http://isorecorder.alexfeinman.com/) - Convert CD/DVD to ISO file.
- [DNF Projects](https://www.dnfprojects.com/) - Direct .NET Framework projects.
- [Trool.io](https://trool.io/) - Rule engine for .NET.

## Data Science & Algorithms

- [Elo rating system](https://en.wikipedia.org/wiki/Elo_rating_system) - Method for calculating relative skill levels.
- [Statistical Ranking papers](https://www.stat.berkeley.edu/~aldous/Papers/me150.pdf) - Research on statistical ranking.
- [Statistical Ranking (Georgia Tech)](https://math.gatech.edu/sites/default/files/images/statistical-ranking.pdf) - Another paper on statistical approaches to ranking.
- [NoSQL Data Modeling Techniques](https://highlyscalable.wordpress.com/2012/03/01/nosql-data-modeling-techniques/) - Guide to NoSQL database modeling.
- [Key-Value Store Data Modeling Techniques](https://medium.com/@wishmithasmendis/from-rdbms-to-key-value-store-data-modeling-techniques-a2874906bc46) - Guide for transitioning from relational to key-value stores.
- [Differential Privacy for Ranking](https://tli2.github.io/assets/pdf/dpr-sigmod2021.pdf) - Research on differential privacy in ranking.
- [OKBC](https://www.researchgate.net/publication/2333835_OKBC_A_Programmatic_Foundation_for_Knowledge_Base_Interoperability) - Open Knowledge Base Connectivity. [Website](http://www.ai.sri.com/~okbc/)
- [Ben Houston DSP](https://benhouston3d.com/dsp/) - Digital Signal Processing resources.

## DevOps & Version Control

- [GitHub Mastering Markdown](https://guides.github.com/features/mastering-markdown/) - Guide to writing markdown for GitHub.
- [C# GitHub Repository Checklist](https://gist.github.com/ZacharyPatten/08532b31ef5efc7593b32326b498023a) - Checklist for setting up C# repositories on GitHub.
- [Private fork of public repo guide](https://gist.github.com/0xjac/85097472043b697ab57ba1b1c7530274) - How to maintain a private fork of a public repository.

## Package Managers

### Unity Package Managers
- [OpenUPM](https://openupm.com/) - Open Unity Package Manager registry.
- [Awesome UPM](https://github.com/starikcetin/awesome-upm) - Curated list of UPM packages.
- [XCrew.dev](https://xcrew.dev/) - Unity package registry.
- [UPM Packages](https://upm-packages.dev/) - Another Unity package registry.
- [Unity NuGet Registry](https://unitynuget-registry.azurewebsites.net/) - NuGet packages for Unity.
- [Unity NuGet](https://github.com/xoofx/UnityNuGet) - NuGet packages as Unity packages.

## Notable People & Organizations

- [Cysharp](https://github.com/Cysharp) - Organization focusing on high-performance .NET libraries.
- [neuecc](https://github.com/neuecc) - Creator of MessagePack-CSharp and other high-performance libraries.
- [Endjin](https://endjin.com/what-we-do/open-source/) - Company contributing to open-source .NET projects.

## Learning Resources

- ["Why Your Huge Tech Team Isn't Delivering"](https://mogest.medium.com/why-your-huge-tech-team-isnt-delivering-3851be27712c) - Article on team productivity issues.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request to add new resources or improve existing ones.

### Guidelines for Contributing
- Ensure the resource is related to the Microsoft ecosystem (.NET, C#, Azure, etc.)
- Provide a brief description of what the resource is or does
- Favor open-source projects, especially those that are unusual, specialized, or obscure
- Check that the link is working and points to the appropriate resource
- Follow the established format for consistency

## Changelog

### 2024-05-21: Curation and Enhancement
- Added "Contributing" section with guidelines
- Improved organization with more subcategories
- Added new specialized and obscure projects
- Enhanced descriptions for better clarity
- Improved cross-referencing between sections
- Standardized formatting across all entries

### 2024-05-14: Major Reorganization
- Complete restructuring of the list into logical categories
- Added table of contents for easier navigation
- Added descriptions for all resources
- Standardized formatting
- Grouped related resources together
- Added this changelog section

---

## License

This awesome list is under the [CC0 License](LICENSE).
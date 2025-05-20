# Awesome Microsoft Ecosystem [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License: CC0](https://img.shields.io/badge/License-CC0-lightgrey.svg)](LICENSE)

A curated list of interesting, useful, and sometimes obscure open-source projects, tools, and resources within the .NET, C#, Azure, and larger Microsoft ecosystem. This list focuses on highlighting both popular and specialized solutions that advanced developers might find valuable.

> 🔎 Looking for a specific type of tool? Use the Table of Contents below to navigate to the relevant section!

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
- [Quickenshtein](https://github.com/Turnerj/Quickenshtein) - High-performance Levenshtein distance implementation with SIMD and threading support.

## C# Libraries & Tools

### Functional Programming
- [language-ext](https://github.com/louthy/language-ext) - C# functional language extensions that provide a base set of functional programming features.
- [Optional](https://github.com/nlkl/Optional) - A robust option type for C#.
- [CSharpFunctionalExtensions](https://github.com/vkhorikov/CSharpFunctionalExtensions) - Functional extensions for C#.
- [Lemonad](https://github.com/inputfalken/Lemonad) - Functional programming library for C#.

### Parsing & Code Analysis
- [CppAst.NET](https://github.com/xoofx/CppAst.NET) - A .NET library for parsing C/C++ code into a C# object model.
- [Sawmill](https://github.com/benjamin-hodgson/Sawmill) - Tools for working with immutable trees, based on Uniform Boilerplate and List Processing.
- [Pidgin](https://github.com/benjamin-hodgson/Pidgin) - A lightweight, fast, and flexible parsing library for C#.
- [Gherkin.NET](https://github.com/cucumber/gherkin-dotnet) - .NET parser for the Gherkin language.
- [GParse](https://github.com/GGG-KILLER/GParse) - Modular parsing library for C#.
- [libpe](https://www.codeproject.com/Articles/5205732/libpe-PE32-PE32plus-Binaries-Viewer-Library) - Library for viewing and analyzing Windows PE32/PE32+ binary files.

### Development Tools
- [dotnet-repl](https://github.com/jonsequitur/dotnet-repl) - A polyglot REPL built on .NET Interactive.
- [Time Period Library](https://www.codeproject.com/Articles/168662/Time-Period-Library-for-NET) - A .NET library for working with time periods.
- [Universal Type Converter](https://www.codeproject.com/Articles/248440/Universal-Type-Converter) - A utility class to convert between data types.
- [Scientist.NET](https://github.com/scientistproject/Scientist.net) - A .NET library for carefully refactoring critical paths, ported from GitHub's Ruby library.
- [Coyote](https://github.com/microsoft/coyote) - Libraries and tools for building reliable asynchronous software.
- [CliWrap](https://github.com/Tyrrrz/CliWrap) - Library for executing and piping shell commands.

### Serialization & Data Handling
- [MessagePack-CSharp](https://github.com/neuecc/MessagePack-CSharp) - Extremely fast MessagePack serializer for C#.
- [Sqids](https://github.com/sqids/sqids-dotnet) - Generate YouTube-like IDs from numbers.
- [Friflo.Json.Fliox](https://github.com/friflo/Friflo.Json.Fliox) - High-performance JSON serializer.
- [Rope](https://github.com/FlatlinerDOA/Rope) - Rope (immutable string) implementation for C#.
- [EnumerableAsyncProcessor](https://github.com/thomhurst/EnumerableAsyncProcessor) - Process collections asynchronously.
- [Morton Encoding](https://github.com/tedd/Tedd.MortonEncoding) - Implementation of Morton encoding (Z-order curve) in C#.
- [nanoid-net](https://github.com/codeyu/nanoid-net) - Alternative to UUID, tiny, secure, URL-friendly unique strings.
- [ObjectMapper](https://github.com/geekyeggo/dotnet-object-mapper) - Declarative object-to-object mapping for .NET.

## Data & Storage

### High-Performance Storage
- [FASTER](https://microsoft.github.io/FASTER/) - Fast, thread-safe key-value store and cache from Microsoft Research. [Basic concepts](https://microsoft.github.io/FASTER/docs/fasterkv-basics/)
- [SimpleStore](https://www.microsoft.com/en-us/research/project/simplestore/) - A research storage system for client-cloud applications.
- [Memstate](https://github.com/DevrexLabs/memstate) - In-memory event-sourced ACID-transactional distributed object graph engine for .NET.
- [Akka.Persistence](https://github.com/akkadotnet/akka.net/tree/dev/src/core/Akka.Persistence) - Event-sourcing abstraction for Akka.NET actors.
- [Marten](https://github.com/JasperFx/marten) - .NET transactional document DB and event store on PostgreSQL.

### Messaging & Event Processing
- [Rebus](https://github.com/rebus-org/Rebus) - Simple and lean service bus implementation for .NET.
- [AMBROSIA](https://github.com/microsoft/AMBROSIA) - A platform for distributed applications that provides virtually perfect fault tolerance and seamless upgrades.
- [Trill](https://github.com/Microsoft/Trill) - A high-performance single-node in-memory streaming analytics engine.
- [MassTransit](https://github.com/MassTransit/MassTransit) - Distributed application framework for .NET.
- [NServiceBus](https://github.com/Particular/NServiceBus) - The most popular service bus for .NET.

### Data Integration & Synchronization
- [GraphQL.RepoDb](https://github.com/cajuncoding/GraphQL.RepoDb) - GraphQL integration for RepoDb ORM.
- [dotmim.sync](https://github.com/mimetis/dotmim.sync) - A .NET cross-platform data sync library.
- [Octodiff](https://github.com/OctopusDeploy/Octodiff) - Implementation of remote differential compression for efficient file transfer.
- [DbUp](https://github.com/DbUp/DbUp) - .NET library that helps you to deploy changes to SQL Server databases.
- [GenericRepository](https://github.com/SharpRepository/SharpRepository) - Generic Repository with rich LINQ filter capabilities.
- [Nisti.Data](https://github.com/miklund/Nisti.Data) - Lightweight database access layer for .NET.

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

### Distributed Computing Frameworks
- [Orleans](https://github.com/dotnet/orleans) - Cross-platform framework for building distributed applications. See also: [Awesome Orleans](https://github.com/OrleansContrib/Awesome-Orleans).
- [Dasync](https://github.com/Dasync/Dasync) - Distributed programming framework for .NET.
- [Akka.NET](https://github.com/akkadotnet/akka.net) - .NET port of the popular Java/Scala actor model framework. Related: [Akka.Persistence](#data--storage) for event sourcing.
- [Dapr](https://github.com/dapr/dapr) - Portable, event-driven runtime to build distributed applications. Works with [Azure](#azure--cloud-resources).
- [Service Fabric](https://github.com/microsoft/service-fabric) - Microsoft's distributed systems platform for packaging, deploying, and managing microservices.

### Cryptography & Security
- [Miscreant.NET](https://github.com/miscreant/miscreant.net) - C# implementation of Miscreant misuse-resistant encryption library with AES-SIV and AES-PMAC-SIV. [Website](https://miscreant.io)
- [Noise.NET](https://github.com/Metalnem/noise) - .NET Standard implementation of the Noise Protocol Framework.
- [BCrypt.NET](https://github.com/BcryptNet/bcrypt.net) - Modern and safe cryptographic library for .NET.
- [NSec](https://github.com/ektrah/nsec) - Modern cryptographic library for .NET based on libsodium.
- [HashLib](https://github.com/brandondahler/HashLib) - Collection of cryptographic hashing algorithms for .NET.

### Shell & Process Management
- [ProcessX](https://github.com/Cysharp/ProcessX) - Improved Process and shell scripting library for .NET.
- [Spectre.Console](https://github.com/spectreconsole/spectre.console) - Library for creating beautiful console applications. See also: [Console Applications](#console-applications).

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

### Neural Networks & Machine Learning
- [RyskampLearningMachine](https://github.com/useaible/RyskampLearningMachine) - Neural network machine learning library for .NET. [Website](http://useaible.com/)
- [GeneticSharp](https://github.com/giacomelli/GeneticSharp) - Genetic algorithm library for .NET Core and .NET Framework.
- [Textc](https://github.com/takenet/textc-csharp) - C# NLP command parser.
- [Accord.NET](https://github.com/accord-net/framework) - Machine learning, computer vision, statistics and general scientific computing for .NET.
- [ML.NET](https://github.com/dotnet/machinelearning) - Cross-platform machine learning framework for .NET.
- [TorchSharp](https://github.com/dotnet/TorchSharp) - .NET bindings for PyTorch.
- [BrightWire](https://github.com/jdermody/brightwire) - GPU/CPU machine learning framework for .NET.
- [TensorFlow.NET](https://github.com/SciSharp/TensorFlow.NET) - .NET bindings for TensorFlow.

### LLM Integration & Tools
- [ChatGPT-Next-Web](https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web) - Cross-platform ChatGPT UI using Next.js.
- [copilot-gpt4-service](https://github.com/aaamoon/copilot-gpt4-service) - Convert GitHub Copilot requests to GPT-4 requests.
- [OpenAI-DotNet](https://github.com/RageAgainstThePixel/OpenAI-DotNet) - Unofficial C# client for OpenAI API.
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) - Integration of LLMs with C# and Python.
- [PrivateGPT.NET](https://github.com/DefTruth/PrivateGPT.NET) - Privately run LLMs on documents using only C# and .NET.
- [LLamaSharp](https://github.com/SciSharp/LLamaSharp) - .NET binding for llama.cpp.
- [GitHub Copilot Chat](https://docs.github.com/en/copilot/github-copilot-chat/about-github-copilot-chat) - AI chat assistant that integrates directly with your development environment.

## Code Analysis & Compilation

- [CompilerExplorer](https://godbolt.org/) - Tool to explore compiler output. [GitHub](https://github.com/compiler-explorer/compiler-explorer)
- [flattened.net](https://flattened.net/) - Native C# compiler.
- [Essence Pattern in C#](https://www.codeproject.com/Articles/7349/The-Essence-Pattern-in-C) - Pattern for building type-safe APIs.
- [EssenceSharp](https://github.com/EssenceSharp/cSharp) - Modern metaprogramming for .NET. [Archive](https://archive.codeplex.com/?p=essencesharp)
- [MetaLinq](https://github.com/mcintyre321/MetaLinq) - LINQ but for expressions.

## Utilities & Helpers

### File & System Utilities
- [ISO Recorder](http://isorecorder.alexfeinman.com/) - Convert CD/DVD to ISO file.
- [DNF Projects](https://www.dnfprojects.com/) - Direct .NET Framework projects.
- [Process Explorer](https://docs.microsoft.com/en-us/sysinternals/downloads/process-explorer) - Advanced Task Manager alternative from Sysinternals.
- [Autoruns](https://docs.microsoft.com/en-us/sysinternals/downloads/autoruns) - Find and manage auto-starting applications.
- [WizTree](https://wiztreefree.com/) - Fastest disk space analyzer for Windows.

### Development Utilities
- [Trool.io](https://trool.io/) - Rule engine for .NET.
- [YamlDotNet](https://github.com/aaubry/YamlDotNet) - .NET library for YAML.
- [Sharp Compress](https://github.com/adamhathcock/sharpcompress) - .NET library for manipulating archives.
- [Humanizer](https://github.com/Humanizr/Humanizer) - Manipulation and display of strings, enums, dates, times, timespans, numbers and quantities.
- [SharpZipLib](https://github.com/icsharpcode/SharpZipLib) - Compression library for .NET.
- [SmartFormat](https://github.com/axuno/SmartFormat) - String formatting library with advanced features.

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

### Git & GitHub Tools
- [GitHub Markdown Guide](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) - Official guide to writing markdown for GitHub.
- [C# GitHub Repository Checklist](https://gist.github.com/ZacharyPatten/08532b31ef5efc7593b32326b498023a) - Checklist for setting up C# repositories on GitHub.
- [Private fork of public repo guide](https://gist.github.com/0xjac/85097472043b697ab57ba1b1c7530274) - How to maintain a private fork of a public repository.
- [git-tfs](https://github.com/git-tfs/git-tfs) - Two-way bridge between TFS and Git.
- [GitVersion](https://github.com/GitTools/GitVersion) - Generate a SemVer version number based on your Git repository.
- [GitHub Copilot](https://github.com/features/copilot) - AI pair programmer that offers autocomplete-style suggestions. [Documentation](COPILOT.md)
- [Copilot for CLI](https://docs.github.com/en/copilot/github-copilot-in-the-cli/about-github-copilot-in-the-cli) - AI assistance for shell commands directly in your terminal.

### CI/CD & Deployment
- [Cake](https://github.com/cake-build/cake) - Cross-platform build automation system with a C# DSL.
- [NUKE](https://github.com/nuke-build/nuke) - Build automation system for C# with a type-safe and IDE-friendly approach.
- [Octopus Deploy](https://github.com/OctopusDeploy) - DevOps tool to simplify complex deployments.
- [GitPitch](https://github.com/gitpitch/gitpitch) - Create and present slide decks from git repos.
- [Publish to GitHub](https://github.com/Tyrrrz/PublishToGitHub) - GitHub Action to publish changes with automated commits.
- [GitHub Copilot for PRs](https://docs.github.com/en/copilot/github-copilot-for-pull-requests/about-github-copilot-for-pull-requests) - AI-powered assistance for pull request descriptions and reviews.
- [GitHub Copilot for Issues](https://docs.github.com/en/copilot/github-copilot-in-issues/about-github-copilot-in-issues) - AI assistance for creating and managing GitHub issues.

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

### Articles & Blog Posts
- ["Why Your Huge Tech Team Isn't Delivering"](https://mogest.medium.com/why-your-huge-tech-team-isnt-delivering-3851be27712c) - Article on team productivity issues.
- ["Performance Best Practices in C#"](https://github.com/adamsitnik/awesome-dot-net-performance) - Curated list of resources about .NET performance.
- ["Async/Await Best Practices"](https://github.com/davidfowl/AspNetCoreDiagnosticScenarios/blob/master/AsyncGuidance.md) - Guidance for working with async/await in .NET.

### Books & Documentation
- [C# Language Design Notes](https://github.com/dotnet/csharplang) - Official C# language design notes and proposals.
- ["Writing High-Performance .NET Code"](https://www.writinghighperf.net/) - Book by Ben Watson about performance optimization.
- ["Pro .NET Memory Management"](https://prodotnetmemory.com/) - Book by Konrad Kokosa about .NET memory management.

### Courses & Tutorials
- [.NET Core Tutorials](https://dotnetcoretutorials.com/) - Practical tutorials for learning .NET Core.
- [Blazor University](https://blazor-university.com/) - Free Blazor training and resources.
- [Microservices with .NET](https://dotnet.microsoft.com/learn/aspnet/microservice-tutorial) - Official Microsoft tutorial on microservices.
- [Learn Razor Pages](https://www.learnrazorpages.com/) - Free ASP.NET Core tutorials.

> 💡 **Know a great resource that's not listed?** See the [Contributing](#contributing) section to add your suggestions!

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request to add new resources or improve existing ones.

### Guidelines for Contributing
- Ensure the resource is related to the Microsoft ecosystem (.NET, C#, Azure, etc.).
- Prioritize open-source projects, especially those that are unusual, specialized, or obscure.
- Provide a brief description (one sentence) of what the resource is or does.
- Format entries as: `- [Name](URL) - Description.` (note the period at the end).
- Check that links are working and point to the appropriate resource.
- Place the entry in the appropriate section, or suggest a new section if needed.
- For projects with multiple resources, consider adding: `[Website](URL)` or `[Documentation](URL)` after the description.
- Keep entries alphabetized within each section/subsection when possible.

### How to Contribute
1. Fork the repository
2. Create a new branch for your changes
3. Add your contributions following the guidelines above
4. Submit a pull request with a clear description of your additions/changes

## Changelog

### 2024-05-21: Curation and Enhancement
- Added repository badges for better visibility
- Created detailed "Contributing" section with comprehensive guidelines
- Improved organization with logical subcategories across all sections
- Added dedicated "Azure & Cloud Resources" section with 10+ new resources
- Enhanced C# Libraries & Tools section with functional programming resources
- Added 30+ new specialized and obscure projects across all categories
- Enhanced descriptions for better clarity and consistency
- Improved cross-referencing between related sections
- Added note encouraging contributions
- Standardized formatting across all entries
- Fixed outdated links and improved navigation

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
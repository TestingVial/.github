# TestingVial · GitHub

Write business‑oriented tests using the **Testing Vial** approach!

The **TestingVial** organization hosts a collection of open‑source projects designed to bring the *Testing Vial* philosophy - originally introduced in the article [Introducing the Testing Vial: a (better?) alternative to Testing Diamond and Testing Pyramid](https://www.code4it.dev/blog/testing-vial) - to multiple programming languages and ecosystems.

## 🎯 Purpose of the Organization

The goal of this organization is to provide a unified ecosystem that supports the full Testing Vial workflow:

### 1. Language‑specific Vial Attributes / Annotations

Each language‑focused repository defines a way to tag test cases using the **Vial attribute**, enabling developers to classify and describe tests in a business‑oriented, human‑friendly way.

Examples include:

*   **TestingVial.NET** – a C# implementation of the Vial attribute [(GitHub repo)](https://github.com/TestingVial/TestingVial.NET)
*   Future repositories for other languages (Python, Java, JavaScript, Go, etc.)

### 2. CLI Tools to Extract Vials

Dedicated CLI tools will parse source code looking for Vial‑annotated tests and generate metadata files with the `.vial` extension.

These `.vial` files act as a standardized, language‑agnostic test description format.

### 3. Tools That Consume `.vial` Files

Additional tooling will interpret `.vial` files to enable:

*   Documentation generation
*   Test analytics
*   Coverage mapping
*   Reporting
*   Integrations with external platforms

This three‑layer structure ensures that **any language can produce Vials**, and **any tool can consume them**, making the ecosystem highly extensible.

 



<!--
D2 diagram (ELK engine)
Tema: everglade green 

input: {
  dotnet: .NET {
    app: YOUR .NET Application

    vial: TestingVial.NET
    vial.shape: package

    cli: CLI .NET
    cli.shape: step

    app -> vial: enriches tests with
    cli -> vial: reads metadata from
  }

  python: Python {
    app: YOUR Python Application

    vial: TestingVial for Python
    vial.shape: package
    cli: CLI Python
    cli.shape: step

    app -> vial: enriches tests with
    cli -> vial: reads metadata from
  }

  node: Node.JS {
    app: YOUR Node.JS Application

    vial: TestingVial for Node.JS
    vial.shape: package
    cli: CLI for Node.JS
    cli.shape: step

    app -> vial: enriches tests with
    cli -> vial: reads metadata from
  }
}

file: file.vial
file.shape: page

input.dotnet.cli -> file: generates
input.python.cli -> file: generates
input.node.cli -> file: generates

output: {
  htmlConverter: HTML converter
  htmlConverter.shape: hexagon
  vsCodeExtension: VSCode extension
  vsCodeExtension.shape: hexagon
  standaloneTool: Standalone tool
  standaloneTool.shape: hexagon

  _.file -> htmlConverter
  _.file -> vsCodeExtension
  _.file -> standaloneTool
}

-->

<img width="5096" height="2578" alt="image" src="https://github.com/user-attachments/assets/c0559199-8e32-4d24-99db-d91f4ceef2d1" />



## 🧩 Vision

The long‑term vision for the TestingVial organization is to offer:

*   A complete multi‑language suite of Vial attribute libraries
*   CLI utilities for extracting and validating Vials
*   Developer tools, dashboards, and automations that make Vial‑based testing a natural part of the development lifecycle

By standardizing how tests are described and discovered, the Testing Vial helps teams write **more meaningful**, **business‑aligned**, and **actionable** tests.

## 📚 Current Status

The organization currently includes:

*   **TestingVial.NET** (C# implementation) [\[github.com\]](https://github.com/TestingVial/TestingVial.NET)
*   Additional repositories and tooling are under active development.

## 🤝 Contributing

Contributions are welcome!  

Whether you're building a Vial implementation for a new language, improving CLI tools, or contributing to documentation, your help can expand the Testing Vial ecosystem.

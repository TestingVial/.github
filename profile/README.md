## Hi there 👋

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->



<!--
D2 diagram (ELK engine)
classes: {
  done: {
    style: {
      stroke-width: 0
      fill: "#44C7B1"
      shadow: true
      border-radius: 5
    }
  }
  ongoing: {
    style: {
      fill: "orange"
    }
  }
}

k: Keys (Legend) {
  a: To be implemented/proposed
  b: Ongoing
  b.class: ongoing
  c: Implemented
  c.class: done
}

input: {
  dotnet: .NET {
    app: YOUR .NET Application

    vial: TestingVial for .NET
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

  _.file -> htmlConverter
  _.file -> vsCodeExtension
}

-->

<img width="5096" height="2578" alt="image" src="https://github.com/user-attachments/assets/c0559199-8e32-4d24-99db-d91f4ceef2d1" />

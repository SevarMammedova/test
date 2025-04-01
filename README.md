<p align="center">
  <a href="http://www.theunwindai.com">
    <img src="https://github.com/user-attachments/assets/9ebbb44d-3d21-4280-b48b-45414b274f59" width="900px" alt="Unwind AI">
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/shubhamsaboo/">
    <img src="https://img.shields.io/badge/-Follow%20Shubham%20Saboo-blue?logo=linkedin&style=flat-square" alt="LinkedIn">
  </a>
  <a href="https://twitter.com/Saboo_Shubham_">
    <img src="https://img.shields.io/twitter/follow/Shubham_Saboo" alt="Twitter">
  </a>
</p>

<hr/>

[![Discord](https://img.shields.io/discord/1312302100125843476?logo=discord&label=discord)](https://glama.ai/mcp/discord)
[![Subreddit subscribers](https://img.shields.io/reddit/subreddit-subscribers/mcp?style=flat&logo=reddit&label=subreddit)](https://www.reddit.com/r/mcp/)
[![build status](https://img.shields.io/azure-devops/build/dnceng-public/public/17/main)](https://dev.azure.com/dnceng-public/public/_build?definitionId=17)

# What is NuGetForUnity?

NuGetForUnity is a NuGet client built from scratch to run inside the Unity Editor. NuGet is a package management system which makes it easy to create packages that are distributed on a server and consumed by users. NuGet supports [semantic versioning](http://semver.org/) for packages as well as dependencies on other packages.

You can learn more about NuGet here: [nuget.org](https://www.nuget.org/)

## PHOTO

# How do I install NuGetForUnity?

<details>
<summary>Install via OpenUPM</summary>
The package is available on the <a href="https://openupm.com/packages/com.github-glitchenzo.nugetforunity/">openupm</a> registry. So you can install it via openupm-cli or manually using a scoped registry see documentation at <a href="https://openupm.com/packages/com.github-glitchenzo.nugetforunity/">openupm</a>.

```
openupm add com.github-glitchenzo.nugetforunity
```

</details>

<details>
<summary>Install as GIT dependency via Package Manager</summary>

#### Unity 2019.3 or newer

1. Open Package Manager window (Window | Package Manager)
1. Click `+` button on the upper-left of a window, and select "Add package from git URL..."
1. Enter the following URL and click `Add` button

```
https://github.com/GlitchEnzo/NuGetForUnity.git?path=/src/NuGetForUnity
```

> **_NOTE:_** To install a concrete version you can specify the version by prepending #v{version} e.g. `#v2.0.0`. For more see [Unity UPM Documentation](https://docs.unity3d.com/Manual/upm-git.html).

#### Unity 2019.2 or earlier

1. Close Unity Editor
1. Open Packages/manifest.json by any Text editor
1. Insert the following line after `"dependencies": {`, and save the file.

    ```json
    "com.glitchenzo.nugetforunity": "https://github.com/GlitchEnzo/NuGetForUnity.git?path=/src/NuGetForUnity",
    ```

1. Reopen Unity project in Unity Editor

</details>


## Licence

Project is licenced under the [MIT licence](https://github.com/AvaloniaUI/Avalonia/blob/master/licence.md).


# 🌟 Awesome LLM Apps

A curated collection of awesome LLM apps built with RAG and AI agents. This repository features LLM apps that use models from OpenAI, Anthropic, Google, and open-source models like DeepSeek, Qwen or Llama that you can run locally on your computer.

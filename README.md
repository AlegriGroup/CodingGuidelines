[![Alegri](Alegri-Logo.png)](http://www.alegri.eu)

# Coding Guidelines
*by [Alegri International Service GmbH](http://www.alegri.eu)*

- this document is in draft state -

# Namespaces

We use the recommendation of Microsoft, which is
> Alegri.(&lt;Product&gt;|&lt;Technology&gt;)[.&lt;Feature&gt;][.&lt;Subnamespace&gt;]

# Git
We use git with git flow as our source code control and release management.
It recommended to use tools like SourceTree for easier usage.

## Branching
- Fork from develop branch to a own repository
- Code like a hero
- Create a pull request to develop branch

## git flow:
- Start a feature branch from develop branch (SourceTree)
- Finish feature branch (SourceTree)
- Commit to develop branch (SourceTree)
- Merge master branch (GitHub)
- Create a release tag (GitHub)

## NuGet
- Commit on develop triggers a NuGet (or myget) pre-release package
- Create a release on GitHub triggers a NuGet stable package

# Alegri projects on GitHub

| Name | Description |
|---|---|
| [Alegri.Data.EF6](https://github.com/AlegriGroup/Alegri.Data.EF6) | Provides infrastructure elements to build a data access layer based on Entity Framework 6.1.3 |

# Alegri demos on GitHub
| Name | Description |
|---|---|
| [AspNetCore-RTM-1.0-Demos](https://github.com/AlegriGroup/AspNetCore-RTM-1.0-Demos) | TechTalk from [BenjaminAbt](https://github.com/BenjaminAbt) about ASP.NET Core |

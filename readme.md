<!--
GENERATED FILE - DO NOT EDIT
This file was generated by [MarkdownSnippets](https://github.com/SimonCropp/MarkdownSnippets).
Source File: /readme.source.md
To change this file edit the source file and then run MarkdownSnippets.
-->

# <img src="/src/icon.png" height="30px"> Verify.Phash

[![Build status](https://ci.appveyor.com/api/projects/status/18lflc71pchw565r?svg=true)](https://ci.appveyor.com/project/SimonCropp/Verify-Phash)
[![NuGet Status](https://img.shields.io/nuget/v/Verify.Phash.svg)](https://www.nuget.org/packages/Verify.Phash/)

Extends [Verify](https://github.com/SimonCropp/Verify) to allow verification of documents via [Phash](https://github.com/pgrho/phash).

Contains [comparers](https://github.com/SimonCropp/Verify/blob/master/docs/comparer.md) for png, jpg, bmp, and tiff.

Support is available via a [Tidelift Subscription](https://tidelift.com/subscription/pkg/nuget-verify.aspose?utm_source=nuget-verify.aspose&utm_medium=referral&utm_campaign=enterprise).

<!-- toc -->
## Contents

  * [Usage](#usage)
    * [Comparers](#comparers)
  * [Security contact information](#security-contact-information)<!-- endtoc -->


## NuGet package

https://nuget.org/packages/Verify.Phash/


## Usage

Given a test with the following definition:

<!-- snippet: TestDefinition -->
<a id='snippet-testdefinition'/></a>
```cs
public class Samples :
    VerifyBase
{
    public Samples(ITestOutputHelper output) :
        base(output)
    {
    }

    static Samples()
    {
        VerifyPhash.Initialize();
    }
```
<sup><a href='/src/Tests/Samples.cs#L8-L21' title='File snippet `testdefinition` was extracted from'>snippet source</a> | <a href='#snippet-testdefinition' title='Navigate to start of snippet `testdefinition`'>anchor</a></sup>
<!-- endsnippet -->


### Comparers

Register all comparers

```
VerifyPhash.RegisterComparers();
```


## Security contact information

To report a security vulnerability, use the [Tidelift security contact](https://tidelift.com/security). Tidelift will coordinate the fix and disclosure.


## Icon

[Hash Brown](https://thenounproject.com/term/hash/1129857/) designed by [Icon Mark](https://thenounproject.com/iconmark) from [The Noun Project](https://thenounproject.com/).

# 🍴`https://open-dot.net`🍽
Back in 2014, .NET was open-sourced. It’s now 2021 and the issue of the [.NET debugger being proprietary](https://github.com/dotnet/core/issues/505) was opened in 2017. A couple weeks back the .NET programming language (the runtime/SDK) had MIT code ripped out of it [by a Corporate Vice President](https://www.theverge.com/2021/10/22/22740701/microsoft-dotnet-hot-reload-removal-decision-open-source) to sell more Visual Studio licenses.

> "Product managers don't have the authority to yank something in a release candidate with a go-live license :)" - [Phillip Carter](https://news.ycombinator.com/item?id=28989077)

This [situation is so disappointing](https://dusted.codes/can-we-trust-microsoft-with-open-source) because .NET is yet to complete its transition to an open programming language. The Ballmeresq cold war with tooling vendors only [harms the ecosystem](https://twitter.com/ReedCopsey/status/1461546064859783170?s=20). The more people who can use .NET and that are attracted to .NET the more Microsoft can sell Azure because there’s great attach rates and uplift between .NET folks and Azure.

> ".NET, Visual Studio, and Visual Studio Code are all expensive ad campaigns funded by Azure. .NET and Visual Studio have excellent attach rate to Azure" - [msft-throwaway](https://news.ycombinator.com/item?id=28990820)

How can Microsoft expect .NET to [compete equally in open source](https://twitter.com/ReedCopsey/status/1461523223535882241) with programming languages where everything is developed in the open and not black boxed or walled off to large demographics of developers? Every marketing activity Microsoft has done with .NET about “we are open-source” is fundamentally lipstick on a pig if there is no unified way to debug programs authored in the language. 

What use is an open-source programming language that can only be debugged with proprietary software? This is not a problem for languages that .NET competes against in mindshare (Golang/Rust). Why did [dnSpy](https://github.com/dnSpy/dnSpy), [MonoDevelop](https://www.monodevelop.com), [Linqpad](https://www.linqpad.net), [JetBrains](https://www.jetbrains.com/help/rider/Debugging_Code.html) & [Samsung](https://github.com/Samsung/netcoredbg) have to reinvent the wheel? It's 2021 and the .NET platform is fractured at a foundational level.

Let's be honest here DevDiv... 

**Visual Studio is constraining the innovation of the .NET platform** 

The .NET JIT and key foundations that enable innovation could have been lightyears ahead had Microsoft invested in the platform properly for the past 15 years if the focus of DevDiv wasn't prioritised on making features that could sell more Visual Studio licenses: IntelliTrace, CodeLens, Architecture Explorer, Coded UI Tests, Fakes and HotReload.

What would programming languages and a platform that didn’t have the Visual Studio baggage look like? 

What would .NET look like if it didn't lose _that_ generation of brains back in 2006?

We all know that having openly developed modern and decent IDE extensibility would provide fertile ground for innovation (build system integration / debuggers / better integration with open-source projects on GitHub ) in the .NET platform. So why hasn't it happened yet?

# next steps

Send a pull-request to https://github.com/open-dotnet/.github/blob/master/README.md containing a random emoji to receive an invitation to join this GitHub organisation, join the [.NET evolution discord community](https://aka.ms/dotnet-discord) and [participate in the discussions](https://github.com/open-dotnet/.github/issues/7).

# social media

<a href="https://twitter.com/opendotnet?ref_src=twsrc%5Etfw" class="twitter-follow-button" data-show-count="false">Follow @opendotnet</a>

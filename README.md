HkFinancialFunctions 
===
Calculation Utility For Financial Operations :package:

[![Build Status](https://travis-ci.org/senvardarsemih/hk-financial-functions.svg?branch=master)](https://travis-ci.org/senvardarsemih/hk-financial-functions)
[![Build status](https://ci.appveyor.com/api/projects/status/kso6tmjv4oamwjmd?svg=true)](https://ci.appveyor.com/project/senvardarsemih/hk-financial-functions)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=senvardarsemih_hk-financial-functions&metric=alert_status)](https://sonarcloud.io/dashboard?id=senvardarsemih_hk-financial-functions)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=senvardarsemih_hk-financial-functions&metric=coverage)](https://sonarcloud.io/dashboard?id=senvardarsemih_hk-financial-functions)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=senvardarsemih_hk-financial-functions&metric=bugs)](https://sonarcloud.io/dashboard?id=senvardarsemih_hk-financial-functions)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=senvardarsemih_hk-financial-functions&metric=reliability_rating)](https://sonarcloud.io/dashboard?id=senvardarsemih_hk-financial-functions)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=senvardarsemih_hk-financial-functions&metric=security_rating)](https://sonarcloud.io/dashboard?id=senvardarsemih_hk-financial-functions)
![Nuget](https://img.shields.io/nuget/v/HkFinancialFunctions.svg?style=flat-square)
![Nuget](https://img.shields.io/nuget/dt/HkFinancialFunctions.svg)

## Description

As a lead online financial aggregator , we have to calculate every customer needs with certain accuracy.
We used to use a different nuget library for this kind of calculations [ExcelFinancialFunctions](https://www.nuget.org/packages/ExcelFinancialFunctions/)
But this library written F#, it's hard to extend or understand what's happening in it.
So we converted base financial functions from F# to C# and pack it with nuget so everbody can use it.

## Who?

We are **_Hesapkurdu R&D Team_**.You can check our services at [Hesapkurdu](https://www.hesapkurdu.com/) 
You can find out who we are & what we are doing at [Hesapkurdu Team](https://github.com/orgs/Hesapkurdu/teams/hesapkurdu)

## Where can I get it?

First, [install NuGet](http://docs.nuget.org/docs/start-here/installing-nuget).
Then install package via package manager console with this command.

```
PM> Install-Package HkFinancialFunctions
```

You can also get it from .net cli.

```
> dotnet add package HkFinancialFunctions
```

## Contributing

Any contributions welcome. Please fork this repository and create a pull request notifying your changes and why.

## Financial Dictionary 

We are using shortened names of some financial terms.You can find the list here :

* fv : Future Value
* pv : Present Value
* irr : Internal Return Rate
* iPmt : Interest Payment
* nPer : Number Of Periods
* nPv : Net Present Value
* pmt : Payment
* pPmt : Capital Payment

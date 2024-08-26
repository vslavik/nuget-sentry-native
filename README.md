
Unofficial NuGet package for Sentry SDK for C/C++
=================================================

[![NuGet Version and Downloads count](https://buildstats.info/nuget/Unofficial.Sentry.Native)](https://www.nuget.org/packages/Unofficial.Sentry.Native)  [![Build package](https://github.com/vslavik/nuget-sentry-native/actions/workflows/build-package.yml/badge.svg)](https://github.com/vslavik/nuget-sentry-native/actions/workflows/build-package.yml)

This is an unofficial package of the Sentry native SDK, intended for use as a NuGet dependency.

It includes the [sentry-native](https://github.com/getsentry/sentry-native) SDK as well as the
[sentry-cli](https://github.com/getsentry/sentry-cli) tool.


How to use
----------

Add the package as C++ project's dependency in Visual Studio. The package includes necessary rules to add the include directories, link the libraries and copy required DLL and EXE files to the output path.

You can use the `$(SentryCLI)` msbuild variable to invoke `sentry-cli`.

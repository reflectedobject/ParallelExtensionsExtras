[Stackoverflow Post]: https://stackoverflow.com/questions/5663395/net-observabledictionary "Stackoverflow Post"
[Samples for Parallel Programming with the .NET Framework]:(http://code.msdn.microsoft.com/ParExtSamples)
[A Tour of ParallelExtensionsExtras]:(http://blogs.msdn.com/b/pfxteam/archive/2010/04/04/9990342.aspx)
[a copy of the original]:(https://github.com/donatasm/ParallelExtensionsExtras)

# ParallelExtensionsExtrasStandard

This is a (hacked) version with all for **.Net Standard (2.0)**. No code was modified, just disabled.
The assembly outputs as ***ParallelExtensionsExtrasStandard*** while still using the same namespace. 

## Why ?
Needed a basic thread-safe observable collection along with some additional features to be used across .Net Core. 
* It has lot's of goodies. Thanks for the original implementation!
* This [Stackoverflow Post] inspired me to the use the lib. 

You can find [a copy of the original] library 

## Changes
* Removed all functinoality that did not build for .Net standard without code modifications.

## Want to contribute?
* Add a test project
* Report Bugs

# From the Original

Provides a plethora of interesting and useful extensions to take advantage of and complement 
the functionality available in the .NET Framework 4 for parallel programming.

ParallelExtensionsExtras is not a fully tested nor stable code base, but it does provide a 
wealth of code you can use as a starting point for your own solutions or simply as a learning 
tool to understand how various kinds of functionality might be implemented

* [Samples for Parallel Programming with the .NET Framework]
* [A Tour of ParallelExtensionsExtras]

License: MS-LPL
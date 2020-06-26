# BugTracker

A simple bug tracking system. Connects to a pair of databases, dbo.ActiveBugs and dbo.ResolvedBugs, to manage the bugs.
It is designed as a WPF app using .NET Core, but much of the behaviour is separated from the design and can easily be recycled for, e.g. mobile apps.

New bugs are added to dbo.ActiveBugs, then moved to dbo.ResolvedBugs when resolved.

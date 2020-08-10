<img align="right" width="80" height="80" data-rmimg src="https://endev.at/content/projects/WrapSQL/EndevLibsLogo.svg">

# WrapSQL

![GitHub](https://img.shields.io/github/license/TobiHatti/WrapSQL)
[![GitHub Release Date](https://img.shields.io/github/release-date-pre/TobiHatti/WrapSQL)](https://github.com/TobiHatti/WrapSQL/releases)
[![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/TobiHatti/WrapSQL?include_prereleases)](https://github.com/TobiHatti/WrapSQL/releases)
[![GitHub last commit](https://img.shields.io/github/last-commit/TobiHatti/WrapSQL)](https://github.com/TobiHatti/WrapSQL/commits/master)
[![GitHub issues](https://img.shields.io/github/issues-raw/TobiHatti/WrapSQL)](https://github.com/TobiHatti/WrapSQL/issues)
[![GitHub language count](https://img.shields.io/github/languages/count/TobiHatti/WrapSQL)](https://github.com/TobiHatti/WrapSQL)

![image](https://endev.at/content/projects/SQL-Wrapper-Classes/WrapSQL_Banner_300.svg)

Multiple wrapper-classes for several languages and DB-Types

### Supported Languages and DB-Types
- C# (Soon on NuGet)
  - MySQL
  - SQLite
  - ODBC
  - OleDb
- VB.NET
  - MySQL
  - SQLite
  - ODBC
  - OleDb
- PHP
  - MySQL

## Finding the right file or assembly
Navigate to "Finished" and select your desired Language, then select either the source-file or the assembly and add it to your own project.

A full documentation is included in every language-sub-folder:
- [README - C#](https://github.com/TobiHatti/WrapSQL/tree/master/Finished/C%23)
- [README - VB.NET](https://github.com/TobiHatti/WrapSQL/blob/master/Finished/VB.NET)
- [README - PHP](https://github.com/TobiHatti/WrapSQL/blob/master/Finished/PHP)

__NOTE: Some Files/Assemblies/Libraries require additional packages, such as NuGet packages, to work without any errors!__

## Quick overview
These Methods/Function exists for every language. Check corresponding readme for additional features.

```cs
// Executes a non-query statement, e.g. UPDATE, INSERT, DELETE, ...
WrapSQL.ExecuteNonQuery("UPDATE ...", parameter1, parameter2, ...);

// Returns a single value from a select-statement
WrapSQL.ExecuteScalar("SELECT COUNT(*) FROM ...", parameter1, parameter2, ...);

// Returns all effected rows retrieved by the select-statement
WrapSQL.ExecuteQuery("SELECT * FROM ...", parameter1, parameter2, ...);
```

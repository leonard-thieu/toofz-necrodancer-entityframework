# toofz Data

[![Build status](https://ci.appveyor.com/api/projects/status/cowbksjnikl2928m/branch/master?svg=true)](https://ci.appveyor.com/project/leonard-thieu/toofz-necrodancer-entityframework/branch/master)
[![codecov](https://codecov.io/gh/leonard-thieu/toofz-data/branch/master/graph/badge.svg)](https://codecov.io/gh/leonard-thieu/toofz-data)
[![MyGet](https://img.shields.io/myget/toofz/v/toofz.Data.svg)](https://www.myget.org/feed/toofz/package/nuget/toofz.Data)

## Overview

**toofz Data** serves as the data access layer (DAL) for **toofz**. Retrieving data is done through an Entity Framework Code First model. 
Modifying data uses a combination of `SqlBulkCopy` and raw SQL for performant bulk inserting and upserting.

---

**toofz Data** is a component of **toofz**. 
Information about other projects that support **toofz** can be found in the [meta-repository](https://github.com/leonard-thieu/toofz-necrodancer).

### Dependents

* [toofz API](https://github.com/leonard-thieu/api.toofz.com)
* [toofz Leaderboards Service](https://github.com/leonard-thieu/leaderboards-service)
* [toofz Daily Leaderboards Service](https://github.com/leonard-thieu/daily-leaderboards-service)
* [toofz Players Service](https://github.com/leonard-thieu/players-service)
* [toofz Replays Service](https://github.com/leonard-thieu/replays-service)

### Dependencies

* [toofz NecroDancer Core](https://github.com/leonard-thieu/toofz-necrodancer-core)

## Requirements

* .NET Framework 4.6.1
* MS SQL Server

## Building and testing

Visual Studio 2017 (version 15.3 or later) can be used to build and run tests. Integration tests require MS SQL Server.

## License

**toofz Data** is released under the [MIT License](LICENSE).
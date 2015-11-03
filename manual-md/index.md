November 2015

# ScalaRelational User Manual v1.1.0
**Author:** Matt Hicks, Tim Nieradzik

**Affiliation:** OUTR Technologies, LLC

## Table of contents
* [Introduction](introduction.md)
 * [Why not an ORM?](introduction.md#why-not-an-orm)
 * [Why not Interpolation?](introduction.md#why-not-interpolation)
 * [Why not Functional-Relational Programming?](introduction.md#why-not-functionalrelational-programming)
 * [Our approach: DSL and Mapper](introduction.md#our-approach-dsl-and-mapper)
 * [Features](introduction.md#features)
* [Getting started](getting-started.md)
 * [sbt dependencies](getting-started.md#sbt-dependencies)
 * [Library imports](getting-started.md#library-imports)
 * [Schema](getting-started.md#schema)
 * [Create the database](getting-started.md#create-the-database)
 * [Inserting](getting-started.md#inserting)
 * [Querying](getting-started.md#querying)
 * [Remarks](getting-started.md#remarks)
* [Mapper](mapper.md)
 * [sbt dependency](mapper.md#sbt-dependency)
 * [Library imports](mapper.md#library-imports-1)
 * [Table definition](mapper.md#table-definition)
 * [Entities](mapper.md#entities)
 * [Insert](mapper.md#insert)
 * [Batch inserting](mapper.md#batch-inserting)
 * [Query](mapper.md#query)
 * [Polymorphic tables](mapper.md#polymorphic-tables)
* [Querying](querying-1.md)
 * [Session management](querying-1.md#session-management)
 * [Transactions](querying-1.md#transactions)
 * [Select](querying-1.md#select)
 * [Update](querying-1.md#update)
 * [Delete](querying-1.md#delete)
 * [SQL functions](querying-1.md#sql-functions)
* [Table definition](table-definition-1.md)
 * [Mapper](table-definition-1.md#mapper-1)
 * [Column types](table-definition-1.md#column-types)
 * [References](table-definition-1.md#references)
 * [Defining a custom type](table-definition-1.md#defining-a-custom-type)
 * [Column properties](table-definition-1.md#column-properties)
 * [Versioning](table-definition-1.md#versioning)
* [Architecture](architecture.md)
 * [JDBC](architecture.md#jdbc)
 * [Macros](architecture.md#macros)
* [Databases](databases.md)
 * [Compatibility](databases.md#compatibility)
 * [H2](databases.md#h2)
 * [MariaDB/MySQL](databases.md#mariadbmysql)
* [Support](support.md)
 * [Test cases](support.md#test-cases)
 * [Links](support.md#links)
 * [Commercial Support](support.md#commercial-support)
* [Contributing](contributing.md)
 * [Manual](contributing.md#manual)
 * [Developing](contributing.md#developing)
 * [Committing](contributing.md#committing)
 * [License](contributing.md#license)
 * [Releases](contributing.md#releases)
* [Appendix: Changelog](appendix-changelog.md)
* [Appendix: Benchmarks](appendix-benchmarks.md)
* [Appendix: License](appendix-license.md)

*Abstract:* ScalaRelational is a type-safe framework for defining, modifying, and querying SQL databases in Scala.
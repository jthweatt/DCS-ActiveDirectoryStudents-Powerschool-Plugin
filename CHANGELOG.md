# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [1.2.0] - 2021-12-06

### Added

- Active Directory Student named query will now return the DCID field for the Students table. Utilize this column for as the unique identifier for a student account record.

- Active Directory Student named query will now return Entry and Exit codes and dates. This will help with detection of provisional enrollments that can affect the Autocomm import process.

## [1.1.0] - 2021-10-01

### Added

- Active Directory Students named query now returns Enrollment Status and Homeroom. Homeroom is formatted as _section-number teacher-lastname_.

## [1.0.0] - 2021-07-20

- Initial release build.

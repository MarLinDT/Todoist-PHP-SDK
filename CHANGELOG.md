# Change Log
All notable changes to this project will be documented in this file.

## 0.1.0 - 2014-12-21
### Added
- Started to code this library.
- Implemented loginUser() to login a user.
- Aliased loginUser() as getUserDetails(), because that’s what it does. ;)
- Implemented testToken() to check if the internally set token is valid.
- Implemented static getTimezones(), which returns all the different time zones Todoist supports.
- Implemented static registerUser() to register a user.
- Implemented static deleteUser() to delete a user. But be warned: This API(!) is buggy, because there is currently no way to check if the call really work, as the API returns “ok” all the time.

[Unreleased]: https://github.com/FabianBeiner/Todoist-PHP-SDK/compare/v0.1.0...HEAD
# Changelog

All notable changes to this project will be documented in this file.

The format is based on
[Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to
[Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.2.0](https://www.github.com/terraform-google-modules/terraform-google-bootstrap/compare/v1.1.0...v1.2.0) (2020-07-06)


### Features

* Add ability to define custom list of branches to trigger apply and custom cloudbuild YAML for terraform builds ([#41](https://www.github.com/terraform-google-modules/terraform-google-bootstrap/issues/41)) ([02467c8](https://www.github.com/terraform-google-modules/terraform-google-bootstrap/commit/02467c860b68cfab4e65241cae4406feb95a5674))
* Add skip_gcloud_download flag ([#39](https://www.github.com/terraform-google-modules/terraform-google-bootstrap/issues/39)) ([0e06b29](https://www.github.com/terraform-google-modules/terraform-google-bootstrap/commit/0e06b299a22c454cc0406c34de59fde150d33095))
* option to target bootstrap module at a folder ([#40](https://www.github.com/terraform-google-modules/terraform-google-bootstrap/issues/40)) ([fa923a5](https://www.github.com/terraform-google-modules/terraform-google-bootstrap/commit/fa923a5242146837ca9d5001390f9200ccc40a7f))

## [1.1.0](https://www.github.com/terraform-google-modules/terraform-google-bootstrap/compare/v1.0.0...v1.1.0) (2020-04-16)

### Features

* Add serviceusage api to the defaults (#13)
* Make sure group_org_admins has projectCreator permission. (#15)
* Add folder mover permission by default
* Add ability to customize / upgrade terraform version (#17)

## [1.0.0](https://www.github.com/terraform-google-modules/terraform-google-bootstrap/compare/v0.3.0...v1.0.0) (2020-01-27)


### ⚠ BREAKING CHANGES

* Increased minimum Google provider version to 3.3

### Features

* Upgrade to Project Factory 7.0 ([#9](https://www.github.com/terraform-google-modules/terraform-google-bootstrap/issues/9)) ([b0bb86b](https://www.github.com/terraform-google-modules/terraform-google-bootstrap/commit/b0bb86b666fc7e434f646ef35f7eaba6dc98e2d7))

## [0.3.0] - 2019-12-18

### Fixed
- Fixed [#5] where org admins were not able to access the terraform state bucket when using service account impersonation.

## [0.2.0] - 2019-12-16

### Added

- The `project_labels` and `storage_bucket_labels` variables. [#2]

### Changed

- The storage buckets are changed to enforce Bucket Policy Only access. [#3]
- The Terraform service account receives Security Admin by default. [#4]

## [0.1.0] - 2019-11-21

### Added

- Initial release. [#1]

[Unreleased]: https://github.com/terraform-google-modules/terraform-google-bootstrap/compare/v0.3.0...HEAD
[0.3.0]: https://github.com/terraform-google-modules/terraform-google-bootstrap/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/terraform-google-modules/terraform-google-bootstrap/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/terraform-google-modules/terraform-google-bootstrap/releases/tag/v0.1.0
[#5]: https://github.com/terraform-google-modules/terraform-google-bootstrap/issues/5
[#4]: https://github.com/terraform-google-modules/terraform-google-bootstrap/pull/4
[#3]: https://github.com/terraform-google-modules/terraform-google-bootstrap/issues/3
[#2]: https://github.com/terraform-google-modules/terraform-google-bootstrap/issues/2
[#1]: https://github.com/terraform-google-modules/terraform-google-bootstrap/pull/1

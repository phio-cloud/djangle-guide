# Versioning

Versioning is critical for consistency, predictability, and transparency in software. We use [Semantic Versioning](https://semver.org/).

In summary from the official documentation:

Given a version number MAJOR.MINOR.PATCH, increment the:

* MAJOR version when you make incompatible API changes.
* MINOR version when you add functionality in a backwards-compatible manner.
* PATCH version when you make backwards-compatible bug fixes.

Additional labels for prerelease and build metadata are available as extensions to the MAJOR.MINOR.PATCH format.


## Additional Guidelines

* Start development at `0.1.0` and increment the minor version for each internal release.
* Software being used in production should be `1.0.0`. 
* Each release should be performed within Github.
* Each release should be accompanied with release notes.
	* What's new.
	* What's been fixed.
	* What's been improved.
	* What's been deprecated.

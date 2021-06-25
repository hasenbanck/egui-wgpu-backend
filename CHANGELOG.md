# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Updated
- Target egui 0.13

## [0.9.0] - 2021-06-20
### Updated
- Target wgpu 0.9
- Port shaders to WGSL.
- Add sample count to RenderPass.
- Allow setting the texture filter mode for user textures.

## [0.8.0] - 2021-05-11
### Updated
- Target egui 0.12

## [0.7.0] - 2021-05-01
### Updated
- Target wgpu 0.8

## [0.6.0] - 2021-04-13
### Updated
- Target egui 0.11
- Set "strip_index_format" to None.

## [0.5.0] - 2021-03-16
### Updated
- Target egui 0.10
- Fix sRGB color font handling (web + native)

### Added
- Added a function to use off-screen textures inside the egui UI.

## [0.4.0] - 2021-02-01
### Updated
- Target egui 0.8.
- Target wgpu 0.7.

## [0.3.0] - 2020-12-17
### Updated
- Target egui 0.5.

## [0.2.2] - 2020-11-16
### Updated
- Removed the mutability on GPU resources.
- Some clippy cleanups.
- Updated dependencies.

## [0.2.1] - 2020-11-13
### Updated
- Switch to linear texture filtering for the default sampler.

## [0.2.0] - 2020-11-13
### Added
- Add support for user textures.
### Updated
- Target egui 0.3.

## [0.1.0] - 2020-10-12
### Added
- Initial commit.

## 0.6.1

- Fixed memory corruption in new_shader / new_program.

## 0.6.0

- Uniform warnings.

### 0.5.6

- Fixed runtime reification of uniforms.

### 0.5.5

- Support for runtime reification of uniforms.

### 0.5.4

- Added support for getting textures’ texels.

### 0.5.3

- Support for raw texture uploads.

### 0.5.2

- Added documentation link.

### 0.5.1

- *[internal]* Fixed vertex input offsets. That issue makes all prior versions fail when trying to
  handle multi-attributes vertices. You are very advised to upgrade to this version then.

## 0.5.0

- Fixed viewport issue.
- Removed the need of **core**.
- Removed `UniformName`.
- Fixed the `update_textures` function regarding **luminance**.
- Using `AsRef` for `update_textures`.
- Adapted mipmaps as `usize`.
- Panic if unknown pixel format.

### 0.4.3

- Implemented `Uniform` for `Texture`.

### 0.4.2

- Fixed `HasFramebuffer::free_framebuffer`.

### 0.4.1

- Crate fixed because of *0.4.0* being broken then yanked.

## 0.4.0

- Implemented existential quantification for `Pipeline`.
- Added travis CI support.

### 0.3.2

- Added `ProgramProxy` in the export list of lib.rs.

### 0.3.1

- Added `ProgramProxy` alias.

## 0.3.0

- `Program` now has its *uniform interface* tagged in the type.
- Added support for `luminance-0.4.0`.

### 0.2.1

- Removed `W` use from `Buffer` as it was removed in `luminance-0.3.0`.

## 0.2.0

- Added support for `luminance-0.2.0`.

## 0.1.0

- Initial revision.

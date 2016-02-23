# Release notes for iScroll

---

## Version 5.2.0 - 2016-02-23

### Fixes
* Unified click handling, always listen to click, prevent on tap.
* Removed `options.clickPreventDefault`


---

## Version 5.1.5 - 2016-02-10

### Fixes
* Changed default build to `dist` instead of `iscroll`

### New features
* Added `options.clickPreventDefault` to avoid clicks leaking through when scrolling.

---

##  Version 5.1.4 - 2015-12-14

### Fixes
* Added a guard for indicatorsMap


---

##  Version 5.1.1 - 2014.01.10

### Fixes
* Infinite scroll now switch from `transform` to `top/left` based on `useTransform` option.
* [#555](https://github.com/cubiq/iscroll/issues/555) removed unused variable
* [#372](https://github.com/cubiq/iscroll/issues/372) case insensitive check on tag names

### New features
* New `off` method to unload custom events
* Added `options.deceleration` to alter the momentum duration/speed
* Added release notes file

---

##  Version 5.1.0 - 2014.01.09

### Fixes
* [#558](https://github.com/cubiq/iscroll/issues/558) false positive for `isBadAndroid`

### New features
* Infinite scrolling
* Documentation
* `_execEvent` supports arguments

### Changes
* dist/minified files are no longer pushed to the main repo

---

*I started collecting release notes from version 5.1.0*

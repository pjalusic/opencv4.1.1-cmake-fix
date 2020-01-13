# opencv4.1.1-cmake-fix

Fix for building opencv 4.1.1 on Google Coral Dev Board. All changes needs to be done in `cmake` folder.

## How to

either
- download `OpenCVFindLibsPerf.diff` file and apply the changes:
  ```bash
  git apply OpenCVFindLibsPerf.diff
  ```
or
- download `OpenCVFindLibsPerf.cmake` and replace existing

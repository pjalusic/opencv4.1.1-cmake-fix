# opencv4.1.1-cmake-fix

Fix for building opencv 4.1.1 on Google Coral Dev Board. All changes needs to be done in `cmake` folder.

## How to

- clone this repository: 
  ```bash
  git clone https://github.com/pjalusic/opencv4.1.1-cmake-fix.git
  ```
- copy the .diff file into current folder 
  ```bash
  cp opencv4.1.1-cmake-fix/OpenCVFindLibsPerf.diff .
  ```
- apply the changes:
  ```bash
  git apply OpenCVFindLibsPerf.diff
  ```

# OpenRadioss External libraries

## What is OpenRadioss?

**Altair® Radioss®** is an industry-proven analysis solution that helps users evaluate and optimize product performance for highly nonlinear problems under dynamic loadings. For more than 30 years, organizations have used Altair Radioss to streamline and optimize the digital design process, replace costly physical tests with quick and efficient simulation, and speed up design optimization iterations.

**OpenRadioss** is the publicly available open-source code base that a worldwide community of researchers, software developers, and industry leaders are enhancing every day. OpenRadioss is changing the game by empowering users to make rapid contributions that tackle the latest challenges brought on by rapidly evolving technologies like battery development, lightweight materials and composites, human body models and biomaterials, autonomous driving and flight, as well as the desire to give passengers the safest environment possible via virtual testing.

With OpenRadioss, scientists and technologists can focus their research on a stable code base under professional maintenance that benefits from the large library of existing finite element capabilities and the continuous integration and continuous development tools provided to contributors.

For more information on the OpenRadioss project, please visit [www.openradioss.org](https://www.openradioss.org)

If you have any questions about OpenRadioss, please feel free to contact <webmaster@openradioss.org>.

## OpenRadioss External libraries repository

This repository hosts the external libraries needeed to build OpenRadioss.

The libraries are packed in release assets. OpenRadioss Starter and Engine build procedure are  downloading the release asset during compilation process according to the needed version.

## Repository content

Following third party libraries are stored in this repository:

* h3d: Altair h3d format writing library
* lapack: Lapack need for some Starter and Engine option.
* metis: Metis librry for Starter
* zlib: zlib for Starter and Engine

The license directory contains license description for all third party libaries.

**Note on the hm_reader library:**

The hm_reader library is added in the assets during its creation. It is not stored in the repository.

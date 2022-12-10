

<div align='left'>
    <font size="7" bold> <strong>VADRay<strong></font>
</div>

<br/>

[![Build Status](https://dev.azure.com/virtualads/VAD/_apis/build/status/VADRay?branchName=main)](https://dev.azure.com/virtualads/VAD/_build/latest?definitionId=54&branchName=main)

---

## Introduction 
A ray tracer for VAD team

<div align="center">
  <img width="500px" height="500px" src="https://github.com/Microsoft-Virtual-Ads/assets/blob/main/gallery/bunny2.png?raw=true"/>
  <img width="500px" height="500px" src="https://github.com/Microsoft-Virtual-Ads/assets/blob/main/gallery/bunny.png?raw=true"/>
</div>

<br/>
<div align="center">
  <img width="500px" height="500px" src="https://github.com/Microsoft-Virtual-Ads/assets/blob/main/gallery/coca2.png?raw=true"/>
  <img width="500px" height="500px" src="https://raw.githubusercontent.com/Microsoft-Virtual-Ads/assets/main/gallery/coca1.png"/>
</div>

---

## Build and Test
```shell
1. git clone --recursive https://virtualads@dev.azure.com/virtualads/VAD/_git/VADRay

2. Launch powershell as Administrator, and run "set-executionpolicy unrestricted" and enter A

3. Install ispc in tools folder and set the environment variable, e.g. "C:\Program Files\ISPC\ispc-v1.18.0-windows\bin"

4. Run init.cmd (cmd or powershell)

5. Open VADRay.sln and build the solution, run tests
```

---

## Features
This is a Physically based renderer.

- Pathtracing
- AO
- SPPM
- VPT
- Kdtree, BVH, Embree
- Microfacet with GGX distribution
- Low Discrepancy Sequence (Halton, Sobol...)
- ...

---

## License

Copyright (c) Microsoft Corporation. All rights reserved.

Licensed under the [MIT](LICENSE.txt) license.

<!--- Licensed to the Apache Software Foundation (ASF) under one -->
<!--- or more contributor license agreements.  See the NOTICE file -->
<!--- distributed with this work for additional information -->
<!--- regarding copyright ownership.  The ASF licenses this file -->
<!--- to you under the Apache License, Version 2.0 (the -->
<!--- "License"); you may not use this file except in compliance -->
<!--- with the License.  You may obtain a copy of the License at -->

<!---   http://www.apache.org/licenses/LICENSE-2.0 -->

<!--- Unless required by applicable law or agreed to in writing, -->
<!--- software distributed under the License is distributed on an -->
<!--- "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY -->
<!--- KIND, either express or implied.  See the License for the -->
<!--- specific language governing permissions and limitations -->
<!--- under the License. -->

<img src=https://raw.githubusercontent.com/apache/tvm-site/main/images/logo/tvm-logo-small.png width=128/> Open Deep Learning Compiler Stack
==============================================
[Documentation](https://tvm.apache.org/docs) |
[Contributors](CONTRIBUTORS.md) |
[Community](https://tvm.apache.org/community) |
[Release Notes](NEWS.md)

[![Build Status](https://ci.tlcpack.ai/buildStatus/icon?job=tvm/main)](https://ci.tlcpack.ai/job/tvm/job/main/)
[![WinMacBuild](https://github.com/apache/tvm/workflows/WinMacBuild/badge.svg)](https://github.com/apache/tvm/actions?query=workflow%3AWinMacBuild)

Apache TVM is a compiler stack for deep learning systems. It is designed to close the gap between the
productivity-focused deep learning frameworks, and the performance- and efficiency-focused hardware backends.
TVM works with deep learning frameworks to provide end to end compilation to different backends.

Neo-AI/TVM is a downstream branch of TVM that includes vendor- and product-specific features on top of the upstream codebase.

Branches
--------
  * dev [![Build Status](https://neo-ai-ci.amazon-ml.com/job/tvm/job/dev/badge/icon)](https://neo-ai-ci.amazon-ml.com/job/tvm/job/dev/badge/icon) - This is the development branch with most update to date source code.

License
-------
© Contributors Licensed under an [Apache-2.0](LICENSE) license.

Contribute to TVM
-----------------
TVM adopts apache committer model, we aim to create an open source project that is maintained and owned by the community.
Check out the [Contributor Guide](https://tvm.apache.org/docs/contribute/).

Acknowledgement
---------------
We learned a lot from the following projects when building TVM.
- [Halide](https://github.com/halide/Halide): Part of TVM's TIR and arithmetic simplification module
  originates from Halide. We also learned and adapted some part of lowering pipeline from Halide.
- [Loopy](https://github.com/inducer/loopy): use of integer set analysis and its loop transformation primitives.
- [Theano](https://github.com/Theano/Theano): the design inspiration of symbolic scan operator for recurrence.

# LP2020
Repositório de Linguagem de Programação

# **The Art of C++ / Sequences**

![](RackMultipart20200710-4-glfbax_html_49ac0cb03196381.gif)   ![](RackMultipart20200710-4-glfbax_html_49ac0cb03196381.gif)   ![](RackMultipart20200710-4-glfbax_html_49ac0cb03196381.gif)

[The Art of C++](https://taocpp.github.io/) / Sequences is a zero-dependency C++11 header-only library that provides efficient algorithms to generate and work on variadic templates

**Compatibility**

- Requires C++11 or newer.
- Tested with GCC 4.8+, Clang 3.4+, Xcode 6+ and Visual Studio 2017+.

**Provided algorithms and examples**

- All provided templates are in the nested namespace tao::seq.
- All templates don&#39;t use C++14 features, therefore being compatible with C++11. Sometimes, C++14/C++17 features are used conditionally, taking advantage of newer language features when available but providing C++11-compatible implementations otherwise.
- All templates use tao::seq::integer\_sequence, etc. internally, therefore being compatible with C++11.
- All templates use tao::seq::make\_integer\_sequence, etc. internally, therefore using the most scalable solution available.

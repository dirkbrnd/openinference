:robot: I have created a release *beep* *boop*
---


<details><summary>python-openinference-semantic-conventions: 0.1.26</summary>

## [0.1.26](https://github.com/dirkbrnd/openinference/compare/python-openinference-semantic-conventions-v0.1.25...python-openinference-semantic-conventions-v0.1.26) (2025-11-18)


### Features

* Add semantic conventions for agent and graph attributes ([#1748](https://github.com/dirkbrnd/openinference/issues/1748)) ([5f90a80](https://github.com/dirkbrnd/openinference/commit/5f90a8014c216a821c299d0c7ea7aa79a4fc738d))
* **litellm:** align embedding instrumentation with pending spec ([#2238](https://github.com/dirkbrnd/openinference/issues/2238)) ([d03047d](https://github.com/dirkbrnd/openinference/commit/d03047d880fc5538ba1b2fcbb37812a665905d33))
* **openai:** standardize completions to indexed attribute format ([#2242](https://github.com/dirkbrnd/openinference/issues/2242)) ([478d17a](https://github.com/dirkbrnd/openinference/commit/478d17a5433bd6119a8d501899a5eadbd2accccf))
* **semantic-conventions:** enhance provider enum to include XAI and DeepSeek ([#1766](https://github.com/dirkbrnd/openinference/issues/1766)) ([f7e125e](https://github.com/dirkbrnd/openinference/commit/f7e125ea70c181b2a3f069bcca4bae3bb75a7d45))
* **semcov:** Cost semantic convention changes ([#1694](https://github.com/dirkbrnd/openinference/issues/1694)) ([5f904bf](https://github.com/dirkbrnd/openinference/commit/5f904bfad33e109843924aab1a609845a050d6f3))
* **semcov:** Update input and output cost ([#1774](https://github.com/dirkbrnd/openinference/issues/1774)) ([c2ee804](https://github.com/dirkbrnd/openinference/commit/c2ee804e63cb4b5ff393238854c37d99c6f5d675))


### Bug Fixes

* **semconv:** refactor semconv ([#2281](https://github.com/dirkbrnd/openinference/issues/2281)) ([090864b](https://github.com/dirkbrnd/openinference/commit/090864b0549588830c38aaa1fcd9c9700f7caf14))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/dirkbrnd/openinference/issues/2294)) ([48b7a51](https://github.com/dirkbrnd/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
</details>

<details><summary>python-openinference-instrumentation: 0.1.43</summary>

## [0.1.43](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-v0.1.42...python-openinference-instrumentation-v0.1.43) (2025-11-18)


### Features

* add context manager for capturing openinference spans ([#1781](https://github.com/dirkbrnd/openinference/issues/1781)) ([aab3386](https://github.com/dirkbrnd/openinference/commit/aab33868276627705f3e83fe8898429b71a23695))
* add instrumentation for google-adk ([#1759](https://github.com/dirkbrnd/openinference/issues/1759)) ([aeb1769](https://github.com/dirkbrnd/openinference/commit/aeb17692d30cd8112bcad0990f1ec56491a59962))
* Agno instrumentor ([#1603](https://github.com/dirkbrnd/openinference/issues/1603)) ([50f30e2](https://github.com/dirkbrnd/openinference/commit/50f30e26b5fcc074cc8a7dbbc34e9c11b7af0e41))
* Allow to hide llm.prompts span from trace config ([#1863](https://github.com/dirkbrnd/openinference/issues/1863)) ([7d633d8](https://github.com/dirkbrnd/openinference/commit/7d633d8fcf6ab5dbd8596a5900f3982db8e88d89))
* increase default span attribute count limit to 10,000 ([#2042](https://github.com/dirkbrnd/openinference/issues/2042)) ([0e90576](https://github.com/dirkbrnd/openinference/commit/0e90576cd841c73f561ffbb98d9a39cfe035509d))
* **instrumentation:** add dangerously_using_project context manager ([#2134](https://github.com/dirkbrnd/openinference/issues/2134)) ([aed9db0](https://github.com/dirkbrnd/openinference/commit/aed9db05b93d1ae0cb7d8a49977de1926b038740))
* **instrumentation:** add helpers for remaining semantic conventions ([#1606](https://github.com/dirkbrnd/openinference/issues/1606)) ([cb3d4fa](https://github.com/dirkbrnd/openinference/commit/cb3d4fa5f0b5d3281c60fa02fa9219813218e815))
* **litellm:** align embedding instrumentation with pending spec ([#2238](https://github.com/dirkbrnd/openinference/issues/2238)) ([d03047d](https://github.com/dirkbrnd/openinference/commit/d03047d880fc5538ba1b2fcbb37812a665905d33))
* **openai:** standardize completions to indexed attribute format ([#2242](https://github.com/dirkbrnd/openinference/issues/2242)) ([478d17a](https://github.com/dirkbrnd/openinference/commit/478d17a5433bd6119a8d501899a5eadbd2accccf))
* pydanticai instrumentation ([#1639](https://github.com/dirkbrnd/openinference/issues/1639)) ([d8c5b9c](https://github.com/dirkbrnd/openinference/commit/d8c5b9cdf793dcce247b2ea852c28eba3a1989bc))
* **python:** get_first_span_id via a context manager ([#2013](https://github.com/dirkbrnd/openinference/issues/2013)) ([b0b080c](https://github.com/dirkbrnd/openinference/commit/b0b080c564a2fb72b8f6796cad603f0166bcc767))


### Bug Fixes

* Enable sampling when using OpenInference tracer ([#1782](https://github.com/dirkbrnd/openinference/issues/1782)) ([b4007cf](https://github.com/dirkbrnd/openinference/commit/b4007cffc5857028d6004aebd369877cab96d801))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/dirkbrnd/openinference/issues/2294)) ([48b7a51](https://github.com/dirkbrnd/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/dirkbrnd/openinference/issues/1567)) ([c2f428c](https://github.com/dirkbrnd/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))
* version upper bound on wrapt &lt;2.0 ([#2325](https://github.com/dirkbrnd/openinference/issues/2325)) ([57a4fa3](https://github.com/dirkbrnd/openinference/commit/57a4fa3329327bea41d6498c992d32ad87fd334c))


### Documentation

* update readmes for development setup and fixes ([#1629](https://github.com/dirkbrnd/openinference/issues/1629)) ([7b211b3](https://github.com/dirkbrnd/openinference/commit/7b211b3b1624ab433ba35568112f0a1d8964456f))
</details>

<details><summary>python-openinference-instrumentation-agno: 0.1.24</summary>

## [0.1.24](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-agno-v0.1.23...python-openinference-instrumentation-agno-v0.1.24) (2025-11-18)


### Features

* Agno instrumentor ([#1603](https://github.com/dirkbrnd/openinference/issues/1603)) ([50f30e2](https://github.com/dirkbrnd/openinference/commit/50f30e26b5fcc074cc8a7dbbc34e9c11b7af0e41))
* **Agno:** Capture agent graph attributes  ([#2090](https://github.com/dirkbrnd/openinference/issues/2090)) ([7930348](https://github.com/dirkbrnd/openinference/commit/7930348788c292958b3701119dc4c2837a341c53))
* **Agno:** Capture graph attributes for agent visual ([#2053](https://github.com/dirkbrnd/openinference/issues/2053)) ([8d5ae09](https://github.com/dirkbrnd/openinference/commit/8d5ae09b09fbcfaae7bab0dea25db3a2ad076a4d))
* **agno:** enable user tracking ([#1997](https://github.com/dirkbrnd/openinference/issues/1997)) ([d76f5f1](https://github.com/dirkbrnd/openinference/commit/d76f5f1ef112658a8286d9becf8c9f114b7bc911))
* **agno:** remove duplicate constants and resolve tool call issue ([#2304](https://github.com/dirkbrnd/openinference/issues/2304)) ([2f15069](https://github.com/dirkbrnd/openinference/commit/2f15069dbda1e0a030f6d095f5156fdd3ae6d2c6))
* enhance function call span attributes with input value and erro& ([#1836](https://github.com/dirkbrnd/openinference/issues/1836)) ([5d239df](https://github.com/dirkbrnd/openinference/commit/5d239dfbebcfaf34f276e9169be644b91eeafd09))
* Prioritize subclasses method wrapping to prevent multiple spans ([#1809](https://github.com/dirkbrnd/openinference/issues/1809)) ([cc37471](https://github.com/dirkbrnd/openinference/commit/cc37471bcf2be18ff205ab4e49654be42c27daee))
* Updated Agno attributes ([#2262](https://github.com/dirkbrnd/openinference/issues/2262)) ([a4a2135](https://github.com/dirkbrnd/openinference/commit/a4a213510a88117cbd0f15c4e84a84c8ee9b470d))
* Updates for new Agno verison ([#1647](https://github.com/dirkbrnd/openinference/issues/1647)) ([8292d0d](https://github.com/dirkbrnd/openinference/commit/8292d0d5620a9c58c4646e553704a31fd3f8cba3))


### Bug Fixes

* Agno duplicate model invoke ([#1614](https://github.com/dirkbrnd/openinference/issues/1614)) ([919e776](https://github.com/dirkbrnd/openinference/commit/919e776c41fc902f76e8da495c7618ae0ad84292))
* Agno Session ID issues ([#2313](https://github.com/dirkbrnd/openinference/issues/2313)) ([34402a0](https://github.com/dirkbrnd/openinference/commit/34402a0a8478e1b047a76c6a885c5256cec015bc))
* Agno streaming tool call handling ([#2309](https://github.com/dirkbrnd/openinference/issues/2309)) ([4b7da83](https://github.com/dirkbrnd/openinference/commit/4b7da833ae9a91989d09ea78c38ca2e0bd44c0b1))
* agno team id release ([#2415](https://github.com/dirkbrnd/openinference/issues/2415)) ([dcd3aa7](https://github.com/dirkbrnd/openinference/commit/dcd3aa7f33192a30976485c1a01b06765da24010))
* Agno v2 fixes ([#2211](https://github.com/dirkbrnd/openinference/issues/2211)) ([278f570](https://github.com/dirkbrnd/openinference/commit/278f570130635d99672126554b9d3a950c658ff4))
* **agno:** Allow agent.name to be `None` in `arun`. ([#1621](https://github.com/dirkbrnd/openinference/issues/1621)) ([5288979](https://github.com/dirkbrnd/openinference/commit/52889796daa5ac221af21b76d77b80e594cdcf89))
* **agno:** capture session_id and user_id for teams too ([#2086](https://github.com/dirkbrnd/openinference/issues/2086)) ([0a51d50](https://github.com/dirkbrnd/openinference/commit/0a51d50be89a440d6df2fca90fe72ab730ee7267))
* **agno:** Resolving CI issues for Agno ([#2380](https://github.com/dirkbrnd/openinference/issues/2380)) ([a82ef6c](https://github.com/dirkbrnd/openinference/commit/a82ef6c34a79d53c892c5017d76cce053655801d))
* **agno:** Update _output_value_and_mime_type to properly deserialize output messages ([#2433](https://github.com/dirkbrnd/openinference/issues/2433)) ([600d2f3](https://github.com/dirkbrnd/openinference/commit/600d2f3f320bed94bcae4ae4ed956c2d178a1e1c))
* correct usage of user id & session id ([#2138](https://github.com/dirkbrnd/openinference/issues/2138)) ([165b7e8](https://github.com/dirkbrnd/openinference/commit/165b7e890cb9691ff1ab3890288c97dc046f1a1b))
* filter sensitive model params ([#1737](https://github.com/dirkbrnd/openinference/issues/1737)) ([fe7ebbe](https://github.com/dirkbrnd/openinference/commit/fe7ebbe9f7663e39d6f18ee1be9f775f0f6e7fb4))
* Get last run output ([#2369](https://github.com/dirkbrnd/openinference/issues/2369)) ([57a9758](https://github.com/dirkbrnd/openinference/commit/57a97585512f34550d5a50508ca801440cda1071))
* handle AgnoInstrumentor failing with OpenAIResponses ([#1701](https://github.com/dirkbrnd/openinference/issues/1701)) ([f33fadf](https://github.com/dirkbrnd/openinference/commit/f33fadf5a67fd4bce8ba590cdae4c9b7d1133d74))
* Iterators for runs ([#2406](https://github.com/dirkbrnd/openinference/issues/2406)) ([6ac1483](https://github.com/dirkbrnd/openinference/commit/6ac14839368a932265cf64b8682586533b1633e2))
* nullable agent.name in agno instrumentation arun ([#1803](https://github.com/dirkbrnd/openinference/issues/1803)) ([c2cc388](https://github.com/dirkbrnd/openinference/commit/c2cc3884c3eb2ba00ddb992cc7b2aff1709bd891))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/dirkbrnd/openinference/issues/2294)) ([48b7a51](https://github.com/dirkbrnd/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
</details>

<details><summary>python-openinference-instrumentation-mistralai: 1.3.5</summary>

## [1.3.5](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-mistralai-v1.3.4...python-openinference-instrumentation-mistralai-v1.3.5) (2025-11-18)


### Bug Fixes

* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/dirkbrnd/openinference/issues/2294)) ([48b7a51](https://github.com/dirkbrnd/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/dirkbrnd/openinference/issues/1567)) ([c2f428c](https://github.com/dirkbrnd/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))
</details>

<details><summary>python-openinference-instrumentation-openai: 0.1.41</summary>

## [0.1.41](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-openai-v0.1.40...python-openinference-instrumentation-openai-v0.1.41) (2025-11-18)


### Features

* instrument OpenAI responses API ([#1521](https://github.com/dirkbrnd/openinference/issues/1521)) ([64cde2b](https://github.com/dirkbrnd/openinference/commit/64cde2b7230bfae3e7f7fb1141708a86ceea6b1a))
* **litellm:** align embedding instrumentation with pending spec ([#2238](https://github.com/dirkbrnd/openinference/issues/2238)) ([d03047d](https://github.com/dirkbrnd/openinference/commit/d03047d880fc5538ba1b2fcbb37812a665905d33))
* openai + openai agent support custom tool calls ([#2080](https://github.com/dirkbrnd/openinference/issues/2080)) ([ee8693c](https://github.com/dirkbrnd/openinference/commit/ee8693c3325380440e4af4e0df708851c5598c30))
* Openai audio + reasoning token counts ([#1547](https://github.com/dirkbrnd/openinference/issues/1547)) ([cbae31b](https://github.com/dirkbrnd/openinference/commit/cbae31b2838234a3fe388a1501caadd281ac545e))
* **openai:** align embedding instrumentation with pending spec ([#2210](https://github.com/dirkbrnd/openinference/issues/2210)) ([df5b9d5](https://github.com/dirkbrnd/openinference/commit/df5b9d5dc080eddc4c91b6cb413eadb59f6c9982))
* **openai:** implement image redaction for input values when hide_input_images=True ([#2146](https://github.com/dirkbrnd/openinference/issues/2146)) ([fac0604](https://github.com/dirkbrnd/openinference/commit/fac0604caeedf0b0332151dfde69f0b51b554652))
* **openai:** standardize completions to indexed attribute format ([#2242](https://github.com/dirkbrnd/openinference/issues/2242)) ([478d17a](https://github.com/dirkbrnd/openinference/commit/478d17a5433bd6119a8d501899a5eadbd2accccf))


### Bug Fixes

* CI Failures For OpenAI & OpenAI Agents ([#1725](https://github.com/dirkbrnd/openinference/issues/1725)) ([69576ca](https://github.com/dirkbrnd/openinference/commit/69576cac4628f7d3b1b36558ad6cf8e4ae65b2d8))
* CI Failures For OpenAI & OpenAI Agents Follow Up ([#1733](https://github.com/dirkbrnd/openinference/issues/1733)) ([ec1e855](https://github.com/dirkbrnd/openinference/commit/ec1e8552b40c8a04ee2b3b92073e41e405b95293))
* **openai:** add tool_id accumulator for resposne ([#2241](https://github.com/dirkbrnd/openinference/issues/2241)) ([cb6e1a6](https://github.com/dirkbrnd/openinference/commit/cb6e1a6f68a6262b0eb50d045eef002b086288c4))
* **openai:** handle complex output types in responses API for openai 2 compat ([#2253](https://github.com/dirkbrnd/openinference/issues/2253)) ([a209e6a](https://github.com/dirkbrnd/openinference/commit/a209e6a1a33b36a497de5cc44d7059a723a75020))
* **openai:** handle string format for image_url in chat completions ([#2213](https://github.com/dirkbrnd/openinference/issues/2213)) ([4d09a7e](https://github.com/dirkbrnd/openinference/commit/4d09a7ec101a849ca74e36820caaff519ebe610e))
* **openai:** update lower bound on openinference-semantic-conventions ([#2279](https://github.com/dirkbrnd/openinference/issues/2279)) ([45cfad1](https://github.com/dirkbrnd/openinference/commit/45cfad1d27d247b1a58d08f10db6ed5896863c69))
* ruff formating fix & bump ruff version in dev requirements ([#1600](https://github.com/dirkbrnd/openinference/issues/1600)) ([076bb79](https://github.com/dirkbrnd/openinference/commit/076bb7966d44fccdb2ab94e6f379ef4ae22c39b1))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/dirkbrnd/openinference/issues/2294)) ([48b7a51](https://github.com/dirkbrnd/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/dirkbrnd/openinference/issues/1567)) ([c2f428c](https://github.com/dirkbrnd/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))
</details>

<details><summary>python-openinference-instrumentation-openai-agents: 2.0.0</summary>

## [2.0.0](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-openai-agents-v1.3.1...python-openinference-instrumentation-openai-agents-v2.0.0) (2025-11-18)


###   BREAKING CHANGES

* set openinference processor as the exclusive processor by default ([#1792](https://github.com/dirkbrnd/openinference/issues/1792))

### Features

* openai + openai agent support custom tool calls ([#2080](https://github.com/dirkbrnd/openinference/issues/2080)) ([ee8693c](https://github.com/dirkbrnd/openinference/commit/ee8693c3325380440e4af4e0df708851c5598c30))
* **openai-agents:** add support for exclusive processor configuration ([#1586](https://github.com/dirkbrnd/openinference/issues/1586)) ([47c2ac3](https://github.com/dirkbrnd/openinference/commit/47c2ac350a113bf7df45fbcebdfc19504e73723c))
* **openai-agents:** capture graph.node.id and graph.node.parent_id semantics  ([#1854](https://github.com/dirkbrnd/openinference/issues/1854)) ([0864c13](https://github.com/dirkbrnd/openinference/commit/0864c13fdfa9e289468ac0a79a2860a155be46de))
* **openai:** implement image redaction for input values when hide_input_images=True ([#2146](https://github.com/dirkbrnd/openinference/issues/2146)) ([fac0604](https://github.com/dirkbrnd/openinference/commit/fac0604caeedf0b0332151dfde69f0b51b554652))
* set openinference processor as the exclusive processor by default ([#1792](https://github.com/dirkbrnd/openinference/issues/1792)) ([d56abb1](https://github.com/dirkbrnd/openinference/commit/d56abb1935aa4a96925214c39cef045381ab9b15))


### Bug Fixes

* CI Failures For OpenAI & OpenAI Agents ([#1725](https://github.com/dirkbrnd/openinference/issues/1725)) ([69576ca](https://github.com/dirkbrnd/openinference/commit/69576cac4628f7d3b1b36558ad6cf8e4ae65b2d8))
* CI Failures For OpenAI & OpenAI Agents Follow Up ([#1733](https://github.com/dirkbrnd/openinference/issues/1733)) ([ec1e855](https://github.com/dirkbrnd/openinference/commit/ec1e8552b40c8a04ee2b3b92073e41e405b95293))
* CI issues for openai agents ([#2367](https://github.com/dirkbrnd/openinference/issues/2367)) ([a18078b](https://github.com/dirkbrnd/openinference/commit/a18078bb150134b5988c454b9143e1ef93fc4aa6))
* fix IndexError for empty function output ([#1878](https://github.com/dirkbrnd/openinference/issues/1878)) ([e6453e7](https://github.com/dirkbrnd/openinference/commit/e6453e72784aac519e05c98b541a551500b814a4))
* **openai_agents:** Set status `on_span_end`. ([#1556](https://github.com/dirkbrnd/openinference/issues/1556)) ([2b53efa](https://github.com/dirkbrnd/openinference/commit/2b53efa491d81ab5852387f5a4d2e87972262616))
* openai-agents CI add eval_type_backport dependency for Python &lt;3.10 compatibility ([#2004](https://github.com/dirkbrnd/openinference/issues/2004)) ([f38ed8e](https://github.com/dirkbrnd/openinference/commit/f38ed8efe6734297a3e77c0b4d4ddde32bc8ba11))
* ruff formating fix & bump ruff version in dev requirements ([#1600](https://github.com/dirkbrnd/openinference/issues/1600)) ([076bb79](https://github.com/dirkbrnd/openinference/commit/076bb7966d44fccdb2ab94e6f379ef4ae22c39b1))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/dirkbrnd/openinference/issues/1567)) ([c2f428c](https://github.com/dirkbrnd/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))
</details>

<details><summary>python-openinference-instrumentation-vertexai: 0.1.12</summary>

## [0.1.12](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-vertexai-v0.1.11...python-openinference-instrumentation-vertexai-v0.1.12) (2025-11-18)


### Bug Fixes

* support function call parts when streaming ([#1587](https://github.com/dirkbrnd/openinference/issues/1587)) ([43abca2](https://github.com/dirkbrnd/openinference/commit/43abca26f75277f1a605389b1e99a19220104820))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/dirkbrnd/openinference/issues/1567)) ([c2f428c](https://github.com/dirkbrnd/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))
</details>

<details><summary>python-openinference-instrumentation-llama-index: 4.4.0</summary>

## [4.4.0](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-llama-index-v4.3.9...python-openinference-instrumentation-llama-index-v4.4.0) (2025-11-18)


### Features

* **llama-index:** Add LLM provider detection with lazy imports - res& ([#1710](https://github.com/dirkbrnd/openinference/issues/1710)) ([f20ac82](https://github.com/dirkbrnd/openinference/commit/f20ac827b1b38fe298e69753f6718b52e0807aa0))


### Bug Fixes

* Bump llama index version for tests + fix tests ([#1992](https://github.com/dirkbrnd/openinference/issues/1992)) ([a70bcd5](https://github.com/dirkbrnd/openinference/commit/a70bcd5090568dcf48b56cc2feb081d33febf3de))
* capture tools from chat kwargs ([#1509](https://github.com/dirkbrnd/openinference/issues/1509)) ([2083836](https://github.com/dirkbrnd/openinference/commit/2083836872dd9b3f4c40bcf66a2c3054f30aa59a))
* Llama Index CI issues ([#2455](https://github.com/dirkbrnd/openinference/issues/2455)) ([d8957a2](https://github.com/dirkbrnd/openinference/commit/d8957a2d65c5a23b58e6f3decac76f1bc9e4d624))
* llama-index support vertex-ai token counts ([#1986](https://github.com/dirkbrnd/openinference/issues/1986)) ([f75b573](https://github.com/dirkbrnd/openinference/commit/f75b573fe09851a2708de8aa26fef388138256c3))
* **llama-index:** Fixing output messages attributes types ([#2291](https://github.com/dirkbrnd/openinference/issues/2291)) ([45d9332](https://github.com/dirkbrnd/openinference/commit/45d9332fb9571361ea397e82a6b3a1582c20f804))
* **llama-index:** handle BaseAgent import changes in v0.13.0+ ([#2023](https://github.com/dirkbrnd/openinference/issues/2023)) ([62ce073](https://github.com/dirkbrnd/openinference/commit/62ce073c98887851dd02dfd785b791e7e7ca9cb5))
* **llama-index:** tools ui fix ([#1802](https://github.com/dirkbrnd/openinference/issues/1802)) ([c81bda4](https://github.com/dirkbrnd/openinference/commit/c81bda4e490677913e72d48509112f544970d57c))
* non-ascii characters in input.value ([#2199](https://github.com/dirkbrnd/openinference/issues/2199)) ([8bfdd0d](https://github.com/dirkbrnd/openinference/commit/8bfdd0d65aae74649a1087ec6796193485e0a73b))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/dirkbrnd/openinference/issues/2294)) ([48b7a51](https://github.com/dirkbrnd/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
* update dependancies for security ([#2320](https://github.com/dirkbrnd/openinference/issues/2320)) ([c7eab4f](https://github.com/dirkbrnd/openinference/commit/c7eab4fbcac5b7d7407d9ed9c28706d4919421fb))
</details>

<details><summary>python-openinference-instrumentation-dspy: 0.1.31</summary>

## [0.1.31](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-dspy-v0.1.30...python-openinference-instrumentation-dspy-v0.1.31) (2025-11-18)


### Features

* Add model name and provider fields to DSPy for better model tracking/instrumentation [#1730](https://github.com/dirkbrnd/openinference/issues/1730) ([#1730](https://github.com/dirkbrnd/openinference/issues/1730)) ([3613f66](https://github.com/dirkbrnd/openinference/commit/3613f66331d3529f9131c2b9432696a79a4b7b21))
* **dspy:** Add initial support for async tracing ([#1597](https://github.com/dirkbrnd/openinference/issues/1597)) ([205bdf0](https://github.com/dirkbrnd/openinference/commit/205bdf0e3a8da1c86802735112d9eff9f8dd0c5f))
* **dspy:** Display Module.forward Output in JSON Format ([#1729](https://github.com/dirkbrnd/openinference/issues/1729)) ([591a2d9](https://github.com/dirkbrnd/openinference/commit/591a2d921d6fa09342059d71d43da46076ba8fad))
* **dspy:** Instrument DSPy DummyLM ([#2067](https://github.com/dirkbrnd/openinference/issues/2067)) ([0b0349d](https://github.com/dirkbrnd/openinference/commit/0b0349d14f227ac6b51fdf461c4e614e8b80582a))
* **dspy:** Instrument DSPy.Tool ([#1617](https://github.com/dirkbrnd/openinference/issues/1617)) ([e1ee8ff](https://github.com/dirkbrnd/openinference/commit/e1ee8ff86148a3fe0a8abf69bde675c8e0491cf5))


### Bug Fixes

* **dspy:** mask api keys passed as arguments ([#1990](https://github.com/dirkbrnd/openinference/issues/1990)) ([98218a1](https://github.com/dirkbrnd/openinference/commit/98218a1bf710f860a93eb941194e2abcc2eec63f))
* **dspy:** replace configure() with context() in async tests ([#2178](https://github.com/dirkbrnd/openinference/issues/2178)) ([90c59e0](https://github.com/dirkbrnd/openinference/commit/90c59e01c48a0d89a93172ed8e9d2436117b7cbc))
* **dspy:** upstream max token default value change ([#1718](https://github.com/dirkbrnd/openinference/issues/1718)) ([1654bc1](https://github.com/dirkbrnd/openinference/commit/1654bc1e0734b0424f67d678ad1e5e4271a9942c))
* **instrumentation-dspy:** pin urllib3&lt;2.0 for pytest-recording compatibility ([#2007](https://github.com/dirkbrnd/openinference/issues/2007)) ([51f5040](https://github.com/dirkbrnd/openinference/commit/51f5040af8bef8f7407dde7451ea1f2fb6ca7950))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/dirkbrnd/openinference/issues/2294)) ([48b7a51](https://github.com/dirkbrnd/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/dirkbrnd/openinference/issues/1567)) ([c2f428c](https://github.com/dirkbrnd/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))
</details>

<details><summary>python-openinference-instrumentation-bedrock: 0.1.32</summary>

## [0.1.32](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-bedrock-v0.1.31...python-openinference-instrumentation-bedrock-v0.1.32) (2025-11-18)


### Features

* Add bedrock-agent instrumentation ([#1363](https://github.com/dirkbrnd/openinference/issues/1363)) ([e174240](https://github.com/dirkbrnd/openinference/commit/e174240a09db59c74b816efb3bc3176cc581d31e))
* **bedrock-agents:** Added Support for bedrock invoke inline agent ([#2256](https://github.com/dirkbrnd/openinference/issues/2256)) ([2d4e27e](https://github.com/dirkbrnd/openinference/commit/2d4e27eb29496154ef26754de36eb10a4312f4e5))
* **bedrock:** Add instrumentation for guardrailTrace ([#2058](https://github.com/dirkbrnd/openinference/issues/2058)) ([8ea1eef](https://github.com/dirkbrnd/openinference/commit/8ea1eef5db0a334c5ca66c77f7217246156d7ef0))
* **bedrock:** added support for retrieve, retrieve and generate ([#1786](https://github.com/dirkbrnd/openinference/issues/1786)) ([2652fa7](https://github.com/dirkbrnd/openinference/commit/2652fa7372a02980b55425591f16b61626db297c))
* **bedrock:** Bedrock converse streaming support added ([#2172](https://github.com/dirkbrnd/openinference/issues/2172)) ([5b9ba8f](https://github.com/dirkbrnd/openinference/commit/5b9ba8f8739170cf1aa4e6ae359449382bcd9416))
* **bedrock:** Multi Agent Support, capturing time metrics from metadata ([#1656](https://github.com/dirkbrnd/openinference/issues/1656)) ([ed367a2](https://github.com/dirkbrnd/openinference/commit/ed367a2707dd00d1e2fd9b7249deecd08ddd466f))


### Bug Fixes

* Added exception to span when invoke_agent throws an exception  ([#1742](https://github.com/dirkbrnd/openinference/issues/1742)) ([1027d18](https://github.com/dirkbrnd/openinference/commit/1027d185ed233edacf8cfc76993c761a3b6a8afe))
* **bedrock:** fix test compatibility with boto3-latest ([#2243](https://github.com/dirkbrnd/openinference/issues/2243)) ([7cf5760](https://github.com/dirkbrnd/openinference/commit/7cf576059859e370a3f83b60d0e2c9ff6d6971b7))
* **bedrock:** fixing invoke model api calls ([#1760](https://github.com/dirkbrnd/openinference/issues/1760)) ([0ce91a5](https://github.com/dirkbrnd/openinference/commit/0ce91a5da29c36160b16da7194c4c59dca24bed4))
* **bedrock:** Included apipath into metadata ([#1775](https://github.com/dirkbrnd/openinference/issues/1775)) ([081d630](https://github.com/dirkbrnd/openinference/commit/081d630d2147134574cf2dd47630592d58e5f00d))
* ruff formating fix & bump ruff version in dev requirements ([#1600](https://github.com/dirkbrnd/openinference/issues/1600)) ([076bb79](https://github.com/dirkbrnd/openinference/commit/076bb7966d44fccdb2ab94e6f379ef4ae22c39b1))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/dirkbrnd/openinference/issues/2294)) ([48b7a51](https://github.com/dirkbrnd/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/dirkbrnd/openinference/issues/1567)) ([c2f428c](https://github.com/dirkbrnd/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))
</details>

<details><summary>python-openinference-instrumentation-langchain: 0.1.56</summary>

## [0.1.56](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-langchain-v0.1.55...python-openinference-instrumentation-langchain-v0.1.56) (2025-11-18)


### Features

* add span attributes `llm.provider` and `llm.system` to langchain instrumentation ([#1791](https://github.com/dirkbrnd/openinference/issues/1791)) ([545f52d](https://github.com/dirkbrnd/openinference/commit/545f52d25ce803410d92ba7f18da8bf2a8d87087))
* Instrument sssistant tool calls made by LangGraph  ([#2012](https://github.com/dirkbrnd/openinference/issues/2012)) ([f0e5852](https://github.com/dirkbrnd/openinference/commit/f0e585258aca591dbb4e97cc1a7503b56971cebc))
* **langchain:** track tool schemas from LLM invocation parameters ([#1643](https://github.com/dirkbrnd/openinference/issues/1643)) ([65d3a82](https://github.com/dirkbrnd/openinference/commit/65d3a8219a1a061a4fdea19b17760096b5aca76a))
* unwrap input output keys from io values ([#1993](https://github.com/dirkbrnd/openinference/issues/1993)) ([534c727](https://github.com/dirkbrnd/openinference/commit/534c72764a72cfd995ecf3d0f70ecaafc7cf359a))


### Bug Fixes

* anthropic token count ([#2428](https://github.com/dirkbrnd/openinference/issues/2428)) ([698dc81](https://github.com/dirkbrnd/openinference/commit/698dc81f731140efb128a84892f6c9579c879a10))
* langchain auto instrumentor supports Python 3.14 ([#2292](https://github.com/dirkbrnd/openinference/issues/2292)) ([53b438a](https://github.com/dirkbrnd/openinference/commit/53b438acc181b1b482debbf9e9de263951d8c476))
* **langchain:** anthropic cache token count ([#2414](https://github.com/dirkbrnd/openinference/issues/2414)) ([9f21f0f](https://github.com/dirkbrnd/openinference/commit/9f21f0ffca32c9ba370c621166aa50a4743c6891))
* **Langchain:** Handle custom data in additional kwargs ([#1898](https://github.com/dirkbrnd/openinference/issues/1898)) ([c7f71e1](https://github.com/dirkbrnd/openinference/commit/c7f71e19a128ff6054cd66120bb00b79d70e51ef))
* **langchain:** import testing dependencies from changes brought by langchian v1.0.0 ([#2336](https://github.com/dirkbrnd/openinference/issues/2336)) ([55c9a0d](https://github.com/dirkbrnd/openinference/commit/55c9a0d3a6826f6a9c2fd76a108291a82e2f5b22))
* **Langchain:** map UsageMetadata object ([#2136](https://github.com/dirkbrnd/openinference/issues/2136)) ([dab6cfd](https://github.com/dirkbrnd/openinference/commit/dab6cfd72e6e537f0e8d0b5f78285f46182501fa))
* small typo in str() call ([#1822](https://github.com/dirkbrnd/openinference/issues/1822)) ([4a7385b](https://github.com/dirkbrnd/openinference/commit/4a7385b968330e420c67a9a9066fc0f95b4109c5))
* tool call for anthropic bedrock invoke model ([#1995](https://github.com/dirkbrnd/openinference/issues/1995)) ([c26ffe5](https://github.com/dirkbrnd/openinference/commit/c26ffe57e696221cd82c32e262b4cc8fd32fbe8a))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/dirkbrnd/openinference/issues/2294)) ([48b7a51](https://github.com/dirkbrnd/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/dirkbrnd/openinference/issues/1567)) ([c2f428c](https://github.com/dirkbrnd/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))
* use `llm_output` and `metadata` for model name ([#1819](https://github.com/dirkbrnd/openinference/issues/1819)) ([8cb7439](https://github.com/dirkbrnd/openinference/commit/8cb7439daf45910f918468651624519de1c1b8de))


### Documentation

* create gemini_tracing.py ([#1456](https://github.com/dirkbrnd/openinference/issues/1456)) ([46e135f](https://github.com/dirkbrnd/openinference/commit/46e135fdc394234e80510808fbd8b04746365b66))
</details>

<details><summary>python-openinference-instrumentation-guardrails: 0.1.11</summary>

## [0.1.11](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-guardrails-v0.1.10...python-openinference-instrumentation-guardrails-v0.1.11) (2025-11-18)


### Bug Fixes

* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/dirkbrnd/openinference/issues/2294)) ([48b7a51](https://github.com/dirkbrnd/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/dirkbrnd/openinference/issues/1567)) ([c2f428c](https://github.com/dirkbrnd/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))
</details>

<details><summary>python-openinference-instrumentation-crewai: 0.1.17</summary>

## [0.1.17](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-crewai-v0.1.16...python-openinference-instrumentation-crewai-v0.1.17) (2025-11-18)


### Features

* **crewai:** capture graph.node.id and graph.node.parent_id semantics ([#1794](https://github.com/dirkbrnd/openinference/issues/1794)) ([4645932](https://github.com/dirkbrnd/openinference/commit/4645932b68f7ed5ab3ecd8818ddad9e1011c027e))
* **crewai:** Enable Tracing Support For CrewAI Flows ([#2286](https://github.com/dirkbrnd/openinference/issues/2286)) ([4930cb1](https://github.com/dirkbrnd/openinference/commit/4930cb11f86845b10b02ed2cab03c63880419915))
* **crewai:** enhance span naming to include crew, agent, and tool context ([#2202](https://github.com/dirkbrnd/openinference/issues/2202)) ([af44991](https://github.com/dirkbrnd/openinference/commit/af44991003f70fc21701b2f1ead8a19554cd37e2))


### Bug Fixes

* **crewai:** CI Failures For CrewAI ([#2359](https://github.com/dirkbrnd/openinference/issues/2359)) ([0921129](https://github.com/dirkbrnd/openinference/commit/092112969c663b2215bd8a036441b8341a15d239))
* **crewai:** crewai default empty tasks ([#1682](https://github.com/dirkbrnd/openinference/issues/1682)) ([4a47bfc](https://github.com/dirkbrnd/openinference/commit/4a47bfc065b88b55bfcb7605abf66ef12a286ec9))
* **crewai:** CrewAI Flow Traces Not Generated With Async ([#2308](https://github.com/dirkbrnd/openinference/issues/2308)) ([7e7f532](https://github.com/dirkbrnd/openinference/commit/7e7f53283df61a0d78df01ab808bacdddd14620a))
* **crewai:** Not Getting Inputs For CrewAI Root Span ([#2193](https://github.com/dirkbrnd/openinference/issues/2193)) ([9cf3b8f](https://github.com/dirkbrnd/openinference/commit/9cf3b8fa0f432f6b6f783fc25a9d3d78f9164d4e))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/dirkbrnd/openinference/issues/1567)) ([c2f428c](https://github.com/dirkbrnd/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))
</details>

<details><summary>python-openinference-instrumentation-haystack: 0.1.29</summary>

## [0.1.29](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-haystack-v0.1.28...python-openinference-instrumentation-haystack-v0.1.29) (2025-11-18)


### Features

* **haysack-ai:** haystack async pipeline support ([#2300](https://github.com/dirkbrnd/openinference/issues/2300)) ([abd8837](https://github.com/dirkbrnd/openinference/commit/abd883711e519149142d214576e0ecf104e0a522))
* **haystack:** Added Components instrumentation ([#2383](https://github.com/dirkbrnd/openinference/issues/2383)) ([f22d546](https://github.com/dirkbrnd/openinference/commit/f22d54638a655078b6919e5e05b1678b613931e3))


### Bug Fixes

* CI Failures For Haystack ([#1736](https://github.com/dirkbrnd/openinference/issues/1736)) ([673dc40](https://github.com/dirkbrnd/openinference/commit/673dc4071845aa3282f9516de6a57d4c92790240))
* **haystack:** fixing ci issues for haystack-ai ([#1623](https://github.com/dirkbrnd/openinference/issues/1623)) ([daffa8e](https://github.com/dirkbrnd/openinference/commit/daffa8e3fa9825daa76268a91a208b8c77dd1cb1))
* **haystack:** support base64-encoded embeddings and list[Document] hints ([#2245](https://github.com/dirkbrnd/openinference/issues/2245)) ([75e5a1f](https://github.com/dirkbrnd/openinference/commit/75e5a1fbf245109fec99c6fde90dffe499380797))
* ruff formating fix & bump ruff version in dev requirements ([#1600](https://github.com/dirkbrnd/openinference/issues/1600)) ([076bb79](https://github.com/dirkbrnd/openinference/commit/076bb7966d44fccdb2ab94e6f379ef4ae22c39b1))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/dirkbrnd/openinference/issues/2294)) ([48b7a51](https://github.com/dirkbrnd/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/dirkbrnd/openinference/issues/1567)) ([c2f428c](https://github.com/dirkbrnd/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))
</details>

<details><summary>python-openinference-instrumentation-litellm: 0.1.29</summary>

## [0.1.29](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-litellm-v0.1.28...python-openinference-instrumentation-litellm-v0.1.29) (2025-11-18)


### Features

* **litellm:** add llm provider attributes ([#2094](https://github.com/dirkbrnd/openinference/issues/2094)) ([86e681a](https://github.com/dirkbrnd/openinference/commit/86e681aaf98116016848fc7d1b6c26a8c6607a25))
* **litellm:** Added Support for responses API in litellm instrumentor ([#2209](https://github.com/dirkbrnd/openinference/issues/2209)) ([1abc662](https://github.com/dirkbrnd/openinference/commit/1abc6624fc82381a2017f7871f1041391cea0eab))
* **litellm:** align embedding instrumentation with pending spec ([#2238](https://github.com/dirkbrnd/openinference/issues/2238)) ([d03047d](https://github.com/dirkbrnd/openinference/commit/d03047d880fc5538ba1b2fcbb37812a665905d33))
* **litellm:** track tool schemas from kwargs in litellm completion functions ([#1865](https://github.com/dirkbrnd/openinference/issues/1865)) ([4df17c3](https://github.com/dirkbrnd/openinference/commit/4df17c3562c1168db14af86fe5173b00e1ffadeb))
* reasoning, cache, audio token counts litellm ([#1516](https://github.com/dirkbrnd/openinference/issues/1516)) ([89fd465](https://github.com/dirkbrnd/openinference/commit/89fd465ff432d001fbca9cd3e4cca57bcf476d8a))


### Bug Fixes

* **litellm:** display tool_calls from model output ([#1722](https://github.com/dirkbrnd/openinference/issues/1722)) ([53c9fa5](https://github.com/dirkbrnd/openinference/commit/53c9fa5498135728364d122eefe2bf23ea30b47c))
* **litellm:** Fixing Invocation Params, Output Messages ([#1838](https://github.com/dirkbrnd/openinference/issues/1838)) ([9f15912](https://github.com/dirkbrnd/openinference/commit/9f15912bc87e697e1021db0b63e9d2c8b3d1e377))
* **litellm:** full JSON output ([#1735](https://github.com/dirkbrnd/openinference/issues/1735)) ([891fc26](https://github.com/dirkbrnd/openinference/commit/891fc265cd4a4c5600e7dd261e78ad4ad14e9cc6))
* **litellm:** remove sensitive info from invocation params ([#1571](https://github.com/dirkbrnd/openinference/issues/1571)) ([fe4f784](https://github.com/dirkbrnd/openinference/commit/fe4f784a020db96f41a2a1f49b1fe8a497369933))
* Missing Span Status In LiteLLM ([#1754](https://github.com/dirkbrnd/openinference/issues/1754)) ([126f816](https://github.com/dirkbrnd/openinference/commit/126f816577bf4450e0c15c3ac8fa8f7f754c58e5))
* Start span before API call ([#1562](https://github.com/dirkbrnd/openinference/issues/1562)) ([7d9306b](https://github.com/dirkbrnd/openinference/commit/7d9306b2f0654600b0a19c06319895470368fdde))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/dirkbrnd/openinference/issues/2294)) ([48b7a51](https://github.com/dirkbrnd/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/dirkbrnd/openinference/issues/1567)) ([c2f428c](https://github.com/dirkbrnd/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))
</details>

<details><summary>python-openinference-instrumentation-groq: 0.1.13</summary>

## [0.1.13](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-groq-v0.1.12...python-openinference-instrumentation-groq-v0.1.13) (2025-11-18)


### Bug Fixes

* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/dirkbrnd/openinference/issues/2294)) ([48b7a51](https://github.com/dirkbrnd/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/dirkbrnd/openinference/issues/1567)) ([c2f428c](https://github.com/dirkbrnd/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))
</details>

<details><summary>python-openinference-instrumentation-instructor: 0.1.13</summary>

## [0.1.13](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-instructor-v0.1.12...python-openinference-instrumentation-instructor-v0.1.13) (2025-11-18)


### Bug Fixes

* instructor output bug fix ([#1549](https://github.com/dirkbrnd/openinference/issues/1549)) ([905325f](https://github.com/dirkbrnd/openinference/commit/905325f324dd1d8079cebbb169b0b7fc933a8e0c))
* **instructor:** Added compatibility with the latest instructor versi& ([#2287](https://github.com/dirkbrnd/openinference/issues/2287)) ([5c5a02b](https://github.com/dirkbrnd/openinference/commit/5c5a02b84ee07106c3f50c193fa803460baa3c32))
* **instructor:** JSON Serialization Error for max_retries in Span Attributes ([#2212](https://github.com/dirkbrnd/openinference/issues/2212)) ([c6d1d40](https://github.com/dirkbrnd/openinference/commit/c6d1d40e98a123bb1029d0b7e4120de45f81d100))
* **instructor:** make UserInfo fields optional for streaming partial responses ([#2295](https://github.com/dirkbrnd/openinference/issues/2295)) ([5bb52cf](https://github.com/dirkbrnd/openinference/commit/5bb52cfe25d0ec9693d562110c0af1097b7518b5))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/dirkbrnd/openinference/issues/1567)) ([c2f428c](https://github.com/dirkbrnd/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))
</details>

<details><summary>python-openinference-instrumentation-anthropic: 0.1.21</summary>

## [0.1.21](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-anthropic-v0.1.20...python-openinference-instrumentation-anthropic-v0.1.21) (2025-11-18)


### Features

* **anthropic:** add stream wrapper and tests ([#1572](https://github.com/dirkbrnd/openinference/issues/1572)) ([918aa01](https://github.com/dirkbrnd/openinference/commit/918aa017441fd4c8cffdbcaab287913349a41a60))
* **anthropic:** Added support for anthropic sdk input images rendering  ([#2091](https://github.com/dirkbrnd/openinference/issues/2091)) ([d2684b4](https://github.com/dirkbrnd/openinference/commit/d2684b4b20e3b0199051c553580a8b27b673727f))


### Bug Fixes

* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/dirkbrnd/openinference/issues/2294)) ([48b7a51](https://github.com/dirkbrnd/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/dirkbrnd/openinference/issues/1567)) ([c2f428c](https://github.com/dirkbrnd/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))
</details>

<details><summary>python-openinference-instrumentation-smolagents: 0.1.21</summary>

## [0.1.21](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-smolagents-v0.1.20...python-openinference-instrumentation-smolagents-v0.1.21) (2025-11-18)


### Features

* **smolagents:** Improve Display Of Handled Errors ([#1845](https://github.com/dirkbrnd/openinference/issues/1845)) ([fb7eb1f](https://github.com/dirkbrnd/openinference/commit/fb7eb1fa36adb7bb5ff001dce196c32ceb244a18))


### Bug Fixes

* **smolagents:** Getting Multiple Traces While Streaming Code Agent ([#1872](https://github.com/dirkbrnd/openinference/issues/1872)) ([420ea79](https://github.com/dirkbrnd/openinference/commit/420ea79a5fd2ce572cb7bdcb38b6585107cce465))
* **smolagents:** include reasoning content ([#1697](https://github.com/dirkbrnd/openinference/issues/1697)) ([0c8ea99](https://github.com/dirkbrnd/openinference/commit/0c8ea99312874f605e1ab751e38dd13c8b0d4ea0))
* **smolagents:** instrument both __call__ and generate methods for complete model tracing ([#1744](https://github.com/dirkbrnd/openinference/issues/1744)) ([a963b96](https://github.com/dirkbrnd/openinference/commit/a963b9619776abe79fb6719eeb9eda01850aeff5))
* **smolagents:** Not Getting Step Spans From Latest Smolagents ([#2171](https://github.com/dirkbrnd/openinference/issues/2171)) ([14f0a19](https://github.com/dirkbrnd/openinference/commit/14f0a1994a43476f77b1e906912d4a572d194700))
* **smolagents:** prevent duplicate llm spans ([#2118](https://github.com/dirkbrnd/openinference/issues/2118)) ([f1a2946](https://github.com/dirkbrnd/openinference/commit/f1a29460344d37e7e431d2bd76bc6f724bcbb931))
* **smolagents:** tool spans fix ([#2425](https://github.com/dirkbrnd/openinference/issues/2425)) ([248d025](https://github.com/dirkbrnd/openinference/commit/248d025c71cfc6b378b6128635c8e37a39afef20))
* **smolagents:** use new token_usage structure ([#2087](https://github.com/dirkbrnd/openinference/issues/2087)) ([c691712](https://github.com/dirkbrnd/openinference/commit/c6917124a236eb6deff1e1faf214075662ebfc58))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/dirkbrnd/openinference/issues/2294)) ([48b7a51](https://github.com/dirkbrnd/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/dirkbrnd/openinference/issues/1567)) ([c2f428c](https://github.com/dirkbrnd/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))
</details>

<details><summary>python-openinference-instrumentation-autogen: 0.1.11</summary>

## [0.1.11](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-autogen-v0.1.10...python-openinference-instrumentation-autogen-v0.1.11) (2025-11-18)


### Bug Fixes

* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/dirkbrnd/openinference/issues/2294)) ([48b7a51](https://github.com/dirkbrnd/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/dirkbrnd/openinference/issues/1567)) ([c2f428c](https://github.com/dirkbrnd/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))
</details>

<details><summary>python-openinference-instrumentation-beeai: 0.1.14</summary>

## [0.1.14](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-beeai-v0.1.13...python-openinference-instrumentation-beeai-v0.1.14) (2025-11-18)


### Features

* BeeAI Framework Updates ([#2060](https://github.com/dirkbrnd/openinference/issues/2060)) ([720d1fe](https://github.com/dirkbrnd/openinference/commit/720d1fe2db55fa95fa9721438b441c4f7924c726))
* beeai python package ([#1496](https://github.com/dirkbrnd/openinference/issues/1496)) ([143b770](https://github.com/dirkbrnd/openinference/commit/143b770500e615fb692b3e5f945e8dc22e69c1d1))
* **beeai:** updates so we can run 0.1.19 ([#1576](https://github.com/dirkbrnd/openinference/issues/1576)) ([84129f0](https://github.com/dirkbrnd/openinference/commit/84129f0212763c96e23961695c4915ec5d14f2f7))
* **python:** update beeai version ([#1552](https://github.com/dirkbrnd/openinference/issues/1552)) ([48f04bb](https://github.com/dirkbrnd/openinference/commit/48f04bb7fdd03525d7824d9889aebb745d012a5e))
* update BeeAI data serialization ([#2108](https://github.com/dirkbrnd/openinference/issues/2108)) ([0994ec5](https://github.com/dirkbrnd/openinference/commit/0994ec58ffbb905da975b5e0be5ea9b512ca528b))
* update beeai framework package ([#1525](https://github.com/dirkbrnd/openinference/issues/1525)) ([dc8d128](https://github.com/dirkbrnd/openinference/commit/dc8d128042c661babb75b2609bb2f97d155ae9d8))
* update beeai-framework ([#2227](https://github.com/dirkbrnd/openinference/issues/2227)) ([8f8204d](https://github.com/dirkbrnd/openinference/commit/8f8204dfb5e2de4ad172f4af2cba056435bf5762))
* update beeai-framework integration ([#1829](https://github.com/dirkbrnd/openinference/issues/1829)) ([c788ec3](https://github.com/dirkbrnd/openinference/commit/c788ec3b8f1783fba1bb3d57022523d5de684b0a))


### Bug Fixes

* beeai python package ([#1522](https://github.com/dirkbrnd/openinference/issues/1522)) ([36b50d7](https://github.com/dirkbrnd/openinference/commit/36b50d7386f475a13a3665620b95cf4ade4e5ced))
* **beeaI:** dedupe traces/spans ([#2148](https://github.com/dirkbrnd/openinference/issues/2148)) ([c528758](https://github.com/dirkbrnd/openinference/commit/c5287584878089c4ea891b6768c5f2e4d86cbdb9))
* **beeai:** update for RequirementAgent move from experimental to stable ([#2255](https://github.com/dirkbrnd/openinference/issues/2255)) ([f511485](https://github.com/dirkbrnd/openinference/commit/f51148592ac904b488fbe5c0d8a0815a09e34ad3))
* removes spurious print(2) from python beeai and converts rest to loggers ([#1560](https://github.com/dirkbrnd/openinference/issues/1560)) ([038209a](https://github.com/dirkbrnd/openinference/commit/038209ab6be0d95181db19c1ae15b244ec7afe0a))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/dirkbrnd/openinference/issues/2294)) ([48b7a51](https://github.com/dirkbrnd/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/dirkbrnd/openinference/issues/1567)) ([c2f428c](https://github.com/dirkbrnd/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))
</details>

<details><summary>python-openinference-instrumentation-portkey: 0.1.8</summary>

## [0.1.8](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-portkey-v0.1.7...python-openinference-instrumentation-portkey-v0.1.8) (2025-11-18)


### Features

* portkey chat completions ([#1495](https://github.com/dirkbrnd/openinference/issues/1495)) ([0866af3](https://github.com/dirkbrnd/openinference/commit/0866af3e9428f59c67704899da37a63cfbef453c))
* **portkey:** Add support for propmt template calls ([#1663](https://github.com/dirkbrnd/openinference/issues/1663)) ([c1e813e](https://github.com/dirkbrnd/openinference/commit/c1e813e26c62713229958c625c088ffe46ea1608))
* **portkey:** Support instrumentation of `portkey_ai.AsyncPortkey` ([#2407](https://github.com/dirkbrnd/openinference/issues/2407)) ([118ef32](https://github.com/dirkbrnd/openinference/commit/118ef329a797c59e1e91ce00a3a13fd165c8fded))


### Bug Fixes

* **portkey:** CI Failures For Portkey ([#2368](https://github.com/dirkbrnd/openinference/issues/2368)) ([3654315](https://github.com/dirkbrnd/openinference/commit/365431588857ae5f15385f9dfc2f681e386b9845))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/dirkbrnd/openinference/issues/2294)) ([48b7a51](https://github.com/dirkbrnd/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
* update dependancies for security ([#2320](https://github.com/dirkbrnd/openinference/issues/2320)) ([c7eab4f](https://github.com/dirkbrnd/openinference/commit/c7eab4fbcac5b7d7407d9ed9c28706d4919421fb))
* update lower bound on openinference-semantic-conventions ([#1567](https://github.com/dirkbrnd/openinference/issues/1567)) ([c2f428c](https://github.com/dirkbrnd/openinference/commit/c2f428c5916c3dd62cf6670358f37111d4f7fd25))
</details>

<details><summary>python-openinference-instrumentation-mcp: 1.4.0</summary>

## [1.4.0](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-mcp-v1.3.3...python-openinference-instrumentation-mcp-v1.4.0) (2025-11-18)


### Features

* **mcp-python:** move instrumentation to transport layer ([#1563](https://github.com/dirkbrnd/openinference/issues/1563)) ([2ef9208](https://github.com/dirkbrnd/openinference/commit/2ef9208ecdf51e5cf5fba87da20f052ddb198668))
* **mcp:** add instrumentation support for Streamable-HTTP transport and bump mcp dependency to e1.8.1 ([#1640](https://github.com/dirkbrnd/openinference/issues/1640)) ([4df8976](https://github.com/dirkbrnd/openinference/commit/4df8976066f1911321ee31f7732854787079e981))
* **mcp:** mcp python context propagation ([#1524](https://github.com/dirkbrnd/openinference/issues/1524)) ([1af5f7d](https://github.com/dirkbrnd/openinference/commit/1af5f7d2e7c78e8fdebf9aaf2e50ccaa74eb6f9a))


### Bug Fixes

* **mcp:** handle ValidationError in stdio stream instrumentation ([#2170](https://github.com/dirkbrnd/openinference/issues/2170)) ([48aa236](https://github.com/dirkbrnd/openinference/commit/48aa2362a97a7efb029bd1f1e339297e6c6feec0))
* **mcp:** support mcp&gt;=1.8.0 with new SessionMessage structure ([#1634](https://github.com/dirkbrnd/openinference/issues/1634)) ([ba6af47](https://github.com/dirkbrnd/openinference/commit/ba6af477e97585a41f4a58efcb45890e9bb6c89c))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/dirkbrnd/openinference/issues/2294)) ([48b7a51](https://github.com/dirkbrnd/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
* update dependancies for security ([#2320](https://github.com/dirkbrnd/openinference/issues/2320)) ([c7eab4f](https://github.com/dirkbrnd/openinference/commit/c7eab4fbcac5b7d7407d9ed9c28706d4919421fb))
</details>

<details><summary>python-openinference-instrumentation-google-genai: 0.1.9</summary>

## [0.1.9](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-google-genai-v0.1.8...python-openinference-instrumentation-google-genai-v0.1.9) (2025-11-18)


### Features

* add Google GenAI instrumentation ([#1500](https://github.com/dirkbrnd/openinference/issues/1500)) ([1e669a8](https://github.com/dirkbrnd/openinference/commit/1e669a8af18bdfd8a0f92f716b49a7f6c105952a))
* Google Gen AI Tool Code Support ([#1763](https://github.com/dirkbrnd/openinference/issues/1763)) ([ec5cc3f](https://github.com/dirkbrnd/openinference/commit/ec5cc3f535cfb546f08506d18b93c373b494c7c2))


### Bug Fixes

* fix config_json serialization for GoogleGenAIInstrumentor ([#1855](https://github.com/dirkbrnd/openinference/issues/1855)) ([1702a1d](https://github.com/dirkbrnd/openinference/commit/1702a1d755d8ebc64fb3fa17e36579a6935d9dbd))
* google genai with pydantic ([#1724](https://github.com/dirkbrnd/openinference/issues/1724)) ([e2ea09a](https://github.com/dirkbrnd/openinference/commit/e2ea09a5395f47a5b60ec7961d22114293ebb4f1))
* **google-genai:** fix wrong tool attribute when setting llm input_message attribute ([#2260](https://github.com/dirkbrnd/openinference/issues/2260)) ([8ee0569](https://github.com/dirkbrnd/openinference/commit/8ee0569ae3e7bbf8c66f8bca2a34727d31cd007d))
* **google-genai:** Set input message attributes for function call and function response parts ([#2252](https://github.com/dirkbrnd/openinference/issues/2252)) ([be4b9c1](https://github.com/dirkbrnd/openinference/commit/be4b9c150f6a33a1ee394d19f7c8e7c7886fe307))
* include reasoning and audio token count for genai and adk instrumentors ([#1812](https://github.com/dirkbrnd/openinference/issues/1812)) ([921ff07](https://github.com/dirkbrnd/openinference/commit/921ff073e28ac2755b651dcdfac9ab3dbd673e70))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/dirkbrnd/openinference/issues/2294)) ([48b7a51](https://github.com/dirkbrnd/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))


### Documentation

* fix google genai import in README ([#1605](https://github.com/dirkbrnd/openinference/issues/1605)) ([60ee275](https://github.com/dirkbrnd/openinference/commit/60ee2755fa99a68debbe5e9d84c25b92e99c5e31))
</details>

<details><summary>python-openinference-instrumentation-autogen-agentchat: 0.1.7</summary>

## [0.1.7](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-autogen-agentchat-v0.1.6...python-openinference-instrumentation-autogen-agentchat-v0.1.7) (2025-11-18)


### Features

* **autogen-agentchat:** add tool call semantic convention attributes ([#2104](https://github.com/dirkbrnd/openinference/issues/2104)) ([fe0780d](https://github.com/dirkbrnd/openinference/commit/fe0780d243e9ecf89e6548e5793c7265dede1b86))
* **autogen-agentchat:** auto instrumentation ([#1611](https://github.com/dirkbrnd/openinference/issues/1611)) ([3c5857c](https://github.com/dirkbrnd/openinference/commit/3c5857c2864c3b367888683d1fd470ec631c389f))
* **autogen-agentchat:** capture graph.node.id and graph.node.parent_id semantics ([#1867](https://github.com/dirkbrnd/openinference/issues/1867)) ([9f8ca03](https://github.com/dirkbrnd/openinference/commit/9f8ca0373856e94305e531ef1e325525b5958ff9))
* **autogen-agentchat:** instrumenting AssistantAgent, BaseOpenAIChatCompletionClient, and BaseGroupChat ([#1790](https://github.com/dirkbrnd/openinference/issues/1790)) ([3a53ede](https://github.com/dirkbrnd/openinference/commit/3a53ede8716e1a2d862ec653740b93881ebb1106))


### Bug Fixes

* **autogen-agentchat:** filter out invalid kwargs before binding calls and record new vcrs for tests for autogen version 0.6.x ([#1871](https://github.com/dirkbrnd/openinference/issues/1871)) ([9c4ada0](https://github.com/dirkbrnd/openinference/commit/9c4ada0847be85fff074ef493ad2f138f80369d2))
* autogent-agentchat modelname fix ([#2436](https://github.com/dirkbrnd/openinference/issues/2436)) ([1547025](https://github.com/dirkbrnd/openinference/commit/1547025474eef190d1ae85b49faa8f9c3329db08))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/dirkbrnd/openinference/issues/2294)) ([48b7a51](https://github.com/dirkbrnd/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
</details>

<details><summary>python-openinference-instrumentation-pydantic-ai: 0.1.10</summary>

## [0.1.10](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-pydantic-ai-v0.1.9...python-openinference-instrumentation-pydantic-ai-v0.1.10) (2025-11-18)


### Features

* pydanticai instrumentation ([#1639](https://github.com/dirkbrnd/openinference/issues/1639)) ([d8c5b9c](https://github.com/dirkbrnd/openinference/commit/d8c5b9cdf793dcce247b2ea852c28eba3a1989bc))
* update pydantic-ai to v2 tracing format ([#2186](https://github.com/dirkbrnd/openinference/issues/2186)) ([5eecce5](https://github.com/dirkbrnd/openinference/commit/5eecce5c648d710d3ad9397e23773096e5903352))


### Bug Fixes

* pydantic-ai add tool call result ([#2305](https://github.com/dirkbrnd/openinference/issues/2305)) ([ede428c](https://github.com/dirkbrnd/openinference/commit/ede428cc5653b1c8d89c6ba68753a1a57fb2bacd))
* pydantic-ai fix span filtering ([#2016](https://github.com/dirkbrnd/openinference/issues/2016)) ([c139f36](https://github.com/dirkbrnd/openinference/commit/c139f3677233fb7c76b0b2bff5b4a2dafe1921dc))
* pydantic-ai properly instrument tools and instructions ([#2250](https://github.com/dirkbrnd/openinference/issues/2250)) ([6458835](https://github.com/dirkbrnd/openinference/commit/64588357d31137dafcd855c9c610ce241dcd0519))
* pydantic-ai use final user message as input value ([#2237](https://github.com/dirkbrnd/openinference/issues/2237)) ([208232d](https://github.com/dirkbrnd/openinference/commit/208232dfd6d47e8123beea41c47c8fc556012325))
* rename pydantic ai test dir ([#1706](https://github.com/dirkbrnd/openinference/issues/1706)) ([d45b00c](https://github.com/dirkbrnd/openinference/commit/d45b00cce1d5960e090dac3801a914523fb0355c))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/dirkbrnd/openinference/issues/2294)) ([48b7a51](https://github.com/dirkbrnd/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))


### Documentation

* fix pip install in readme ([#1705](https://github.com/dirkbrnd/openinference/issues/1705)) ([4fbad21](https://github.com/dirkbrnd/openinference/commit/4fbad21f700325af4cd5d314881ec004a859bdf8))
</details>

<details><summary>python-openinference-instrumentation-google-adk: 0.1.7</summary>

## [0.1.7](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-google-adk-v0.1.6...python-openinference-instrumentation-google-adk-v0.1.7) (2025-11-18)


### Features

* add instrumentation for google-adk ([#1759](https://github.com/dirkbrnd/openinference/issues/1759)) ([aeb1769](https://github.com/dirkbrnd/openinference/commit/aeb17692d30cd8112bcad0990f1ec56491a59962))


### Bug Fixes

* **google-adk:** fix test compatibility with v1.13.0 ([#2176](https://github.com/dirkbrnd/openinference/issues/2176)) ([dbe0668](https://github.com/dirkbrnd/openinference/commit/dbe066844397be079e90900ab3eff9a920dbf436))
* **google-adk:** remove dependency on private telemetry API ([#2244](https://github.com/dirkbrnd/openinference/issues/2244)) ([e07939d](https://github.com/dirkbrnd/openinference/commit/e07939d2ae530212e81004ef466d01e34f798b2d))
* include reasoning and audio token count for genai and adk instrumentors ([#1812](https://github.com/dirkbrnd/openinference/issues/1812)) ([921ff07](https://github.com/dirkbrnd/openinference/commit/921ff073e28ac2755b651dcdfac9ab3dbd673e70))
* pydantic model serialization for input value and image bytes for google-adk ([#2031](https://github.com/dirkbrnd/openinference/issues/2031)) ([46ef152](https://github.com/dirkbrnd/openinference/commit/46ef1522f73cf98f8c2b318b7afc7444160033b3))
* serialization of response schema in invocation parameters for google-adk ([#2033](https://github.com/dirkbrnd/openinference/issues/2033)) ([586689f](https://github.com/dirkbrnd/openinference/commit/586689f4ec6a37a6f3961740ebff4734f92ec3e5))
* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/dirkbrnd/openinference/issues/2294)) ([48b7a51](https://github.com/dirkbrnd/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
</details>

<details><summary>python-openinference-instrumentation-openlit: 0.1.3</summary>

## [0.1.3](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-openlit-v0.1.2...python-openinference-instrumentation-openlit-v0.1.3) (2025-11-18)


### Features

* Openlit span processor ([#2021](https://github.com/dirkbrnd/openinference/issues/2021)) ([99c4c99](https://github.com/dirkbrnd/openinference/commit/99c4c994b42486192bf07699ea6b75c3bd29efa1))
* Openlit span processor ([#2120](https://github.com/dirkbrnd/openinference/issues/2120)) ([5280702](https://github.com/dirkbrnd/openinference/commit/5280702ac7df30575eeb4bac416411f43c43ad8b))
* Openlit span processor ([#2127](https://github.com/dirkbrnd/openinference/issues/2127)) ([a039137](https://github.com/dirkbrnd/openinference/commit/a039137c99f4162963fab37359df04763310e001))
* **openlit:** implement span processor ([#2149](https://github.com/dirkbrnd/openinference/issues/2149)) ([51689ae](https://github.com/dirkbrnd/openinference/commit/51689aea3c41b513b22dcf3513389e91ec4c8f1e))
* **openlit:** openlit span processor ([#2151](https://github.com/dirkbrnd/openinference/issues/2151)) ([013102e](https://github.com/dirkbrnd/openinference/commit/013102e586ab0f8e441c6caec02c5b4c48bd5643))


### Bug Fixes

* fixing comments/file strings in openinference-instrumentation-openlit ([#2159](https://github.com/dirkbrnd/openinference/issues/2159)) ([7a0a9d1](https://github.com/dirkbrnd/openinference/commit/7a0a9d146aa2ce7f060e996c05b15b9dbbedb2fc))
</details>

<details><summary>python-openinference-instrumentation-openllmetry: 0.1.4</summary>

## [0.1.4](https://github.com/dirkbrnd/openinference/compare/python-openinference-instrumentation-openllmetry-v0.1.3...python-openinference-instrumentation-openllmetry-v0.1.4) (2025-11-18)


### Features

* openinference-instrumentation-openllmetry (openllmetry converter) ([#1789](https://github.com/dirkbrnd/openinference/issues/1789)) ([55fb98e](https://github.com/dirkbrnd/openinference/commit/55fb98e8f23dd1d485a760e04496e0629bce6de0))
* Openlit span processor ([#2021](https://github.com/dirkbrnd/openinference/issues/2021)) ([99c4c99](https://github.com/dirkbrnd/openinference/commit/99c4c994b42486192bf07699ea6b75c3bd29efa1))


### Bug Fixes

* Update build flies and CI env to include Python3.14  ([#2294](https://github.com/dirkbrnd/openinference/issues/2294)) ([48b7a51](https://github.com/dirkbrnd/openinference/commit/48b7a515cde2180f590a5a370a73d5ce1c73501d))
</details>

<details><summary>java-openinference-semantic-conventions: 0.1.10</summary>

## [0.1.10](https://github.com/dirkbrnd/openinference/compare/java-openinference-semantic-conventions-v0.1.9...java-openinference-semantic-conventions-v0.1.10) (2025-11-18)


### Features

* Java release only, please ([#1881](https://github.com/dirkbrnd/openinference/issues/1881)) ([0c75997](https://github.com/dirkbrnd/openinference/commit/0c759977688c05a813a5121255f9da063aa9b4b0))
* **java:** add tool calling instrumentation, prepare dependabot PR ([#1901](https://github.com/dirkbrnd/openinference/issues/1901)) ([33d3ded](https://github.com/dirkbrnd/openinference/commit/33d3ded20fbd3097b4ee567c77d540526c480555))
* **langchain4j:** Java Openinference client, langchain4j example ([#1817](https://github.com/dirkbrnd/openinference/issues/1817)) ([9ffb378](https://github.com/dirkbrnd/openinference/commit/9ffb378c70396cb991136ebbeb8368eee493725d))
* new experimental release ([#2050](https://github.com/dirkbrnd/openinference/issues/2050)) ([3afeed2](https://github.com/dirkbrnd/openinference/commit/3afeed2d72d52a0d96217c9c1c6e1f7d3e983c73))
* Spring AI instrumentation, Java 17 update ([#2036](https://github.com/dirkbrnd/openinference/issues/2036)) ([b260225](https://github.com/dirkbrnd/openinference/commit/b2602255b7954296a70fa02b2c98d67c514d9b9f))
* Upgrade workflow java 17 ([#2044](https://github.com/dirkbrnd/openinference/issues/2044)) ([2084e8e](https://github.com/dirkbrnd/openinference/commit/2084e8e48761fbb9e575bf4fbfc0f75ba3998d2e))
* use generic updater markers ([#1887](https://github.com/dirkbrnd/openinference/issues/1887)) ([ffda77a](https://github.com/dirkbrnd/openinference/commit/ffda77a10970d8616cbf57a5565aeb5fc9aede9a))


### Bug Fixes

* bump java, add release-please gradle property ([#1875](https://github.com/dirkbrnd/openinference/issues/1875)) ([8bd49ee](https://github.com/dirkbrnd/openinference/commit/8bd49ee132c59974c1742fac309c5a91601dc45a))
* exclude java from python release path, read version from gradle.& ([#1877](https://github.com/dirkbrnd/openinference/issues/1877)) ([f2a14bc](https://github.com/dirkbrnd/openinference/commit/f2a14bc212491a01417eb08975be6ee0f9f99355))
* snapshot publish ([#1883](https://github.com/dirkbrnd/openinference/issues/1883)) ([1c2532e](https://github.com/dirkbrnd/openinference/commit/1c2532ecc2abb82c8bbdd87091a565dafd705756))
* SpringAI linking with correct dependencies ([#2098](https://github.com/dirkbrnd/openinference/issues/2098)) ([8d944f8](https://github.com/dirkbrnd/openinference/commit/8d944f8ab3b4b54ec449a256465128a7083d8e9e))
* typo on release ([#1884](https://github.com/dirkbrnd/openinference/issues/1884)) ([5c2718e](https://github.com/dirkbrnd/openinference/commit/5c2718e4dabff57be14f897ad8da23b03d208eab))
</details>

<details><summary>java-openinference-instrumentation: 0.1.8</summary>

## [0.1.8](https://github.com/dirkbrnd/openinference/compare/java-openinference-instrumentation-v0.1.7...java-openinference-instrumentation-v0.1.8) (2025-11-18)


### Features

* add dependabot github action ([#1904](https://github.com/dirkbrnd/openinference/issues/1904)) ([1283dfc](https://github.com/dirkbrnd/openinference/commit/1283dfc3fcc9f728780f8c6a1ab865aa1f647a63))
* **langchain4j:** Java Openinference client, langchain4j example ([#1817](https://github.com/dirkbrnd/openinference/issues/1817)) ([9ffb378](https://github.com/dirkbrnd/openinference/commit/9ffb378c70396cb991136ebbeb8368eee493725d))
* new experimental release ([#2050](https://github.com/dirkbrnd/openinference/issues/2050)) ([3afeed2](https://github.com/dirkbrnd/openinference/commit/3afeed2d72d52a0d96217c9c1c6e1f7d3e983c73))
* Spring AI instrumentation, Java 17 update ([#2036](https://github.com/dirkbrnd/openinference/issues/2036)) ([b260225](https://github.com/dirkbrnd/openinference/commit/b2602255b7954296a70fa02b2c98d67c514d9b9f))
* Upgrade workflow java 17 ([#2044](https://github.com/dirkbrnd/openinference/issues/2044)) ([2084e8e](https://github.com/dirkbrnd/openinference/commit/2084e8e48761fbb9e575bf4fbfc0f75ba3998d2e))
* use generic updater markers ([#1887](https://github.com/dirkbrnd/openinference/issues/1887)) ([ffda77a](https://github.com/dirkbrnd/openinference/commit/ffda77a10970d8616cbf57a5565aeb5fc9aede9a))


### Bug Fixes

* bump java, add release-please gradle property ([#1875](https://github.com/dirkbrnd/openinference/issues/1875)) ([8bd49ee](https://github.com/dirkbrnd/openinference/commit/8bd49ee132c59974c1742fac309c5a91601dc45a))
* SpringAI linking with correct dependencies ([#2098](https://github.com/dirkbrnd/openinference/issues/2098)) ([8d944f8](https://github.com/dirkbrnd/openinference/commit/8d944f8ab3b4b54ec449a256465128a7083d8e9e))
</details>

<details><summary>java-openinference-instrumentation-langchain4j: 0.1.6</summary>

## [0.1.6](https://github.com/dirkbrnd/openinference/compare/java-openinference-instrumentation-langchain4j-v0.1.5...java-openinference-instrumentation-langchain4j-v0.1.6) (2025-11-18)


### Features

* **java:** add tool calling instrumentation, prepare dependabot PR ([#1901](https://github.com/dirkbrnd/openinference/issues/1901)) ([33d3ded](https://github.com/dirkbrnd/openinference/commit/33d3ded20fbd3097b4ee567c77d540526c480555))
* **langchain4j:** Java Openinference client, langchain4j example ([#1817](https://github.com/dirkbrnd/openinference/issues/1817)) ([9ffb378](https://github.com/dirkbrnd/openinference/commit/9ffb378c70396cb991136ebbeb8368eee493725d))
* new experimental release ([#2050](https://github.com/dirkbrnd/openinference/issues/2050)) ([3afeed2](https://github.com/dirkbrnd/openinference/commit/3afeed2d72d52a0d96217c9c1c6e1f7d3e983c73))
* Spring AI instrumentation, Java 17 update ([#2036](https://github.com/dirkbrnd/openinference/issues/2036)) ([b260225](https://github.com/dirkbrnd/openinference/commit/b2602255b7954296a70fa02b2c98d67c514d9b9f))
* Upgrade workflow java 17 ([#2044](https://github.com/dirkbrnd/openinference/issues/2044)) ([2084e8e](https://github.com/dirkbrnd/openinference/commit/2084e8e48761fbb9e575bf4fbfc0f75ba3998d2e))
* use generic updater markers ([#1887](https://github.com/dirkbrnd/openinference/issues/1887)) ([ffda77a](https://github.com/dirkbrnd/openinference/commit/ffda77a10970d8616cbf57a5565aeb5fc9aede9a))


### Bug Fixes

* bump java, add release-please gradle property ([#1875](https://github.com/dirkbrnd/openinference/issues/1875)) ([8bd49ee](https://github.com/dirkbrnd/openinference/commit/8bd49ee132c59974c1742fac309c5a91601dc45a))
</details>

<details><summary>java-openinference-instrumentation-springAI: 0.1.8</summary>

## [0.1.8](https://github.com/dirkbrnd/openinference/compare/java-openinference-instrumentation-springAI-v0.1.7...java-openinference-instrumentation-springAI-v0.1.8) (2025-11-18)


### Features

* new experimental release ([#2050](https://github.com/dirkbrnd/openinference/issues/2050)) ([3afeed2](https://github.com/dirkbrnd/openinference/commit/3afeed2d72d52a0d96217c9c1c6e1f7d3e983c73))
* Spring AI instrumentation, Java 17 update ([#2036](https://github.com/dirkbrnd/openinference/issues/2036)) ([b260225](https://github.com/dirkbrnd/openinference/commit/b2602255b7954296a70fa02b2c98d67c514d9b9f))
* Upgrade workflow java 17 ([#2044](https://github.com/dirkbrnd/openinference/issues/2044)) ([2084e8e](https://github.com/dirkbrnd/openinference/commit/2084e8e48761fbb9e575bf4fbfc0f75ba3998d2e))


### Bug Fixes

* jreleaser dependency release, all packages need their version ([#2075](https://github.com/dirkbrnd/openinference/issues/2075)) ([5a2de93](https://github.com/dirkbrnd/openinference/commit/5a2de939136b2d151a831e8911a62a0c3f7b7717))
* SpringAI linking with correct dependencies ([#2098](https://github.com/dirkbrnd/openinference/issues/2098)) ([8d944f8](https://github.com/dirkbrnd/openinference/commit/8d944f8ab3b4b54ec449a256465128a7083d8e9e))
* SpringAI multiple output messages ([#2106](https://github.com/dirkbrnd/openinference/issues/2106)) ([3c5fd97](https://github.com/dirkbrnd/openinference/commit/3c5fd97ed045a36dd95d4689a8b5315b95ee6366))
* trigger springAI release ([#2061](https://github.com/dirkbrnd/openinference/issues/2061)) ([e97f324](https://github.com/dirkbrnd/openinference/commit/e97f324ca8a12d788148edd9a031fabfe7055e55))
</details>

---
This PR was generated with [Release Please](https://github.com/googleapis/release-please). See [documentation](https://github.com/googleapis/release-please#release-please).
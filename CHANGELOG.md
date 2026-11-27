# Changelog

Release notes are generated from conventional commits by
[release-please](https://github.com/googleapis/release-please).

## [0.5.0](https://github.com/mati-cloud/wraithterm-patched/compare/v0.6.1...v0.5.0) (2026-11-27)


### Features

* **a11y:** screen reader announcements, row mirror and keyboard exit ([37c7595](https://github.com/mati-cloud/wraithterm-patched/commit/37c75958dbb7a93b59410a0cc6b5ce64a3e74f7d))
* add GPU post-process effects and custom WGSL shaders ([6040feb](https://github.com/mati-cloud/wraithterm-patched/commit/6040feb943c1f6f8ad825d122fae7b9735eb13c4)), closes [#43](https://github.com/mati-cloud/wraithterm-patched/issues/43)
* add React, Vue, Svelte and &lt;wraith-term&gt; bindings ([9b9c876](https://github.com/mati-cloud/wraithterm-patched/commit/9b9c876dff587037e91f5782a03a70dc9d6eb3bb)), closes [#42](https://github.com/mati-cloud/wraithterm-patched/issues/42)
* box drawing as geometry and theme palettes in the libghostty profile ([4df2eda](https://github.com/mati-cloud/wraithterm-patched/commit/4df2eda63042340bc23c7759bfc7b8be4910a935))
* bring validated terminal performance and demos into review ([320eee6](https://github.com/mati-cloud/wraithterm-patched/commit/320eee6f53712b285024e96d20ac3dff94cf0311))
* **cli:** run your shell in a tab with wraithterm serve ([40607f0](https://github.com/mati-cloud/wraithterm-patched/commit/40607f0ce3192bfdb97140eff01c601020e4b3c2))
* **cli:** your shell in a tab with wraithterm serve ([5a1ab5e](https://github.com/mati-cloud/wraithterm-patched/commit/5a1ab5ef183f321b2ea9266e1cc822bda839650d))
* command blocks API, gutter and shell integration for both profiles ([fe489e0](https://github.com/mati-cloud/wraithterm-patched/commit/fe489e0d034694b108b26eb66389cd0f3e9c131e)), closes [#48](https://github.com/mati-cloud/wraithterm-patched/issues/48)
* command blocks from OSC 133 shell integration ([bd31175](https://github.com/mati-cloud/wraithterm-patched/commit/bd311758b6abee5f4536740521975b63fd17358c))
* **core:** bridge libghostty into Rust terminal state ([9083e43](https://github.com/mati-cloud/wraithterm-patched/commit/9083e43af1bbb3431c653ff950e2f0a67bbbc1a1))
* **demo:** add a landing page with a live terminal hero and in-browser race ([817aef9](https://github.com/mati-cloud/wraithterm-patched/commit/817aef927b7970560e51f91147a9fad32443e7cf))
* **demo:** add a live dashboard workload to the benchmark harness ([9aed8f4](https://github.com/mati-cloud/wraithterm-patched/commit/9aed8f41613c183c65ae876166c124667cf98f5e))
* **demo:** add ember-themed Pipes stress lab and GPU comparison ([aa8a716](https://github.com/mati-cloud/wraithterm-patched/commit/aa8a7165ec4a2bce5d60f194038421ea3a1752dd))
* **demo:** add the effects lab with a custom shader gallery ([48d4bff](https://github.com/mati-cloud/wraithterm-patched/commit/48d4bff92670d38b005ef95deefd25b1b8b3fd6a)), closes [#43](https://github.com/mati-cloud/wraithterm-patched/issues/43)
* **demo:** build and verify the native terminal playground ([de032e7](https://github.com/mati-cloud/wraithterm-patched/commit/de032e7002deef61c8c3f51d99f329b46263eab0))
* **demo:** build the Ghost Reactor terminal showcase ([8e30e66](https://github.com/mati-cloud/wraithterm-patched/commit/8e30e6609d95881f0459ab1f75677a165e6ddafd))
* **demo:** effects selector on Fleet and effects in the benchmark ([0412106](https://github.com/mati-cloud/wraithterm-patched/commit/041210663fbfe2a97d7719fa5422d0b669bce60e)), closes [#68](https://github.com/mati-cloud/wraithterm-patched/issues/68)
* **demo:** exercise xterm addons and renderer fallbacks ([589b950](https://github.com/mati-cloud/wraithterm-patched/commit/589b9509bf87f27ffad4fda4edec3924eb0f0ade))
* **demo:** expose XP pipe count and growth controls ([e968715](https://github.com/mati-cloud/wraithterm-patched/commit/e968715f0c53574a69279bc9d715fafae2e421ff))
* **demo:** generate shaded 3D pipes as portable ANSI frames ([f748fe6](https://github.com/mati-cloud/wraithterm-patched/commit/f748fe602de72cccf1d4590c0489f1a5b3ac9f39))
* **demo:** grow continuous XP pipes through a rotating 3D scene ([c1f8c35](https://github.com/mati-cloud/wraithterm-patched/commit/c1f8c353ea450ce5da258b7a513b613681ee9ca8))
* **demo:** grow sealed pipes through seeded reset cycles ([35a772f](https://github.com/mati-cloud/wraithterm-patched/commit/35a772f747c18ef182064311c80be50a29ae13cf))
* **demo:** port the native app's custom shaders to the browser gallery ([d87360f](https://github.com/mati-cloud/wraithterm-patched/commit/d87360f74d14b3564bfb7ec6c208efdf5e02d5ba)), closes [#68](https://github.com/mati-cloud/wraithterm-patched/issues/68)
* **demo:** rebuild the native and xterm.js playgrounds ([1026cc7](https://github.com/mati-cloud/wraithterm-patched/commit/1026cc757c429358dc186c51256874863afa2c2a))
* draw pooled terminals into one shared WebGPU surface per worker ([e5fbb60](https://github.com/mati-cloud/wraithterm-patched/commit/e5fbb60c6b7547c66f676788a1a6e22eaddf2043)), closes [#45](https://github.com/mati-cloud/wraithterm-patched/issues/45)
* **engine:** track OSC 133 command blocks with Ghostty tracked refs ([a986aa5](https://github.com/mati-cloud/wraithterm-patched/commit/a986aa56e38c08bbb92fa099c81dc3cad255e658)), closes [#48](https://github.com/mati-cloud/wraithterm-patched/issues/48)
* expose the adapter a terminal draws with ([dcc76fa](https://github.com/mati-cloud/wraithterm-patched/commit/dcc76fac1c623eb77aaa22fc58041699105c24d2))
* expose VT state snapshots and grid digests from the headless engine ([c08ca79](https://github.com/mati-cloud/wraithterm-patched/commit/c08ca799f8e47ba218f4fefd294c89f74252bfc6)), closes [#47](https://github.com/mati-cloud/wraithterm-patched/issues/47)
* **fleet:** GPU effects over shared surfaces with pool.setEffects() ([f747765](https://github.com/mati-cloud/wraithterm-patched/commit/f7477658e6dfb25d2edd6d436e869131f6896d5d)), closes [#68](https://github.com/mati-cloud/wraithterm-patched/issues/68)
* GPU effects (CRT, bloom, cursor trail) and custom WGSL shaders ([a7cfb53](https://github.com/mati-cloud/wraithterm-patched/commit/a7cfb5311a36233725d20275e2cdf392d8939795))
* **gpu:** draw cells with an instanced WebGPU pipeline ([050cde6](https://github.com/mati-cloud/wraithterm-patched/commit/050cde6dc6530f94f20569bde8a07d5f09626f3d))
* let the engine worker own the terminal's WebSocket ([0873abe](https://github.com/mati-cloud/wraithterm-patched/commit/0873abe3014ffee0855c199f36097b1ab558a0fa))
* **native:** add history search, selection and keyboard hooks ([488a2f3](https://github.com/mati-cloud/wraithterm-patched/commit/488a2f33d404b728304fab17ab11f1c3e40a6a6c))
* **native:** add history search, selection gestures and keyboard hooks ([e3fe564](https://github.com/mati-cloud/wraithterm-patched/commit/e3fe564afcf6e9d561a9c89109e83a67e46dea6b))
* **native:** enable Kitty graphics in the terminal core ([bd6cb0a](https://github.com/mati-cloud/wraithterm-patched/commit/bd6cb0aec28f56fd7ca50e9729306727047c6e2f))
* **native:** expose optional render submission notifications ([44a975a](https://github.com/mati-cloud/wraithterm-patched/commit/44a975a8060a3b7daffe54c1c85525f0e3896973))
* **native:** Kitty graphics on WebGPU ([638b454](https://github.com/mati-cloud/wraithterm-patched/commit/638b45405bf277e2320354c49fa31b848f3e4413))
* **native:** ligatures and complex-script run shaping ([15936f3](https://github.com/mati-cloud/wraithterm-patched/commit/15936f3449766a1cf7fd7e87e37b9c3adccf66a4))
* **native:** render Kitty graphics on WebGPU ([705d683](https://github.com/mati-cloud/wraithterm-patched/commit/705d68325d22943766536a74b3f54227f16d4365))
* **native:** share workers and GPU devices across terminals ([64c1d7a](https://github.com/mati-cloud/wraithterm-patched/commit/64c1d7ab7c1b8fd863d170f9793766ebade63f61))
* **native:** support live fonts and display scale changes ([c364123](https://github.com/mati-cloud/wraithterm-patched/commit/c3641231295844eb3c28188fe47cd7af9e2014d6))
* **native:** support live fonts, zoom and display scale changes ([049c0ba](https://github.com/mati-cloud/wraithterm-patched/commit/049c0bad2279d64344579b7eadf4a9681d632394))
* **native:** terminal pool for many terminals in one tab ([7ceea66](https://github.com/mati-cloud/wraithterm-patched/commit/7ceea66158d9dc9dc4343817e52cbd41f4e7c125))
* pressKey for key panels, alternate-screen wheel arrows and selectWords ([6e305d4](https://github.com/mati-cloud/wraithterm-patched/commit/6e305d48b45e35c462bb6e9879b8b86dd1a24c8e))
* React, Vue, Svelte and &lt;wraith-term&gt; bindings ([2b3f45b](https://github.com/mati-cloud/wraithterm-patched/commit/2b3f45b9cffc3c127c232625c836743089b44874))
* record, replay and scrub terminal sessions ([a9bdbd9](https://github.com/mati-cloud/wraithterm-patched/commit/a9bdbd9f9e40d0c0698a2d1f488cd1528501a7f3)), closes [#47](https://github.com/mati-cloud/wraithterm-patched/issues/47)
* **sdk:** define typed terminal transport and input contracts ([87b5078](https://github.com/mati-cloud/wraithterm-patched/commit/87b50785192001660edc810f739fb439b4d7cf79))
* **sdk:** mount terminals and connect ordered PTY transports ([c792536](https://github.com/mati-cloud/wraithterm-patched/commit/c79253662ec6122560c478897ea0d7db1cdf6c9f))
* **site:** a pixel ghost that follows the pointer through the hero terminal ([6f0ca9e](https://github.com/mati-cloud/wraithterm-patched/commit/6f0ca9e4256f10f7fcc730623ad7cf55991f667a))
* **site:** a snappy ghost and a glyph trail behind the pointer ([5a0034f](https://github.com/mati-cloud/wraithterm-patched/commit/5a0034f48048ddfec1bbd18fef5fca2e1dea2e09))
* **site:** add a Kitty graphics lab ([afc6050](https://github.com/mati-cloud/wraithterm-patched/commit/afc6050da9989189a595e2c0de9a4c27444fd3f2))
* **site:** Manrope, a Labs section, a warm favicon and a terminal pipeline ([951e53d](https://github.com/mati-cloud/wraithterm-patched/commit/951e53d59a8a551d5a64a6aecf367b106bd92626))
* style faces for bold, italic and bold italic, and wider Kitty keyboard and graphics tests ([0e6f513](https://github.com/mati-cloud/wraithterm-patched/commit/0e6f513311d7279f0260b5d735e1a0514f467513))
* **text:** shape and rasterize cached terminal glyphs ([97e388d](https://github.com/mati-cloud/wraithterm-patched/commit/97e388dc47c5aa889cae6e70d8f52e6712988eaf))
* **video:** a font picker with a live preview of every screen ([d062366](https://github.com/mati-cloud/wraithterm-patched/commit/d062366e2d64c75e3932117f2bac0820083a89c7))
* **video:** a slower build, real glyph art for "How fast?", fewer screens ([4b6a9d5](https://github.com/mati-cloud/wraithterm-patched/commit/4b6a9d52dbf682f2a8bf8162862cc949d7fc957e))
* **video:** add machined studio shots and Lyria soundtrack edit ([bdb7815](https://github.com/mati-cloud/wraithterm-patched/commit/bdb78158bf765b700cb55007573dd353ddb960ae))
* **video:** assemble Phantom product film in fframes ([f12ec01](https://github.com/mati-cloud/wraithterm-patched/commit/f12ec01b5b35822f7c85c24518c487f7ecf12c29))
* **video:** bring the website ghost into the product film ([805ba36](https://github.com/mati-cloud/wraithterm-patched/commit/805ba36a8db1fc57378a069888d5055b95003dd8))
* **video:** lead into the drop with "The spooky fast web terminal…" ([a5e51b5](https://github.com/mati-cloud/wraithterm-patched/commit/a5e51b5d326744ce22f75065537c87f74627acc3))
* **video:** rebuild the launch video as "The Arrival" ([a27c167](https://github.com/mati-cloud/wraithterm-patched/commit/a27c1676e89ff53f3ff7df49622db2069a809851))
* **video:** render the launch video with fframes and a synthesized score ([df5c66f](https://github.com/mati-cloud/wraithterm-patched/commit/df5c66f9da8fc3905104269a016c1d5c9f26ac0a))
* **video:** sell Wraith through evidence and integration ([99d994e](https://github.com/mati-cloud/wraithterm-patched/commit/99d994e8f4c80c2f9f12552def9dcd4aa6b9477a))
* **video:** set the launch video in the chosen fonts ([a9990e2](https://github.com/mati-cloud/wraithterm-patched/commit/a9990e244dd536de2a33cbe70456429cf686e487))
* **video:** sync the score to product story cues ([3804022](https://github.com/mati-cloud/wraithterm-patched/commit/3804022ac4c4d5cb2db207f379c3637cd6e50ea3))
* **vite:** preserve worker and engine assets in consumers ([4697730](https://github.com/mati-cloud/wraithterm-patched/commit/469773011fdc2820c4fd4d89b5126ef5d803bf47))
* **wasm:** expose terminal and compositor browser bindings ([7539545](https://github.com/mati-cloud/wraithterm-patched/commit/753954539131dccf93cbc1fdca25657899ca60aa))
* **worker:** serialize commands and schedule damaged frames ([40dbed3](https://github.com/mati-cloud/wraithterm-patched/commit/40dbed3aabe93718dd06f23ee04f6434634132b7))
* **xterm:** cache browser glyphs by scalar and style ([cb12e3b](https://github.com/mati-cloud/wraithterm-patched/commit/cb12e3b0c9750fc67d28674fc578c345d6caff97))
* **xterm:** composite buffer cells through Rust WebGPU ([9c8f94f](https://github.com/mati-cloud/wraithterm-patched/commit/9c8f94fc4a8e939e6a033c85459737bae30f0794))
* **xterm:** export the drop-in Terminal implementation ([326f505](https://github.com/mati-cloud/wraithterm-patched/commit/326f505fbf1369be6059d4e6595006f73348babf))
* **xterm:** pin upstream API declarations and renderer boundaries ([ca1dde3](https://github.com/mati-cloud/wraithterm-patched/commit/ca1dde3fadb47cc89366a413b049340267e7228a))
* **xterm:** render transparency and minimum contrast on WebGPU ([3645588](https://github.com/mati-cloud/wraithterm-patched/commit/36455882af074890ae2513f8a332b57223232d27))


### Performance

* accelerate compatible bulk text across wrapped rows ([a12280b](https://github.com/mati-cloud/wraithterm-patched/commit/a12280b87196e07dad0bde7ad0a8987bef6df5da))
* batch serve's PTY output into larger WebSocket messages ([66f6f5b](https://github.com/mati-cloud/wraithterm-patched/commit/66f6f5b1558c17c699c87e5dd032ab33270e2419))
* contain each terminal's layout, paint and style ([0492fa0](https://github.com/mati-cloud/wraithterm-patched/commit/0492fa0aeaa8b75ec552d4a78a24786816af81d9)), closes [#67](https://github.com/mati-cloud/wraithterm-patched/issues/67)
* **demo:** encode reactor frames directly and remove live GPU stalls ([e9be65b](https://github.com/mati-cloud/wraithterm-patched/commit/e9be65b32601cd6387fba1531c4740b9073a0636))
* **engine:** one uniform write and one pipeline bind per shared frame ([4e089f1](https://github.com/mati-cloud/wraithterm-patched/commit/4e089f12f6d32c2421e737df3a47c1dd584db5ae)), closes [#67](https://github.com/mati-cloud/wraithterm-patched/issues/67)
* **engine:** reuse buffers when copying scrolled rows ([4e1ab98](https://github.com/mati-cloud/wraithterm-patched/commit/4e1ab9888fa5d08ca48f44ced50b446789fb3a16))
* **fleet:** re-measure shared-surface placements only when they can change ([54aed01](https://github.com/mati-cloud/wraithterm-patched/commit/54aed01bf5c21c5c31cd0246caa3210d469738bd)), closes [#67](https://github.com/mati-cloud/wraithterm-patched/issues/67)
* **ghostty:** decode cells from generated public ABI layouts ([445b7b2](https://github.com/mati-cloud/wraithterm-patched/commit/445b7b2da0a2acca31f976c132027e0f7a87f3ac))
* **ghostty:** inline SGR attribute parsing ([5d6043c](https://github.com/mati-cloud/wraithterm-patched/commit/5d6043ca03f17b0e2b07f9851c4c52e87846294d))
* **ghostty:** intern SGR styles once per command ([76bdae0](https://github.com/mati-cloud/wraithterm-patched/commit/76bdae005b70f7c102306350960b7fa6da47747f))
* **ghostty:** read ordinary cells from bulk row views ([d06e87a](https://github.com/mati-cloud/wraithterm-patched/commit/d06e87a134b37aef6c883efbaff8e7ec116b82ad))
* **input:** batch parameters and fixed-width terminal runs ([2a7d89c](https://github.com/mati-cloud/wraithterm-patched/commit/2a7d89c81197dc86ac86fb97fe4261da036313f0))
* **input:** streamline CSI entry and generated dispatch ([e7158f9](https://github.com/mati-cloud/wraithterm-patched/commit/e7158f911428bb1ce504b6176cbe4b861c7614f7))
* keep each terminal's hidden textarea out of compositor layers ([f8af694](https://github.com/mati-cloud/wraithterm-patched/commit/f8af694b31e90efb069f401ea3becc0ca4a3f008)), closes [#67](https://github.com/mati-cloud/wraithterm-patched/issues/67)
* measure keystroke-to-pixel latency; render idle echoes at once ([2c66654](https://github.com/mati-cloud/wraithterm-patched/commit/2c66654e721b56d4512a596df950de8b9964061d))
* **native:** cache search pages and yield without timer clamping ([cb3e7d5](https://github.com/mati-cloud/wraithterm-patched/commit/cb3e7d5a0451417f4982fef67b41a8a138128625))
* **native:** remove search timer delays and cache history pages ([2255e2e](https://github.com/mati-cloud/wraithterm-patched/commit/2255e2e95b5e07e5bdec75619f8559954ab534d7))
* **native:** reuse moved rows in the snapshot and the GPU packer ([0d38d43](https://github.com/mati-cloud/wraithterm-patched/commit/0d38d439096195ee8153e942554a940f90f033bd))
* **native:** snapshot cells with fewer libghostty queries ([bc85492](https://github.com/mati-cloud/wraithterm-patched/commit/bc8549275345ab9f51a3f37363df7ccc83215e62))
* **native:** suspend normal GPU draws outside visible panels ([2e747ea](https://github.com/mati-cloud/wraithterm-patched/commit/2e747ea6bf24a780cacf359b1ca52724856c0f1c))
* open serve's WebSocket in the engine worker, off the main thread ([3f6548d](https://github.com/mati-cloud/wraithterm-patched/commit/3f6548dbe0b314f7e1b0a9ccac72f53597534fb2))
* pack 20-byte GPU cells and draw glyphs only where ink exists ([e875242](https://github.com/mati-cloud/wraithterm-patched/commit/e8752429ea33384077399ce088cb86ff4d1f95a8))
* **pool:** batch pooled terminals' messages per worker ([9338774](https://github.com/mati-cloud/wraithterm-patched/commit/9338774007512d5789175a31adc8b34056fb5af8)), closes [#67](https://github.com/mati-cloud/wraithterm-patched/issues/67)
* **pool:** one write buffer per worker batch, stats only when observed ([96369eb](https://github.com/mati-cloud/wraithterm-patched/commit/96369eb1a5cb6ce85f023a344a8dee9355196248)), closes [#67](https://github.com/mati-cloud/wraithterm-patched/issues/67)
* read serve's PTY from a worker thread ([a7849e2](https://github.com/mati-cloud/wraithterm-patched/commit/a7849e2886139da6a32f7e8cca71dc2d2546ea49))
* read serve's PTY into a shared ring without stack traces ([1f48fa6](https://github.com/mati-cloud/wraithterm-patched/commit/1f48fa67dc24724d59c67a1344dacca1aa477fd6)), closes [#60](https://github.com/mati-cloud/wraithterm-patched/issues/60)
* render an idle terminal's next write at once ([7c308c3](https://github.com/mati-cloud/wraithterm-patched/commit/7c308c3d19f274fda4930e420e4f9462e78636dd)), closes [#59](https://github.com/mati-cloud/wraithterm-patched/issues/59)
* **renderer:** keep search decorations and link hover on WebGPU ([20ed5ff](https://github.com/mati-cloud/wraithterm-patched/commit/20ed5ff02fac3dc5263cc993df69d89359d0b151))
* **renderer:** retain GPU row slots across scrolling and sparse damage ([9324a9e](https://github.com/mati-cloud/wraithterm-patched/commit/9324a9efbb5de36624dc7358ed6612e8e9a21e3c))
* **sdk:** send each write burst to the worker as one batch ([0edcab9](https://github.com/mati-cloud/wraithterm-patched/commit/0edcab9b3726083bc0bef42ca591d7e7e3506b73))
* show the IME preedit span only while composing ([d7cd18d](https://github.com/mati-cloud/wraithterm-patched/commit/d7cd18db9de11b3632f10de1a3d74d1d6ac1badd)), closes [#67](https://github.com/mati-cloud/wraithterm-patched/issues/67)
* stop native GPU draws for hidden terminal panels ([a206cf3](https://github.com/mati-cloud/wraithterm-patched/commit/a206cf3a36449dc829796eb59880787fa9417d30))
* stop re-layerizing the page on every unfocused cursor move ([94b0ec7](https://github.com/mati-cloud/wraithterm-patched/commit/94b0ec70ad0fe683bdb4e3e220c6cda866114966)), closes [#45](https://github.com/mati-cloud/wraithterm-patched/issues/45)
* warm up the first engine in each worker during idle time ([73f9788](https://github.com/mati-cloud/wraithterm-patched/commit/73f9788e727252a102b268b3bb2fc8f53486138c))
* warm up the Wasm engine; measure SIMD and build flags ([c787121](https://github.com/mati-cloud/wraithterm-patched/commit/c787121fb4960382a507a5cdce8e0cf4f703c824))
* **wasm:** reuse compositor-owned cell and uniform staging ([53cd908](https://github.com/mati-cloud/wraithterm-patched/commit/53cd9082491181ea7182da7688de367630f902ee))
* **xterm:** accelerate common SGR actions without bypassing parser hooks ([0507849](https://github.com/mati-cloud/wraithterm-patched/commit/05078496ca98961d26573da2e57d99d52f0727cb))
* **xterm:** bulk print fixed-width text across wrapped rows ([7bbfee6](https://github.com/mati-cloud/wraithterm-patched/commit/7bbfee6d19f11fd6c65b0fa5df7c87b82d8d9c99))
* **xterm:** preserve the compact single-row print path ([efc9574](https://github.com/mati-cloud/wraithterm-patched/commit/efc95749aa4141b10b38fa081c41e180b969ff29))
* **xterm:** read ordinary cells directly from packed buffer rows ([3cfd61e](https://github.com/mati-cloud/wraithterm-patched/commit/3cfd61eeece70f1858083c4418198379e83e9e91))
* **xterm:** resolve optional visual attributes from packed row words ([ef77d0d](https://github.com/mati-cloud/wraithterm-patched/commit/ef77d0d32f05765077c5d9bc98007d2d3b1b6e2b))
* **xterm:** retain GPU rows for unchanged selection refreshes ([ded1ef1](https://github.com/mati-cloud/wraithterm-patched/commit/ded1ef1d70eb0334d3aabc2333c7f604e48faa1c))
* **xterm:** reuse unchanged and scrolled rows; upload only changed spans ([4e468d8](https://github.com/mati-cloud/wraithterm-patched/commit/4e468d8661310638e45e482571daec70878e75db))


### Bug fixes

* a glyph narrower than its cells is centred in them ([74dc930](https://github.com/mati-cloud/wraithterm-patched/commit/74dc930291db7a05de3dd4c9ce74530a70b3f9e8))
* a key that sends input, or a paste, brings a scrolled-back viewport to the prompt ([1886226](https://github.com/mati-cloud/wraithterm-patched/commit/1886226f3e1151e396f041baf79854cd591d01b3))
* a saved cursor below the cursor doesn't push text into history on shrinking ([c0b33c0](https://github.com/mati-cloud/wraithterm-patched/commit/c0b33c057a87b7c1b0b69271d3db32a461b98e5c))
* **a11y:** hold accessibility config until the worker has started ([c266ed4](https://github.com/mati-cloud/wraithterm-patched/commit/c266ed47e0e5503f85aa868c8b1d3517bc245002))
* **a11y:** show the focus ring only for the focus a Tab caused ([c252051](https://github.com/mati-cloud/wraithterm-patched/commit/c2520512212e8232d9c3152108fde7691d36c5ce))
* **bindings:** stop live grid changes on fitting terminals and late onReady ([e42377a](https://github.com/mati-cloud/wraithterm-patched/commit/e42377a1549cfcf9d711f0bc433bb8b482fec3d7))
* busybox `clear` (CSI H, CSI J) takes the screen's Kitty images too ([6b60f93](https://github.com/mati-cloud/wraithterm-patched/commit/6b60f93c50e868475cb9fcbb65006072fa79c68b))
* clearing the scrollback deletes the Kitty images placed in it ([e4e6139](https://github.com/mati-cloud/wraithterm-patched/commit/e4e61398b181d0c3520bde7c7a84dadf0b2b8734))
* correct bash integration cmdlines for unsaved and non-ASCII commands ([db6df0c](https://github.com/mati-cloud/wraithterm-patched/commit/db6df0c696b0f2e0e9c0d19d6aa78db6e1fbfa2f))
* **demo:** clamp the reactor startup clock ([ea398b1](https://github.com/mati-cloud/wraithterm-patched/commit/ea398b189c70d62a683772428248447ac102c833))
* **demo:** clear stale Pipes statistics when rebuilding ([2dacda1](https://github.com/mati-cloud/wraithterm-patched/commit/2dacda1f3c9b81b92ae36b5de1d163ba61c832c9))
* **demo:** keep the Fleet HUD on one stable line ([30ae285](https://github.com/mati-cloud/wraithterm-patched/commit/30ae285bcc08ef4ca3eb0c2471ae2341c5933455)), closes [#67](https://github.com/mati-cloud/wraithterm-patched/issues/67)
* drop the worker socket when the terminal fails ([75ca66b](https://github.com/mati-cloud/wraithterm-patched/commit/75ca66bd26ecc5b5446891610b1344cffa06a0fb))
* **effects:** survive dispose during setEffects and restore trail after reduced motion ([bda3871](https://github.com/mati-cloud/wraithterm-patched/commit/bda3871c1a2f37fc8cdc6477a70c969654a5fd6c))
* **engine:** report blocks erased by clear as truncated ([34489dc](https://github.com/mati-cloud/wraithterm-patched/commit/34489dc7889a4b4946f7f10e36de34fe2a51c916))
* fall back to the typed command in the native profile ([a30dca5](https://github.com/mati-cloud/wraithterm-patched/commit/a30dca55f2316eedfe98dcc517f459cba447489a))
* **fleet:** don't touch a surface while its effects are being configured ([193f6a2](https://github.com/mati-cloud/wraithterm-patched/commit/193f6a2e54de509e985452e043470ef2f8eb9ced)), closes [#68](https://github.com/mati-cloud/wraithterm-patched/issues/68)
* **fleet:** queue shared-surface effects with terminal creation ([42ff896](https://github.com/mati-cloud/wraithterm-patched/commit/42ff8969bd8441f285dd2a1446c1bb52feae8f27)), closes [#68](https://github.com/mati-cloud/wraithterm-patched/issues/68)
* grapheme clustering on by default, so emoji sequences and flags take one cell ([7ad4b02](https://github.com/mati-cloud/wraithterm-patched/commit/7ad4b02bc48db1971a7b5cf1816ad45bb927160b))
* hide styled-hidden and re-clip moved hosts on shared surfaces ([9908ea9](https://github.com/mati-cloud/wraithterm-patched/commit/9908ea9302538a342732558ca2b4d9b7047bcf44))
* ignore command-block replies while a terminal disposes ([00e893e](https://github.com/mati-cloud/wraithterm-patched/commit/00e893e450b05bc0d82eb8a24a555be22b566f99))
* keep double box-drawing joins open ([f48c217](https://github.com/mati-cloud/wraithterm-patched/commit/f48c217f9ebfb5d35a10844381b07821e4fa228d))
* keep internal player seeks from raising unhandled rejections ([50b2a72](https://github.com/mati-cloud/wraithterm-patched/commit/50b2a72ac8f3e8075735463d2b560725f0f2e971)), closes [#47](https://github.com/mati-cloud/wraithterm-patched/issues/47)
* keep the jump to the prompt out of screen reader announcements ([cd54c82](https://github.com/mati-cloud/wraithterm-patched/commit/cd54c82a7f9c3d96a0ef873925ef79b147941d92))
* keep unplaced and partly visible Kitty images when erasing ([f453f17](https://github.com/mati-cloud/wraithterm-patched/commit/f453f17fd66553fa4ca2b761991a8f48caeefdb0))
* keep Wraith.player from deadlocking under top-level await ([ee33a8b](https://github.com/mati-cloud/wraithterm-patched/commit/ee33a8be168b9c0ab803ad72725df74a90f43f2e))
* **native:** honor configured scrollback line retention ([d58d63b](https://github.com/mati-cloud/wraithterm-patched/commit/d58d63bd4ea132310727d046283bb5f895f1c6d2))
* **native:** honor configured scrollback line retention ([ebf484b](https://github.com/mati-cloud/wraithterm-patched/commit/ebf484b58984760d3c5a2461ca8c1504180fc8f3))
* read grid digests inside synchronized output without releasing it ([1567485](https://github.com/mati-cloud/wraithterm-patched/commit/1567485220fc8644ed08c7a905a89795643068b4)), closes [#47](https://github.com/mati-cloud/wraithterm-patched/issues/47)
* reapply the layered Ghostty patch on a tree already patched ([fb65486](https://github.com/mati-cloud/wraithterm-patched/commit/fb65486a453169d49eebc9847f2519d9f592b92d))
* record resizes in the order the worker applies them ([415563b](https://github.com/mati-cloud/wraithterm-patched/commit/415563b574f2c13a644dbe414e097e5e3e1bff62))
* **serve:** stop the PTY reader thread before node-pty closes the master ([92f242e](https://github.com/mati-cloud/wraithterm-patched/commit/92f242ee8c75bcd26351e50f70b08d15a8a496a8))
* **text:** synthesize bold by widening coverage, not offsetting outlines ([6750ac6](https://github.com/mati-cloud/wraithterm-patched/commit/6750ac6badd646fe4d797f64bd347e31a17392b2))
* U+FE0F prefers a colour font over the text font's glyph ([02d6283](https://github.com/mati-cloud/wraithterm-patched/commit/02d6283e8e8b94863fb0dfaf511166fef8ab2a34))
* **xterm:** draw block elements and braille as exact cell geometry ([0d5368f](https://github.com/mati-cloud/wraithterm-patched/commit/0d5368f5dc0d8ebb46f06f83fa87e4a0a564291a))


### Documentation

* **a11y:** describe what announcements: 'always' actually gates on ([accbcc0](https://github.com/mati-cloud/wraithterm-patched/commit/accbcc0217aab75040ff3bb8e50637af3a655c0d))
* **bench:** publish controlled browser terminal comparison ([0fd9c8e](https://github.com/mati-cloud/wraithterm-patched/commit/0fd9c8e23d12758f096144c0dc98cfa43dcc7925))
* **bench:** record 452 terminal workflow and resource runs ([3400232](https://github.com/mati-cloud/wraithterm-patched/commit/3400232f58bf6846d0e792801a2a940f642bcbe5))
* **bench:** retain counted-search gains and undecorated controls ([84c668a](https://github.com/mati-cloud/wraithterm-patched/commit/84c668af5c8dacbdbb62e403e4a9cb314b5ad472))
* **bench:** retain hidden-panel efficiency and visible CPU controls ([e65f309](https://github.com/mati-cloud/wraithterm-patched/commit/e65f309904c23b0d3ac58efd2f2b615f893f3ce7))
* **bench:** retain paired wrapped-text gains and fallback controls ([92f85e3](https://github.com/mati-cloud/wraithterm-patched/commit/92f85e35caf37a0cdbdf7aed52c4cd682dae01db))
* **bench:** retain repeated GPU visual-option comparisons ([84b3d67](https://github.com/mati-cloud/wraithterm-patched/commit/84b3d672fe55a443efb0fb17ba884472a60d16ed))
* define performance evidence and release priorities ([169eb24](https://github.com/mati-cloud/wraithterm-patched/commit/169eb24602095fde53e0fcec56d7afda4e8af8c7))
* describe native and drop-in package integration ([fbd9e82](https://github.com/mati-cloud/wraithterm-patched/commit/fbd9e82523c92a34388a2dbd458c543993bb9a4a))
* describe native Kitty graphics and record streaming throughput ([7289db3](https://github.com/mati-cloud/wraithterm-patched/commit/7289db3a14c4b396ff481b120a10aef9c52242a6))
* document accessibility and compare it with wterm ([564fb28](https://github.com/mati-cloud/wraithterm-patched/commit/564fb28b7a2027086ee114018eb1c62cb6a088b5))
* document command blocks and measure their overhead ([3de3011](https://github.com/mati-cloud/wraithterm-patched/commit/3de3011d1435ff25ff3cac5f920890ae064d98c6)), closes [#48](https://github.com/mati-cloud/wraithterm-patched/issues/48)
* document framework bindings and add a &lt;wraith-term&gt; demo ([5c3723e](https://github.com/mati-cloud/wraithterm-patched/commit/5c3723eeb9c9c8342ee88ee89a0472daedf2bccb)), closes [#42](https://github.com/mati-cloud/wraithterm-patched/issues/42)
* document recording, asciicast and the scrubbable player ([87514b5](https://github.com/mati-cloud/wraithterm-patched/commit/87514b589458ea0863817efacd3c1439d675a7d2)), closes [#47](https://github.com/mati-cloud/wraithterm-patched/issues/47)
* document the terminal pool and record many-terminal results ([b35b3a6](https://github.com/mati-cloud/wraithterm-patched/commit/b35b3a647e5e74da48e1424b9cb11c3e710de7c3))
* drop the banner that repeated the README logo ([297973e](https://github.com/mati-cloud/wraithterm-patched/commit/297973eb2bfdd7f426f5d0266858b8c56a40e0fd))
* explain architecture and terminal compatibility limits ([a365f9f](https://github.com/mati-cloud/wraithterm-patched/commit/a365f9f8dea4e65dde8c1821a0d98e847a7373be))
* **fleet:** measured 60+ updates per terminal at 1,000 terminals ([53c1b29](https://github.com/mati-cloud/wraithterm-patched/commit/53c1b295cf3f2806d002478fe65f36f593a823c4)), closes [#67](https://github.com/mati-cloud/wraithterm-patched/issues/67)
* **fleet:** measured shared-surface effects at 1,000 terminals ([ae82443](https://github.com/mati-cloud/wraithterm-patched/commit/ae8244343c1c6c3237bde46a5db6dbecf3faa030)), closes [#68](https://github.com/mati-cloud/wraithterm-patched/issues/68)
* fork for daimon — grid snapshot, transparency, OSC 52, drag/copy fixes ([e2afe3b](https://github.com/mati-cloud/wraithterm-patched/commit/e2afe3bbf72a789ce1d7c6cf65df7903a85839d1))
* give the README a logo, banner and a quick tour ([8ccd57d](https://github.com/mati-cloud/wraithterm-patched/commit/8ccd57dc7a585ed61e94180c46ba539bad9b4595))
* measure and document GPU effects ([de0790f](https://github.com/mati-cloud/wraithterm-patched/commit/de0790f6c32df91c36fb02cee974170eb8ebaa4f)), closes [#43](https://github.com/mati-cloud/wraithterm-patched/issues/43)
* **perf:** record nine-path study and paired confirmation ([e34117e](https://github.com/mati-cloud/wraithterm-patched/commit/e34117e8198ede1fe283f6de72b70f05fbe85d5b))
* **perf:** record Pipes workload validation and measured throughput ([f420711](https://github.com/mati-cloud/wraithterm-patched/commit/f420711b13a137285055c5d3c9130ba44d6d4415))
* **perf:** record retained row gains and the remaining dense parser bottleneck ([574b206](https://github.com/mati-cloud/wraithterm-patched/commit/574b206d6c91c4661c13263060cbe7083ac0662e))
* **perf:** record SGR parser gains and longer dense validation ([d9cc333](https://github.com/mati-cloud/wraithterm-patched/commit/d9cc333499a0db60224a3441290b946f510a121b))
* record replay seek latency on a 10-minute session ([0ef13cd](https://github.com/mati-cloud/wraithterm-patched/commit/0ef13cda54f846152b7e0553bfbb79e07863d90b)), closes [#47](https://github.com/mati-cloud/wraithterm-patched/issues/47)
* record the efficiency pass and correct stale layout claims ([c6a77bd](https://github.com/mati-cloud/wraithterm-patched/commit/c6a77bd823c865417b002ade39bbe70c52a2bc3c))
* record the resource-efficiency benchmark of Wraith and other web terminals ([21f4f57](https://github.com/mati-cloud/wraithterm-patched/commit/21f4f572d3be39970cf908fdeb7cdc97715607f1)), closes [#69](https://github.com/mati-cloud/wraithterm-patched/issues/69)
* rename engine warm-up report and state its measurement limits ([2de5b0f](https://github.com/mati-cloud/wraithterm-patched/commit/2de5b0fa2cfc3b57916ad5f26cd0a3a7c1c102cf))
* report the headed fleet benchmark and document shared surfaces ([53ecd08](https://github.com/mati-cloud/wraithterm-patched/commit/53ecd08f84980003686ad61bd9f798b5f1b3d6e7)), closes [#45](https://github.com/mati-cloud/wraithterm-patched/issues/45)
* state shared atlas capacity and opacity limits in both READMEs ([127d4a3](https://github.com/mati-cloud/wraithterm-patched/commit/127d4a3ee9130f137cecef404cc8454cb1290fce))
* state that recordings start empty ([1cf25a3](https://github.com/mati-cloud/wraithterm-patched/commit/1cf25a34d3c81b177cb4d9790d37a6297e6d1745))
* tagline the README "Spooky fast web terminal." ([275d8c7](https://github.com/mati-cloud/wraithterm-patched/commit/275d8c76be8719c66c1ff3189f631dc04d649125))


### Benchmarks

* **a11y:** measure screen reader mode overhead and record validation ([66fab23](https://github.com/mati-cloud/wraithterm-patched/commit/66fab23681d5e52ae5e1097de437287246a99b32))
* add a per-process resource-efficiency harness for web terminals ([6ef632f](https://github.com/mati-cloud/wraithterm-patched/commit/6ef632f596e417cbc7e1dc6b67f241421d3f8458)), closes [#69](https://github.com/mati-cloud/wraithterm-patched/issues/69)
* add engine-only throughput, first-content and worker profile harnesses ([c2dc4be](https://github.com/mati-cloud/wraithterm-patched/commit/c2dc4be69ab34cd1d3b573cc955b70bc41701901))
* add headed fleet benchmark for shared vs per-canvas pools ([df8b8db](https://github.com/mati-cloud/wraithterm-patched/commit/df8b8dbc3f62e424ea6a911ff07b16c56461b85f)), closes [#45](https://github.com/mati-cloud/wraithterm-patched/issues/45)
* alternate input actions on one device and probe API compatibility ([7492f5f](https://github.com/mati-cloud/wraithterm-patched/commit/7492f5f67a460ac5ed5e536fdaf7676741d1ef98))
* compare retained GPU rows with xterm in rotated paired runs ([e40f434](https://github.com/mati-cloud/wraithterm-patched/commit/e40f434fcc3358119a2650fece1e427f792a8ee0))
* compare terminal renderers on a complex Unicode scene ([032022a](https://github.com/mati-cloud/wraithterm-patched/commit/032022a496c1a4183a0b3a168fe08f777a0a912d))
* fingerprint SDK input code and bound comparison runs ([08c117f](https://github.com/mati-cloud/wraithterm-patched/commit/08c117f6c17daae74b89374a701071191a9f25d5))
* flag lost WebGL contexts and unretained scrollback in the report ([2674f17](https://github.com/mati-cloud/wraithterm-patched/commit/2674f17babab52b86bf7300f02ad2b68575e40d1)), closes [#69](https://github.com/mati-cloud/wraithterm-patched/issues/69)
* **fleet:** add a worker-fed mode, profiler and run metadata ([b7a6c79](https://github.com/mati-cloud/wraithterm-patched/commit/b7a6c7921296442782d8c75cfde727b4ea5040a7)), closes [#67](https://github.com/mati-cloud/wraithterm-patched/issues/67)
* **fleet:** measure older builds of the Fleet page too ([d0d7f5a](https://github.com/mati-cloud/wraithterm-patched/commit/d0d7f5a463cf6a93446606987d44e248fa713f59)), closes [#67](https://github.com/mati-cloud/wraithterm-patched/issues/67)
* **fleet:** record Long Animation Frames with script attribution ([2b794b7](https://github.com/mati-cloud/wraithterm-patched/commit/2b794b75a5c50e72929ded012482d57ed79fb9e9)), closes [#67](https://github.com/mati-cloud/wraithterm-patched/issues/67)
* generate the efficiency report and bound the load wait ([e8c26ca](https://github.com/mati-cloud/wraithterm-patched/commit/e8c26caf46e96207b269d0ffed830d73e6158777)), closes [#69](https://github.com/mati-cloud/wraithterm-patched/issues/69)
* make the native-Ghostty scripts portable across concurrent runs ([5dc8e63](https://github.com/mati-cloud/wraithterm-patched/commit/5dc8e63cc18a24997392edea8665fcd0819efd9c)), closes [#60](https://github.com/mati-cloud/wraithterm-patched/issues/60)
* measure Chrome CPU and device-wide GPU utilization ([68fec00](https://github.com/mati-cloud/wraithterm-patched/commit/68fec001fdd1d41be24e488e9dc6481d7637068d))
* measure keystroke-to-pixel latency through serve ([d255384](https://github.com/mati-cloud/wraithterm-patched/commit/d255384de8b81bfb21f5f39fcce90fe9197b73a0)), closes [#59](https://github.com/mati-cloud/wraithterm-patched/issues/59)
* preserve head-to-head renderer results and methodology ([5f5b129](https://github.com/mati-cloud/wraithterm-patched/commit/5f5b1290df7e15fb863a2e989ff9b02863a9dbae))
* profile renderer CPU hot paths ([642960c](https://github.com/mati-cloud/wraithterm-patched/commit/642960c7fcdd7f0f170677439aad0380381ada6b))
* profile the optimized pipeline and rank further improvements ([7b89d00](https://github.com/mati-cloud/wraithterm-patched/commit/7b89d00d57584b3ca553de560e1452a29e49c724))
* record alternating optimization and utilization results ([81573a4](https://github.com/mati-cloud/wraithterm-patched/commit/81573a4647441fad2882888fb0894f437569e425))
* record packing and staging comparisons with release evidence ([a136240](https://github.com/mati-cloud/wraithterm-patched/commit/a136240efaac7678f1b84d18e63d3a32cc2f27e9))
* record serve's ring reader against [#57](https://github.com/mati-cloud/wraithterm-patched/issues/57), with a browserless client ([a05efe2](https://github.com/mati-cloud/wraithterm-patched/commit/a05efe23f87cfd4d5d440879adc165f94eceb835)), closes [#60](https://github.com/mati-cloud/wraithterm-patched/issues/60)
* record the launch comparison against xterm.js ([1c2d80a](https://github.com/mati-cloud/wraithterm-patched/commit/1c2d80a44a11e72a290c01a272104e5c9eba170b))
* repeat efficiency runs that end on battery power ([ad4c3fd](https://github.com/mati-cloud/wraithterm-patched/commit/ad4c3fd8050ba23fce477221f4a5383888624782)), closes [#69](https://github.com/mati-cloud/wraithterm-patched/issues/69)
* repeat efficiency runs that overlap a Fleet benchmark ([74829d4](https://github.com/mati-cloud/wraithterm-patched/commit/74829d432d59aa524ec74c184c527b9b9f56a2e8)), closes [#69](https://github.com/mati-cloud/wraithterm-patched/issues/69)
* test parser, fused staging and Wasm packing alternatives ([dd701cb](https://github.com/mati-cloud/wraithterm-patched/commit/dd701cb2cbc37bcdf7ecd95007b5aaecae9fb86c))
* write the efficiency findings from the measured summary ([2ca8b75](https://github.com/mati-cloud/wraithterm-patched/commit/2ca8b75b0757741c06af2003701e229fb80eb7fc)), closes [#69](https://github.com/mati-cloud/wraithterm-patched/issues/69)


### Chores

* release 0.5.0 ([c17715a](https://github.com/mati-cloud/wraithterm-patched/commit/c17715a9e05ab2257bc0eeb08afcadd0535a4940))

## [0.6.1](https://github.com/betterclever/wraithterm/compare/v0.6.0...v0.6.1) (2026-11-06)


### Bug fixes

* a saved cursor below the cursor doesn't push text into history on shrinking ([c0b33c0](https://github.com/betterclever/wraithterm/commit/c0b33c057a87b7c1b0b69271d3db32a461b98e5c))
* reapply the layered Ghostty patch on a tree already patched ([fb65486](https://github.com/betterclever/wraithterm/commit/fb65486a453169d49eebc9847f2519d9f592b92d))
* U+FE0F prefers a colour font over the text font's glyph ([02d6283](https://github.com/betterclever/wraithterm/commit/02d6283e8e8b94863fb0dfaf511166fef8ab2a34))

## [0.6.0](https://github.com/betterclever/wraithterm/compare/v0.5.0...v0.6.0) (2026-11-04)


### Features

* **a11y:** screen reader announcements, row mirror and keyboard exit ([37c7595](https://github.com/betterclever/wraithterm/commit/37c75958dbb7a93b59410a0cc6b5ce64a3e74f7d))
* add GPU post-process effects and custom WGSL shaders ([6040feb](https://github.com/betterclever/wraithterm/commit/6040feb943c1f6f8ad825d122fae7b9735eb13c4)), closes [#43](https://github.com/betterclever/wraithterm/issues/43)
* add React, Vue, Svelte and &lt;wraith-term&gt; bindings ([9b9c876](https://github.com/betterclever/wraithterm/commit/9b9c876dff587037e91f5782a03a70dc9d6eb3bb)), closes [#42](https://github.com/betterclever/wraithterm/issues/42)
* box drawing as geometry and theme palettes in the libghostty profile ([4df2eda](https://github.com/betterclever/wraithterm/commit/4df2eda63042340bc23c7759bfc7b8be4910a935))
* command blocks API, gutter and shell integration for both profiles ([fe489e0](https://github.com/betterclever/wraithterm/commit/fe489e0d034694b108b26eb66389cd0f3e9c131e)), closes [#48](https://github.com/betterclever/wraithterm/issues/48)
* command blocks from OSC 133 shell integration ([bd31175](https://github.com/betterclever/wraithterm/commit/bd311758b6abee5f4536740521975b63fd17358c))
* **demo:** add the effects lab with a custom shader gallery ([48d4bff](https://github.com/betterclever/wraithterm/commit/48d4bff92670d38b005ef95deefd25b1b8b3fd6a)), closes [#43](https://github.com/betterclever/wraithterm/issues/43)
* **demo:** effects selector on Fleet and effects in the benchmark ([0412106](https://github.com/betterclever/wraithterm/commit/041210663fbfe2a97d7719fa5422d0b669bce60e)), closes [#68](https://github.com/betterclever/wraithterm/issues/68)
* **demo:** port the native app's custom shaders to the browser gallery ([d87360f](https://github.com/betterclever/wraithterm/commit/d87360f74d14b3564bfb7ec6c208efdf5e02d5ba)), closes [#68](https://github.com/betterclever/wraithterm/issues/68)
* draw pooled terminals into one shared WebGPU surface per worker ([e5fbb60](https://github.com/betterclever/wraithterm/commit/e5fbb60c6b7547c66f676788a1a6e22eaddf2043)), closes [#45](https://github.com/betterclever/wraithterm/issues/45)
* **engine:** track OSC 133 command blocks with Ghostty tracked refs ([a986aa5](https://github.com/betterclever/wraithterm/commit/a986aa56e38c08bbb92fa099c81dc3cad255e658)), closes [#48](https://github.com/betterclever/wraithterm/issues/48)
* expose the adapter a terminal draws with ([dcc76fa](https://github.com/betterclever/wraithterm/commit/dcc76fac1c623eb77aaa22fc58041699105c24d2))
* expose VT state snapshots and grid digests from the headless engine ([c08ca79](https://github.com/betterclever/wraithterm/commit/c08ca799f8e47ba218f4fefd294c89f74252bfc6)), closes [#47](https://github.com/betterclever/wraithterm/issues/47)
* **fleet:** GPU effects over shared surfaces with pool.setEffects() ([f747765](https://github.com/betterclever/wraithterm/commit/f7477658e6dfb25d2edd6d436e869131f6896d5d)), closes [#68](https://github.com/betterclever/wraithterm/issues/68)
* GPU effects (CRT, bloom, cursor trail) and custom WGSL shaders ([a7cfb53](https://github.com/betterclever/wraithterm/commit/a7cfb5311a36233725d20275e2cdf392d8939795))
* let the engine worker own the terminal's WebSocket ([0873abe](https://github.com/betterclever/wraithterm/commit/0873abe3014ffee0855c199f36097b1ab558a0fa))
* pressKey for key panels, alternate-screen wheel arrows and selectWords ([6e305d4](https://github.com/betterclever/wraithterm/commit/6e305d48b45e35c462bb6e9879b8b86dd1a24c8e))
* React, Vue, Svelte and &lt;wraith-term&gt; bindings ([2b3f45b](https://github.com/betterclever/wraithterm/commit/2b3f45b9cffc3c127c232625c836743089b44874))
* record, replay and scrub terminal sessions ([a9bdbd9](https://github.com/betterclever/wraithterm/commit/a9bdbd9f9e40d0c0698a2d1f488cd1528501a7f3)), closes [#47](https://github.com/betterclever/wraithterm/issues/47)
* style faces for bold, italic and bold italic, and wider Kitty keyboard and graphics tests ([0e6f513](https://github.com/betterclever/wraithterm/commit/0e6f513311d7279f0260b5d735e1a0514f467513))


### Performance

* batch serve's PTY output into larger WebSocket messages ([66f6f5b](https://github.com/betterclever/wraithterm/commit/66f6f5b1558c17c699c87e5dd032ab33270e2419))
* contain each terminal's layout, paint and style ([0492fa0](https://github.com/betterclever/wraithterm/commit/0492fa0aeaa8b75ec552d4a78a24786816af81d9)), closes [#67](https://github.com/betterclever/wraithterm/issues/67)
* **engine:** one uniform write and one pipeline bind per shared frame ([4e089f1](https://github.com/betterclever/wraithterm/commit/4e089f12f6d32c2421e737df3a47c1dd584db5ae)), closes [#67](https://github.com/betterclever/wraithterm/issues/67)
* **engine:** reuse buffers when copying scrolled rows ([4e1ab98](https://github.com/betterclever/wraithterm/commit/4e1ab9888fa5d08ca48f44ced50b446789fb3a16))
* **fleet:** re-measure shared-surface placements only when they can change ([54aed01](https://github.com/betterclever/wraithterm/commit/54aed01bf5c21c5c31cd0246caa3210d469738bd)), closes [#67](https://github.com/betterclever/wraithterm/issues/67)
* keep each terminal's hidden textarea out of compositor layers ([f8af694](https://github.com/betterclever/wraithterm/commit/f8af694b31e90efb069f401ea3becc0ca4a3f008)), closes [#67](https://github.com/betterclever/wraithterm/issues/67)
* measure keystroke-to-pixel latency; render idle echoes at once ([2c66654](https://github.com/betterclever/wraithterm/commit/2c66654e721b56d4512a596df950de8b9964061d))
* open serve's WebSocket in the engine worker, off the main thread ([3f6548d](https://github.com/betterclever/wraithterm/commit/3f6548dbe0b314f7e1b0a9ccac72f53597534fb2))
* **pool:** batch pooled terminals' messages per worker ([9338774](https://github.com/betterclever/wraithterm/commit/9338774007512d5789175a31adc8b34056fb5af8)), closes [#67](https://github.com/betterclever/wraithterm/issues/67)
* **pool:** one write buffer per worker batch, stats only when observed ([96369eb](https://github.com/betterclever/wraithterm/commit/96369eb1a5cb6ce85f023a344a8dee9355196248)), closes [#67](https://github.com/betterclever/wraithterm/issues/67)
* read serve's PTY from a worker thread ([a7849e2](https://github.com/betterclever/wraithterm/commit/a7849e2886139da6a32f7e8cca71dc2d2546ea49))
* read serve's PTY into a shared ring without stack traces ([1f48fa6](https://github.com/betterclever/wraithterm/commit/1f48fa67dc24724d59c67a1344dacca1aa477fd6)), closes [#60](https://github.com/betterclever/wraithterm/issues/60)
* render an idle terminal's next write at once ([7c308c3](https://github.com/betterclever/wraithterm/commit/7c308c3d19f274fda4930e420e4f9462e78636dd)), closes [#59](https://github.com/betterclever/wraithterm/issues/59)
* show the IME preedit span only while composing ([d7cd18d](https://github.com/betterclever/wraithterm/commit/d7cd18db9de11b3632f10de1a3d74d1d6ac1badd)), closes [#67](https://github.com/betterclever/wraithterm/issues/67)
* stop re-layerizing the page on every unfocused cursor move ([94b0ec7](https://github.com/betterclever/wraithterm/commit/94b0ec70ad0fe683bdb4e3e220c6cda866114966)), closes [#45](https://github.com/betterclever/wraithterm/issues/45)
* warm up the first engine in each worker during idle time ([73f9788](https://github.com/betterclever/wraithterm/commit/73f9788e727252a102b268b3bb2fc8f53486138c))
* warm up the Wasm engine; measure SIMD and build flags ([c787121](https://github.com/betterclever/wraithterm/commit/c787121fb4960382a507a5cdce8e0cf4f703c824))


### Bug fixes

* a glyph narrower than its cells is centred in them ([74dc930](https://github.com/betterclever/wraithterm/commit/74dc930291db7a05de3dd4c9ce74530a70b3f9e8))
* a key that sends input, or a paste, brings a scrolled-back viewport to the prompt ([1886226](https://github.com/betterclever/wraithterm/commit/1886226f3e1151e396f041baf79854cd591d01b3))
* **a11y:** hold accessibility config until the worker has started ([c266ed4](https://github.com/betterclever/wraithterm/commit/c266ed47e0e5503f85aa868c8b1d3517bc245002))
* **a11y:** show the focus ring only for the focus a Tab caused ([c252051](https://github.com/betterclever/wraithterm/commit/c2520512212e8232d9c3152108fde7691d36c5ce))
* **bindings:** stop live grid changes on fitting terminals and late onReady ([e42377a](https://github.com/betterclever/wraithterm/commit/e42377a1549cfcf9d711f0bc433bb8b482fec3d7))
* busybox `clear` (CSI H, CSI J) takes the screen's Kitty images too ([6b60f93](https://github.com/betterclever/wraithterm/commit/6b60f93c50e868475cb9fcbb65006072fa79c68b))
* clearing the scrollback deletes the Kitty images placed in it ([e4e6139](https://github.com/betterclever/wraithterm/commit/e4e61398b181d0c3520bde7c7a84dadf0b2b8734))
* correct bash integration cmdlines for unsaved and non-ASCII commands ([db6df0c](https://github.com/betterclever/wraithterm/commit/db6df0c696b0f2e0e9c0d19d6aa78db6e1fbfa2f))
* **demo:** keep the Fleet HUD on one stable line ([30ae285](https://github.com/betterclever/wraithterm/commit/30ae285bcc08ef4ca3eb0c2471ae2341c5933455)), closes [#67](https://github.com/betterclever/wraithterm/issues/67)
* drop the worker socket when the terminal fails ([75ca66b](https://github.com/betterclever/wraithterm/commit/75ca66bd26ecc5b5446891610b1344cffa06a0fb))
* **effects:** survive dispose during setEffects and restore trail after reduced motion ([bda3871](https://github.com/betterclever/wraithterm/commit/bda3871c1a2f37fc8cdc6477a70c969654a5fd6c))
* **engine:** report blocks erased by clear as truncated ([34489dc](https://github.com/betterclever/wraithterm/commit/34489dc7889a4b4946f7f10e36de34fe2a51c916))
* fall back to the typed command in the native profile ([a30dca5](https://github.com/betterclever/wraithterm/commit/a30dca55f2316eedfe98dcc517f459cba447489a))
* **fleet:** don't touch a surface while its effects are being configured ([193f6a2](https://github.com/betterclever/wraithterm/commit/193f6a2e54de509e985452e043470ef2f8eb9ced)), closes [#68](https://github.com/betterclever/wraithterm/issues/68)
* **fleet:** queue shared-surface effects with terminal creation ([42ff896](https://github.com/betterclever/wraithterm/commit/42ff8969bd8441f285dd2a1446c1bb52feae8f27)), closes [#68](https://github.com/betterclever/wraithterm/issues/68)
* grapheme clustering on by default, so emoji sequences and flags take one cell ([7ad4b02](https://github.com/betterclever/wraithterm/commit/7ad4b02bc48db1971a7b5cf1816ad45bb927160b))
* hide styled-hidden and re-clip moved hosts on shared surfaces ([9908ea9](https://github.com/betterclever/wraithterm/commit/9908ea9302538a342732558ca2b4d9b7047bcf44))
* ignore command-block replies while a terminal disposes ([00e893e](https://github.com/betterclever/wraithterm/commit/00e893e450b05bc0d82eb8a24a555be22b566f99))
* keep double box-drawing joins open ([f48c217](https://github.com/betterclever/wraithterm/commit/f48c217f9ebfb5d35a10844381b07821e4fa228d))
* keep internal player seeks from raising unhandled rejections ([50b2a72](https://github.com/betterclever/wraithterm/commit/50b2a72ac8f3e8075735463d2b560725f0f2e971)), closes [#47](https://github.com/betterclever/wraithterm/issues/47)
* keep the jump to the prompt out of screen reader announcements ([cd54c82](https://github.com/betterclever/wraithterm/commit/cd54c82a7f9c3d96a0ef873925ef79b147941d92))
* keep unplaced and partly visible Kitty images when erasing ([f453f17](https://github.com/betterclever/wraithterm/commit/f453f17fd66553fa4ca2b761991a8f48caeefdb0))
* keep Wraith.player from deadlocking under top-level await ([ee33a8b](https://github.com/betterclever/wraithterm/commit/ee33a8be168b9c0ab803ad72725df74a90f43f2e))
* read grid digests inside synchronized output without releasing it ([1567485](https://github.com/betterclever/wraithterm/commit/1567485220fc8644ed08c7a905a89795643068b4)), closes [#47](https://github.com/betterclever/wraithterm/issues/47)
* record resizes in the order the worker applies them ([415563b](https://github.com/betterclever/wraithterm/commit/415563b574f2c13a644dbe414e097e5e3e1bff62))
* **serve:** stop the PTY reader thread before node-pty closes the master ([92f242e](https://github.com/betterclever/wraithterm/commit/92f242ee8c75bcd26351e50f70b08d15a8a496a8))


### Documentation

* **a11y:** describe what announcements: 'always' actually gates on ([accbcc0](https://github.com/betterclever/wraithterm/commit/accbcc0217aab75040ff3bb8e50637af3a655c0d))
* document accessibility and compare it with wterm ([564fb28](https://github.com/betterclever/wraithterm/commit/564fb28b7a2027086ee114018eb1c62cb6a088b5))
* document command blocks and measure their overhead ([3de3011](https://github.com/betterclever/wraithterm/commit/3de3011d1435ff25ff3cac5f920890ae064d98c6)), closes [#48](https://github.com/betterclever/wraithterm/issues/48)
* document framework bindings and add a &lt;wraith-term&gt; demo ([5c3723e](https://github.com/betterclever/wraithterm/commit/5c3723eeb9c9c8342ee88ee89a0472daedf2bccb)), closes [#42](https://github.com/betterclever/wraithterm/issues/42)
* document recording, asciicast and the scrubbable player ([87514b5](https://github.com/betterclever/wraithterm/commit/87514b589458ea0863817efacd3c1439d675a7d2)), closes [#47](https://github.com/betterclever/wraithterm/issues/47)
* **fleet:** measured 60+ updates per terminal at 1,000 terminals ([53c1b29](https://github.com/betterclever/wraithterm/commit/53c1b295cf3f2806d002478fe65f36f593a823c4)), closes [#67](https://github.com/betterclever/wraithterm/issues/67)
* **fleet:** measured shared-surface effects at 1,000 terminals ([ae82443](https://github.com/betterclever/wraithterm/commit/ae8244343c1c6c3237bde46a5db6dbecf3faa030)), closes [#68](https://github.com/betterclever/wraithterm/issues/68)
* measure and document GPU effects ([de0790f](https://github.com/betterclever/wraithterm/commit/de0790f6c32df91c36fb02cee974170eb8ebaa4f)), closes [#43](https://github.com/betterclever/wraithterm/issues/43)
* record replay seek latency on a 10-minute session ([0ef13cd](https://github.com/betterclever/wraithterm/commit/0ef13cda54f846152b7e0553bfbb79e07863d90b)), closes [#47](https://github.com/betterclever/wraithterm/issues/47)
* record the resource-efficiency benchmark of Wraith and other web terminals ([21f4f57](https://github.com/betterclever/wraithterm/commit/21f4f572d3be39970cf908fdeb7cdc97715607f1)), closes [#69](https://github.com/betterclever/wraithterm/issues/69)
* rename engine warm-up report and state its measurement limits ([2de5b0f](https://github.com/betterclever/wraithterm/commit/2de5b0fa2cfc3b57916ad5f26cd0a3a7c1c102cf))
* report the headed fleet benchmark and document shared surfaces ([53ecd08](https://github.com/betterclever/wraithterm/commit/53ecd08f84980003686ad61bd9f798b5f1b3d6e7)), closes [#45](https://github.com/betterclever/wraithterm/issues/45)
* state shared atlas capacity and opacity limits in both READMEs ([127d4a3](https://github.com/betterclever/wraithterm/commit/127d4a3ee9130f137cecef404cc8454cb1290fce))
* state that recordings start empty ([1cf25a3](https://github.com/betterclever/wraithterm/commit/1cf25a34d3c81b177cb4d9790d37a6297e6d1745))


### Benchmarks

* **a11y:** measure screen reader mode overhead and record validation ([66fab23](https://github.com/betterclever/wraithterm/commit/66fab23681d5e52ae5e1097de437287246a99b32))
* add a per-process resource-efficiency harness for web terminals ([6ef632f](https://github.com/betterclever/wraithterm/commit/6ef632f596e417cbc7e1dc6b67f241421d3f8458)), closes [#69](https://github.com/betterclever/wraithterm/issues/69)
* add engine-only throughput, first-content and worker profile harnesses ([c2dc4be](https://github.com/betterclever/wraithterm/commit/c2dc4be69ab34cd1d3b573cc955b70bc41701901))
* add headed fleet benchmark for shared vs per-canvas pools ([df8b8db](https://github.com/betterclever/wraithterm/commit/df8b8dbc3f62e424ea6a911ff07b16c56461b85f)), closes [#45](https://github.com/betterclever/wraithterm/issues/45)
* flag lost WebGL contexts and unretained scrollback in the report ([2674f17](https://github.com/betterclever/wraithterm/commit/2674f17babab52b86bf7300f02ad2b68575e40d1)), closes [#69](https://github.com/betterclever/wraithterm/issues/69)
* **fleet:** add a worker-fed mode, profiler and run metadata ([b7a6c79](https://github.com/betterclever/wraithterm/commit/b7a6c7921296442782d8c75cfde727b4ea5040a7)), closes [#67](https://github.com/betterclever/wraithterm/issues/67)
* **fleet:** measure older builds of the Fleet page too ([d0d7f5a](https://github.com/betterclever/wraithterm/commit/d0d7f5a463cf6a93446606987d44e248fa713f59)), closes [#67](https://github.com/betterclever/wraithterm/issues/67)
* **fleet:** record Long Animation Frames with script attribution ([2b794b7](https://github.com/betterclever/wraithterm/commit/2b794b75a5c50e72929ded012482d57ed79fb9e9)), closes [#67](https://github.com/betterclever/wraithterm/issues/67)
* generate the efficiency report and bound the load wait ([e8c26ca](https://github.com/betterclever/wraithterm/commit/e8c26caf46e96207b269d0ffed830d73e6158777)), closes [#69](https://github.com/betterclever/wraithterm/issues/69)
* make the native-Ghostty scripts portable across concurrent runs ([5dc8e63](https://github.com/betterclever/wraithterm/commit/5dc8e63cc18a24997392edea8665fcd0819efd9c)), closes [#60](https://github.com/betterclever/wraithterm/issues/60)
* measure keystroke-to-pixel latency through serve ([d255384](https://github.com/betterclever/wraithterm/commit/d255384de8b81bfb21f5f39fcce90fe9197b73a0)), closes [#59](https://github.com/betterclever/wraithterm/issues/59)
* record serve's ring reader against [#57](https://github.com/betterclever/wraithterm/issues/57), with a browserless client ([a05efe2](https://github.com/betterclever/wraithterm/commit/a05efe23f87cfd4d5d440879adc165f94eceb835)), closes [#60](https://github.com/betterclever/wraithterm/issues/60)
* repeat efficiency runs that end on battery power ([ad4c3fd](https://github.com/betterclever/wraithterm/commit/ad4c3fd8050ba23fce477221f4a5383888624782)), closes [#69](https://github.com/betterclever/wraithterm/issues/69)
* repeat efficiency runs that overlap a Fleet benchmark ([74829d4](https://github.com/betterclever/wraithterm/commit/74829d432d59aa524ec74c184c527b9b9f56a2e8)), closes [#69](https://github.com/betterclever/wraithterm/issues/69)
* write the efficiency findings from the measured summary ([2ca8b75](https://github.com/betterclever/wraithterm/commit/2ca8b75b0757741c06af2003701e229fb80eb7fc)), closes [#69](https://github.com/betterclever/wraithterm/issues/69)

## [0.5.0](https://github.com/betterclever/wraithterm/compare/v0.3.0...v0.5.0) (2026-10-24)


### Features

* bring validated terminal performance and demos into review ([320eee6](https://github.com/betterclever/wraithterm/commit/320eee6f53712b285024e96d20ac3dff94cf0311))
* **cli:** run your shell in a tab with wraithterm serve ([40607f0](https://github.com/betterclever/wraithterm/commit/40607f0ce3192bfdb97140eff01c601020e4b3c2))
* **cli:** your shell in a tab with wraithterm serve ([5a1ab5e](https://github.com/betterclever/wraithterm/commit/5a1ab5ef183f321b2ea9266e1cc822bda839650d))
* **demo:** grow continuous XP pipes through a rotating 3D scene ([c1f8c35](https://github.com/betterclever/wraithterm/commit/c1f8c353ea450ce5da258b7a513b613681ee9ca8))
* **native:** add history search, selection and keyboard hooks ([488a2f3](https://github.com/betterclever/wraithterm/commit/488a2f33d404b728304fab17ab11f1c3e40a6a6c))
* **native:** add history search, selection gestures and keyboard hooks ([e3fe564](https://github.com/betterclever/wraithterm/commit/e3fe564afcf6e9d561a9c89109e83a67e46dea6b))
* **native:** enable Kitty graphics in the terminal core ([bd6cb0a](https://github.com/betterclever/wraithterm/commit/bd6cb0aec28f56fd7ca50e9729306727047c6e2f))
* **native:** expose optional render submission notifications ([44a975a](https://github.com/betterclever/wraithterm/commit/44a975a8060a3b7daffe54c1c85525f0e3896973))
* **native:** Kitty graphics on WebGPU ([638b454](https://github.com/betterclever/wraithterm/commit/638b45405bf277e2320354c49fa31b848f3e4413))
* **native:** ligatures and complex-script run shaping ([15936f3](https://github.com/betterclever/wraithterm/commit/15936f3449766a1cf7fd7e87e37b9c3adccf66a4))
* **native:** render Kitty graphics on WebGPU ([705d683](https://github.com/betterclever/wraithterm/commit/705d68325d22943766536a74b3f54227f16d4365))
* **native:** share workers and GPU devices across terminals ([64c1d7a](https://github.com/betterclever/wraithterm/commit/64c1d7ab7c1b8fd863d170f9793766ebade63f61))
* **native:** support live fonts and display scale changes ([c364123](https://github.com/betterclever/wraithterm/commit/c3641231295844eb3c28188fe47cd7af9e2014d6))
* **native:** support live fonts, zoom and display scale changes ([049c0ba](https://github.com/betterclever/wraithterm/commit/049c0bad2279d64344579b7eadf4a9681d632394))
* **native:** terminal pool for many terminals in one tab ([7ceea66](https://github.com/betterclever/wraithterm/commit/7ceea66158d9dc9dc4343817e52cbd41f4e7c125))
* **site:** add a Kitty graphics lab ([afc6050](https://github.com/betterclever/wraithterm/commit/afc6050da9989189a595e2c0de9a4c27444fd3f2))
* **xterm:** render transparency and minimum contrast on WebGPU ([3645588](https://github.com/betterclever/wraithterm/commit/36455882af074890ae2513f8a332b57223232d27))


### Performance

* accelerate compatible bulk text across wrapped rows ([a12280b](https://github.com/betterclever/wraithterm/commit/a12280b87196e07dad0bde7ad0a8987bef6df5da))
* **ghostty:** decode cells from generated public ABI layouts ([445b7b2](https://github.com/betterclever/wraithterm/commit/445b7b2da0a2acca31f976c132027e0f7a87f3ac))
* **ghostty:** inline SGR attribute parsing ([5d6043c](https://github.com/betterclever/wraithterm/commit/5d6043ca03f17b0e2b07f9851c4c52e87846294d))
* **ghostty:** intern SGR styles once per command ([76bdae0](https://github.com/betterclever/wraithterm/commit/76bdae005b70f7c102306350960b7fa6da47747f))
* **ghostty:** read ordinary cells from bulk row views ([d06e87a](https://github.com/betterclever/wraithterm/commit/d06e87a134b37aef6c883efbaff8e7ec116b82ad))
* **input:** streamline CSI entry and generated dispatch ([e7158f9](https://github.com/betterclever/wraithterm/commit/e7158f911428bb1ce504b6176cbe4b861c7614f7))
* **native:** cache search pages and yield without timer clamping ([cb3e7d5](https://github.com/betterclever/wraithterm/commit/cb3e7d5a0451417f4982fef67b41a8a138128625))
* **native:** remove search timer delays and cache history pages ([2255e2e](https://github.com/betterclever/wraithterm/commit/2255e2e95b5e07e5bdec75619f8559954ab534d7))
* **native:** suspend normal GPU draws outside visible panels ([2e747ea](https://github.com/betterclever/wraithterm/commit/2e747ea6bf24a780cacf359b1ca52724856c0f1c))
* stop native GPU draws for hidden terminal panels ([a206cf3](https://github.com/betterclever/wraithterm/commit/a206cf3a36449dc829796eb59880787fa9417d30))
* **xterm:** bulk print fixed-width text across wrapped rows ([7bbfee6](https://github.com/betterclever/wraithterm/commit/7bbfee6d19f11fd6c65b0fa5df7c87b82d8d9c99))
* **xterm:** preserve the compact single-row print path ([efc9574](https://github.com/betterclever/wraithterm/commit/efc95749aa4141b10b38fa081c41e180b969ff29))
* **xterm:** resolve optional visual attributes from packed row words ([ef77d0d](https://github.com/betterclever/wraithterm/commit/ef77d0d32f05765077c5d9bc98007d2d3b1b6e2b))
* **xterm:** retain GPU rows for unchanged selection refreshes ([ded1ef1](https://github.com/betterclever/wraithterm/commit/ded1ef1d70eb0334d3aabc2333c7f604e48faa1c))


### Bug fixes

* **native:** honor configured scrollback line retention ([d58d63b](https://github.com/betterclever/wraithterm/commit/d58d63bd4ea132310727d046283bb5f895f1c6d2))
* **native:** honor configured scrollback line retention ([ebf484b](https://github.com/betterclever/wraithterm/commit/ebf484b58984760d3c5a2461ca8c1504180fc8f3))


### Documentation

* **bench:** publish controlled browser terminal comparison ([0fd9c8e](https://github.com/betterclever/wraithterm/commit/0fd9c8e23d12758f096144c0dc98cfa43dcc7925))
* **bench:** record 452 terminal workflow and resource runs ([3400232](https://github.com/betterclever/wraithterm/commit/3400232f58bf6846d0e792801a2a940f642bcbe5))
* **bench:** retain counted-search gains and undecorated controls ([84c668a](https://github.com/betterclever/wraithterm/commit/84c668af5c8dacbdbb62e403e4a9cb314b5ad472))
* **bench:** retain hidden-panel efficiency and visible CPU controls ([e65f309](https://github.com/betterclever/wraithterm/commit/e65f309904c23b0d3ac58efd2f2b615f893f3ce7))
* **bench:** retain paired wrapped-text gains and fallback controls ([92f85e3](https://github.com/betterclever/wraithterm/commit/92f85e35caf37a0cdbdf7aed52c4cd682dae01db))
* **bench:** retain repeated GPU visual-option comparisons ([84b3d67](https://github.com/betterclever/wraithterm/commit/84b3d672fe55a443efb0fb17ba884472a60d16ed))
* describe native Kitty graphics and record streaming throughput ([7289db3](https://github.com/betterclever/wraithterm/commit/7289db3a14c4b396ff481b120a10aef9c52242a6))
* document the terminal pool and record many-terminal results ([b35b3a6](https://github.com/betterclever/wraithterm/commit/b35b3a647e5e74da48e1424b9cb11c3e710de7c3))


### Chores

* release 0.5.0 ([c17715a](https://github.com/betterclever/wraithterm/commit/c17715a9e05ab2257bc0eeb08afcadd0535a4940))

## [0.3.0](https://github.com/betterclever/wraithterm/compare/v0.2.0...v0.3.0) (2026-10-10)


### Features

* **demo:** rebuild the native and xterm.js playgrounds ([1026cc7](https://github.com/betterclever/wraithterm/commit/1026cc757c429358dc186c51256874863afa2c2a))
* **site:** a pixel ghost that follows the pointer through the hero terminal ([6f0ca9e](https://github.com/betterclever/wraithterm/commit/6f0ca9e4256f10f7fcc730623ad7cf55991f667a))
* **site:** a snappy ghost and a glyph trail behind the pointer ([5a0034f](https://github.com/betterclever/wraithterm/commit/5a0034f48048ddfec1bbd18fef5fca2e1dea2e09))
* **site:** Manrope, a Labs section, a warm favicon and a terminal pipeline ([951e53d](https://github.com/betterclever/wraithterm/commit/951e53d59a8a551d5a64a6aecf367b106bd92626))
* **video:** a font picker with a live preview of every screen ([d062366](https://github.com/betterclever/wraithterm/commit/d062366e2d64c75e3932117f2bac0820083a89c7))
* **video:** a slower build, real glyph art for "How fast?", fewer screens ([4b6a9d5](https://github.com/betterclever/wraithterm/commit/4b6a9d52dbf682f2a8bf8162862cc949d7fc957e))
* **video:** lead into the drop with "The spooky fast web terminal…" ([a5e51b5](https://github.com/betterclever/wraithterm/commit/a5e51b5d326744ce22f75065537c87f74627acc3))
* **video:** set the launch video in the chosen fonts ([a9990e2](https://github.com/betterclever/wraithterm/commit/a9990e244dd536de2a33cbe70456429cf686e487))


### Documentation

* drop the banner that repeated the README logo ([297973e](https://github.com/betterclever/wraithterm/commit/297973eb2bfdd7f426f5d0266858b8c56a40e0fd))
* tagline the README "Spooky fast web terminal." ([275d8c7](https://github.com/betterclever/wraithterm/commit/275d8c76be8719c66c1ff3189f631dc04d649125))

## 0.2.0 (2026-10-11)

The first public release.

### Features

- `wraithterm/xterm`: a complete xterm.js 6.0 `Terminal` with original methods, events,
  options, parser hooks, buffer views and addon contracts, rendered by Rust on WebGPU.
- `Wraith.mount()`: Ghostty's `libghostty-vt` and the renderer in one Wasm module, inside a
  dedicated worker, with an ordered PTY transport.
- A live dashboard workload and an in-browser race against xterm.js at wraithterm.com.

### Performance

- 20-byte GPU cells, glyph quads sized to their ink, and row reuse in both profiles: a
  one-cell edit uploads one row.
- Fewer libghostty queries per cell and batched SDK writes.
- On a dense 240×80 scene, 2.5 ms of CPU per update versus 37.7 ms for xterm.js DOM and
  9.8 ms for xterm.js + WebGL (Chrome 155, Apple M5 Max;
  [report](docs/benchmarks/launch/REPORT.md)).

### Bug fixes

- Synthetic bold no longer collapses glyphs such as `i` in the native renderer.
- Block elements and braille tile without seams in the xterm-compatible renderer.

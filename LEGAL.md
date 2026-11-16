# Legal notes for Embryo Synth

Embryo Synth is a modified version of **Yosys** (https://github.com/YosysHQ/yosys), copyright its authors.
License: **ISC license (bundled parts such as ABC keep their own permissive licenses)**. The original license files are kept unchanged: COPYING.

First lines of those files when we forked (2026-11-16):
- `COPYING`: ISC License / Copyright (C) 2012 - 2026  Claire Xenia Wolf <claire@yosyshq.com> / Permission to use, copy, modify, and/or distribute this software for any

## When we offer it to people
- Keep the copyright notice and permission notice in all copies.
- Bundled parts (ABC and others) keep their own notices.
- "Yosys" is the original project name; ours is Embryo Synth, "based on Yosys".
- Running it on our own servers for people (inside the apps) is not handing out the program; we still keep our source public.
- Chips and layouts people make with it belong to them; the tool's license does not cover what it produces.
- No warranty beyond what the license says.

## Bundled parts (git submodules) and their licenses
- abc: University of California permissive license (copyright.txt)
- frontends/slang/lib: ISC
- libs/slang, libs/cxxopts, libs/fmt, libs/tomlplusplus: MIT
- libs/symfpu: GPL-3.0 or BSD-3-Clause, our choice: we use it under BSD-3-Clause
- libs/boost_regex: Boost Software License 1.0
All are permissive (with symfpu taken as BSD-3), so Embryo Synth can be offered under ISC plus those notices.

# Informate language models

The files in the [`models` release](https://github.com/thewiffedshot/informate-models/releases/tag/models)
are what Informate (informate-game@simon-is.live) downloads the first time a language is
played. They are **unmodified copies** of packages published on [nuget.org](https://www.nuget.org)
and [PyPI](https://pypi.org), mirrored under their original names so the game does not depend
on those sites staying reachable. The game checks every file against the hash its original
publisher gives for it and refuses any that does not match, and it falls back to the original
site if a file here cannot be fetched.

Nothing here is Informate's own work. Each file is under its own licence:

| files | project | licence |
|---|---|---|
| `catalyst.models.*.nupkg` | [Catalyst](https://github.com/curiosity-ai/catalyst), Copyright (c) Curiosity GmbH | MIT |
| `lucene.net.*.nupkg` | [Lucene.Net](https://lucenenet.apache.org), Copyright (c) The Apache Software Foundation | Apache 2.0: `licenses/Lucene.Net-LICENSE.txt`, `licenses/Lucene.Net-NOTICE.txt` |
| `j2n.*.nupkg` | [J2N](https://github.com/NightOwl888/J2N) | Apache 2.0: `licenses/J2N-LICENSE.txt` |
| `jieba.net.*.nupkg` | [jieba.NET](https://github.com/anderscui/jieba.NET), Copyright (c) 2015 andersc; its dictionary from [jieba](https://github.com/fxsjy/jieba), Copyright (c) 2013 Sun Junyi | MIT |
| `system.configuration.configurationmanager.*.nupkg` | [.NET](https://github.com/dotnet/runtime), Copyright (c) .NET Foundation and Contributors | MIT |
| `libnmecab.*.nupkg` | [NMeCab](https://github.com/komutan/NMeCab), Copyright (c) Tsuyoshi Komuta; a port of MeCab, Copyright (c) Taku Kudo and Nippon Telegraph and Telephone Corporation | LGPL 2.1: `licenses/LibNMeCab-LGPL-2.1.txt`. Its source is in the same release, `NMeCab-0.10.2-source.zip` |
| `python_mecab_ko_dic-*.whl` | [mecab-ko-dic](https://bitbucket.org/eunjeon/mecab-ko-dic), packaged by [python-mecab-ko-dic](https://pypi.org/project/python-mecab-ko-dic/) | Apache 2.0: `licenses/mecab-ko-dic-LICENSE.txt` |

Each package also carries its own licence and notice files, where its publisher included them.

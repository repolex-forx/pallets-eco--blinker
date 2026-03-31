# Repolex Knowledge Graph of pallets-eco/blinker

RDF knowledge graph data for [pallets-eco/blinker](https://github.com/pallets-eco/blinker), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download pallets-eco/blinker
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 11b46cf60db28c0dede87a93d62a2578c4cdca7d.nq.gz
│   │   ├── 28e19c7e743fb9427afad8f258f844cfdeeb3851.nq.gz
│   │   ├── 2a6e30897bc3461788d5ed86b6a809c8a7143cb1.nq.gz
│   │   ├── 2adbe03d2243ba7bf07fad09728bc1f179999ae2.nq.gz
│   │   ├── 3e534565a811c5e8d8ea01f5c5f7e5c1de4fcfde.nq.gz
│   │   ├── 876a12a1988c1789799a1d6919abdce38a62a0ff.nq.gz
│   │   └── 9f3c4b5a7790ed2451dde1646de5761e290f2e4a.nq.gz
│   ├── lsp
│   │   ├── 11b46cf60db28c0dede87a93d62a2578c4cdca7d.nq.gz
│   │   ├── 28e19c7e743fb9427afad8f258f844cfdeeb3851.nq.gz
│   │   ├── 2a6e30897bc3461788d5ed86b6a809c8a7143cb1.nq.gz
│   │   ├── 2adbe03d2243ba7bf07fad09728bc1f179999ae2.nq.gz
│   │   ├── 3e534565a811c5e8d8ea01f5c5f7e5c1de4fcfde.nq.gz
│   │   ├── 876a12a1988c1789799a1d6919abdce38a62a0ff.nq.gz
│   │   └── 9f3c4b5a7790ed2451dde1646de5761e290f2e4a.nq.gz
│   └── repolex
│       ├── 11b46cf60db28c0dede87a93d62a2578c4cdca7d.nq.gz
│       ├── 28e19c7e743fb9427afad8f258f844cfdeeb3851.nq.gz
│       ├── 2a6e30897bc3461788d5ed86b6a809c8a7143cb1.nq.gz
│       ├── 2adbe03d2243ba7bf07fad09728bc1f179999ae2.nq.gz
│       ├── 3e534565a811c5e8d8ea01f5c5f7e5c1de4fcfde.nq.gz
│       ├── 876a12a1988c1789799a1d6919abdce38a62a0ff.nq.gz
│       └── 9f3c4b5a7790ed2451dde1646de5761e290f2e4a.nq.gz
├── blob
│   ├── 000c902a2564d2d4a551edb646a9d654d9e7041b.nq.gz
│   ├── 01aaea5c518104c8b9a83cf2af589e932b55f1ad.nq.gz
│   ├── 01b06b2e2893c6da8f1a9907519deec594ce6a1b.nq.gz
│   ├── 0517fe56af8fb03f702cfa4e86ffa9aa538cb27c.nq.gz
│   ├── 068d94cec22937bf15e670e83fa9112700635c9c.nq.gz
│   ├── 074101bba5e8190326842b43e80d4556670bb232.nq.gz
│   ├── 07ddd989fe3b5ed2bf34b77227dad0dd94014ccd.nq.gz
│   ├── 081173df1d682063fb6b88097d9f9454baf6aeae.nq.gz
│   ├── 0ace8b24884c396586ac164addf2467c0ef3d438.nq.gz
│   ├── 0c112da89b5c8b52d4b40ad662d8c6c7062c2fd7.nq.gz
│   ├── 0d7a6bcd8b99b77988b647e740e9b8fb141b533a.nq.gz
│   ├── 123183bcf3f2616df1285df1cf871c98c2fe8949.nq.gz
│   ├── 133c57a0642e997e52ad5235c00930cf94919b3e.nq.gz
│   ├── 13afd660ed0177cddb1afe22ae8a0955d3f7ad8b.nq.gz
│   ├── 1736c9adaca8485f5aea356e7a36e189086c8ff0.nq.gz
│   ├── 177dcab6baf3f67e69aa00f323e45bdfdec4113d.nq.gz
│   ├── 1ca9c161cc3256e249267afb72666580148eea02.nq.gz
│   ├── 1e67c0916388f24833563be8d32ae8d707b1536a.nq.gz
│   ├── 1efde82b173ffe47e0b7410a7d28addacff74a11.nq.gz
│   ├── 1f47f125e5c06e827ba4df75cffd838547a4163a.nq.gz
│   ├── 20ef9d8836d29e7397c5e2fefae0388f014f8753.nq.gz
│   ├── 22228a1cd2fd561782e0fc49bbbe17d61007f4d8.nq.gz
│   ├── 2637dd0f58f625037763639502185905d6808ebe.nq.gz
│   ├── 2853115cae7cf8facedbd8073c92c0c9e1a4f533.nq.gz
│   ├── 29f3632fcd26e531a323d4a9db960efcb415c972.nq.gz
│   ├── 2a7531b22b5ac3934d27bb193a12f0b1812573f7.nq.gz
│   ├── 2ff985a67af35fdfd1076354b771c425867cdab4.nq.gz
│   ├── 304c00bc2aada199ec5863a1352f1e918320e42e.nq.gz
│   ├── 325ba80e44355d4d355055041c16a6db0642726e.nq.gz
│   ├── 337ebc235884bcca4709dafc585de0bc19ac0709.nq.gz
│   ├── 378eac25d311703f3f2cd456d8036da525cd0366.nq.gz
│   ├── 39ac90c174d1cf8bf83097db11f4ce121b1161b2.nq.gz
│   ├── 39c365f76124bcf9f35e339031a8cbfe84a2dadb.nq.gz
│   ├── 3f09b7226f957619124ee750a515946e88995ce8.nq.gz
│   ├── 40966db312cb2948b4f06e08b593c19f7da47dcc.nq.gz
│   ├── 41180b45aae818fbd8c8621dfbe22913a951ae0e.nq.gz
│   ├── 416c891a3466f86e168abc0da008c1ff69bb65d1.nq.gz
│   ├── 462ccd31926e3a8e0cbb320c2c0acbaae2bdd516.nq.gz
│   ├── 463736a3000872fe57c2f8ab96771cdccfd4d70c.nq.gz
│   ├── 4b711c67d3e1fb0f6e55cf75f5c63913e15bc63f.nq.gz
│   ├── 4f802f4057fbb38f7270ca1c349329962c2b4774.nq.gz
│   ├── 504a3d47bd6b70d0599c478c159d6308cbfaa692.nq.gz
│   ├── 521431d90cb4c1a6d97478fa6a2faaf35e041ae6.nq.gz
│   ├── 53916269427d369d35433c5ad6ae81124baf7cee.nq.gz
│   ├── 53fca7e29765d12678121793382d352a2f0dde2e.nq.gz
│   ├── 554a7c60f63fbfaa2713b3023ab7e8451fb526ce.nq.gz
│   ├── 59b959fec6b09421a53c15087df3731f125d0286.nq.gz
│   ├── 5bbd2005f045a17b9b95c3c7445ec3ad73be667e.nq.gz
│   ├── 5ec50975d1d7854a9e09737400a741ff1595f71f.nq.gz
│   ├── 62086aa57fca0a8c751a7c82f61ff9b14bbb1746.nq.gz
│   ├── 62c1b887d73cc6325731f0c9c97927df23a42d1d.nq.gz
│   ├── 65be3d75321daa1b96efce91c103419c4622bbb7.nq.gz
│   ├── 671732f1bbf56902293b0a0c7bbe67ebcf6d6fec.nq.gz
│   ├── 6bb1491e8ba9f2a9f26a21d31cfee5df05e418ae.nq.gz
│   ├── 6de8000877cf8df2d5ae108e792f737f41d2b350.nq.gz
│   ├── 70b44e2fc5db30a8846ac96e49164c6a93f5bd24.nq.gz
│   ├── 70ee6b2d5f43e65e62a5ac2fb888e27df9eb9821.nq.gz
│   ├── 71d66d3bd40b533a0e1f3d3722a895a0d8c4e11b.nq.gz
│   ├── 72fdd8e01ba981e8694071eefcaaa22d16636e21.nq.gz
│   ├── 74abdef21ecc65f3cc392be21c38880cc2aa461f.nq.gz
│   ├── 7521ac3c5432d602d86dbac5ade7f408662667f1.nq.gz
│   ├── 75f993343a4890c4df3f1ecf2fc0bd61a1c48d9e.nq.gz
│   ├── 784ba4e121dac11f5d79f1723d8c00166f709225.nq.gz
│   ├── 79c9825adbacb5d8c6eaee51863b8a40051d97c8.nq.gz
│   ├── 7b18580dec0b91c0a42cc5b688d380cd1074d5cc.nq.gz
│   ├── 7e222fd852fd6bcd527589ec95b9c0af84ebb498.nq.gz
│   ├── 80e24e21c10386baad8dedf17c4756f34f7e8230.nq.gz
│   ├── 81f60c8ec28421ae0d126f4cefc50b0935f8a1ff.nq.gz
│   ├── 848b0ea32c4baa559660c112484ab40f91e01f1d.nq.gz
│   ├── 84a7b3768e62e8d53b0734f09174c5d560ca3a4d.nq.gz
│   ├── 865c68597994a02456d113489a5d931464d2b9c5.nq.gz
│   ├── 87699c45b5bc12bda85da5e2586fee7533e3bd88.nq.gz
│   ├── 883dded1c8298e8cd11f9fabd26eccd393fc7006.nq.gz
│   ├── 88e18188ab9de35802d700de2400598c582b9a8e.nq.gz
│   ├── 897efa713227b72ed1ac08082643c681713baf95.nq.gz
│   ├── 8a3e4f95b97eba3dc8005b87432a322beedf5eda.nq.gz
│   ├── 8aa65255b9d058d7ef95739e311ca992cc9ee764.nq.gz
│   ├── 8be59c5dc36bac6517788b5003db1822a89a6c2f.nq.gz
│   ├── 8dd5b87863340d07e994343020825ffd6489a67c.nq.gz
│   ├── 90f94bc32b917f4902e37ebf40553590c3b3a521.nq.gz
│   ├── 9141cd7a5c0bf54a73fdc6a38111551790714df3.nq.gz
│   ├── 9201046a144472238b4869db302be8eb61ef1264.nq.gz
│   ├── 93a9c483d555286d337aeb79677b960814dfbbb7.nq.gz
│   ├── 954237b9b9f2b248bb1397a15c055c0af1cad03e.nq.gz
│   ├── 95fefe0df76b579695385391e8366cd132bf45da.nq.gz
│   ├── 9825178c3a74185f479fbbe9d1f6123355b98fdb.nq.gz
│   ├── 997fef516eb7c819d303610175c3ccb38a1d7583.nq.gz
│   ├── 9de44e64e4574298737d7c5aa92d92d78057d0b8.nq.gz
│   ├── 9ecbc3db3f661dcdb73094eb8da71f026726e479.nq.gz
│   ├── 9ecc4895274bca9b26b8e012ce8fd53de1c497a4.nq.gz
│   ├── a07a53a153868c0008511a149af953e939e606d7.nq.gz
│   ├── a3969bbbe0f7c904021aed56068c0214bebf1724.nq.gz
│   ├── a56ea9879e978332f8e513f517d7c1fff0fd19da.nq.gz
│   ├── a91266de03dfe6d433c8cdb2f99834e6b0af0152.nq.gz
│   ├── ab651af6316ceeebd05d79dc0efd51d35334a5d9.nq.gz
│   ├── ab73fb81d6feac57591eec7c4bf09662f583ef8e.nq.gz
│   ├── acf469fbfbecab81314089f7127a1bfda07508c5.nq.gz
│   ├── b0a55829c28227b0412ce93410a49b6327d80b89.nq.gz
│   ├── b9d703586deb018a80053c2a6406bef9b10ad961.nq.gz
│   ├── ba3fd777497d8a8369916141293596d11055363f.nq.gz
│   ├── bed55ca9d83c80d886b19d7ca7dfe69a378a5a5a.nq.gz
│   ├── bef49d58304b7077b9e8ec117c9ff194945d94db.nq.gz
│   ├── c294f3b87274cb794700a621bf29ee6e0323b856.nq.gz
│   ├── c2f111a8771030bbd661ae9af8d6ccf65f05f042.nq.gz
│   ├── c58c26d1849c41dfbd6f3eff6975e7401a0dd23d.nq.gz
│   ├── c71076b8e02d75a43cac02b84549590d98a918b5.nq.gz
│   ├── c7af9ee459eea7a2b26dd3e62593b0fb1003c52e.nq.gz
│   ├── c8b7bda73861f90d7be3f676d3315c6f5e057a3c.nq.gz
│   ├── c93527eca8b97bb6f030e8428c39cecb0e085d71.nq.gz
│   ├── ca0f5af9bb584ab448b3ae28f3be6fe1c262be29.nq.gz
│   ├── cab56636c2eed4f47f3d8e18c1590ff3fb50c8eb.nq.gz
│   ├── cc4068a9b7b3ea315a0a046e2a172b7f5841687d.nq.gz
│   ├── d014caa0ff2564a1e83485fadd8c9b5efcdc3853.nq.gz
│   ├── d0e65723d6e6c9f00c00818f2aa5fdbe50369f26.nq.gz
│   ├── d1219e585b78e5602af9e7ab265a7e182b11becc.nq.gz
│   ├── d278ca08e39bb5054ef039200cf30e9c1bff0e7f.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d6658cf8aa8b7c2d69db879e9e1dbb70f0611ab3.nq.gz
│   ├── d8c87e7d2c292c564144408c3944bbebbb915a57.nq.gz
│   ├── d9a34273377fa24d50d4716722114ac22c3a2c5e.nq.gz
│   ├── db1749db31620631c4462cf192c2c235f67b4300.nq.gz
│   ├── dbb67e35faf4686efb8c52eb25dc763f2f38e6e2.nq.gz
│   ├── dc017aa74c6731d2552eb4035f8c0a3a4ef3d21d.nq.gz
│   ├── dcb70c1899df9c8e5b4ead958d796efde6a2929e.nq.gz
│   ├── e038098fc27bf65c6ee271034d31b89f39dce433.nq.gz
│   ├── e079f8a6038dd2dc8512967540f96ee0de172067.nq.gz
│   ├── e3bc6d4781358b4acfb6409910494fbcf3963531.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e74db47723fd69129b55d0b8cce8cf12dcf524d2.nq.gz
│   ├── e8414f0e92ba321898f736bb7383546266446745.nq.gz
│   ├── ea2f786449722d85cba4a552cae9d830a1a7ded9.nq.gz
│   ├── eb8210380a2ac18dde0e563f279c830c33165d35.nq.gz
│   ├── edcf4fb032044ac63039fcb96644cb90e8b7878d.nq.gz
│   ├── ee4ba018603bb4fed80a0a9460ee9bdff7353c31.nq.gz
│   ├── eff87134a2ba0fda9571f058315b76ecff20060d.nq.gz
│   ├── f06ebc003a0cc3ea7fd78b4f4f1361353aeb2da1.nq.gz
│   ├── f0aa93ac8e33ed68cf6516ffc2e61785693a2f94.nq.gz
│   ├── f45cba72053bbf930f90c42fb6f198cf2bce595c.nq.gz
│   ├── f52760bd111b19ef0ed15e01d71765701864e9cb.nq.gz
│   └── f707a458f3fbcc3ac0d4d5b96ee21f7f72dbeea5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 11b46cf60db28c0dede87a93d62a2578c4cdca7d.nq.gz
│   ├── 28e19c7e743fb9427afad8f258f844cfdeeb3851.nq.gz
│   ├── 2a6e30897bc3461788d5ed86b6a809c8a7143cb1.nq.gz
│   ├── 2adbe03d2243ba7bf07fad09728bc1f179999ae2.nq.gz
│   ├── 3e534565a811c5e8d8ea01f5c5f7e5c1de4fcfde.nq.gz
│   ├── 876a12a1988c1789799a1d6919abdce38a62a0ff.nq.gz
│   └── 9f3c4b5a7790ed2451dde1646de5761e290f2e4a.nq.gz
├── filetree
│   ├── 11b46cf60db28c0dede87a93d62a2578c4cdca7d.nq.gz
│   ├── 26f65bde4ff7b828392d51d456dc3753bfd9961a.nq.gz
│   ├── 28e19c7e743fb9427afad8f258f844cfdeeb3851.nq.gz
│   ├── 2a6e30897bc3461788d5ed86b6a809c8a7143cb1.nq.gz
│   ├── 2adbe03d2243ba7bf07fad09728bc1f179999ae2.nq.gz
│   ├── 3e534565a811c5e8d8ea01f5c5f7e5c1de4fcfde.nq.gz
│   ├── 876a12a1988c1789799a1d6919abdce38a62a0ff.nq.gz
│   └── 9f3c4b5a7790ed2451dde1646de5761e290f2e4a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 181 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |

## Source repository

[pallets-eco/blinker](https://github.com/pallets-eco/blinker)

---
*Parsed on 2026-03-31 by [repolex](https://repolex.ai)*

# Repolex Knowledge Graph of bcgit/bc-java

RDF knowledge graph data for [bcgit/bc-java](https://github.com/bcgit/bc-java), parsed by [repolex](https://repolex.ai).

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
lexq download bcgit/bc-java
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 228211ecb973fe87fdd0fc4ab16ba0446ec1a29c
│   │   │   ├── chunk-001.nq.gz
│   │   │   ├── chunk-002.nq.gz
│   │   │   ├── chunk-003.nq.gz
│   │   │   ├── chunk-004.nq.gz
│   │   │   ├── chunk-005.nq.gz
│   │   │   ├── chunk-006.nq.gz
│   │   │   ├── chunk-007.nq.gz
│   │   │   └── chunk-008.nq.gz
│   │   ├── 52b0902592e770b8116f80f2eab7a4048b589d7d
│   │   │   ├── chunk-001.nq.gz
│   │   │   ├── chunk-002.nq.gz
│   │   │   ├── chunk-003.nq.gz
│   │   │   ├── chunk-004.nq.gz
│   │   │   └── chunk-005.nq.gz
│   │   ├── d4cc9614fc849e840ffdc7941f4a2941131d0c9c
│   │   │   ├── chunk-001.nq.gz
│   │   │   ├── chunk-002.nq.gz
│   │   │   ├── chunk-003.nq.gz
│   │   │   ├── chunk-004.nq.gz
│   │   │   ├── chunk-005.nq.gz
│   │   │   ├── chunk-006.nq.gz
│   │   │   ├── chunk-007.nq.gz
│   │   │   └── chunk-008.nq.gz
│   │   └── de42702b6cda2631e8e3ff94f8458198860b328e
│   │       ├── chunk-001.nq.gz
│   │       ├── chunk-002.nq.gz
│   │       ├── chunk-003.nq.gz
│   │       ├── chunk-004.nq.gz
│   │       ├── chunk-005.nq.gz
│   │       ├── chunk-006.nq.gz
│   │       ├── chunk-007.nq.gz
│   │       └── chunk-008.nq.gz
│   ├── lsp
│   │   ├── 228211ecb973fe87fdd0fc4ab16ba0446ec1a29c.nq.gz
│   │   ├── 52b0902592e770b8116f80f2eab7a4048b589d7d.nq.gz
│   │   └── de42702b6cda2631e8e3ff94f8458198860b328e.nq.gz
│   └── repolex
│       └── 228211ecb973fe87fdd0fc4ab16ba0446ec1a29c
│           ├── chunk-001.nq.gz
│           └── chunk-002.nq.gz
└── blob
    ├── 0001cd8187e5fd8f459e90f73b2429e83770800e.nq.gz
    ├── 0002ab0a267170f2a147a7ccb7d915d83e1f2ce0.nq.gz
    ├── 0009819faace505666436e1eddb246827f9da8d4.nq.gz
    ├── 000b0c476b27dab93dc0b9a6dd3d82f1a5d7c3a4.nq.gz
    ├── 00172b74acb6533faafaf450ea2a3263777403f0.nq.gz
    ├── 001af3c85db66f91a01f457ddaaec306b048fc56.nq.gz
    ├── 001cd5998ca5f70efd1de61f0d5c090754be31f9.nq.gz
    ├── 001dab3ec8d5422d68736978cfe0aa3469bf19e1.nq.gz
    ├── 00295797c3c0627c45b9f34e11f42a1548a821be.nq.gz
    ├── 0038f90fcb271c09184e74431d69da7fdb6268fb.nq.gz
    ├── 003faeb666b98d19234a9ec1e279c0d5cc8fa3d3.nq.gz
    ├── 00447be0bc015688221009fb1882019a409c5135.nq.gz
    ├── 0046767e3eaa4f0cde49a5fe4195443753c02cc5.nq.gz
    ├── 00488606e82f84c45c8d51800bec1c66e315579a.nq.gz
    ├── 004a7455b728d0b16e5649eb8e6f733d12e90e53.nq.gz
    ├── 004c3693b735e24fc1d0991edc657660dbd046f5.nq.gz
    ├── 0052100a514555fcc15e41aafaa65ec731d4da69.nq.gz
    ├── 006c890785485c936d9868a13a72fa9d9dcf004c.nq.gz
    ├── 007e743e750a0b591559f5cb06c3bbfd7f7666ed.nq.gz
    ├── 007fa98f90c77e5eb57213f91752841c3a29d964.nq.gz
    ├── 008d4d8c04dd0abe27d6d5748bd3c4b52676906c.nq.gz
    ├── 009dcd43e3dc553c12cd2ecab942e93310edcad6.nq.gz
    ├── 009ddfe85c5c24315c2d94de8e7a7ca11be050cb.nq.gz
    ├── 00a124b65824aa5f640b9fe07a7cd6f52c99b523.nq.gz
    ├── 00a57d59e79b6f1b66fc602c7be5948e803b1d52.nq.gz
    ├── 00a9660731fca499348b7fe8750f5f67e5765a59.nq.gz
    ├── 00aabad1ece0023ff128f8cbba153c56a812b2e4.nq.gz
    ├── 00ae4a1830395e778fb82215befa2d28283eb497.nq.gz
    ├── 00b56dd74367f081e744fa0065ae8712329d487a.nq.gz
    ├── 00b6a2ca3fc35d8bac1a945fd47a1498efa93686.nq.gz
    ├── 00be081a3d2123a0a2869342f4a53bd5f708a437.nq.gz
    ├── 00ca0a200dc3816a7d33cc0e8ff2d50a1b18b526.nq.gz
    ├── 00cbae57096dc9c90771e74ec6d555dd461e5c2c.nq.gz
    ├── 00d30761090fdb0729431fc29f2f3cebea8f9bfd.nq.gz
    ├── 00da1f27671902c7c1826ae9efaf5323fc5e9004.nq.gz
    ├── 00dd63bb27accdaa52075d08f524e0b1ff96d93a.nq.gz
    ├── 00e0c79f59713bf6214637d0ecb32dad0c1ec18a.nq.gz
    ├── 00f106678facc59aae4e878d6ba42862ffe1571b.nq.gz
    ├── 00f117cfa88ff6a59e301513c2a67f9084c167be.nq.gz
    ├── 00f76fbbd6a7d109d5dbd28d5fec0136ef40fa7a.nq.gz
    ├── 00f8cbaa6b295d95153d00fb3f96b8faaa45158e.nq.gz
    ├── 00f980508c22f03b071f25357cf2c23224a6aefa.nq.gz
    ├── 00fcf65bdb12010459d5ca4677145f9a0d247890.nq.gz
    ├── 00fdd2c55c4baa1b8664483a2a9f9ff57d80a2ed.nq.gz
    ├── 01047e916f2e4b934f5d56834633651915695437.nq.gz
    ├── 010d23a256beabc65b03751f8cad0caed03b8b73.nq.gz
    ├── 010e12c2ede3732b56846606fbf53b1876a74205.nq.gz
    ├── 01167b57bb281656d1fa7cf865cd60708ef3da19.nq.gz
    ├── 011e97c5e04c17ce9373e95982876dac464781b5.nq.gz
    ├── 012b440a11aeb9c82c364190786e5cb5e70d2d0f.nq.gz
    ├── 012f2e06b331aebb28001fbcef49beb84cbbcdb5.nq.gz
    ├── 0134be46dbadebb8b36070417448e5c38ea0ec69.nq.gz
    ├── 01371e7fe7958de59b5cd4c8430d1b3bba6fd9a3.nq.gz
    ├── 013e775b3c9de8cce55d37820a1a8a2b755303fb.nq.gz
    ├── 013eeb31c3be0b7bb723195ecd9a27b61e4c06ba.nq.gz
    ├── 0146fec1ddb0e8ded78d94fc183907ca7ea3ca97.nq.gz
    ├── 01486441007e5664d1260246a58a99bd0c4fe043.nq.gz
    ├── 015557ad35b4c0835121aac9f606228ad3e8a062.nq.gz
    ├── 01588b6a3b26d9116ac7c25617721785068553ed.nq.gz
    ├── 015a75afa847a2957c80fb20af7c65b6831c6a2c.nq.gz
    ├── 015ff0510febce96d71d759f80a53cf1ca19ba52.nq.gz
    ├── 0166d99f3d241524b5352cd4a9f4388192a6922f.nq.gz
    ├── 017138757f3778bf6d798e9d5bf5bc1c0c4083b9.nq.gz
    ├── 0178425ecb5a7fbd4352e86fe50e162124719c99.nq.gz
    ├── 017e1046cb25de2d11ff1e3dd4cd3a43674985e3.nq.gz
    ├── 018a802566234a4985e74e0f5352ff4a24258dd7.nq.gz
    ├── 019ada270797920d1497b160825151d1460c2e88.nq.gz
    ├── 019af544241b1f3884e9ed5c9f4b7dc12233d6b5.nq.gz
    ├── 01a0a1514756a76f9bf6b5dc05899a684e6eefbf.nq.gz
    ├── 01a21a15e3243c2b8a9c31f318f3d9b00fdaed59.nq.gz
    ├── 01a5d9a468619160325dbf1c45fc31a3fa288793.nq.gz
    ├── 01a8dd5fa9c0ad102966915a1c43c807348c46e5.nq.gz
    ├── 01aae50c927dd367b7cb26d59bc33ba3f19d610e.nq.gz
    ├── 01b254ebf0a4baf20b00973cde363c491eeefd83.nq.gz
    ├── 01b97e9ae210d318c266789f324e6ef086399bd2.nq.gz
    ├── 01baf0f990c2b1b4849a0d7edb2fefd11c4e46ca.nq.gz
    ├── 01bb2cd5190e3b81c1a9b9fec5c5d01bb4a82f5f.nq.gz
    ├── 01bce302c4b5d89d1ea831d835c1aa816e710bc1.nq.gz
    ├── 01c1bbd186b4bc7bf587b6e2ed996382be28a00f.nq.gz
    ├── 01c46f1aa5cf19775928fe39f8715f061689cc64.nq.gz
    ├── 01cccf33dc7b7223f06abd81a27ccaef27d190ed.nq.gz
    ├── 01dbcc65d5d7c52eede62128126cb001df9df433.nq.gz
    ├── 01ea4d0b76dcc73fed43ab364bc60adc61bf619a.nq.gz
    ├── 01f87037dc5b52d1a8066b78d4d66cc65b0f0f00.nq.gz
    ├── 01fe385674f32c64c094aaeb1f7bb2bfb1f8269a.nq.gz
    ├── 021b0f7d1eee51d1b7b4fc3dc412d6c465e77e42.nq.gz
    ├── 021df23daef9b524a5f4db6dd158ae58f31e006d.nq.gz
    ├── 022a7c36c92cdc6d791a2e20c9f1dc18badc48ce.nq.gz
    ├── 022c01832d3fc9c0bda8a90aee3a0de4668bcb24.nq.gz
    ├── 02319a38bfe312265d15089ed24badde2c5eeec2.nq.gz
    ├── 0237b3a609193ea2465512e2dc1b16ed8c37fb2a.nq.gz
    ├── 023be0b6a5d8508cbfbe392ac42746eff000ea58.nq.gz
    ├── 02448610df9946e34798ffe980d1e3d060796139.nq.gz
    ├── 024b107b2d4cf3faf705d83edd75c9fdb3e04157.nq.gz
    ├── 024bbd66efd75c0ce925575024b05873fa19eeca.nq.gz
    ├── 0250dcb5ce15af92c0b4bca485c8006899fe4996.nq.gz
    ├── 025327f6b1c6c5fc126dbc13515c3c121aeea87b.nq.gz
    ├── 02579a94b8d698d3f4d9f40ef1445477321b5d3b.nq.gz
    ├── 025b6bbbac3ca0080cd3033a298632c20def6ae6.nq.gz
    ├── 025e1371bc223e12c5272782e757e476f3aee37d.nq.gz
    ├── 025f477565a2a3015189da918c06f9f522a3bbcd.nq.gz
    ├── 0261d9622e6d4174b6e020581e0af9bf4a55ab2d.nq.gz
    ├── 02626ac23e62b6c11d2ad3501bd0691a8dcd4b4d.nq.gz
    ├── 0265642150612fd3d3f4bdfe878accc90edecbb4.nq.gz
    ├── 02674215a393782b35c16942c845bdb904f0cef8.nq.gz
    ├── 02714873d29e4a7b7c07e6617d5f8b7e4bf06ac7.nq.gz
    ├── 02781922b166e48d37c66ac6e8150a642c08cdf3.nq.gz
    ├── 027af6326cb5e2ba9d5ac118cf5be5ac14fe2a1e.nq.gz
    ├── 027b0133e485102ae31e94eaffecce2fde4ae669.nq.gz
    ├── 027d0da345a1ca1adec0671ad1960deda82b2d10.nq.gz
    ├── 027f2d894a8086f851e71aa40699442a64ebcbe8.nq.gz
    ├── 0287f0402761f2be2c2e3dc043135ac314301cd3.nq.gz
    ├── 028cf79470347cffefb5a3359fbcfe1952bf7c11.nq.gz
    ├── 02964ae875e23db65cf5957f7b3eef6c54323ee5.nq.gz
    ├── 029d88ac247332bd40e5809fb43f3c55e9cb9a98.nq.gz
    ├── 02a691c6c4a59ad1fede2afafff3692a76002cf9.nq.gz
    ├── 02ae69019ac60858419b5b8cf8a927a24fbb10f5.nq.gz
    ├── 02aeffa914f244fe65a09dfb168a3f5888859f86.nq.gz
    ├── 02b1bd02d5ac0110359c73524869986d65752ead.nq.gz
    ├── 02b51291132436d6c673db590ffbf0e6a8395c1a.nq.gz
    ├── 02be17931eda0a348be14ad966b409b820caa9c6.nq.gz
    ├── 02c3db9f79bbc43a1babee454df01f55c77a394b.nq.gz
    ├── 02ca898fc7d30802049c19b12938b4734d062261.nq.gz
    ├── 02cb8811b28ef616d1e67951fd1eaed7cdb838c2.nq.gz
    ├── 02cf7f4a8a10f85a37f09afe20023db8e12d7a85.nq.gz
    ├── 02d6122b639502765a647b752afd9deb8893e725.nq.gz
    ├── 02db7b3ca6eb218a1e0e3f21307563c7455b761b.nq.gz
    ├── 02edcf5ede7ff88dfd8bacd2979625ec3c3fe905.nq.gz
    ├── 02f029a2c1382ea6e93f41338b4fad9b49eaf47c.nq.gz
    ├── 02f0cf9b79945a4e5272a7583061c087323924b8.nq.gz
    ├── 02f3f265980856a680e984673d4caf3e18fd8f7f.nq.gz
    ├── 02f7f5d60df55f1e79946e9e97cb3f4926fb46e3.nq.gz
    ├── 02f7fe41eebeb29d6f24f4b1ccbf218d5d87b461.nq.gz
    ├── 02fd9d837ddb66e676e3dd5e62f35dd601cca8e3.nq.gz
    ├── 03016e1f2db3648fa8aa3ce0c8f2a2d8fe895851.nq.gz
    ├── 0307013edb760d210f3cbdf38d6c00d78eec82af.nq.gz
    ├── 030ddd962201843f554099211519d7bc4873bb1d.nq.gz
    ├── 03204d7cb8ec2ecde6bc23501f6cdab26da51f66.nq.gz
    ├── 0324b121e637fbb51b39a105027d2b7a58521530.nq.gz
    ├── 032dfab6f2d6ca7e2586fae1caa74247ec73a984.nq.gz
    ├── 0331538186b581082fe3767c4c2519c6a1b49772.nq.gz
    ├── 033b27577e2ac6c0abee5e6cf6da805e14f68f53.nq.gz
    ├── 033dad0f6fa4346b7fcf83b899f6fc4dcd297974.nq.gz
    ├── 033facdda6af47414075784bb1a0c359cdc767ec.nq.gz
    ├── 0341e5903a7ca0c15ceaac741074d8e7e8545c88.nq.gz
    ├── 034d64d4c27889150c1c3822ddb8b6c655933977.nq.gz
    ├── 034de7fe0afd2a935bc508a3e36d04e6336ff6ab.nq.gz
    ├── 034ed3709bcc42a1949b26ff962150336277fa1a.nq.gz
    ├── 03509d172568f5b5238b6042fee88b368d3b682c.nq.gz
    ├── 0354ecf79055152862ef3390e616890eb96c53e0.nq.gz
    ├── 035d7ec218e9be503f2ce658cc49613dfcf0ba71.nq.gz
    ├── 035f895e09febcd56a4a7c12defff9f95834a342.nq.gz
    ├── 03617e48a7e6893b3d7ac19eb6d587990f00882f.nq.gz
    ├── 0361e9fbf98c863bb2e460c1b531fc634578ccea.nq.gz
    ├── 036248b7384ae2ec4a1e6cc485263843fd1e46b0.nq.gz
    ├── 0362dde87b99386c957c41df5d96e0ae661fb61e.nq.gz
    ├── 0363f6ef51dafb020c6f36f8131cc26338ebfb8e.nq.gz
    ├── 036c6a0d58edb9c521944bd0dd6b39bacdfd07e0.nq.gz
    ├── 0378c83e74f8aa2e864135acf0b12da43d6c7207.nq.gz
    ├── 03820c3b73b6d81efde0c8ede434aff2ee86de2c.nq.gz
    ├── 038320aac446ec8bf7f59ce844d1c6afc4a964a9.nq.gz
    ├── 039381dba4a56faa27d20efb0eb164a07f8a4119.nq.gz
    ├── 0393cdf05825ad6df21291235a41b61e5b5505b8.nq.gz
    ├── 03993046dd09c3f60cebc3a9cb7e8327a01e35aa.nq.gz
    ├── 039bd7638f297b04fe515756fe4874b7233dfcac.nq.gz
    └── 03ac1604da0b53e30828bd8ea21e77bca0f2d742.nq.gz

11 directories, 200 files
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

[bcgit/bc-java](https://github.com/bcgit/bc-java)

---
*Parsed on 2026-04-16 by [repolex](https://repolex.ai)*

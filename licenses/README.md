# Licenses of the bundled libraries

The wheels link these libraries in, built from the sources below. Each
directory holds the license texts of one of them, copied unchanged from
those sources. RocksDict's own license is `LICENSE` at the top of the tree.

| Directory | Source |
| --- | --- |
| `rust-rocksdb` | submodule `rust-rocksdb`, Congyuwang/rust-rocksdb at `4cf3c68a993b807bc54ff1c5293cdf49e62aaf72` |
| `rocksdb` | its submodule `librocksdb-sys/rocksdb`, facebook/rocksdb at `44e95d8af5d7ec503b3f1d5754c3379ab6c29a9d` |
| `snappy` | its submodule `librocksdb-sys/snappy`, google/snappy at `23b3286820105438c5dbb9bc22f1bb85c5812c8a` |
| `lz4` | crate `lz4-sys` 1.11.1+lz4-1.10.0, `liblz4/lib/LICENSE` |
| `zstd` | crate `zstd-sys` 2.0.15+zstd.1.5.7, `zstd/LICENSE` and `zstd/COPYING` |
| `zlib` | crate `libz-sys` 1.1.22, `src/zlib/LICENSE` |
| `bzip2` | crate `bzip2-sys` 0.1.13+1.0.8, `bzip2-1.0.8/LICENSE` |

The crate versions are those of `Cargo.lock`. Update these texts when a
pin or a locked version changes.

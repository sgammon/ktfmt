### PGO Profiles

Run `./pgo_train.sh` from the repository root to generate `default.iprof` in this
folder. The generated profile is intentionally ignored because it is large.

Pass `-Pktfmt.native.pgo=true` to `./gradlew :ktfmt:nativeCompile` to build with
the generated profile.

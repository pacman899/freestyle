# Changelog

## 11/09/2017 - Version 0.4.2

Release changes:

* Updates Artifacts Section ([#423](https://github.com/frees-io/freestyle/pull/423))
* Adds a custom deploy job stage for releasing ([#422](https://github.com/frees-io/freestyle/pull/422))
* Fixes Artifact Names in docs ([#424](https://github.com/frees-io/freestyle/pull/424))
* Import freestyle slick example ([#425](https://github.com/frees-io/freestyle/pull/425))
* Add hammock docs ([#426](https://github.com/frees-io/freestyle/pull/426))
* Excludes slick example from test coverage ([#427](https://github.com/frees-io/freestyle/pull/427))
* Changes home frees.io ([#429](https://github.com/frees-io/freestyle/pull/429))
* Meta tags social ([#434](https://github.com/frees-io/freestyle/pull/434))
* Adds an implicit conversion for ListenableFuture[Void] ([#435](https://github.com/frees-io/freestyle/pull/435))
* Adds the implicits through a trait for easy composition ([#437](https://github.com/frees-io/freestyle/pull/437))
* Releases 0.4.2 version ([#438](https://github.com/frees-io/freestyle/pull/438))
* frees-rpc Documentation ([#432](https://github.com/frees-io/freestyle/pull/432))
* Disables tests in deploy stage ([#439](https://github.com/frees-io/freestyle/pull/439))


## 10/24/2017 - Version 0.4.1

Release changes:

* Moves integrations and docs back home ([#412](https://github.com/frees-io/freestyle/pull/412))
* Receive build notifications via Atomist ([#413](https://github.com/frees-io/freestyle/pull/413))
* README adjustments ([#397](https://github.com/frees-io/freestyle/pull/397))
* Frees Examples in Main Repo ([#417](https://github.com/frees-io/freestyle/pull/417))
* Removed dependency frees-fs2 from README ([#419](https://github.com/frees-io/freestyle/pull/419))
* Releases Freestyle 0.4.1 ([#420](https://github.com/frees-io/freestyle/pull/420))
* frees-http integrations ([#415](https://github.com/frees-io/freestyle/pull/415))


## 10/10/2017 - Version 0.4.0

Release changes:

* Release Process Update ([#379](https://github.com/frees-io/freestyle/pull/379))
* create pipelined interpreters for logger ([#353](https://github.com/frees-io/freestyle/pull/353))
* Adding support for case classy ([#378](https://github.com/frees-io/freestyle/pull/378))
* From Guavas ListenableFuture to any M[_] : AsyncContext ([#385](https://github.com/frees-io/freestyle/pull/385))
* Adding test to check config method for nested configurations ([#387](https://github.com/frees-io/freestyle/pull/387))
* Improve the implicit error around "uber" handler resolution ([#389](https://github.com/frees-io/freestyle/pull/389))
* adds commercial support statement ([#393](https://github.com/frees-io/freestyle/pull/393))
* Move Monix tests to tests module ([#394](https://github.com/frees-io/freestyle/pull/394))
* Rename algebra operation suffix from `OP` to `Op` ([#395](https://github.com/frees-io/freestyle/pull/395))
* Rename modules to frees-xxx ([#396](https://github.com/frees-io/freestyle/pull/396))
* Remove shapeless as a dependency for the published libraries ([#405](https://github.com/frees-io/freestyle/pull/405))
* Update to Cats 1.0.0-MF ([#408](https://github.com/frees-io/freestyle/pull/408))
* Update Scala in Travis and sbt-freestyle ([#409](https://github.com/frees-io/freestyle/pull/409))
* Releases freestyle-core 0.4.0 ([#410](https://github.com/frees-io/freestyle/pull/410))


## 07/02/2017 - Version 0.3.1

Release changes:

* Freestyle Build Matrix ([#358](https://github.com/frees-io/freestyle/pull/358))
* Release Process Guide ([#356](https://github.com/frees-io/freestyle/pull/356))
* Refactor Implicits ([#351](https://github.com/frees-io/freestyle/pull/351))
* Enables freestyle-docs build check  ([#359](https://github.com/frees-io/freestyle/pull/359))
* @debug StaticAnnotation ([#360](https://github.com/frees-io/freestyle/pull/360))
* Adding tests to freestyle-cache CacheTests ([#316](https://github.com/frees-io/freestyle/pull/316))
* Remove MonadError requirement for logging algebra ([#363](https://github.com/frees-io/freestyle/pull/363))
* reduce deps on scala imports ([#366](https://github.com/frees-io/freestyle/pull/366))
* Uses scalaMetaSettings through the project plugin ([#376](https://github.com/frees-io/freestyle/pull/376))
* Enable implicit args and context bound implicits in @free traits ([#377](https://github.com/frees-io/freestyle/pull/377))


## 06/12/2017 - Version 0.3.0

Release changes:

* bump mainecoon-core to 0.1.1 ([#342](https://github.com/frees-io/freestyle/pull/342))
* Enables CI checks for Freestyle Projects ([#343](https://github.com/frees-io/freestyle/pull/343))
* Calculates coverage only for JVM, excluding JS tests ([#350](https://github.com/frees-io/freestyle/pull/350))
* DA-73 Scalameta migration ([#344](https://github.com/frees-io/freestyle/pull/344))


## 06/02/2017 - Version 0.2.0

Release changes:

* Updates Docs and catches the new sbt-freestyle plugin config ([#303](https://github.com/frees-io/freestyle/pull/303))
* Adds section describing current Freestyle dependencies ([#305](https://github.com/frees-io/freestyle/pull/305))
* Add FunctorK for finally tagless ([#310](https://github.com/frees-io/freestyle/pull/310))
* Fixing async module's codecov reports ([#306](https://github.com/frees-io/freestyle/pull/306))
* Upgrades Tut config ([#320](https://github.com/frees-io/freestyle/pull/320))
* Fix no string interpolation ([#323](https://github.com/frees-io/freestyle/pull/323))
* Allows FS type aliases in @module traits ([#318](https://github.com/frees-io/freestyle/pull/318))
* Adds failing test (for nested coproducts) as ignored ([#324](https://github.com/frees-io/freestyle/pull/324))
* Optimization: Replace FunctionK pattern matching with JVM switch for faster @free programs ([#315](https://github.com/frees-io/freestyle/pull/315))
* My apologies for this println ([#327](https://github.com/frees-io/freestyle/pull/327))
* Removes docs module since it has been moved to its own repository ([#328](https://github.com/frees-io/freestyle/pull/328))
* Fixes img broken link in README ([#329](https://github.com/frees-io/freestyle/pull/329))
* All types should be FQN pointing to _root_.freestyle.InjK ([#331](https://github.com/frees-io/freestyle/pull/331))
* Checks Docs project in CI ([#330](https://github.com/frees-io/freestyle/pull/330))
* Use nested coproduct list support from Iota 0.2.x ([#326](https://github.com/frees-io/freestyle/pull/326))
* Git Docs: branch and swallow clone ([#336](https://github.com/frees-io/freestyle/pull/336))
* Disables docs check until CI is fixed ([#338](https://github.com/frees-io/freestyle/pull/338))
* Docs Setup Conditional ([#334](https://github.com/frees-io/freestyle/pull/334))
* Releases 0.2.0 ([#340](https://github.com/frees-io/freestyle/pull/340))


## 05/08/2017 - Version 0.1.1

Release changes:

* Links header image to frees.io ([#277](https://github.com/frees-io/freestyle/pull/277))
* Prevents OOM Issues in Releasing Process ([#279](https://github.com/frees-io/freestyle/pull/279))
* Update fs-home.html ([#281](https://github.com/frees-io/freestyle/pull/281))
* Downgrades Scalajs Badge ([#278](https://github.com/frees-io/freestyle/pull/278))
* Update fs-home.html ([#282](https://github.com/frees-io/freestyle/pull/282))
* Update fs-home.html ([#283](https://github.com/frees-io/freestyle/pull/283))
* Set GA token in sbt-microsites settings ([#286](https://github.com/frees-io/freestyle/pull/286))
* Update Core Concepts link in navigation menu ([#284](https://github.com/frees-io/freestyle/pull/284))
* Fixes broken file at cats README.md ([#289](https://github.com/frees-io/freestyle/pull/289))
* Adds viewport meta Tag ([#290](https://github.com/frees-io/freestyle/pull/290))
* Removes sudo: required from Travis file ([#291](https://github.com/frees-io/freestyle/pull/291))
* Fix org in docs to show stars and watchers ([#294](https://github.com/frees-io/freestyle/pull/294))
* Fixed problem with a test application.conf file being included on the freestyle deployed jars… ([#295](https://github.com/frees-io/freestyle/pull/295))
* Changes microsite org to `frees-io` ([#296](https://github.com/frees-io/freestyle/pull/296))
* Renaming tests files ([#293](https://github.com/frees-io/freestyle/pull/293))
* Integrates sbt-freestyle Plugin ([#297](https://github.com/frees-io/freestyle/pull/297))
* Moves integration modules to its Subdirectory ([#298](https://github.com/frees-io/freestyle/pull/298))
* Revert "Moves integration modules to its Subdirectory" ([#299](https://github.com/frees-io/freestyle/pull/299))
* Removes Migrated Modules ([#300](https://github.com/frees-io/freestyle/pull/300))
* Releases 0.1.1 patch version under io.frees GroupId ([#301](https://github.com/frees-io/freestyle/pull/301))


## 05/02/2017 - Version 0.1.0

Release changes:

* Bumps org plugin version ([#218](https://github.com/47deg/freestyle/pull/218))
* Fix broken links in README.md ([#180](https://github.com/47deg/freestyle/pull/180))
* Reorganize integration documentation to integration directory ([#232](https://github.com/47deg/freestyle/pull/232))
* FS-221 Remove wrapper objects in tests ([#230](https://github.com/47deg/freestyle/pull/230))
* FS-229 Pass codeblocks to tut ([#233](https://github.com/47deg/freestyle/pull/233))
* FS-93 - 1 Auto-generate `F[_]` parameter from  ([#194](https://github.com/47deg/freestyle/pull/194))
* Removing Kazari integration ([#236](https://github.com/47deg/freestyle/pull/236))
* FS-234 Unify OpPar and OpSeq ([#237](https://github.com/47deg/freestyle/pull/237))
* Fixes freestyle-effects repository documentation ([#240](https://github.com/47deg/freestyle/pull/240))
* Integrates the new sbt-org-policies version ([#244](https://github.com/47deg/freestyle/pull/244))
* Removes -Xlint from tutScalacOptions and scalacOptions ([#248](https://github.com/47deg/freestyle/pull/248))
* FS-238 Remove F from Module ([#243](https://github.com/47deg/freestyle/pull/243))
* Tagless Final encoding for Freestyle ([#242](https://github.com/47deg/freestyle/pull/242))
* Fixes tagless section permalink ([#249](https://github.com/47deg/freestyle/pull/249))
* Simplify Exec ([#250](https://github.com/47deg/freestyle/pull/250))
* Add Monix doc sections ([#253](https://github.com/47deg/freestyle/pull/253))
* Adds Coursier and Travis Cache ([#255](https://github.com/47deg/freestyle/pull/255))
* Remove `.freeS` syntax for `F[A]` ([#256](https://github.com/47deg/freestyle/pull/256))
* Rework module macro to support targeting iota and cats coproduct types ([#261](https://github.com/47deg/freestyle/pull/261))
* Fix wording in freestyle-cache documentation ([#263](https://github.com/47deg/freestyle/pull/263))
* Remove experimental/unreleased notice ([#266](https://github.com/47deg/freestyle/pull/266))
* Mre doc edits round 2 ([#268](https://github.com/47deg/freestyle/pull/268))
* Adds module section to README ([#267](https://github.com/47deg/freestyle/pull/267))
* Removed ambiguous implicit extensions because FreeS is also a Free ([#273](https://github.com/47deg/freestyle/pull/273))
* Catch exceptions in freestyle-config ([#271](https://github.com/47deg/freestyle/pull/271))
* Tries to fix random test failures at http Play module ([#272](https://github.com/47deg/freestyle/pull/272))
* Rename `exec` to `interpret` ([#274](https://github.com/47deg/freestyle/pull/274))
* Releases Freestyle 0.1.0. ([#270](https://github.com/47deg/freestyle/pull/270))
* Add simple test for InjK ([#275](https://github.com/47deg/freestyle/pull/275))
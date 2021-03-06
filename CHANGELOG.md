# Change Log

## [0.5.0](https://github.com/TypistTech/wp-kses-view/tree/0.5.0) (2019-04-23)
[Full Changelog](https://github.com/TypistTech/wp-kses-view/compare/0.4.2...0.5.0)

**Merged pull requests:**

- View: ::getRenderCallable --\> ::getRenderClosure [\#34](https://github.com/TypistTech/wp-kses-view/pull/34) ([TangRufus](https://github.com/TangRufus))
- Apply code style [\#33](https://github.com/TypistTech/wp-kses-view/pull/33) ([TangRufus](https://github.com/TangRufus))
- Add `ViewInterface::getRenderCallable\($context = null\): callable` [\#32](https://github.com/TypistTech/wp-kses-view/pull/32) ([TangRufus](https://github.com/TangRufus))

## [0.4.2](https://github.com/TypistTech/wp-kses-view/tree/0.4.2) (2019-04-09)
[Full Changelog](https://github.com/TypistTech/wp-kses-view/compare/0.4.1...0.4.2)

**Merged pull requests:**

- Version bump 0.4.2 [\#31](https://github.com/TypistTech/wp-kses-view/pull/31) ([TangRufus](https://github.com/TangRufus))
- Update coding standards; Remove `.github`; Git: Track composer.lock [\#30](https://github.com/TypistTech/wp-kses-view/pull/30) ([TangRufus](https://github.com/TangRufus))
- Factory: Allow class `attribute`; Remove test related stuffs [\#29](https://github.com/TypistTech/wp-kses-view/pull/29) ([TangRufus](https://github.com/TangRufus))
- TravisCI: Fix test config [\#28](https://github.com/TypistTech/wp-kses-view/pull/28) ([TangRufus](https://github.com/TangRufus))
- Only includes `WITH\_COVERAGE=true` in PHP 7.1 [\#27](https://github.com/TypistTech/wp-kses-view/pull/27) ([TangRufus](https://github.com/TangRufus))

## [0.4.1](https://github.com/TypistTech/wp-kses-view/tree/0.4.1) (2018-02-12)
[Full Changelog](https://github.com/TypistTech/wp-kses-view/compare/0.4.0...0.4.1)

**Closed issues:**

- Readme: Clarify `toHtml` returns a string [\#18](https://github.com/TypistTech/wp-kses-view/issues/18)

**Merged pull requests:**

- Version bump 0.4.1 [\#26](https://github.com/TypistTech/wp-kses-view/pull/26) ([TangRufus](https://github.com/TangRufus))
- Misc: Update TravisCI & readme & info [\#25](https://github.com/TypistTech/wp-kses-view/pull/25) ([TangRufus](https://github.com/TangRufus))
- Test: Fix incorrect `@covers` [\#24](https://github.com/TypistTech/wp-kses-view/pull/24) ([TangRufus](https://github.com/TangRufus))

## [0.4.0](https://github.com/TypistTech/wp-kses-view/tree/0.4.0) (2017-10-29)
[Full Changelog](https://github.com/TypistTech/wp-kses-view/compare/0.3.0...0.4.0)

**Closed issues:**

- Add `NullView` [\#21](https://github.com/TypistTech/wp-kses-view/issues/21)
- Don't throw `UnexpectedValueException` in `ViewAwareTrait::getView` [\#20](https://github.com/TypistTech/wp-kses-view/issues/20)

**Merged pull requests:**

- Version bump 0.4.0 [\#23](https://github.com/TypistTech/wp-kses-view/pull/23) ([TangRufus](https://github.com/TangRufus))
- Add `NullView` and use it as default [\#22](https://github.com/TypistTech/wp-kses-view/pull/22) ([TangRufus](https://github.com/TangRufus))
- Codeception Example: Change dbHost to IP [\#19](https://github.com/TypistTech/wp-kses-view/pull/19) ([TangRufus](https://github.com/TangRufus))
- TravisCI: Add PHP 7.2 [\#17](https://github.com/TypistTech/wp-kses-view/pull/17) ([TangRufus](https://github.com/TangRufus))

## [0.3.0](https://github.com/TypistTech/wp-kses-view/tree/0.3.0) (2017-10-26)
[Full Changelog](https://github.com/TypistTech/wp-kses-view/compare/0.2.0...0.3.0)

**Closed issues:**

- Add `ViewInterface::toHtml\(\)` [\#11](https://github.com/TypistTech/wp-kses-view/issues/11)

**Merged pull requests:**

- Version bump 0.3.0 [\#15](https://github.com/TypistTech/wp-kses-view/pull/15) ([TangRufus](https://github.com/TangRufus))
- Rename: `Factory::buildAdminPage` -\> `::buildFormPage` [\#14](https://github.com/TypistTech/wp-kses-view/pull/14) ([TangRufus](https://github.com/TangRufus))
- Add `ViewAwareTrait::toHtml\(\)` [\#13](https://github.com/TypistTech/wp-kses-view/pull/13) ([TangRufus](https://github.com/TangRufus))
- Add `ViewInterface::toHtml\(\)` [\#12](https://github.com/TypistTech/wp-kses-view/pull/12) ([TangRufus](https://github.com/TangRufus))
- Composer: Suggest `typisttech/wp-tabbed-admin-pages` [\#8](https://github.com/TypistTech/wp-kses-view/pull/8) ([TangRufus](https://github.com/TangRufus))

## [0.2.0](https://github.com/TypistTech/wp-kses-view/tree/0.2.0) (2017-10-21)
[Full Changelog](https://github.com/TypistTech/wp-kses-view/compare/0.1.0...0.2.0)

**Merged pull requests:**

- Version bump 0.2.0 [\#7](https://github.com/TypistTech/wp-kses-view/pull/7) ([TangRufus](https://github.com/TangRufus))
- Rename: `ViewInterface::echoKses` -\> `::render` [\#6](https://github.com/TypistTech/wp-kses-view/pull/6) ([TangRufus](https://github.com/TangRufus))
- Add `ViewAwareTraitInterface::render` [\#5](https://github.com/TypistTech/wp-kses-view/pull/5) ([TangRufus](https://github.com/TangRufus))

## [0.1.0](https://github.com/TypistTech/wp-kses-view/tree/0.1.0) (2017-10-20)
**Merged pull requests:**

- Version bump 0.1.0 [\#4](https://github.com/TypistTech/wp-kses-view/pull/4) ([TangRufus](https://github.com/TangRufus))
- Scrutinizer: Remove `align\_assignments` [\#3](https://github.com/TypistTech/wp-kses-view/pull/3) ([TangRufus](https://github.com/TangRufus))
- Add `ViewAwareTrait` and `ViewAwareTraitInterface` [\#2](https://github.com/TypistTech/wp-kses-view/pull/2) ([TangRufus](https://github.com/TangRufus))
- First release [\#1](https://github.com/TypistTech/wp-kses-view/pull/1) ([TangRufus](https://github.com/TangRufus))



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*
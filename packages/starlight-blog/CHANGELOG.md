# starlight-blog

## 0.16.0

### Minor Changes

- [#100](https://github.com/HiDeoo/starlight-blog/pull/100) [`679e509`](https://github.com/HiDeoo/starlight-blog/commit/679e50998bad26034735c99302de5645dd87bf6e) Thanks [@HiDeoo](https://github.com/HiDeoo)! - Adds support for Astro v5, drops support for Astro v4.

  ⚠️ **BREAKING CHANGE:** The minimum supported version of Starlight is now `0.30.0`.

  Please follow the [upgrade guide](https://github.com/withastro/starlight/releases/tag/%40astrojs/starlight%400.30.0) to update your project.

  Note that the [`legacy.collections` flag](https://docs.astro.build/en/reference/legacy-flags/#collections) is not supported by this plugin and you should update your collections to use Astro's new Content Layer API.

  ⚠️ **BREAKING CHANGE:** The generated RSS feed no longer includes content of blog posts due to a [regression](https://github.com/withastro/astro/issues/12669) in Astro v5. The feature will be restored in a future release. If you rely on this feature, please stay on a previous version of Starlight and Astro in the meantime.
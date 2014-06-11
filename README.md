# MacType.Decency

MacType.Decency is a MacType profile that provides decent solutions to font rendering and font substitutions for Windows operating systems under English locale and Chiense locale.

For English-locale Windows, the profile uses the following fonts:

| Environment | Font                              |
|-------------|-----------------------------------|
| Windows UI  | Microsoft YaHei UI, Lucida Grande |
| Firefox     | FZLanTingHei-R-GBK                |

For Chinese-locale Windows, the profile uses the following fonts:

| Environment | Font                              |
|-------------|-----------------------------------|
| Windows UI  | Microsoft YaHei UI                |
| Firefox     | FZLanTingHei-R-GBK                |

The choice of fonts is for maximal compatibility and best performance and effect. 

## Installation

1. Make sure you have installed the recommended fonts used by this profile.
2. Install [MacType](https://code.google.com/p/mactype/).
3. Download this repository and extract the ini files to ini folder of where you installed MacType.
4. Start configuration and choose the proper file in your need.

## Recommended configurations

### Firefox

The profile has been tuning not only for the operating system but also for Firefox. Please use the following fonts in correspondence to optimize the effects.

1. [Source Serif Pro](https://github.com/adobe/source-serif-pro/tree/release)
2. [Source Sans Pro](https://github.com/adobe/source-sans-pro/tree/release)
3. [Source Code Pro](https://github.com/adobe/source-code-pro/tree/release)

Enter `about:config` and change the following configurations:

| Key                                                      | Value |
|----------------------------------------------------------|-------|
| gfx.direct2d.disabled                                    | true  |
| gfx.font_loader.delay                                    | -1    |
| gfx.font_rendering.cleartype.always_use_for_content;true | true  |
| gfx.font_rendering.cleartype_params.cleartype_level      | 100   |
| gfx.font_rendering.cleartype_params.enhanced_contrast    | 100   |
| gfx.font_rendering.cleartype_params.gamma                | 1400  |
| gfx.font_rendering.cleartype_params.pixel_structure      | 1     |
| gfx.font_rendering.cleartype_params.rendering_mode       | 5     |
| gfx.font_rendering.fallback.always_use_cmaps             | true  |
| gfx.use_text_smoothing_setting                           | true  |

## License

This project is under [MIT License](http://opensource.org/licenses/MIT).
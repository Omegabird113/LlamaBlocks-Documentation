# The LlamaBlocks Versioning System
The current LlamaBlocks version system produces versions in the format `x.y.z` or `x.y.z-s` where:

| Segment | Meaning                                                 | Examples                                            |
|:--------|:--------------------------------------------------------|:----------------------------------------------------|
| `x`     | a game-changing update                                  | A rewrite, a ridiculous amount of new features, etc |
| `y`     | represents an update which changes features or behavior | New blocks, Minecraft version update, new function in the computer, etc |
| `z`     | a bugfix or smaller enhancement update                  | A hotfix/bugfix, small texture/GUI change, etc      |
| `s`     | a development version suffix                            | A suffix to denote a beta or RC build of a future update (e.g. `beta2` or `rc1`) |

> [!Note]
> In Beta/RC versions, the format in the mods menu will be a different version to the display version in `/llamablocks about`. In betas, the format `x.y.z.b` is used where `b` is the beta number (e.g. `1.3.0-beta5` appears as `1.3.0.5`). For Release Candidates, it's more complex with a `x.y.z.rb` system where `r` is the release candidate number (it looks like it's being multiplied by 10 due to its placement), but the beta number also still increments for the b value (e.g. `1.3.0-rc1` which would be `beta 4`, so it becomes `1.3.0.14`). This versioning weirdness is due to MCreator stripping any text or dashes from versions before generating code. 

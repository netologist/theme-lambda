### Lambda

[![MIT License](https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square)](/LICENSE)
[![Fish Shell Version](https://img.shields.io/badge/fish-v2.2.0-007EC7.svg?style=flat-square)](http://fishshell.com)

<br/>

#### Screenshot

<p align="center">
<img src="https://raw.githubusercontent.com/hasanozgan/theme-lambda/master/screenshot.png">
</p>

###### Added VirtualEnv Support
![preview](https://i.imgur.com/fWurs47.png)

###### Added Mode Indicator Support
<p align="center">
<img src="https://raw.githubusercontent.com/js402882/theme-lambda/master/screenshot-mode-indicator.png">
</p>

#### Install

#### [Fisherman]

```fish
fisher i lambda
```

##### [Oh-My-Fish]

```fish
omf install lambda
```

##### [home-manager]
```nix
plugins = [
  {
    name = "theme-lambda";
    src = pkgs.fetchFromGitHub {
      owner = "hasanozgan";
      repo = "theme-lambda";
      rev = "1d599f05dc560d7c9fa0660fa72e2d32251f6f65";
      sha256 = "1s0pyc7nlxlynszlskmzrg57rq2nszbkzjq714hl15g1 gxp95k";
    };
  }
];
```


##### Fish Mode Indicator Installation Note

Disable default Fish mode indicator via

```
function fish_mode_prompt; end
funcsave fish_mode_prompt
```

Details in https://fishshell.com/docs/current/cmds/fish_mode_prompt.html




[Fisherman]: https://github.com/fisherman/fisherman
[Oh-My-Fish]: https://github.com/oh-my-fish/oh-my-fish
[home-manager]: https://github.com/nix-community/home-manager

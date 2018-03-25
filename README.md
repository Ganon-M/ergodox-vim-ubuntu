Performance testing and training was carried out on [typing.io](https://typing.io/) which provides real source code as training material. Relative performance is in comparison to a baseline measurement I obtained using a conventional keyboard. After using it for 2+ months I would not consider switching back to a conventional keyboard for programming due to the hugely increased comfort and the very reasonable increase in typing speed. You can purchase these keyboards on [ergodox-ez.com](https://ergodox-ez.com/).

| Time (days) | Typing speed (wpm) | Relative performance  |
| ----------- |:------------------:| ---------------------:|
| +1          | 8                  | 18%                   |
| +7          | 22                 | 49%                   |
| +14         | 35                 | 78%                   |
| +28         | 47                 | 105%                  |
| +56         | 58                 | 129%                  |

# Considerations
This layout is designed for Vim users and also contains mappings to facilitate easy navigation of Ubuntu workspaces, of which I am a heavy user. I code mostly in Java, Kotlin and JavaScript so some of the layout choices may implicitly reflect that.

The alphabetic layout is QWERTY for two reasons
1. I did not want to have to change conventional mappings in software I use e.g. Vim's 'hjkl' which are designed for QWERTY keyboards
2. I did not want to lose too much familiarity with traditional keyboards as I seldom use them since the Ergodox is my primary keyboard now.

There are two shift keys (one on each island's thumb group). You should use the LHS shift key when modifying something on the RHS and vice versa. This avoids hand contortions.

The `layer0->layer1` modifier is the most heavily used, so it was placed in a more easily reached location than the `layer0->layer2` modifier. Like the shift keys, there is a duplicate on each side. When typing e.g. braces/parentheses/curly braces, the RHS index finger very comfortably reaches the RHS `layer0->layer1` button.

# Layout
[link to layout](http://configure.ergodox-ez.com/keyboard_layouts/kxlgmg/edit) if you want to modify it further

**layer0**
![layer0](https://github.com/Ganon-M/ergodox-vim-ubuntu/blob/master/layout/layer0.png)
**layer1**
![layer1](https://github.com/Ganon-M/ergodox-vim-ubuntu/blob/master/layout/layer1.png)
**layer2**
![layer2](https://github.com/Ganon-M/ergodox-vim-ubuntu/blob/master/layout/layer2.png)
**layer3**
![layer3](https://github.com/Ganon-M/ergodox-vim-ubuntu/blob/master/layout/layer3.png)

# Notes
The layout does not make use of every single key on the Ergodox (in particular the far thumb keys). The reason for this is that they are awkward to reach without contorting your wrists and a goal for this layout was to avoid all wrist flexion if possible.

Many of the special characters are outputting codes that will be recognised by a machine that is in UK keyboard mode. Modification is required for US compatibility

The RHS island is designed to have your fingers resting on the `hjkl` keys. This is one key to the left of the conventional QWERTY touch typing position so the letters 'o' and 'p' are slightly more difficult to reach than they ought to be.

I went through 20+ iterations of this layout before reaching a layout I was totally happy with. Hopefully this might save you that time :)

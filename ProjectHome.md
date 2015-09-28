hqx ("hq" stands for "high quality" and "x" stands for magnification) is one of the pixel art scaling algorithms developed by Maxim Stepin, used in emulators such as Nestopia, bsnes, ZSNES, Snes9x, FCE Ultra and many more. There are 3 hqx filters: hq2x, hq3x, and hq4x, which magnify by factor of 2, 3, and 4 respectively.

hqxSharp is a C# port of of the hqx project on this site (revision three) with added support for transparency, custom tolerances and seamless tiling.

The main focus of hqxSharp lies on asset creation and use in tools; it is not necessarily intended as final output for real-time graphics. This means that additional functionality (like alpha support and variable AYUV thresholds) and easier code are usually preferred over a small performance increase.

Calls to hqx methods are compatible with the corresponding hqxSharp methods and the default parameters match the values used in hqx.

**This project has moved to https://bitbucket.org/Tamschi/hqxsharp/**
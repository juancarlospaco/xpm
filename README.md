# X-Pixmap & NetPBM

- Half the code is Tests, all functions are asserted.
- Only uses `system.nim`, no imports, does not use std lib, easy to maintain.
- `runnableExamples` with `static: ` and `doAssert`.
- Documentation with Examples and Links.
- Works at compile-time, NimScript and JavaScript.
- All functions are `func`, except 1 that does the I/O.
- Tiny `func` of 3 ~ 5 lines, simple code, simple API.
- Functionality can be extended with `sequtils` by the user.
- Examples render 6 small fractals at compile-time to mimic a real-world like usage.
- Only ~300 lines where half are test, 5 image formats.


#### Random example use cases

- Generate Icons of arbitrary sizes instead of bundling them in binaries and installers.
- Generate patterns on client-side browser instead of transferring them over internet.
- Render QR codes, Bar codes, Icons, visual reports, simple diagrams for documentation, etc.
- Plot charts with data of any kind on any target.
- Anything image related, good addition to SVG and HTML that std lib already can do.


#### Format

Image format is loss-less and human-readable, UTF-8 but fits ASCII,
is also valid C source code, can be embedded in C, supports millions of colors and transparency.


#### Links

- Rust lang one https://docs.rs/image/latest/image/pnm/struct.PNMEncoder.html
- Python also has a module to draw images on std lib.
- Spec https://en.wikipedia.org/wiki/X_PixMap
- Spec https://en.wikipedia.org/wiki/Netpbm_format


# Examples with Std Lib only

![fractalito](https://user-images.githubusercontent.com/1189414/76784223-067d9100-6792-11ea-82cc-19574bb8a83f.jpeg)

![fractalito_hexaflake](https://user-images.githubusercontent.com/1189414/76784237-0aa9ae80-6792-11ea-8f57-c70e42739e8d.jpg)

![fractals](https://user-images.githubusercontent.com/1189414/76783936-89eab280-6791-11ea-95d2-1d4054c5d116.png)

![](https://raw.githubusercontent.com/juancarlospaco/netpbm/master/example.jpg)

![](https://raw.githubusercontent.com/juancarlospaco/netpbm/master/fractalito.jpeg)

![](https://raw.githubusercontent.com/juancarlospaco/netpbm/master/fractalito_Vicsek.jpeg)

![](https://raw.githubusercontent.com/juancarlospaco/netpbm/master/fractalito_hexaflake.jpg)

![](https://raw.githubusercontent.com/juancarlospaco/netpbm/master/fractalito_snowflake.jpeg)

![](https://raw.githubusercontent.com/juancarlospaco/netpbm/master/fractalito_spiral.jpeg)

![](https://raw.githubusercontent.com/juancarlospaco/netpbm/master/fractalito_tri.jpeg)

identicon.py: identicon python implementation. (Python ver.3 + Input by Name)
==============================================
Tuned-up by uuuno(https://github.com/uuuno)

Origin source by Shin Adachi <shn@glucose.jp>

## Change Point
- You can input not only numbers, but also string(ex. name).
- You can use on python version3

## usage

### commandline

    python identicon.py [code]

### python

    import identicon
    identicon.render_identicon(code, size)

Return a PIL Image class instance which have generated identicon image.
`size` specifies patch size. Generated image size is 3 * `size`.

# lgtv_dovi_config_gen
Generate a Dolby Vision configuration file for LG TVs.

Usage:
- Clone repo
- Edit `dovi_config_gen.py` to set the measured DCI-P3 primaries in Dolby Vision mode
    - Variables are Rx, Ry, Gx, Gy, Bx, By
- Run with `python dovi_config_gen.py`
- Copy the output into a file named `DolbyVision_UserDisplayConfiguration.TXT`
- Upload to the TV.


For models newer than 2018, remove `TLMS2RGBmat` and rename `ColorPrimaries` to `TPrimaries`.

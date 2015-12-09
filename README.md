# sct
Change screen color temperature and brightness using the Xrandr extension

The original program was written by Ted Unangst (see
http://www.tedunangst.com/flak/post/sct-set-color-temperature) who was
so kind to put it under public domain.

In contrast to other programs that adapt color temperature, this
programs minimizes the required dependencies to an absolute minimum.

I simply added the option to change the brightness, too. The arguments
are as follows:

```
./sct TEMPERATURE BRIGHTNESS
```

where `TEMPERATURE` is given between 1000K and 10000K (default 6500K)
and `BRIGHTNESS` between 0.1 and 1.0 (default 1.0).

# Waiting for external trigger
(I do not remember the date in 2018) Kazuyuki Takeda

To pause implementation of the pulse programmer until the spectrometer receives external trigger signal, use `exttrig` command.

```
Init
  pulse(pw1; gate1, gate2, ...)
  exrttrig
  pulse(pw2; gate3, gate4, ...)
Relax
```

[Back](../index.md)

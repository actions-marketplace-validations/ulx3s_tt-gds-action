# ULX3S Constrain Files

Copied from [emard/ulx3s/doc/constraints](https://github.com/emard/ulx3s/tree/master/doc/constraints)

Note that minor changes have been made in [ulx3s_v20.lpf](./ulx3s_v20.lpf) vs [the original](./ulx3s_v20_original.lpf)

| original                                                       | modified                                                       | description                             |
|----------------------------------------------------------------|----------------------------------------------------------------|-----------------------------------------|
| FREQUENCY PORT "gn[12]" 50 MHZ;                                | # FREQUENCY PORT "gn[12]" 50 MHZ;                              | commented out, duplicate. see line 393  |
| FREQUENCY PORT "gn12" 50 MHZ;                                  | # FREQUENCY PORT "gn12" 50 MHZ;                                | commented out, duplicate. see line 393  |
| IOBUF  PORT "shutdown" PULLMODE=DOWN IO_TYPE=LVCMOS33 DRIVE=4; | IOBUF  PORT "shutdown" PULLMODE=DOWN IO_TYPE=LVCMOS33 DRIVE=4; | not change, added final LF              |
